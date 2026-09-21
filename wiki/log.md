# Log

Hронологический append-only лог всех операций с вики.

---

## [2026-04-18] init | Инициализация базы знаний

Создана структура папок и базовые файлы:
- `raw/sources/`, `raw/web-clipped/`, `raw/assets/`
- `wiki/entities/`, `wiki/concepts/`, `wiki/sources/`, `wiki/synthesis/`
- `wiki/index.md`, `wiki/log.md`
- `CLAUDE.md`

---

## [2026-04-18] ingest | Legislatia Cadastrului - Catalog sistematizat (RM)

**Fisiere sursa:**
- `raw/sources/legislatia-cadastrului-index.html`
- `raw/sources/legislatia-cadastrului-readme.txt`

**Создано:**
- `wiki/sources/legislatia-cadastrului-index.md` - полный каталог 60+ актов по 7 категориям
- `wiki/entities/agcc.md` - AGCC (орган регулирования, с дек. 2023)
- `wiki/entities/ip-cbi.md` - IP CBI (оперативные кадастровые услуги, с 03.01.2024)
- `wiki/entities/arfc.md` - ARFC (ликвидирована, технические приказы действуют)
- `wiki/entities/inds.md` - INDS (инфраструктура пространственных данных)
- `wiki/concepts/cadastru-bunuri-imobile.md` - кадастр недвижимости, РНИ, типы работ
- `wiki/concepts/evaluare-bunuri-imobile.md` - оценка недвижимости, стандарты ИВСК
- `wiki/concepts/fond-funciar.md` - земельный фонд, новый Земельный кодекс
- `wiki/concepts/geodezie-cartografie.md` - геодезия, GNSS/MOLDPOS, топопланы
- `wiki/concepts/date-spatiale-inspire.md` - пространственные данные INSPIRE

**Ключевые факты из источника:**
- ARFC -> AGCC (реорганизация дек. 2023); создан IP CBI с 03.01.2024
- Новый Земельный кодекс CF 22/2024 - в силе с 07.03.2025
- HG 201/2025 заменяет Инструкцию ARFC 112/2005 (с 16.05.2025)
- Стандарты IVSC (SEV 100-233) - обязательны с 01.07.2025

---

## [2026-04-18] ingest | HG 63/2026 - delimitare proprietate publica 2026-2028

- Creat: `wiki/sources/hg-63-2026-delimitare.md`
- Actualizat: `wiki/sources/legislatia-cadastrului-index.md` (inlocuit cu datele corecte)
- Actualizat: `wiki/concepts/fond-funciar.md` - proceduri noi delimitare masiva, plan de contur, termene
- Actualizat: `wiki/index.md`
- Fisier sursa: `raw/sources/hg-63-2026-delimitare.pdf`

Puncte cheie: program extins 2019-2028; Agentia Proprietatii Publice inlocuieste IP CBI in coordonare; plan de contur electronic cu KEP; aprobul tacit dupa 3 zile notificare; Capitolul IV pentru rectificarea hotarelor delimitate anterior.

---

## [2026-04-18] ingest | Acte noi din monitorizare - 8 acte adaugate in wiki

- Actualizat: `wiki/sources/legislatia-cadastrului-index.md`
- Actualizat: `wiki/concepts/evaluare-bunuri-imobile.md` - OAGCC 49, 77, 123 / 2025
- Actualizat: `wiki/concepts/geodezie-cartografie.md` - HG 94, 100/2025; HG 118/2026 (SNP)
- Actualizat: `wiki/concepts/date-spatiale-inspire.md` - HG 91/2026 (INDS 2026-2030)
- HG 63/2026 marcat ca de verificat manual

---

## [2026-04-19] ingest | Ordine ARFC 70/07/71 - instructiuni tehnice cadastrale + anexe

**Fisiere sursa:**
- `raw/sources/ORDIN Nr. 70/` - 16 fisiere (lucrari la teren)
- `raw/sources/ORDIN Nr. 07/` - 27 fisiere (lucrari la cladiri)
- `raw/sources/ORDIN Nr. 71/` - 13 fisiere (formarea bunurilor imobile)

**Creat:**
- `wiki/sources/ordin-arfc-70-2017-teren.md`
- `wiki/sources/ordin-arfc-07-2015-cladiri.md`
- `wiki/sources/ordin-arfc-71-2017-formare.md`

