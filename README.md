# MeetingRecorder

**MeetingRecorder is a free meeting recorder for Mac that works without a bot.** It is a small menu-bar app that records your microphone and your Mac's system audio together, so you get both sides of any call: Zoom, Microsoft Teams, Google Meet, Slack huddles, FaceTime, WhatsApp or anything else that plays sound. Nothing joins the meeting and nothing appears in the participant list.

Website: **[meetingsrecorder.com](https://meetingsrecorder.com)** · Made by Alex Mishin

- **No bot, no host permission.** It records what your Mac plays, so it works when you are a guest.
- **Recordings stay on your Mac.** Each call is saved as an M4A file in a folder you choose. No account.
- **Transcript and summary in one click.** Speaker labels, a short summary and action items. This step is optional and runs in the cloud: the audio is sent for transcription only when you ask for it or turn on auto-transcribe.
- **Free.** Unlimited recording and 20 transcriptions a month.
- **Small and native.** About 4 MB, written in Swift, lives in the menu bar.

**Requirements:** macOS 15 (Sequoia) or later on an Apple Silicon Mac.

> Several Mac apps and open-source projects have similar names. This is MeetingRecorder from meetingsrecorder.com. It is not in the Mac App Store. This repository hosts the releases and the update feed; the source code is not published here.

## Download

**[Latest version](https://github.com/emishin/meetingrecorder-updates/releases/latest)** or with Homebrew:

```bash
brew install --cask meetingrecorder
```

## Installation

1. Open `MeetingRecorder-X.X.dmg`
2. Drag MeetingRecorder to the Applications folder
3. Launch the app from Applications

On first launch, macOS may show a warning:
> "MeetingRecorder cannot be opened because it is from an unidentified developer"

**Solution:** Right-click on the app → Open → click "Open" in the dialog

## Permissions

The app requires two permissions:

### Microphone
A permission request will appear on first launch — click "OK"

### Screen Recording
Required to capture system audio (the other person's voice):
1. System Settings → Privacy & Security → Screen Recording
2. Enable MeetingRecorder
3. Restart the app

## Usage

- The app runs in the menu bar (top panel)
- Click the icon to open the menu
- "Start Recording" — start recording manually
- When a call is detected (Zoom, FaceTime, etc.), a prompt will appear to start recording

**Recordings are saved to:** `~/Documents/MeetingRecordings/`

## Transcription

Free: 20 transcriptions per month. The limit resets automatically on the 1st of each month.

Transcription runs in the cloud. Recording itself works offline, and audio is uploaded only when a transcript is requested.

To enable automatic transcription:
1. Open Settings → Transcription
2. Enable "Auto-transcribe new recordings"

## AI Summaries

Generate AI-powered meeting summaries from your transcripts (powered by GPT-5):
- Click the sparkle icon next to any transcribed recording
- Or enable "Auto-summarize" in Settings for automatic summaries

## Guides

- [How to record a Zoom meeting on a Mac](https://meetingsrecorder.com/blog/record-zoom-mac/)
- [How to record Microsoft Teams on a Mac](https://meetingsrecorder.com/blog/record-teams-mac/)
- [How to record a Google Meet on a Mac](https://meetingsrecorder.com/blog/record-google-meet-mac/)
- [Best bot-free meeting recorders for Mac](https://meetingsrecorder.com/blog/best-bot-free-meeting-recorders-mac/)

## Feedback

- [Report a Bug](https://github.com/emishin/meetingrecorder-updates/issues/new?template=bug_report.md)
- [Request a Feature](https://github.com/emishin/meetingrecorder-updates/issues/new?template=feature_request.md)

## Updates

The app checks for updates automatically. You can also check manually: Menu → Check for Updates.
