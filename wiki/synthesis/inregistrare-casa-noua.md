# Cum se înregistrează o casă nouă în RBI

**Dată:** 2026-04-19

## Răspuns

Înregistrarea unei case individuale nou-construite (cu autorizație) parcurge 4 etape distincte: autorizare → construcție și recepție → lucrare cadastrală → înregistrare în RBI.

---

### Etapa 1: Autorizarea construcției

**Baza legală:** CUC 434/2023 art. 148

- Se obține **certificat de urbanism pentru proiectare** (obligatoriu dacă PUG are >10 ani; facultativ dacă <10 ani)
- Se depune cerere de **autorizație de construire** la APL (primărie)
- Autorizația include numărul cadastral al terenului

---

### Etapa 2: Execuție și recepție

**Baza legală:** CUC 434/2023 art. 192–223

- Se construiește conform autorizației
- La finalizare: **recepție la terminare** (pentru finanțare privată — o singură etapă)
- Comisia de recepție notifică **INST** ([[../entities/inst]])
- **Interdicție:** casa nu poate fi locuită sau exploatată înainte de recepție + înregistrare în RBI

---

### Etapa 3: Lucrarea cadastrală

**Baza legală:** Ordin ARFC 07/2015 (modificat prin OAGCC 117/2025); LP 1543/1998 art. 14 lit. d

Executată de o firmă autorizată (cu inginer cadastral certificat):

1. **Inspecția** clădirii (Schiță clădire — anexa 2): stare generală, rețele edilitare, dotări, stilul arhitectonic
2. **Măsurătorile** exterioare și interioare: planuri pe etaje, suprafețe pe încăperi
3. **Calculul uzurii fizice** (anexa 6): element cu element (fundații, pereți, planșee, acoperiș, pardoseală, goluri); formula: Σ(pondere × cotă × uzură) / Σ(pondere × cotă)
4. **Certificatul de inspecție** (anexele 9/10/11): document oficial emis de inginerul cadastral; conține date complete despre clădire; baza pentru înregistrarea în RBI
5. **Planul geometric** al terenului și clădirii
6. Depunerea documentației la [[../entities/ip-cbi]] ([[../entities/oct]]) pentru **recepția lucrării**

---

### Etapa 4: Înregistrarea în RBI

**Baza legală:** HG 201/2025; LP 1543/1998

- Cererea se depune la **OCT** (Oficiu Cadastral Teritorial) de pe raza imobilului
- Dacă actul este notarial (e.g., contract de superficie): **notarul depune obligatoriu prin PDSE** ([[../entities/pdse]])
- **Termen:** ≤ 10 zile lucrătoare (prelungibil max 40 zile)
- Construcția se înregistrează în **RBI Capitol A+B** (teren + clădire)
- Dacă există apartamente/unități izolate → se deschide suplimentar **Capitol C**

**Condiție obligatorie:** plan geometric recepționat + certificat de inspecție

---

### Structura înregistrării în RBI

| Capitol | Subcapitol | Conținut |
|---|---|---|
| A (teren) | I | Date teren: nr. cadastral, adresă, destinație, mod de folosință, suprafață |
| A (teren) | II | Drept de proprietate: proprietarul, IDNP, temeiul |
| B (clădire) | I | Date clădire: tip (din nomenclatorul HG 201/2025), suprafață, etaje |
| B (clădire) | II | Drept de proprietate |
| A+B | III | Grevări: ipotecă, servitute, interdicții etc. |

**Tipul clădirii** se stabilește conform Anexei 4 HG 201/2025 (16 tipuri): casă individuală = cod 1.

---

### Cronologie orientativă

| Etapă | Durată estimată |
|---|---|
| Obținere autorizație | 30–60 zile (depinde de APL) |
| Construcție | variabil |
| Recepție la terminare | 1–2 săptămâni |
| Lucrare cadastrală | 5–15 zile |
| Recepție lucrare la IP CBI | câteva zile |
| Înregistrare în RBI | ≤ 10 zile lucrătoare |

---

## Surse

- [[../sources/cuc-434-2023]] — autorizare, recepție, INST
- [[../sources/ordin-arfc-07-2015-cladiri]] — lucrarea cadastrală la clădiri, certificatul de inspecție
- [[../sources/hg-201-2025-inscriere-rbi]] — procedura de înregistrare în RBI
- [[../sources/lp-1543-1998-cadastru]] — tipurile de lucrări cadastrale, executanții

## Entități implicate

- [[../entities/ip-cbi]] / [[../entities/oct]] — recepția lucrării + înregistrarea în RBI
- [[../entities/inst]] — notificare la recepția construcției
- [[../entities/pdse]] — depunere electronică prin notar

## Concepte legate

- [[../concepts/cadastru-bunuri-imobile]]
- [[../concepts/urbanism-constructii]]