**Actualizat:** `wiki/index.md`

---

## [2026-04-19] ingest | CUC 434/2023 - Codul Urbanismului si Constructiilor

**Fisier sursa:** `raw/sources/cuc-434-2023-urbanism-constructii.pdf`

**Creat:**
- `wiki/sources/cuc-434-2023.md`
- `wiki/concepts/urbanism-constructii.md`

**Actualizat:** `wiki/index.md`

**Puncte cheie:**
- Exploatarea constructiei = posibila numai dupa receptie + inregistrare la organul cadastral
- Art. 387 alin. (4): inregistrare case neautorizate functionale la 30.01.2024 - termen 30.01.2028
- Art. 220 alin. (4): ridicare topografica de executie pentru retele edilitare -> APL in 30 zile
- LP334/29.01.2026: certificat de edificare gratuit daca APL nu a stabilit taxa

---

## [2026-04-19] ingest | OAGCC 117/2025 - modificarea unor acte normative cadastrale

**Fisier sursa:** `raw/sources/oagcc-117-2025-modificari.pdf`

**Creat:**
- `wiki/sources/oagcc-117-2025-modificari.md`

**Actualizat:** `wiki/sources/ordin-arfc-07-2015-cladiri.md`, `wiki/sources/ordin-arfc-71-2017-formare.md`, `wiki/sources/ordin-arfc-70-2017-teren.md`, `wiki/concepts/urbanism-constructii.md`, `wiki/index.md`

**Puncte cheie:**
- Cap. VI Ordin 07 (nou): lucrari cadastrale simplificate pentru case neautorizate art. 387 CUC
- Ordin ARFC 108/2016 ABROGAT prin art. 4 al prezentului ordin

---

## [2026-04-19] update | Ordin ARFC 108/2016 - marcat ABROGAT

Ordin ARFC 108/2016 (schema de amplasare) ABROGAT prin OAGCC 117/2025, in vigoare 05.01.2026.

**Actualizat:** `wiki/entities/arfc.md`, `wiki/concepts/cadastru-bunuri-imobile.md`, `wiki/sources/legislatia-cadastrului-index.md`

---

## [2026-04-19] ingest | HG 201/2025 - Regulamentul privind inscrierea in RBI

**Fisier sursa:** `raw/sources/hg-201-2025-inscriere-rbi.pdf`

**Creat:**
- `wiki/sources/hg-201-2025-inscriere-rbi.md`

**Actualizat:** `wiki/concepts/cadastru-bunuri-imobile.md`, `wiki/index.md`

**Puncte cheie:**
- Inlocuieste Instructiunea ARFC 112/2005 (din 16.05.2025)
- Termen examinare: 10 zile lucratoare, prelungire max 40 zile
- Notarul OBLIGAT sa depuna cererea electronic prin PDSE

---

## [2026-04-19] ingest | LP 1543/1998 - OARFC 17/2021 - LP 187/2022 - HG 43/2026

**Creat:** `wiki/sources/lp-1543-1998-cadastru.md`, `wiki/sources/oarfc-17-2021-clasificator-terenuri.md`, `wiki/sources/lp-187-2022-condominiu.md`, `wiki/sources/hg-43-2026-modificari-cadastru.md`

**Actualizat:** `wiki/concepts/cadastru-bunuri-imobile.md`, `wiki/concepts/fond-funciar.md`, `wiki/index.md`

---

## [2026-04-19] update | Entitati noi + pagini de synthesis

**Entitati create:** `wiki/entities/oct.md`, `wiki/entities/pdse.md`, `wiki/entities/inst.md`

**Synthesis create:** `wiki/synthesis/inregistrare-casa-noua.md`, `wiki/synthesis/inregistrare-casa-neautorizata-art387.md`, `wiki/synthesis/formarea-bunurilor-imobile-alegerea-caii.md`

**Actualizat:** `wiki/index.md`

---

## [2026-04-18] monitor | Modificari legislative detectate

Comparatie fata de `wiki/sources/legislatia-cadastrului-index.md`. Acces direct la agcc.gov.md blocat (HTTP 403); analiza s-a efectuat pe baza surselor secundare.

