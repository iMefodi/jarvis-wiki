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

---

## [2026-04-18] ingest | HG 63/2026 — delimitare proprietate publică 2026-2028

- Creat: `wiki/sources/hg-63-2026-delimitare.md`
- Actualizat: `wiki/sources/legislatia-cadastrului-index.md` (înlocuit ⚠️ cu datele corecte)
- Actualizat: `wiki/concepts/fond-funciar.md` — proceduri noi delimitare masivă, plan de contur, termene
- Actualizat: `wiki/index.md`
- Fișier sursă: `raw/sources/hg-63-2026-delimitare.pdf`

Puncte cheie: program extins 2019–2028; Agenția Proprietății Publice înlocuiește IP CBI în coordonare; plan de contur electronic cu KEP; aprobul tacit după 3 zile notificare; Capitolul IV³ pentru rectificarea hotarelor delimitate anterior.

---

## [2026-04-18] ingest | Acte noi din monitorizare — 8 acte adăugate în wiki

- Actualizat: `wiki/sources/legislatia-cadastrului-index.md`
- Actualizat: `wiki/concepts/evaluare-bunuri-imobile.md` — OAGCC 49, 77, 123 / 2025
- Actualizat: `wiki/concepts/geodezie-cartografie.md` — HG 94, 100/2025; HG 118/2026 (SNP)
- Actualizat: `wiki/concepts/date-spatiale-inspire.md` — HG 91/2026 (INDS 2026–2030)
- ⚠️ HG 63/2026 marcat ca „de verificat manual"

---

## [2026-04-19] ingest | Ordine ARFC 70/07/71 — instrucțiuni tehnice cadastrale + anexe

**Fișiere sursă:**
- `raw/sources/ORDIN Nr. 70/` — 16 fișiere (lucrări la teren)
- `raw/sources/ORDIN Nr. 07/` — 27 fișiere (lucrări la clădiri)
- `raw/sources/ORDIN Nr. 71/` — 13 fișiere (formarea bunurilor imobile)

**Creat:**
- `wiki/sources/ordin-arfc-70-2017-teren.md` — aviz vecini, act restabilire/transpunere hotare, act plantații perene, act limită parte din teren
- `wiki/sources/ordin-arfc-07-2015-cladiri.md` — schiță teren/clădire/încăpere, fișă tehnică, calcul uzură (formulă), certificat inspecție
- `wiki/sources/ordin-arfc-71-2017-formare.md` — toate 5 căi de formare, tabel documente obligatorii per cale, cine semnează (agricol vs. construcții)

**Actualizat:** `wiki/index.md`

**Puncte cheie:**
- Ordin 70: transpunere/restabilire = GNSS/taheometru + borne; aviz vecini cu recipisă
- Ordin 07: uzura se calculează formulă element cu element; certificatul de inspecție = baza înregistrării în RBI
- Ordin 71: tabel documente — separare necesită transpunere în teren, divizare nu; reparcelare = prin documentație urbanistică; agricultur → inginer funciar primărie; construcții → arhitect-șef

---

## [2026-04-19] ingest | CUC 434/2023 — Codul Urbanismului și Construcțiilor

**Fișier sursă:** `raw/sources/cuc-434-2023-urbanism-constructii.pdf`

**Creat:**
- `wiki/sources/cuc-434-2023.md` — analiză completă: autorizare, recepție, art. 387, ridicare topografică de execuție
- `wiki/concepts/urbanism-constructii.md` — ciclul de viață al construcției, conexiunea cu cadastrul, termene-cheie

**Actualizat:** `wiki/index.md`

**Puncte cheie:**
- Exploatarea construcției = posibilă numai după recepție + înregistrare la organul cadastral
- Art. 387 alin. (4): înregistrare case neautorizate funcționale la 30.01.2024 — termen 30.01.2028
- Art. 220 alin. (4): ridicare topografică de execuție pentru rețele edilitare → APL în 30 zile
- LP334/29.01.2026: certificat de edificare gratuit dacă APL nu a stabilit taxă

---

## [2026-04-19] ingest | HG 201/2025 — Regulamentul privind înscrierea în RBI

**Fișier sursă:** `raw/sources/hg-201-2025-inscriere-rbi.pdf` (redenumit din 152980.pdf)
**Anexe:** `raw/sources/HOTARARE Nr. 201/` (an. 1 — structura RBI, an. 4 — nomenclator)

**Creat:**
- `wiki/sources/hg-201-2025-inscriere-rbi.md` — regulamentul complet: structura RBI (cap. A/B/C, subcap. I/II/III), procedura, termen 10 zile, 14 temeiuri de respingere, înregistrare provizorie, nomenclator 16 tipuri clădiri

**Actualizat:**
- `wiki/concepts/cadastru-bunuri-imobile.md` — procedura de înregistrare detaliată (HG 201 art. 25, 35, 40)
- `wiki/index.md`

**Puncte cheie:**
- Înlocuiește Instrucțiunea ARFC 112/2005 (din 16.05.2025)
- Termen examinare: ≤ 10 zile lucrătoare, prelungire max 40 zile
- Notarul OBLIGAT să depună cererea electronic prin PDSE
- Înregistrare primară necesită plan geometric recepționat
- Nomenclator: 16 tipuri clădiri, 7 categorii terenuri (Anexa 4)

---

## [2026-04-18] monitor | Modificări legislative detectate

Comparație față de `wiki/sources/legislatia-cadastrului-index.md`. Acces direct la agcc.gov.md blocat (HTTP 403); analiza s-a efectuat pe baza surselor secundare.

**Acte noi identificate (8):**
- HG 94/2025 — Conceptul Atlasului Național al RM (geodezie)
- HG 100/2025 — Conceptul SI „Registrul denumirilor geografice" (geodezie)
- HG 118/2026 — Conceptul SNP + Regulament privind Sistemul Național de Poziționare (geodezie)
- OAGCC 49/2025 — Modelul de evaluare loturi pomicole (evaluare)
- OAGCC 77/2025 — Modelul de evaluare garaje și locuri de parcare (evaluare)
- OAGCC 123/2025 — Instrucțiuni privind Rapoartele de evaluare imobiliară (evaluare)
- HG 91/2026 — Programul INDS 2026–2030 (date spațiale)
- HG 63/2026 — subiect neconfirmat, prezent în legis.md (de verificat)

**Acte modificate:** niciuna detectată
**Acte abrogate:** niciuna nouă față de wiki

Raport detaliat: `wiki/synthesis/monitoring/2026-04-18-modificari-legislative.md`
