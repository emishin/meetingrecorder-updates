# MeetingRecorder

A macOS app for recording meetings with automatic call detection and transcription.

## Download

**[Latest Version](https://github.com/emishin/meetingrecorder-updates/releases/latest)**

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

Free: 5 transcriptions per month. The limit resets automatically.

To enable automatic transcription:
1. Open Settings → Transcription
2. Enable "Auto-transcribe new recordings"

## Feedback

- [Report a Bug](https://github.com/emishin/meetingrecorder-updates/issues/new?template=bug_report.md)
- [Request a Feature](https://github.com/emishin/meetingrecorder-updates/issues/new?template=feature_request.md)

## Updates

The app checks for updates automatically. You can also check manually: Menu → Check for Updates.