**Acte noi identificate (8):**
- HG 94/2025 - Conceptul Atlasului National al RM (geodezie)
- HG 100/2025 - Conceptul SI Registrul denumirilor geografice (geodezie)
- HG 118/2026 - Conceptul SNP + Regulament privind Sistemul National de Pozitionare (geodezie)
- OAGCC 49/2025 - Modelul de evaluare loturi pomicole (evaluare)
- OAGCC 77/2025 - Modelul de evaluare garaje si locuri de parcare (evaluare)
- OAGCC 123/2025 - Instructiuni privind Rapoartele de evaluare imobiliara (evaluare)
- HG 91/2026 - Programul INDS 2026-2030 (date spatiale)
- HG 63/2026 - subiect neconfirmat, prezent in legis.md (de verificat)

**Acte modificate:** niciuna detectata
**Acte abrogate:** niciuna noua fata de wiki

Raport detaliat: `wiki/synthesis/monitoring/2026-04-18-modificari-legislative.md`

---

## [2026-04-19] monitor | Modificari legislative detectate

Perioada acoperita: 2026-04-18 -> 2026-04-19. Acces direct agcc.gov.md blocat (HTTP 403); surse: WebSearch pe gov.md, legis.md, monitorul.gov.md, mass-media.

**Acte noi identificate (1):**
- LP 147-MIDR-2026 - Lege prelungire termen privatizare locuinte de stat: 31.05.2026 -> 31.05.2029

**Acte modificate:** niciuna detectata
**Acte abrogate:** niciuna noua fata de sesiunea precedenta

Raport detaliat: `wiki/synthesis/monitoring/2026-04-19-modificari-legislative.md`

---

## [2026-04-20] monitor | Modificari legislative detectate

Perioada acoperita: 2026-04-19 -> 2026-04-20.

**Acte noi identificate (2 proiecte in faza parlamentara):**
- 200-MIDR-2026 - Program de stat pentru inregistrarea ~12.580 blocuri locative ca condominii
- 83-MIDR-2026 - Proiect de lege modificare CUC 434/2023

Raport detaliat: `wiki/synthesis/monitoring/2026-04-20-modificari-legislative.md`

---

## [2026-04-27] monitor | Modificari legislative detectate

Perioada acoperita: 2026-04-20 -> 2026-04-27.

**Acte noi adoptate (1):**
- Lege amalgamare voluntara UAT (adoptata Parlament 24.04.2026)

Raport detaliat: `wiki/synthesis/monitoring/2026-04-27-modificari-legislative.md`

---

## [2026-05-11] monitor | Modificari legislative detectate

Perioada acoperita: 2026-04-27 -> 2026-05-11.

**Procese operationale noi:** Faza 2 reevaluare masiva imobiliara (comerciale/industriale) - lansata 01.05.2026.

**Acte in curs de promulgare:** LP 147-MIDR-2026; Lege amalgamare UAT; 200-MIDR-2026

Raport detaliat: `wiki/synthesis/monitoring/2026-05-11-modificari-legislative.md`

---

## [2026-05-11] monitor | Modificari legislative detectate - sesiunea 2 (actualizare raport)

**Act nou identificat:** LP 40/2026 - Legea privind activitatea agentilor imobiliari (adoptata 26.03.2026, in vigoare 23.01.2027)

Raport actualizat: `wiki/synthesis/monitoring/2026-05-11-modificari-legislative.md`

---

## [2026-05-18] monitor | Modificari legislative detectate

Perioada acoperita: 2026-05-11 -> 2026-05-18.

**Acte noi identificate (2):**
- **LP 147/2026** (Decret 603-X, 07.05.2026) - abroga art. 88 alin. (7) LP 187/2022
- **OAGCC Ordin 42/2026 (29.04.2026)** - Modelul de evaluare imobile comerciale/industriale (Faza 2)

**Acte modificate:** LP 187/2022 art. 88 alin. (7) - abrogat prin LP 147/2026

Raport detaliat: `wiki/synthesis/monitoring/2026-05-18-modificari-legislative.md`

---

## [2026-05-25] monitor | Modificari legislative detectate

Perioada acoperita: 2026-05-18 -> 2026-05-25.

