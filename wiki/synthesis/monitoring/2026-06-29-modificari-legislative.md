# Modificări legislative detectate — 2026-06-29

**Dată:** 2026-06-29
**Perioadă acoperită:** 2026-06-22 → 2026-06-29
**Sesiune anterioară:** sesiunea din 2026-06-22 (eșec verificare, fără raport — vezi `wiki/log.md`)

## Notă privind accesul la sursă

Acces direct blocat (`HTTP 403 / host_not_allowed`) pentru: `agcc.gov.md/content/legislatia`, `agcc.gov.md/content/ingeocad`, `particip.gov.md`, `gov.md/sites/default/files/media/documents/sedinte-de-guvern/...` (PDF-uri proiecte de hotărâri), `gov.md/ro/sedinte-de-guvern/...` (pagini ședințe). Blocarea persistă de peste 5 săptămâni (din 2026-05-25). Toate constatările de mai jos provin din **WebSearch** (fragmente indexate), nu din citirea directă a documentelor sursă — necesită confirmare manuală.

## Act nou identificat — proiect 342/AGCC/2026 (rezolvă gap-ul INGEOCAD semnalat din 2026-06-08)

Fragmente indexate indică un proiect de Hotărâre de Guvern cu identificator **342/AGCC/2026**, care **modifică HG 959/2023** (organizarea și funcționarea AGCC) prin restructurarea domeniului geodezie-cartografie-cadastru și modificarea altor acte normative conexe. Conform surselor indirecte, acest proiect a fost **aprobat într-o ședință de guvern recentă** (coincide temporal cu ședința din 24.06.2026, în interiorul perioadei monitorizate).

Conținutul confirmă elementul deja semnalat fără sursă din 2026-06-08: **Întreprinderea de Stat „INGEOCAD"** se reorganizează prin transformare în **Instituție Publică „Institutul de Geodezie, Prospecțiuni Tehnice și Cartografie — INGEOCAD"**, fondator AGCC, succesoare de drepturi/obligații, efectiv din **01.07.2026** (peste 2 zile de la data acestui raport).

**Stare confirmare:** identificatorul de proiect (342/AGCC/2026) este confirmat din mai multe interogări; **numărul final al Hotărârii de Guvern, așa cum va apărea în Monitorul Oficial, nu a putut fi confirmat** — nu a fost încă identificat în legis.md sau Monitorul Oficial la data acestei verificări.

**Acțiune recomandată:** verificare manuală prioritară (acces uman la `gov.md/ro/sedinte-de-guvern/sedinta-guvernului-din-24-iunie-2026-ora-1000` și/sau `legis.md`) pentru numărul final al HG, înainte de intrarea în vigoare a reorganizării (01.07.2026). Dacă se confirmă, necesită: intrare nouă în `legislatia-cadastrului-index.md` (categoria 04 — HG, ca modificare la HG 959/2023) și entitate nouă `wiki/entities/ingeocad.md`.

## Proces operațional — extindere termen contestații evaluare în masă

Conform comunicatelor AGCC indexate: termenul de contestare pentru rezultatele evaluării caselor din mediul rural (evaluate pentru prima dată, date publicate ulterior lansării din 26.01.2026) a fost **extins până la 31.07.2026** — alinia cu termenul deja cunoscut pentru Faza 2 (imobile comerciale/industriale, OAGCC 42/2026). Nu este un act normativ nou, ci o extindere operațională a termenului anunțat anterior (30.04.2026 → 31.07.2026 pentru segmentul rural). Valorile noi validate intră în vigoare **01.01.2027** (neschimbat).

## Acte candidate reportate, neconfirmate — fără evoluție în această perioadă

Următoarele rămân neconfirmate față de sesiunea din 2026-06-08/2026-06-22, fără dovezi noi identificate în această sesiune:

| Nr. / Data | Denumire | Stare |
|---|---|---|
| HG 470/2025 | Accederea AGCC la TEGOVA și SPACE4GEO | Neconfirmat (2 mențiuni indirecte) |
| HG 494/2022 | Aderarea fostei ARFC la IVSC | Neconfirmat (1 mențiune) |
| LP 1308/1997 | Prețul normativ și vânzarea-cumpărarea pământului | Menționat ca înlocuit prin CF 22/2024 art.17(6), dar fără intrare proprie în index |
| LP 121/2007 | Administrarea și deetatizarea proprietății publice | Neconfirmat (1 mențiune) |
| Ordin AGCC 61/2023 | Grupuri de lucru INDS | Neconfirmat (1 mențiune) |

## Acte modificate

- **HG 959/2023** — posibil modificată prin proiectul 342/AGCC/2026 (vezi secțiunea de mai sus); neconfirmat definitiv.

## Acte abrogate

Niciuna nouă identificată față de sesiunile precedente (Ordin ARFC 112/2005 și Ordin ARFC 108/2016 rămân singurele abrogări confirmate în index).

## Surse verificate

| Sursă | Acces | Observație |
|-------|-------|-----------|
| agcc.gov.md (toate variantele) | ❌ HTTP 403 `host_not_allowed` | Blocat la nivel de rețea sandbox, persistent de 5+ săptămâni |
| particip.gov.md | ❌ HTTP 403 `host_not_allowed` | — |
| gov.md/sites/default/files/.../sedinte-de-guvern (PDF proiecte) | ❌ HTTP 403 | — |
| gov.md/ro/sedinte-de-guvern/... (pagini ședințe) | ❌ HTTP 403 | — |
| legis.md | ⚠️ Parțial (doar fragmente indexate, pagina nu se încarcă complet prin WebFetch) | — |
| WebSearch (Google) | ✅ | Sursa principală de constatări, toate indirecte |

## Notă metodologică

Toate constatările din acest raport sunt derivate din fragmente indexate de motorul de căutare (WebSearch), fără citire directă a documentului sursă oficial. Nivelul de confirmare este indicat explicit per constatare. Recomandare generală neschimbată față de sesiunile precedente: deblocarea `agcc.gov.md`/`particip.gov.md`/`gov.md` în allowlist-ul de rețea al mediului ar permite verificare directă și ar elimina ambiguitatea privind numărul final al HG 342/AGCC/2026.

## Surse și concepte legate

### Surse wiki
- [[../../sources/legislatia-cadastrului-index]]
- [[../../sources/oagcc-117-2025-modificari]]

### Concepte wiki
- [[../../concepts/evaluare-bunuri-imobile]]
- [[../../concepts/cadastru-bunuri-imobile]]
- [[../../concepts/geodezie-cartografie]]
- [[../../concepts/date-spatiale-inspire]]
