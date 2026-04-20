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

## [2026-04-19] ingest | OAGCC 117/2025 — modificarea unor acte normative cadastrale

**Fișier sursă:** `raw/sources/oagcc-117-2025-modificari.pdf` (redenumit din 151838.pdf)
**Anexe:** `raw/sources/ORDIN Nr. 117/` (an. 9, 16a, 24, 25)

**Creat:**
- `wiki/sources/oagcc-117-2025-modificari.md` — analiza completă: modificări la Ordin 07, 71, 70; abrogare Ordin 108

**Actualizat:**
- `wiki/sources/ordin-arfc-07-2015-cladiri.md` — menționat modificat + Cap. VI nou
- `wiki/sources/ordin-arfc-71-2017-formare.md` — secțiune nouă cu modificările OAGCC 117
- `wiki/sources/ordin-arfc-70-2017-teren.md` — menționat modificat
- `wiki/concepts/urbanism-constructii.md` — procedura lucrărilor simplificate art. 387 (din 05.01.2026)
- `wiki/index.md`

**Puncte cheie:**
- Cap. VI Ordin 07 (nou): lucrări cadastrale simplificate pentru case neautorizate art. 387 CUC
- Clădiri neautorizate se marchează „Clădire neautorizată" în planul geometric
- PUG publicat pe web APL înlocuiește certificatul de urbanism informativ (Ordin 71)
- Interdicție: comasarea terenurilor din UAT diferite
- Ordin ARFC 108/2016 ABROGAT prin art. 4 al prezentului ordin

---

## [2026-04-19] update | Ordin ARFC 108/2016 — marcat ABROGAT

Ordin ARFC 108/2016 (schema de amplasare) **ABROGAT** prin OAGCC 117/2025, în vigoare 05.01.2026.

**Actualizat:**
- `wiki/entities/arfc.md` — mutat din „în vigoare" în secțiunea „abrogate"
- `wiki/concepts/cadastru-bunuri-imobile.md` — referință actualizată; procedura de schema de amplasare rămâne reglementată de art. 71.5 HG 201/2025
- `wiki/sources/legislatia-cadastrului-index.md` — stare actualizată

⚠️ OAGCC 117/2025 (înlocuitor) — neingerat încă în wiki.

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

## [2026-04-19] ingest | LP 1543/1998 · OARFC 17/2021 · LP 187/2022 · HG 43/2026

**Fișiere sursă:**
- `raw/sources/lp-1543-1998-cadastru.pdf` (redenumit din 150224.pdf)
- `raw/sources/oarfc-17-2021-clasificator-terenuri.pdf` + `raw/sources/OARFC17 2021/clasifcatorul terenurilor_17-md.doc` (redenumit din 131277.pdf)
- `raw/sources/lp-187-2022-condominiu.pdf` (redenumit din 148246.pdf)
- `raw/sources/hg-43-2026-modificari-cadastru.pdf` (redenumit din 152961.pdf)

**Creat:**
- `wiki/sources/lp-1543-1998-cadastru.md` — legea-cadru: definiții, 11 tipuri lucrări (LP176/2025), executanți, registrator, transparența datelor
- `wiki/sources/oarfc-17-2021-clasificator-terenuri.md` — clasificator complet: 6 categorii, 50+ coduri de destinație și folosință
- `wiki/sources/lp-187-2022-condominiu.md` — condominiu: cot-parte, asociație proprietari, conexiunea cu RBI
- `wiki/sources/hg-43-2026-modificari-cadastru.md` — acte modificate: HG 201/2025 (nomenclator + parafa + 167.3.7), HG 437/2019, HG 1518/2003, HG 130/2025

**Actualizat:**
- `wiki/concepts/cadastru-bunuri-imobile.md` — adăugate 11 tipuri de lucrări (LP176/2025) + surse noi
- `wiki/concepts/fond-funciar.md` — referință la clasificatorul OARFC 17
- `wiki/index.md`

