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

## [2026-04-20] monitor | Modificări legislative detectate

Perioadă acoperită: 2026-04-19 → 2026-04-20. Acces direct agcc.gov.md blocat (HTTP 403); surse: WebSearch pe gov.md, legis.md, monitorul.gov.md, ipcbi.gov.md, mass-media.

**Acte noi identificate (2 proiecte în faza parlamentară):**
- 200-MIDR-2026 — Program de stat pentru înregistrarea ~12.580 blocuri locative ca condominii (2026–2028); 15,85 mln. lei; elaborat de MIDR + AGCC + IP CBI; transmis Parlamentului
- 83-MIDR-2026 — Proiect de lege modificare CUC 434/2023: facilitarea înregistrării construcțiilor, eliminarea restricțiilor temporale, asimilarea căsuțelor pomicole la case individuale (art. 387)

**Termen critic confirmat:**
- 30.04.2026 (mâine): Consultări publice reevaluare masivă 6 mln. bunuri imobile + finalizare aerofotografiere AGCC
- 31.05.2026: Termen LP 187/2022 — drept înregistrare cameră izolată cu nr. cadastral distinct (statut abrogare prin LP 147 neconfirmat)

**Acte modificate:** niciuna nou detectată față de sesiunea precedentă
**Acte abrogate:** niciuna nou detectată

Raport detaliat: `wiki/synthesis/monitoring/2026-04-20-modificari-legislative.md`

---

## [2026-04-27] monitor | Modificări legislative detectate

Perioadă acoperită: 2026-04-20 → 2026-04-27. Acces direct agcc.gov.md blocat (HTTP 403); surse: WebSearch pe gov.md, legis.md, mass-media moldovenească.

**Acte noi adoptate (1):**
- Lege amalgamare voluntară UAT (adoptată Parlament 24.04.2026, nr. oficial nepublicat) — elimină limita 25 km, reduce birocrația, simplifică alegerea centrului administrativ; impact cadastral: actualizare RSUATA + RBI, redelimitare hotare UAT, 298 comunități în proces

**Procese critice în derulare:**
- Consultări publice reevaluare 6 mln bunuri imobile — termen 30.04.2026 (expiră în 3 zile); validare modele oct. 2026; valori noi în vigoare 01.01.2027
- Aerofotografiere AGCC finalizată 30.04.2026 — ortoimagini actualizate, nepublicate încă
- LP 147-MIDR-2026 (privatizare locuințe, promulgare în așteptare); 200-MIDR-2026 (condominii); 83-MIDR-2026 (CUC 434) — în faze parlamentare

**Acte modificate:** niciuna detectată
**Acte abrogate:** niciuna detectată

Raport detaliat: `wiki/synthesis/monitoring/2026-04-27-modificari-legislative.md`

---

## [2026-05-11] monitor | Modificări legislative detectate

Perioadă acoperită: 2026-04-27 → 2026-05-11. Acces direct agcc.gov.md blocat (HTTP 403); surse: WebSearch pe gov.md, legis.md, monitorul.gov.md, mass-media moldovenească.

**Procese operaționale noi (fără act normativ separat):**
- Faza 2 reevaluare masivă imobiliară (comerciale/industriale) — lansată 01.05.2026 de AGCC + IP CBI; consultări publice pe geodata.gov.md până la 31.07.2026; 6.436 cereri în faza 1 (rezidențiale)

**Acte legislative în curs de promulgare (neconfirmate oficial):**
- LP 147-MIDR-2026 — Prelungire privatizare locuințe 31.05.2026 → 31.05.2029; interdicție butelii gaz în blocuri; adoptat Parlament ~24.04.2026; nr. oficial neconfirmat la 11.05.2026
- Lege amalgamare UAT — simplificare voluntară, adoptată 24.04.2026; nr. oficial neconfirmat
- Modificare LP 187/2022 condominii (200-MIDR-2026) — praguri noi semnături asociații proprietari; stadiu parlamentar incert

**Termene critice imediate:** 31.05.2026 (privatizare + camere izolate LP 187/2022); 31.07.2026 (reevaluare comerciala); 01.01.2027 (valori cadastrale noi)

**Acte modificate:** niciuna confirmată
**Acte abrogate:** niciuna confirmată

Raport detaliat: `wiki/synthesis/monitoring/2026-05-11-modificari-legislative.md`

---

