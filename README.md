# 🎬 Video Downloader GUI — YouTube & TikTok

🚀 Расширенная **Desktop-версия** Telegram-бота [ClipFetch](https://t.me/ClipFetchBot).  
Приложение с GUI для Windows для скачивания видео и аудио с **YouTube и TikTok**, построенное на [yt-dlp](https://github.com/yt-dlp/yt-dlp).

---

## ✨ Возможности

- **YouTube**: скачивание одиночных видео и целых плейлистов  
- **TikTok**: скачивание роликов  
- **Качество**: выбор (лучшее, 1080p, 720p, 480p, 360p)  
- **Аудио**: конвертация только в MP3 (через FFmpeg)  
- **Плейлисты**: поддержка MIX/Radio (RD...) и выбор N первых видео  
- **Cookies**: автоматическое создание `cookies.txt` из браузера  
- **Прогресс**: прогресс-бар с % и скоростью  
- **Языки**: русский 🇷🇺 и английский 🇬🇧 интерфейс  
- **Настройки**: лимит скорости, параллельные загрузки, шаблон имён файлов  
- **Кроссплатформенность**: работает на Windows, Linux и macOS (через Python)  

---

## 📦 Системные требования

- Windows 10/11 x64 (для сборки .exe)  
- Python 3.10+ (для разработки/запуска из исходников)  
- [FFmpeg](https://ffmpeg.org/download.html) в `PATH` (для работы аудио-выгрузки в MP3)  

---

## ⚙️ Установка

### Для разработчиков

1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/<yourname>/video-downloader-gui.git
   cd video-downloader-gui
Установите зависимости:

bash
Копировать код
pip install -r requirements.txt
Запустите приложение:

bash
Копировать код
python app.py
🖥️ Сборка .exe (Windows)
Установите PyInstaller:

bash
Копировать код
pip install pyinstaller
Соберите .exe:

bash
Копировать код
pyinstaller --onefile --noconsole --name VideoDownloader app.py
Готовый файл появится в папке dist/VideoDownloader.exe.


📂 Структура проекта
plaintext
Копировать код
video-downloader-gui/
├── app.py               # главный модуль
├── core/                # конфиг, i18n, cookies, downloader
├── pages/               # страницы UI (YouTube, TikTok, Menu)
├── requirements.txt     # зависимости
├── README.md            # документация
├── LICENSE              # лицензия (MIT)
└── docs/                # скриншоты и документация

🎧 Поддерживаемые форматы
YouTube

Видео: MP4, WebM

Аудио: MP3, M4A

Качество: до 4K (зависит от источника)

TikTok

Видео: MP4

Аудио: MP3

Качество: до 720p

🛠️ Устранение неполадок
FFmpeg не найден: скачайте FFmpeg, добавьте в PATH и перезапустите приложение.

Ошибки загрузки: проверьте интернет, корректность ссылки, попробуйте другой браузер или cookies.txt.

Cookies не работают: убедитесь, что браузер запущен, и попробуйте другой профиль (Chrome/Edge/Chromium).

📜 Лицензия
MIT License — проект полностью открытый и свободный для использования.

📜 Changelog
[1.0.0] - 2025-10-02
Added
Первая публичная версия Video Downloader GUI

Поддержка YouTube (видео + плейлисты)

Поддержка TikTok (видео)

Поддержка качества (1080p, 720p, 480p, 360p)

Выгрузка аудио в MP3 (FFmpeg)

Автосоздание cookies.txt из браузера

Прогресс-бар в GUI

Поддержка RU/EN интерфейса

Настройки (лимит скорости, потоки, шаблон имён)

Fixed
Баг с MIX/Radio плейлистами (добавлено предупреждение)

Исправлено поведение Enter в русской раскладке

Исправлено появление опций плейлистов (только при выборе режима)

Убран лишний текст menu.youtube.btn из меню


Это расширенная десктопная версия Telegram-бота ClipFetch
🌐 Сайт: lagoda1337.ru
