# 🎬 Video Downloader GUI — YouTube & TikTok

🚀 Расширенная **Desktop-версия** Telegram-бота [ClipFetch](https://t.me/ClipFetchBot).  
Приложение с GUI для Windows/Linux/MacOS для скачивания видео и аудио с **YouTube и TikTok**, построенное на [yt-dlp](https://github.com/yt-dlp/yt-dlp).

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


## 📦 Структура
/
├─ index.html # страница (лендинг)
├─ robots.txt # правила для поисковиков
└─ sitemap.xml # карта сайта