**Acte noi identificate (1):** Lege modificare LP 187/2022 condominiu (Decret 612-X, 14.05.2026)

**Acte modificate (1):** LP 187/2022

Raport detaliat: `wiki/synthesis/monitoring/2026-05-25-modificari-legislative.md`

---

## [2026-06-01] monitor | Modificari legislative detectate

Perioada acoperita: 2026-05-25 -> 2026-06-01.

**Actualizari de statut:** LP 70/2026 (30.04.2026, MO 21.05.2026) - numar oficial confirmat.

Lege amalgamare voluntara UAT (189-CS-2026) - publicata MO Nr. 269 din 27.05.2026.

Raport detaliat: `wiki/synthesis/monitoring/2026-06-01-modificari-legislative.md`

## [2026-06-08] monitor | Modificari legislative detectate

Acte candidate, posibil netrackate in index (necesita confirmare manuala):
- HG 470/2025, HG 494/2022, LP 1308/1997, LP 121/2007, Ordin AGCC 61/2023

Dezvoltare institutionala: reorganizarea INGEOCAD (IS -> IP), efectiva 01.07.2026, fondator AGCC.

Raport detaliat: `wiki/synthesis/monitoring/2026-06-08-modificari-legislative.md`

---

## [2026-06-15] monitor | Verificare nereusita - acces blocat la agcc.gov.md

Verificarea automata a actelor normative de pe `agcc.gov.md/content/legislatia` nu a putut fi efectuata: hostul `agcc.gov.md` nu este permis de politica de retea (egress allowlist).

---

## [2026-06-22] monitor | Fara modificari confirmate - acces direct la agcc.gov.md blocat persistent

Fallback prin WebSearch. Nu s-au identificat acte noi confirmate fata de raportul din 2026-06-08.

**Atentie:** reorganizarea INGEOCAD intra in vigoare 01.07.2026 (in 9 zile). Nr. HG neidentificat.

---

## [2026-06-29] monitor | Proiect 342/AGCC/2026 identificat - rezolva partial gap-ul INGEOCAD

Perioada acoperita: 2026-06-22 -> 2026-06-29.

**Act nou identificat (proiect):** Proiect 342/AGCC/2026 - modifica HG 959/2023; baza legala pentru reorganizarea INGEOCAD (IS -> IP, fondator AGCC), efectiva din 01.07.2026.

Raport detaliat: `wiki/synthesis/monitoring/2026-06-29-modificari-legislative.md`

---

## [2026-07-06] monitor | Reorganizarea INGEOCAD confirmata efectiva 01.07.2026; lege condominii adoptata

Perioada acoperita: 2026-06-29 -> 2026-07-06.

**Act confirmat efectiv (1):** Proiect 342/AGCC/2026 -> HG (nr. neconfirmat) - reorganizarea IS INGEOCAD in IP INGEOCAD sub fondatorul AGCC.

**Act nou adoptat (1, nr. oficial neconfirmat):** 200-MIDR-2026 - lege modificare LP 187/2022 condominiu: e-Condominiu.

Raport detaliat: `wiki/synthesis/monitoring/2026-07-06-modificari-legislative.md`

---

## [2026-07-13] monitor | Fara modificari confirmate - acces direct la agcc.gov.md blocat persistent

Perioada acoperita: 2026-07-06 -> 2026-07-13.

**Candidat neconfirmat:** Proiect 475-AGCC-2026.

**Atentie:** 31.07.2026 - termen final contestatii reevaluare masiva Faza 2.

Raport detaliat: `wiki/synthesis/monitoring/2026-07-13-modificari-legislative.md`

---

## [2026-07-13] monitor | Sesiunea 2 - clarificari suplimentare + raport creat

**Clarificari:**
- HG 475-AGCC-2026 - restructurare geodezie-cartografie-cadastru la AGCC + 10 posturi noi; reorganizare IS INGEOCAD -> IP INGEOCAD. Nr. MO neconfirmat.
- LP 70/2026 art. 3 alin. (2) - intra in vigoare 21.08.2026.
- LP 40/2026 agenti imobiliari - in vigoare 9 luni de la publicare (~ian. 2027).

---

## [2026-07-20] monitor | Modificari legislative detectate

Perioada acoperita: 2026-07-13 -> 2026-07-20.

