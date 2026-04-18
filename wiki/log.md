# Log

Хронологический append-only лог всех операций с вики.

---

## [2026-04-18] init | Инициализация базы знаний

Создана структура папок и базовые файлы:
- `raw/sources/`, `raw/web-clipped/`, `raw/assets/`
- `wiki/entities/`, `wiki/concepts/`, `wiki/sources/`, `wiki/synthesis/`
- `wiki/index.md`, `wiki/log.md`
- `CLAUDE.md`

---

## [2026-04-18] ingest | Legislația Cadastrului — Catalog sistematizat (RM)

**Fișiere sursă:**
- `raw/sources/legislatia-cadastrului-index.html`
- `raw/sources/legislatia-cadastrului-readme.txt`

**Создано:**
- `wiki/sources/legislatia-cadastrului-index.md` — полный каталог 60+ актов по 7 категориям
- `wiki/entities/agcc.md` — AGCC (орган регулирования, с дек. 2023)
- `wiki/entities/ip-cbi.md` — IP CBI (оперативные кадастровые услуги, с 03.01.2024)
- `wiki/entities/arfc.md` — ARFC (ликвидирована, технические приказы действуют)
- `wiki/entities/inds.md` — INDS (инфраструктура пространственных данных)
- `wiki/concepts/cadastru-bunuri-imobile.md` — кадастр недвижимости, РНИ, типы работ
- `wiki/concepts/evaluare-bunuri-imobile.md` — оценка недвижимости, стандарты ИВСК
- `wiki/concepts/fond-funciar.md` — земельный фонд, новый Земельный кодекс
- `wiki/concepts/geodezie-cartografie.md` — геодезия, GNSS/MOLDPOS, топопланы
- `wiki/concepts/date-spatiale-inspire.md` — пространственные данные INSPIRE

**Ключевые факты из источника:**
- ARFC → AGCC (реорганизация дек. 2023); создан IP CBI с 03.01.2024
- Новый Земельный кодекс CF 22/2024 — в силе с 07.03.2025
- HG 201/2025 заменяет Инструкцию ARFC 112/2005 (с 16.05.2025)
- Стандарты IVSC (SEV 100–233) — обязательны с 01.07.2025
