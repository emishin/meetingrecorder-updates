# MeetingRecorder

Приложение для записи встреч с автоматическим определением звонков и транскрипцией.

## Скачать

**[Последняя версия](https://github.com/emishin/meetingrecorder-updates/releases/latest)**

## Установка

1. Открой `MeetingRecorder-X.X.dmg`
2. Перетащи MeetingRecorder в папку Applications
3. Запусти приложение из Applications

При первом запуске macOS может показать предупреждение:
> "MeetingRecorder cannot be opened because it is from an unidentified developer"

**Решение:** Нажми правой кнопкой на приложении → Open → в появившемся окне нажми "Open"

## Настройка разрешений

Приложению нужны два разрешения:

### Микрофон
При первом запуске появится запрос — нажми "OK"

### Запись экрана
Нужно для записи системного аудио (звук собеседника):
1. System Settings → Privacy & Security → Screen Recording
2. Включи MeetingRecorder
3. Перезапусти приложение

## Использование

- Приложение работает в menu bar (верхняя панель)
- Нажми на иконку чтобы открыть меню
- "Start Recording" — начать запись вручную
- При обнаружении звонка (Zoom, FaceTime и др.) появится окно с предложением записать

**Записи сохраняются в:** `~/Documents/MeetingRecordings/`

## Транскрипция

Бесплатно: 5 транскрипций в месяц. Лимит сбрасывается автоматически.

Для автоматической расшифровки:
1. Открой Settings → Transcription
2. Включи "Auto-transcribe new recordings"

## Обратная связь

- [Сообщить о баге](https://github.com/emishin/meetingrecorder-updates/issues/new?template=bug_report.md)
- [Предложить фичу](https://github.com/emishin/meetingrecorder-updates/issues/new?template=feature_request.md)

## Обновления

Приложение проверяет обновления автоматически. Также можно проверить вручную: Menu → Check for Updates.
