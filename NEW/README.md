# NEW — Проектирование функциональных требований 
Выполнено в роли **аналитика** на основании README_RUS.md, UC и описания задачи «Запись на стрижку».

## Структура папки

```
NEW/
├── README.md                 # Этот файл
├── tables/
│   ├── csv/                 # Таблицы в формате CSV
│   │   ├── ex00_lifecycle_entities.csv
│   │   ├── ex01_slots_lifecycle.csv
│   │   ├── ex02_entities_lifecycle.csv
│   │   ├── ex03_directories_actions.csv
│   │   ├── ex04_slots_crud.csv
│   │   ├── ex05_slots_additional_actions.csv
│   │   └── ex06_access_rights.csv
│   └── xlsx/                # Таблицы в формате XLSX
│       └── (те же файлы)
├── diagrams/
│   ├── drawio/              # Диаграмма состояний (draw.io)
│   │   └── ex01_slots_state_diagram.drawio
│   ├── mermaid/             # Диаграмма состояний (Mermaid)
│   │   └── ex01_slots_state_diagram.md
│   └── plantuml/            # Диаграмма состояний (PlantUML)
│       └── ex01_slots_state_diagram.puml
├── explanations_a/          # Вариант A: один общий файл
│   └── COLUMNS_DESCRIPTION.md
├── explanations_b/          # Вариант B: отдельный файл на упражнение
│   ├── ex00_columns.md
│   ├── ex01_columns.md
│   └── ... ex06_columns.md
├── explanations_c/          # Вариант C: комментарии в CSV
│   └── (CSV с #-комментариями в первой строке)
├── explanations_d/          # Вариант D: папка docs/
│   └── docs/
│       ├── README.md
│       ├── ex00.md
│       └── ... ex06.md
├── explanations_e/          # Вариант E: словарь данных
│   └── DATA_DICTIONARY.md
└── scripts/
    └── csv_to_xlsx.py       # Конвертер CSV → XLSX
```

## Форматы

| Артефакт | Формат | Примечание |
|----------|--------|------------|
| Таблицы | CSV, XLSX | Разделитель CSV: `;` |
| Диаграмма Ex.01 | draw.io, Mermaid, PlantUML | Жизненный цикл «Слот обслуживания» |
| Пояснения столбцов | 5 вариантов (a–e) | См. папки explanations_* |

## Структура пояснений столбцов

Для каждого столбца указаны:
- **Назначение** — за что отвечает
- **Почему нужен** — связь с заданием/UC
- **Примеры** — типичные значения
- **Связь** — связь с другими столбцами/таблицами

## Как использовать

1. **Таблицы:** открыть CSV в Excel/LibreOffice или XLSX напрямую.
2. **draw.io:** открыть `.drawio` в [diagrams.net](https://app.diagrams.net/) или VS Code с расширением Draw.io.
3. **Mermaid:** просмотреть `.md` в GitHub/GitLab или в VS Code с расширением Mermaid.
4. **PlantUML:** сгенерировать PNG/SVG через [plantuml.com](https://www.plantuml.com/plantuml) или локально.
5. **Пояснения:** выбрать удобный вариант (a–e) в папке `explanations_*`.