**Puncte cheie:**
- LP 1543/1998 art. 14 (LP176/2025): 11 tipuri de lucrări cadastrale enumerate explicit; recepția = obligatorie, efectuată de IP CBI
- LP 1543/1998 art. 15 (LP176/2025): executanții = entități juridice cu cel puțin 1 inginer cadastral certificat; răspunderea = inginerul cadastral
- OARFC 17/2021: 6 categorii × 50+ moduri de folosință cu cod unic; utilizat la întocmirea documentației cadastrale
- LP 187/2022: cot-parte = suprafața unității / suma tuturor unităților; calcul cote-părți = lucrare cadastrală (art. 14 lit. j LP 1543)
- HG 43/2026 (12.03.2026): nomenclatorul clădirilor + poziția 16 „Clădire auxiliară"; nomenclatorul terenurilor + 4.7 „Garaje"; extrase gratuite limitate la 1/an/persoană; IP CBI preia Registrul adreselor de la ASP

---

## [2026-04-19] update | Entități noi + pagini de synthesis

**Entități create:**
- `wiki/entities/oct.md` — OCT: Oficiul Cadastral Teritorial, structura teritorială IP CBI; registrator-șef; competență teritorială
- `wiki/entities/pdse.md` — PDSE: platforma electronică a notarilor pentru depunerea cererilor în RBI (obligatorie HG 201/2025 art. 35)
- `wiki/entities/inst.md` — INST: Inspectoratul Național pentru Supraveghere Tehnică; recepție construcții; Registrul de stat CUC art. 10

**Synthesis create:**
- `wiki/synthesis/inregistrare-casa-noua.md` — flux complet: autorizare CUC → recepție → lucrare cadastrală Ordin 07 → înregistrare RBI HG 201
- `wiki/synthesis/inregistrare-casa-neautorizata-art387.md` — procedura excepțională art. 387 CUC; lucrare simplificată Cap. VI Ordin 07; notare permanentă RBI; termen 30.01.2028
- `wiki/synthesis/formarea-bunurilor-imobile-alegerea-caii.md` — tabel decizie 5 căi; documente per cale; cine semnează (Ordin 71 + OAGCC 117)

**Actualizat:** `wiki/index.md`

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

---

## [2026-04-19] monitor | Modificări legislative detectate

Perioadă acoperită: 2026-04-18 → 2026-04-19. Acces direct agcc.gov.md blocat (HTTP 403); surse: WebSearch pe gov.md, legis.md, monitorul.gov.md, mass-media.

**Acte noi identificate (1, cu nr. final nepublicat):**
- LP 147-MIDR-2026 — Lege prelungire termen privatizare locuințe de stat: 31.05.2026 → 31.05.2029; abrogă norma LP 187/2022 privind numărul cadastral separat al camerelor izolate; adoptat de Parlament ~08–12.04.2026, promulgare în așteptare

**Procese în derulare cu impact cadastral:**
- Consultări publice reevaluare masivă 6 milioane bunuri imobile — termen 30.04.2026 (geodata.gov.md); contestații la OCT 90 zile; valori noi în vigoare 01.01.2027
- Aerofotografiere teritoriu RM (AGCC) — 20.03–30.04.2026, actualizare ortoimagini

**Acte modificate:** niciuna detectată
**Acte abrogate:** niciuna nouă față de sesiunea precedentă

Raport detaliat: `wiki/synthesis/monitoring/2026-04-19-modificari-legislative.md`

---

## [2026-04-20] monitor | Fără modificări legislative

Perioadă acoperită: 2026-04-19 → 2026-04-20. Acces direct agcc.gov.md blocat (HTTP 403); surse: WebSearch pe agcc.gov.md, legis.md, monitorul.gov.md, gov.md, mass-media.

Nu au fost identificate acte normative noi, modificate sau abrogate față de sesiunea precedentă în domeniile geodezie, cartografie, cadastru, evaluare bunuri imobile și date spațiale.

**Situație în curs (neschimbată față de 2026-04-19):**
- LP 147-MIDR-2026 — Lege privatizare locuințe: votat în prima lectură (08.04.2026), a doua lectură și promulgarea în așteptare
- Consultări publice reevaluare masivă bunuri imobile — termen 30.04.2026 (geodata.gov.md)
- Aerofotografiere teritoriu RM (AGCC) — în derulare până 30.04.2026