**Acte noi identificate (3, confirmate din pagina de legislatie AGCC):**
- **OAGCC 57/2026** - Ghidul in evaluare: Evaluarea proprietatilor generatoare de venituri
- **OAGCC 67/2026** - Instructiunea privind planul partii de folosinta a bunului imobil (proprietate comuna)
- **HG 28/2026** - Codul-cadru de etica al profesiei de evaluator de bunuri imobile

Raport detaliat: `wiki/synthesis/monitoring/2026-07-20-modificari-legislative.md`

---

## [2026-07-27] monitor | Modificari legislative detectate

Perioada acoperita: 2026-07-20 -> 2026-07-27.

**Act nou identificat:** AGCC anunt 23.07.2026 - Initiere elaborare ordine AGCC de modificare a modelelor de evaluare imobiliara.

Raport detaliat: `wiki/synthesis/monitoring/2026-07-27-modificari-legislative.md`

---

## [2026-08-03] monitor | Modificari legislative detectate

Perioada acoperita: 2026-07-27 -> 2026-08-03.

**Acte noi confirmate:** niciun act normativ cadastral nou publicat (vacanta parlamentara august).

**Termen expirat (31.07.2026):** contestatii reevaluare masiva - 7.429 depuse (Faza 1+2).

Raport detaliat: `wiki/synthesis/monitoring/2026-08-03-modificari-legislative.md`

---

## [2026-08-10] monitor | Modificari legislative detectate

Perioada acoperita: 2026-08-03 -> 2026-08-10.

**Acte noi confirmate:** niciun act normativ cadastral nou publicat in Monitorul Oficial.

**Eveniment semnificativ:** sedinta Guvernului din 05.08.2026 a aprobat un proiect HG de modificare a HG 959/2023. Nr. oficial neconfirmat.

Raport detaliat: `wiki/synthesis/monitoring/2026-08-10-modificari-legislative.md`

---

## [2026-08-17] monitor | Modificari legislative detectate

Perioada acoperita: 2026-08-10 -> 2026-08-17.

**Acte noi confirmate:** niciun act normativ cadastral nou publicat in Monitorul Oficial (vacanta parlamentara august).

**Sedinta Guvernului 12.08.2026:** aprobata hotarare actualizare cadru normativ cadastral (protectie date personale + acces avocati RBI); nr. HG neconfirmat.

Raport detaliat: `wiki/synthesis/monitoring/2026-08-17-modificari-legislative.md`

---

## [2026-08-24] monitor | LP 70/2026 art. 3 alin. (2) intrat in vigoare 21.08.2026

Perioada acoperita: 2026-08-17 -> 2026-08-24.

**Eveniment legislativ confirmat:** LP 70/2026 art. 3 alin. (2) intrat in vigoare 21.08.2026; APC multi-condominiu: termen 21.09.2026.

Raport detaliat: `wiki/synthesis/monitoring/2026-08-24-modificari-legislative.md`

---

## [2026-08-31] monitor | Modificari legislative detectate

Perioada acoperita: 2026-08-24 -> 2026-08-31. Acces direct agcc.gov.md blocat (HTTP 403, 12+ saptamani consecutiv); surse: WebSearch pe gov.md (sedinte 19.08, 26.08.2026), rlive.md, telegraph.md, monitorul.gov.md (fragmente), legis.md (fragmente).

**Act confirmat (1):**
- **HG 221/2026** (29.04.2026, MO 198-201) - SI Registrul de evidenta a retelelor edilitare (LP 290/2024)

**Acte modificate (1, nr. MO neconfirmat):**
- **HG 463/2026** (19.08.2026) - modificare HG 161/2019 privind lista bunuri imobile proprietate publica de stat

**Candidati persistenti:** HG modificare HG 959/2023 (sedinta 05.08 + 12.08.2026, nr. neconf.); LP 200-MIDR-2026 (e-Condominiu, nr. LP); HG 475-AGCC-2026 (INGEOCAD, nr. MO)

**Termen critic urmator:** 21.09.2026 - APC multi-condominiu (LP 70/2026 art. 3 alin. (2))

Raport detaliat: `wiki/synthesis/monitoring/2026-08-31-modificari-legislative.md`

---

## [2026-09-07] monitor | Modificari legislative detectate

