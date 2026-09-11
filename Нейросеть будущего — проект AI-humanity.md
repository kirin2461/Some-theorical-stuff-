## ✨ Возможности

| Функция | Описание |
|---------|----------|
| 🧠 PAD эмоции | 8 типов эмоций, затухание, уверенность |
| ⚡ Прокачка | Система навыков с 5 уровнями |
| 👤 3D Аватар | VRM/GLB/OBJ на рабочем столе |
| 🔊 XTTS v2 | Клонирование голоса, 15+ языков |
| 🤖 Telegram | Бот с командами |
| 📷 FaceEmotion | Распознавание эмоций через камеру |
| 📅 Calendar | Google Calendar интеграция |
| 🎮 Sci-Fi UI | Киберпанк интерфейс |

---

## 📁 Структура проекта

```
ai-humaity/
├── core/                        # 🧠 Ядро AI (5 модулей)
│   ├── emotion_engine.py        # PAD модель эмоций
│   ├── cognitive_cycle.py       # Когнитивный цикл + GPT
│   ├── skill_system.py          # Система навыков
│   ├── safety_system.py         # Безопасность
│   └── autonomous_life.py       # Автономная жизнь
│   └── memory_manager.py  # Управление памятью и контекстом
│
├── modules/                     # 🔌 Расширения (5 модулей)
│   ├── desktop_avatar.py        # 3D аватар
│   ├── tts_engine.py            # Coqui XTTS v2
│   ├── telegram_integration.py  # Telegram бот
│   ├── face_emotion.py          # FER + OpenCV
│   └── calendar_integration.py  # Google Calendar
│
├── gui/                         # 🎨 Интерфейс (3 файла)
│   ├── main_window_scifi.py     # Главное окно
│   ├── styles_scifi.py          # Sci-Fi стили
│   └── skills_widget.py         # Виджет навыков
│
├── config/                      # ⚙️ Конфигурация
│   └── settings.py              # API ключи
│
├── main.py                      # 🚀 Точка входа
├── start.bat                    # 📦 Лаунчер Windows
├── requirements.txt             # Зависимости
└── README.md
├── utils.py            # 🛠️ Вспомогательные функции
```

---

## 🧠 Ядро (core/)

| Модуль | Описание | Ключевые функции |
|--------|----------|------------------|
| `emotion_engine.py` | PAD модель эмоций | 8 эмоций, decay, confidence |
| `cognitive_cycle.py` | Главный цикл | GPT интеграция, память, анализ |
| `skill_system.py` | Прокачка навыков | 5 уровней, XP формула |
| `safety_system.py` | Безопасность | regex фильтры, 3 режима |
| `autonomous_life.py` | Внутренняя жизнь | Случайные мысли, QTimer |

---

## 🔌 Модули (modules/)

| Модуль | Описание | Форматы/API |
|--------|----------|------------|
| `desktop_avatar.py` | 3D аватар на рабочем столе | VRM, GLB, OBJ |
| `tts_engine.py` | Синтез речи | Coqui XTTS v2, 15+ языков |
| `telegram_integration.py` | Telegram бот | asyncio, команды |
| `face_emotion.py` | Распознавание эмоций | FER, OpenCV, камера |
| `calendar_integration.py` | Google Calendar | OAuth 2.0 |

---

## Связанные документы

- [Когнитивный цикл ИИ — 10 фаз](%D0%9A%D0%BE%D0%B3%D0%BD%D0%B8%D1%82%D0%B8%D0%B2%D0%BD%D1%8B%D0%B9%20%D1%86%D0%B8%D0%BA%D0%BB%20%D0%98%D0%98%20%E2%80%94%2010%20%D1%84%D0%B0%D0%B7.md)
- [Теория когнитивной архитектуры](%D0%A2%D0%B5%D0%BE%D1%80%D0%B8%D1%8F%20%D0%BA%D0%BE%D0%B3%D0%BD%D0%B8%D1%82%D0%B8%D0%B2%D0%BD%D0%BE%D0%B9%20%D0%B0%D1%80%D1%85%D0%B8%D1%82%D0%B5%D0%BA%D1%82%D1%83%D1%80%D1%8B.md)
- [Глоссарий](%D0%93%D0%BB%D0%BE%D1%81%D1%81%D0%B0%D1%80%D0%B8%D0%B9.md)
- ↑ [Карта репозитория](README.md)
