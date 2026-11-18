# Frameworks_Coursework
Курсовая работа по предмету "Фреймворки Python для анализа данных" выполненная командой из двух человек (Окунев Михаил Аркадьевич, Максимов Егор Олегович).

Исходные датасеты:
Текст: https://huggingface.co/datasets/AI-Roadmap/test_emotion_classification_10k_qwen3_8B
Изображения: https://www.kaggle.com/datasets/pierreayfri/minecraft-mobs
## Структура репозитория

```
Frameworks_Coursework/
├── README.md
├── notebooks/
│   └── Курсовая_по_Фреймворкам_для_анализа_данных_(разметка).ipynb
├── text_data/
│   ├── handmade/
│   │   └── data.csv
│   └── generated/
│       └── data.csv
└── image_data/
    ├── raw/
    │   ├── handmade/
    │   └── generated/
    └── clean/
        ├── handmade/
        │   ├── images/
        │   └── boxes.csv
        └── generated/
            ├── images/
            └── boxes.csv
```

Данные разделены по двум признакам:
- **по происхождению:** `handmade` — собраны и размечены вручную, `generated` — сгенерированы;
- **по стадии обработки** (для изображений): `raw` — исходные файлы как есть, `clean` — обработанные изображения.

### `notebooks/`
Jupyter-ноутбук с кодом курсовой.

### `text_data/`
Данные для классификации эмоций в тексте, дополнение к датасету
[AI-Roadmap/test_emotion_classification_10k_qwen3_8B](https://huggingface.co/datasets/AI-Roadmap/test_emotion_classification_10k_qwen3_8B).