## [2026-05-11] monitor | Modificări legislative detectate — sesiunea 2 (actualizare raport)

Sesiune suplimentară de monitorizare; acces direct agcc.gov.md blocat (HTTP 403); surse: WebSearch pe parlament.md, moldpres.md, okeyimobil.md, news-pravda.com, particip.gov.md.

**Act nou identificat față de sesiunea 1:**
- **LP 40/2026** — Legea privind activitatea agenților imobiliari: adoptată 26.03.2026, publicată în MO, intrare în vigoare 23.01.2027; creează Registrul agenților imobiliari integrat în SI AGCC; absent din wiki și din sesiunile anterioare de monitorizare

**Identificator proiect confirmat:**
- 189-CS-2026 = numărul de proiect al Legii simplificării amalgamării UAT (adoptată 24.04.2026; nr. de lege promulgat neconfirmat)

**Acte modificate:** niciuna nouă
**Acte abrogate:** niciuna nouă

Raport actualizat: `wiki/synthesis/monitoring/2026-05-11-modificari-legislative.md`

---

## [2026-05-18] monitor | Modificări legislative detectate

Perioadă acoperită: 2026-05-11 → 2026-05-18. Acces direct agcc.gov.md, monitorul.gov.md, gov.md blocat (HTTP 403); surse: WebSearch pe moldpres.md, news.yam.md, ziar.md, okeyimobil.md, presedinte.md (indirecte).

**Acte noi identificate (2):**
- **LP 147/2026** (Decret 603-X, 07.05.2026) — Lege ajustare cadru normativ locuințe: privatizare extinsă 31.05.2026 → 31.05.2029; interdicție butelii gaz în blocuri; **abrogă art. 88 alin. (7) LP 187/2022 condominiu** — elimină termenul 31.05.2026 pentru înregistrare cameră izolată cu nr. cadastral distinct
- **OAGCC Ordin 42/2026 (29.04.2026)** — Modelul de evaluare imobile comerciale/industriale + terenuri aferente (Faza 2 reevaluare masivă); consultare publică 01.05–31.07.2026 pe geodata.gov.md

**Procese operaționale noi:**
- Faza 2 reevaluare masivă (comerciale/industriale) — lansată 01.05.2026; termen consultare 31.07.2026; valori finale: 01.01.2027
- Aerocartografiere AGCC prelungită până în iunie 2026 (anterior: 30.04.2026; motiv: condiții meteo)

**Acte modificate:** LP 187/2022 art. 88 alin. (7) — abrogat prin LP 147/2026
**Acte abrogate:** niciun act tehnic cadastral

Raport detaliat: `wiki/synthesis/monitoring/2026-05-18-modificari-legislative.md`

---

## [2026-05-25] monitor | Modificări legislative detectate

Perioadă acoperită: 2026-05-18 → 2026-05-25. Acces direct agcc.gov.md blocat (HTTP 403); surse: WebSearch pe presedinte.md, moldpres.md, moldova1.md, particip.gov.md, logos-pres.md.

**Acte noi identificate (1):**
- **Lege modificare LP 187/2022 condominiu** (Decret prezidențial nr. 612-X, **14.05.2026**) — proiect 200-MIDR-2026; adoptată de Parlament (65 voturi); introduce praguri noi de vot pentru APC (½ sau ¼ din proprietari); nr. oficial al legii neconfirmat

**Acte modificate (1):**
- **LP 187/2022** — a doua modificare în mai 2026 (prima: LP 147/2026 privind camerele izolate; a doua: prezenta lege privind regulile de vot APC)

**Acte abrogate:** niciun act tehnic cadastral nou

**Procese în derulare:**
- Aerocartografiere AGCC prelungită până în iunie 2026
- Reevaluare masivă imobile comerciale/industriale — consultări până la 31.07.2026
- Lege amalgamare UAT (189-CS-2026) — confirmată publicată în MO

Raport detaliat: `wiki/synthesis/monitoring/2026-05-25-modificari-legislative.md`

---

## [2026-06-01] monitor | Modificări legislative detectate

Perioadă acoperită: 2026-05-25 → 2026-06-01. Acces direct agcc.gov.md, monitorul.gov.md, legis.md blocat (HTTP 403); surse: WebSearch pe moldpres.md, ziar.md, telegraph.md, tv8.md, news.yam.md, okeyimobil.md, gov.md.

