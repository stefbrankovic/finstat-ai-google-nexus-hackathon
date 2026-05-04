# FinStat AI — CFO u džepu za srpskog preduzetnika

> **Google Nexus Hackathon 2026** · AI/ML solutions for real-world impact  
> Proof of Concept · April 2026

---

## Problem

Vlasnici malih i srednjih preduzeća u Srbiji su istovremeno CEO, CFO i pravni tim — bez ERP sistema i bez tima koji se bavi finansijama, računovodstvom i praćenjem regulative.

- **Finansijska magla** — stanje na računu vidljivo, ali cashflow, rizici i trendovi ostaju ispod radara
- **Regulatorna džungla** — eFakture, PDV, Zakon o radu se menjaju; pravni savetnici su skupi
- **Propuštene prilike** — milijarde dinara u grantovima i subvencijama prolaze nezapaženo

~120.000 MSP firmi u Srbiji: previše složene za Excel, premale za SAP.  
**Niko ih ne opslužuje direktno.**

---

## Rešenje

End-to-end platforma sa dva izlaza:

```
ULAZI                    AI Engine                 IZLAZI
─────────                ──────────                ──────
Bankovni račun    ──→    Baza podataka     ──→    Dashboard
eFakture          ──→    NLP analiza       ──→    AI Chatbot
Pravna legislativa──→    Prognoza          
                         Zakonska provjera 
```

### Dashboard
- Kompletna finansijska analitika i vizuelizacija
- Cashflow prognoza (90 dana) bazirana na ML
- Upozorenja i saveti u realnom vremenu

### AI Chatbot
- Finansijski i pravni savetnik prilagođen srpskom tržištu
- Kvartalni izveštaji na zahtev
- Strategija i plan razvoja biznisa

---

## Zašto sada? Zašto Srbija?

| | |
|---|---|
| **120.000** | MSP firmi — potencijalnih korisnika |
| **2023.** | eFakture postale obavezne — podaci su već digitalni |
| **0** | lokalnih AI rešenja koja prate domaću regulativu |
| **Leto 2026.** | Najavljeno uvođenje eOtpremnica |

PSD2 direktiva otvara bankarske API-je. SEF sistem generiše strukturirane podatke koje niko ne iskorišćava u punoj meri. Nema domaćeg konkurenta koji razume JSON, SEF i srpske zakonske akte.

---

## Biznis model (SaaS)

| Plan | Cena | Za koga |
|------|------|---------|
| Starter | 29€/mes | Preduzetnik koji počinje |
| **Pro** ⭐ | **69€/mes** | Firma 5–50 zaposlenih |
| Agency | 199€/mes | Računovođe & holdinzi |

Alternativni trošak: konsultant ~3.200€/god · advokat ~800€/god · propušteni grant ~5.000€+  
→ Pro plan štedi i do 60% vrednosti.

---

## Fazni plan

| Faza | Period | Šta |
|------|--------|-----|
| ✅ MVP | Hackathon → Q2 2026 | Banka (JSON), eFakture (JSON), Dashboard, AI Chatbot |
| Faza 2 | Q2–Q3 2026 | PDF akti, zakonska baza, pravni Q&A, upozorenja |
| Faza 3 | Q4 2026 | SEF integracija, mejlovi, konkursi i grantovi |

---

## Materijali

- 📊 [`presentation/FinStat_AI_pitch.pdf`](presentation/FinStat_AI_pitch.pdf) — pitch deck
- 🎥 [`demo/demo.mp4`](demo/demo.mp4) — video demonstracija sistema
- 🖼️ [`assets/`](assets/) — slike sa odbrane

---

## Tim

Projekat razvijen u okviru **Google Nexus Hackathon 2026**.

- [Stefan Branković](https://github.com/stefbrankovic) — system design, data pipeline, pitch prezentacija
- *(dodaj kolege i njihove GitHub/LinkedIn profile)*

---

## Tech stack

`Python` · `REST APIs` · `JSON` · `NLP` · `ML (cashflow forecasting)` · `Dashboard`