Perioada acoperita: 2026-08-31 -> 2026-09-07. Acces direct agcc.gov.md blocat (HTTP 403, 14+ saptamani consecutiv); surse: WebSearch pe gov.md, agcc.gov.md (fragmente indexate), legis.md (fragmente), privesc.eu, bani.md, logos-pres.md.

**Acte noi candidate (detectate, necesita confirmare manuala):**
- **OAGCC 79/2026** (08.07.2026) - Cerinte tehnice pentru produse cartografice si seturi de date digitale (neprezent in wiki)
- **OAGCC 91/2026** (14.08.2026) - Standarde ocupationale: Tehnician in evaluarea bunurilor imobile + Tehnician in cadastru (neprezent in wiki)

**Act conex cu impact indirect:**
- **LP 195/2024 + LP 160/2026** - Noua lege protectia datelor cu caracter personal (GDPR), in vigoare 23.08.2026; impact asupra accesului la datele RBI

**Sedinta Guvernului 02.09.2026:** 21 de proiecte, niciun act cadastral specific identificat.

**Candidati persistenti neconfirmati:** HG modificare HG 959/2023 (nr. MO); LP 200-MIDR-2026 / e-Condominiu (nr. LP); HG 475-AGCC-2026 / INGEOCAD (nr. MO)

**Termen critic urmator:** 21.09.2026 - APC multi-condominiu (LP 70/2026 art. 3 alin. (2))

Raport detaliat: `wiki/synthesis/monitoring/2026-09-07-modificari-legislative.md`

---

## [2026-09-14] monitor | Modificari legislative detectate

Perioada acoperita: 2026-09-07 -> 2026-09-14. Acces direct agcc.gov.md blocat (HTTP 403, 15+ saptamani consecutiv); surse: WebSearch pe agcc.gov.md (fragmente indexate), ziarulnational.md, ipn.md, bani.md, gov.md, monitorul.gov.md.

**Acte confirmate (2, din statut candidat neconfirmat):**
- **OAGCC 79/2026** (08.07.2026) — Cerinte tehnice ortoimagini si produse cartografice digitale (geodezie/INDS)
- **OAGCC 91/2026** (14.08.2026) — Standarde ocupationale: Tehnician evaluare bunuri imobile + Tehnician cadastru

**Proiect legislativ nou (prima lectura 10.09.2026):**
- Proiect LP — modificare LP 1543/1998: acces extins RBI (avocati, succesiuni, Min. Apararii) + reparcelare terenuri (procedura noua, competente noi AGCC); urmeaza lectura a doua

**Termen critic imediat:** 21.09.2026 — APC multi-condominiu (LP 70/2026 art. 3 alin. (2)), in 7 zile

Raport detaliat: `wiki/synthesis/monitoring/2026-09-14-modificari-legislative.md`

---

## [2026-09-21] monitor | Modificari legislative detectate

Perioada acoperita: 2026-09-14 -> 2026-09-21. Acces direct agcc.gov.md blocat (HTTP 403, 16+ saptamani consecutiv); surse: WebSearch pe radiochisinau.md, stiri.md, rlive.md, gov.md (sedinta 16.09.2026), ipcbi.gov.md, legis.md.

**Acte noi publicate MO:** niciun act cadastral/geodezic nou identificat in MO Nr. 448-461.

**Proiect legislativ nou (sedinta Guvern 16.09.2026):**
- Proiect MIDR (sec. stat V. Sipitca) — constructiile neautorizate nu vor mai putea fi inregistrate in cadastru; modificare LP 1543/1998; urmează Parlament

**Schimbare operationala (01.10.2026):**
- IP CBI reorganizare servicii teritoriale: 25+ localitati vor fi deservite de SCT proprii (nu mai prin Centre Multifunctionale ASP)

**Termen critic:**
- 21.09.2026 — APC multi-condominiu (LP 70/2026 art. 3 alin. (2)) SE IMPLINESTE ASTAZI

**Candidati persistenti:** HG mod. HG 959/2023; LP 200-MIDR-2026 (e-Condominiu); HG 475-AGCC-2026 (INGEOCAD) — niciuna confirmata cu nr. MO

Raport detaliat: `wiki/synthesis/monitoring/2026-09-21-modificari-legislative.md`