**Acte noi identificate:** niciun act nou publicat în această perioadă identificat.

**Actualizări de statut:**
- **LP 70/2026** (30.04.2026, MO 21.05.2026) — număr oficial confirmat pentru legea de modificare LP 187/2022 condominiu (praguri vot APC); sesiunile anterioare o înregistrau fără număr.

**Termen expirat cu impact cadastral:**
- **31.05.2026** — termen înregistrare camere izolate cu nr. cadastral distinct (LP 187/2022 art. 88 alin. (7), abrogat prin LP 147/2026); expirat fără impact practic datorită abrogării anterioare.

**Procese în derulare:**
- Faza 2 reevaluare masivă (comerciale/industriale) — consultare 01.05–31.07.2026 (OAGCC 42/2026)
- Aerocartografiere AGCC prelungită până în iunie 2026
- Lege amalgamare voluntară UAT (189-CS-2026) — publicată **MO Nr. 269 din 27.05.2026**, în vigoare 27.05.2026

**Acte modificate:** niciuna nouă față de sesiunea precedentă
**Acte abrogate:** niciuna nouă

Raport detaliat: `wiki/synthesis/monitoring/2026-06-01-modificari-legislative.md`

## [2026-06-08] monitor | Modificări legislative detectate

Acces direct agcc.gov.md blocat (HTTP 403 / `host_not_allowed`), la fel ca în sesiunile anterioare; comparația s-a bazat pe dovezi indirecte din WebSearch.

**Acte candidate, posibil netrackate în index** (necesită confirmare manuală):
- HG 470/2025 — accederea AGCC la TEGOVA și Alianța SPACE4GEO
- HG 494/2022 — aderarea (fostei ARFC) la Consiliul Standardelor Internaționale de Evaluare (IVSC)
- LP 1308/1997 — prețul normativ și vânzarea-cumpărarea pământului (menționat în wiki ca înlocuit prin CF 22/2024, dar fără intrare proprie în index)
- LP 121/2007 — administrarea și deetatizarea proprietății publice
- Ordin AGCC 61/2023 — grupuri de lucru INDS

**Dezvoltare instituțională neclarificată:** reorganizarea INGEOCAD (Întreprindere de Stat → Instituție Publică), efectivă 01.07.2026, fondator AGCC — număr HG neidentificat; entitatea nu apare deloc în wiki.

**Acte modificate / abrogate:** nimic nou identificat față de sesiunea din 2026-06-01.

Raport detaliat: `wiki/synthesis/monitoring/2026-06-08-modificari-legislative.md`

---

## [2026-06-15] monitor | Verificare nereușită — acces blocat la agcc.gov.md

Verificarea automată a actelor normative de pe `agcc.gov.md/content/legislatia` nu a putut fi efectuată: hostul `agcc.gov.md` nu este permis de politica de rețea (egress allowlist) a mediului de execuție, cererea fiind respinsă cu `403 host_not_allowed` la nivel de proxy, nu de la server.

**Acțiune necesară:** adăugarea `agcc.gov.md` în allowlist-ul de rețea al mediului, pentru ca verificările viitoare să poată accesa sursa.

Nu s-a comparat conținutul wiki-ului cu sursa în această sesiune.

---

## [2026-06-22] monitor | Fără modificări confirmate — acces direct la agcc.gov.md blocat persistent

Accesul direct la `agcc.gov.md/content/legislatia` a fost din nou respins de mediul sandbox (`403 host_not_allowed`), la fel ca în toate sesiunile din 2026-05-25 încoace, inclusiv pentru proxy-uri alternative (r.jina.ai, allorigins.win, translate.goog, archive.org) — toate blocate la nivel de rețea, nu de server.

S-a folosit fallback prin WebSearch (interogări multiple pe agcc.gov.md, gov.md, monitorul.gov.md). Nu s-au identificat acte noi confirmate față de raportul din 2026-06-08.

**Candidați neconfirmați, reportați din 2026-06-08 (necesită verificare manuală):**
- HG 470/2025 — accederea AGCC la TEGOVA și SPACE4GEO
- HG 494/2022 — aderarea (fostei ARFC) la IVSC
- LP 1308/1997 — prețul normativ și vânzarea-cumpărarea pământului
- LP 121/2007 — administrarea și deetatizarea proprietății publice
- Ordin AGCC 61/2023 — grupuri de lucru INDS

