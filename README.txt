MeetingRecorder v1.0
====================

Приложение для записи встреч с автоматическим определением звонков
и опциональной транскрипцией через AssemblyAI.


УСТАНОВКА
---------

1. Открой MeetingRecorder-1.0.dmg
2. Перетащи MeetingRecorder в папку Applications
3. Запусти приложение из Applications

При первом запуске macOS может показать предупреждение:
"MeetingRecorder cannot be opened because it is from an unidentified developer"

Решение:
- Нажми правой кнопкой на приложении → Open
- В появившемся окне нажми "Open"
- Это нужно сделать только один раз


НАСТРОЙКА РАЗРЕШЕНИЙ
--------------------

Приложению нужны два разрешения:

1. MICROPHONE (Микрофон)
   - При первом запуске появится запрос - нажми "OK"
   - Или: System Settings → Privacy & Security → Microphone → включи MeetingRecorder

2. SCREEN RECORDING (Запись экрана)
   - Нужно для записи системного аудио (звук собеседника)
   - System Settings → Privacy & Security → Screen Recording → включи MeetingRecorder
   - После включения перезапусти приложение


ИСПОЛЬЗОВАНИЕ
-------------

- Приложение работает в menu bar (верхняя панель)
- Нажми на иконку чтобы открыть меню
- "Start Recording" - начать запись вручную
- Автоматически: при обнаружении звонка (Zoom, FaceTime и др.) появится окно с предложением записать

Записи сохраняются в: ~/Documents/MeetingRecordings/


ТРАНСКРИПЦИЯ (опционально)
--------------------------

Для автоматической расшифровки записей:
1. Зарегистрируйся на https://www.assemblyai.com/ (есть бесплатный план)
2. Получи API ключ
3. Открой Settings → Transcription → вставь API ключ
4. Включи "Auto-transcribe new recordings"


ВОПРОСЫ?
--------

Пиши мне!