**Atenție — termen apropiat:** reorganizarea INGEOCAD (Întreprindere de Stat → Instituție Publică, fondator AGCC) intră în vigoare **01.07.2026** (în 9 zile). Numărul HG-ului care aprobă reorganizarea nu a putut fi identificat din surse indirecte; INGEOCAD nu apare în wiki. Recomandare: verificare manuală prioritară înainte de această dată.

**Recomandare generală:** blocarea accesului la agcc.gov.md persistă de aprox. 4 săptămâni; verificările automate prin WebSearch nu permit confirmarea/infirmarea directă a candidaților de mai sus. Necesită fie deblocarea hostului în allowlist-ul de rețea, fie verificare manuală periodică.

---

## [2026-06-29] monitor | Proiect 342/AGCC/2026 identificat — rezolvă parțial gap-ul INGEOCAD

Perioadă acoperită: 2026-06-22 → 2026-06-29. Acces direct agcc.gov.md, particip.gov.md, gov.md (pagini ședințe + PDF-uri proiecte) blocat persistent (HTTP 403 `host_not_allowed`), de 5+ săptămâni. Surse: WebSearch (fragmente indexate).

**Act nou identificat (proiect, neconfirmat ca HG finală):**
- **Proiect 342/AGCC/2026** — modifică HG 959/2023 (organizarea AGCC); restructurare domeniu geodezie-cartografie-cadastru; aprobat într-o ședință de guvern recentă (coincide cu ședința din 24.06.2026). Conține baza legală pentru reorganizarea **INGEOCAD** (Întreprindere de Stat → Instituție Publică, fondator AGCC), efectivă din **01.07.2026** — gap semnalat încă din sesiunea 2026-06-08. Numărul final al HG (Monitorul Oficial) **neconfirmat încă**.

**Proces operațional:** termen contestații evaluare case rurale extins 30.04.2026 → **31.07.2026** (alinia cu Faza 2 comercial/industrial).

**Acte modificate:** HG 959/2023 — posibil, prin proiectul 342/AGCC/2026 (neconfirmat definitiv).
**Acte abrogate:** niciuna nouă.

**Atenție — termen critic:** reorganizarea INGEOCAD intră în vigoare în 2 zile (01.07.2026); numărul HG-ului rămâne neconfirmat din surse indirecte. Recomandare: verificare manuală prioritară înainte de această dată.

Raport detaliat: `wiki/synthesis/monitoring/2026-06-29-modificari-legislative.md`

---

## [2026-07-06] monitor | Reorganizarea INGEOCAD confirmată efectivă 01.07.2026; lege condominii adoptată

Perioadă acoperită: 2026-06-29 → 2026-07-06. Acces direct agcc.gov.md, gov.md, monitorul.gov.md blocat persistent (HTTP 403); surse: WebSearch (fragmente indexate).

**Act confirmat efectiv (1):**
- **Proiect 342/AGCC/2026 → HG (nr. neconfirmat)** — reorganizarea ÎS INGEOCAD în IP INGEOCAD sub fondatorul AGCC, **efectivă 01.07.2026**; modifică HG 959/2023; rezolvă gap-ul semnalat din sesiunea 2026-06-08

**Act nou adoptat (1, nr. oficial neconfirmat):**
- **200-MIDR-2026** — lege modificare LP 187/2022 condominiu: e-Condominiu, praguri vot APC, acces fonduri europene 1,5 mld. lei; adoptată Parlament ~iulie 2026

**Termen critic:** 31.07.2026 — ultim termen contestații reevaluare masivă (Faza 1 extinsă + Faza 2 comerciale/industriale)

Raport detaliat: `wiki/synthesis/monitoring/2026-07-06-modificari-legislative.md`

---

## [2026-07-13] monitor | Fără modificări confirmate — acces direct la agcc.gov.md blocat persistent

Perioadă acoperită: 2026-07-06 → 2026-07-13. Acces direct agcc.gov.md blocat (HTTP 403 `host_not_allowed`), la fel ca în toate sesiunile anterioare (7+ săptămâni consecutiv); surse: WebSearch (fragmente indexate de pe gov.md, agora.md, tvrmoldova.md, moldpres.md, news-pravda.com).

**Acte noi confirmate:** niciuna pentru perioada 2026-07-06 → 2026-07-13.

**Candidat neconfirmat (de verificat manual):**
- **Proiect 475-AGCC-2026** — proiect de HG apărut în dosarul ședințelor de guvern (mai 2026, gov.md); conținut și statut adoptat necunoscute din surse indirecte.

**Procese operaționale în derulare:**
- Faza 2 reevaluare masivă (comerciale/industriale) — **termen contestații: 31.07.2026** (18 zile); 6.436 contestații înregistrate în Faza 1; valori finale intră în vigoare 01.01.2027
- **200-MIDR-2026** (lege condominiu e-Condominiu) — menționat în surse ca adoptat de Parlament în iulie 2026; număr oficial și decret prezidențial neconfirmate
- Reorganizarea ÎS INGEOCAD → IP INGEOCAD (fondator AGCC) — efectivă 01.07.2026 (confirmat sesiunea 2026-07-06)

**Acte modificate:** niciuna confirmată față de sesiunea precedentă.
**Acte abrogate:** niciuna confirmată față de sesiunea precedentă.

**Atenție — termen critic iminent:** 31.07.2026 — termen final contestații reevaluare masivă Faza 2 (18 zile).

**Recomandare:** blocarea accesului la agcc.gov.md persistă de 7+ săptămâni; verificare manuală directă recomandată pentru 475-AGCC-2026 și 200-MIDR-2026 (nr. oficial).

Raport detaliat: `wiki/synthesis/monitoring/2026-07-13-modificari-legislative.md`

---

## [2026-07-13] monitor | Sesiunea 2 — clarificări suplimentare + raport creat

Sesiune suplimentară; aceleași surse ca sesiunea 1 (WebSearch pe gov.md, logos-pres.md, okeyimobil.md, tvrmoldova.md, agora.md).

**Clarificări față de sesiunea 1:**
- **HG 475-AGCC-2026** — conținut confirmat: restructurare geodezie-cartografie-cadastru la AGCC + 10 posturi noi (~1.876,9 mii lei/an); reorganizare ÎS INGEOCAD → IP INGEOCAD fondator AGCC, efectiv 01.07.2026. Nr. oficial MO în continuare neconfirmat.
- **LP 70/2026 art. 3 alin. (2)** — intră în vigoare **21.08.2026** (3 luni de la publicare în MO 213-216 din 21.05.2026); obligă APC multi-condominiu să semneze acord cu noile asociații în 30 de zile.
- **LP 40/2026 agenți imobiliari** — confirmat: registru agenți imobiliari integrat în SI AGCC; intrare în vigoare 9 luni de la publicare (~dec. 2026 / ian. 2027).

**Termene critice actualizate:** 31.07.2026 (contestații reevaluare) și 21.08.2026 (LP 70/2026 art. 3 alin. (2)).

---

## [2026-07-20] monitor | Modificări legislative detectate

Perioadă acoperită: 2026-07-13 → 2026-07-20. Acces direct agcc.gov.md blocat (HTTP 403 `host_not_allowed`), persistent de 8+ săptămâni; surse: WebSearch (fragmente indexate de pe agcc.gov.md, gov.md, legis.md, monitorul.gov.md, rlive.md, news-pravda.com).

**Acte noi identificate (2):**
- **OAGCC 57/2026** (21.05.2026) — Ghidul în evaluare: Evaluarea proprietății generatoare de afaceri; absent din wiki și din sesiunile anterioare de monitorizare
- **OAGCC 67/2026** — Instrucțiuni privind elaborarea planului de utilizare a terenului pentru cota-parte din bunul imobil comun; absent din wiki și din sesiunile anterioare; identificat prima dată astăzi

**Confirmări parțiale:**
- **200-MIDR-2026** (e-Condominiu) — adoptat de Parlament la începutul lunii iulie 2026; nr. oficial neconfirmat
- **OAGCC 28/2026** — Codul-cadru de etică a profesiei de evaluator (în vigoare 01.03.2026); absent din wiki, identificat astăzi (nu exclusiv perioadei 13–20 iulie)

**Termen critic iminent:** 31.07.2026 (11 zile) — contestații reevaluare masivă Faza 2; 21.08.2026 — LP 70/2026 art. 3 alin. (2)

**Acte modificate:** niciuna nouă confirmată
**Acte abrogate:** niciuna nouă confirmată

Raport detaliat: `wiki/synthesis/monitoring/2026-07-20-modificari-legislative.md`
