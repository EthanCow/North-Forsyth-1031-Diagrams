<!-- TAB:overview -->

> **Internal working model only** — not legal advice, not client-facing. No structure is locked; obtain §1031 counsel opinion before Belara closes.

## The deal

Sell **Belara Apartments** ($20M, no debt) and defer gain by reinvesting into **North Forsyth Commerce Center** — ≈$50.3M ground-up industrial (≈327,600 SF, Forsyth County GA) with **Hanover Industrial LLC** as developer.

| | |
|---|---|
| **Belara seller (today)** | Titan Management — **must align with exchanger** (prefer **Kao Management Trust**) |
| **Belara buyer** | Strake Jesuit |
| **Commercial LP (term sheet)** | Kao Management Trust — 95% economics |
| **Developer** | Hanover Industrial LLC |
| **Land** | $6.5M · third-party seller · **under PSA** · unaffiliated |
| **Project cost** | ≈$50.3M · construction loan **≈60% LTC** |
| **QI** | **Riverway Title** |
| **EAT** | TBD |
| **Model Day 0** | **Sept 15, 2026** (Belara + NFCC land / construction start) |
| **Clocks** | Day 45 = Oct 30, 2026 · Day 180 = Mar 14, 2027 |

## Commercial term sheet (unsigned — economics to preserve)

| Item | Term |
|---|---|
| Equity | **95% / 5%** |
| Promote | **20 / 30 / 40%** over **10 / 14 / 18%** IRR |
| Dev fee | **4%** · GC **4.5%** of hard ($300K GMP advance) |
| Overruns | **100% controllable** → Sponsor · **shared** → pro rata |
| Guaranties | Sponsor → lender + JV |
| Close intent | **Simultaneous:** JV + GMP + loan + land + permit |

Hanover has **not signed**. We will submit a **restructured term sheet** — same dollars, different legal sequencing for §1031.

## Why the term sheet LLC (Day 1) conflicts with §1031

The term sheet gives Kao a **95% LLC membership interest** at closing. Post-TCJA, §1031 applies only to **real property** — a partnership/LLC interest is **not** like-kind ([IRC §1031(a)(1)](https://www.law.cornell.edu/uscode/text/26/1031), [Reg. §1.1031(a)-3](https://www.law.cornell.edu/cfr/text/26/1.1031(a)-3)). A ground-up build also requires **QI + EAT** parking — not in the term sheet's simultaneous JV close.

```mermaid
flowchart LR
  subgraph TS["Term sheet — LLC Day 1"]
    K["Kao\n95% LLC interest"]
    H["Hanover\n5% + promote"]
    JV["Delaware LLC\nowns project"]
    K --> JV
    H --> JV
  end
  subgraph REQ["§1031 needs"]
    QI["Riverway Title\nholds $20M"]
    EAT["EAT\nholds title 0–180d"]
    RP["Real property\nto exchanger"]
    QI --> EAT --> RP
  end
  TS -.->|"restructure required"| REQ
```

## Structure paths — compared (none locked)

| Path | What it is | Exchange (draft view) | Hanover gets equity |
|---|---|---|---|
| **A. Term sheet LLC** | JV Day 1 as written | **Fails** — LLC interest | Day 1 |
| **B. TIC + EAT** | Direct co-ownership at Day 180; promote as fee | Uncertain — counsel | Day 180 |
| **C. Exchange then §721** | 100% fee to Kao, then JV after seasoning | MLTN at best | After 12–24+ mo |
| **D. 100% + fee** | Kao owns forever; promote as incentive fee | Strongest exchange | Never (fee) |

**Our stance:** Whatever works — pick with counsel, not by label.

## Timeline & exchange equity draw

**Day 0 = Belara close** (IRS clocks start). Modeled aligned with **NFCC land close / construction start: Sept 15, 2026**. Party-by-party steps → **Kao tab**.

```mermaid
flowchart TB
  subgraph D0["Sept 15 · Day 0"]
    SK["Strake"]:::neutral
    QI["Riverway Title\n$20M"]:::neutral
    EAT["EAT on NFCC title"]:::neutral
    SK -->|"$20M"| QI
    QI -->|"$6.5M land"| EAT
  end
  subgraph D45["Oct 30 · Day 45"]
    ID["Kao identifies NFCC\nin writing to QI"]:::kao
  end
  subgraph BUILD["Oct 2026 – Mar 2027"]
    DR["QI releases funds\n→ EAT → Hanover GC"]:::neutral
  end
  subgraph D180["Mar 14 · Day 180"]
    DEED["EAT deeds property\n→ Kao LLC"]:::kao
  end
  D0 --> D45 --> BUILD --> D180
  classDef kao fill:#e3edf7,stroke:#1f3a5f,color:#0f2440;
  classDef neutral fill:#eef0f2,stroke:#7a8696,color:#333;
```

| Draw — **QI releases to EAT** (exchange equity first) | Calendar (model) | $ | Running total |
|---|---|---|---|
| Land | Sept 15, 2026 | 6.5M | 6.5M |
| Sitework | Oct–Nov 2026 | 5M | 11.5M |
| Foundations | Dec 2026–Feb 2027 | 10M | **21.5M** |

Full build ≈**11 months** (~Aug 2027). ≈$20M §1031 target met if work is **in place, paid QI → EAT → contractors, and documented** by Day 180. Remaining ≈$30M → **construction loan** (~60% LTC) after exchange equity is deployed.

## Hanover entity map (roles — names TBD at formation)

Pattern from Hanover's example deals + term sheet. **Hanover Construction Group** is the **GMP contractor** — not a JV equity holder on this chart.

```mermaid
flowchart TB
  HIND["Hanover Industrial LLC\nSponsor"]:::han
  LAND["Land acquisition SPV"]:::neutral
  INV["Investor LP 95%\n(Kao / Kao Trust)"]:::kao
  HAN5["Hanover GP/LP stack 5%\n+ promote"]:::han
  GC["Hanover Construction Group\nGMP · 4.5% hard\n(contractor only)"]:::han
  EATN["EAT / project entity\nholds title during build"]:::neutral
  HIND --> LAND
  HIND --> HAN5
  INV --> EATN
  HAN5 --> EATN
  LAND --> EATN
  GC -->|"GMP contract"| EATN
  classDef kao fill:#e3edf7,stroke:#1f3a5f,color:#0f2440;
  classDef han fill:#fbeede,stroke:#9c6b1e,color:#5a3d0e;
  classDef neutral fill:#eef0f2,stroke:#7a8696,color:#333;
```

## Key terms (short)

| Term | Meaning |
|---|---|
| **QI** | **Riverway Title** — holds $20M; Kao never touches proceeds |
| **EAT** | Holds title during build (up to 180 days) — provider TBD |
| **Boot** | Taxable if less than ≈$20M qualifying value in place by Day 180 |
| **Like-kind** | Real property only — not LLC/partnership interests |
| **Same taxpayer** | Belara seller = replacement recipient (resolve Titan vs Kao Trust) |

## Open before Belara PSA

1. **Exchangor entity** — align Titan Management → **Kao Management Trust** (preferred)  
2. **Structure path** — B, C, or D above — counsel review  
3. **EAT** provider · lender approval of chosen structure  
4. **Belara PSA** — QI/escrow language (Riverway Title)

## All parties — step index (model)

**Day 0 = Sept 15, 2026** (Belara + NFCC land). Detail by party → tabs.

| Step | When | Strake | Kao / family | Riverway (QI) | EAT | Hanover | Land seller | Lender |
|---|---|---|---|---|---|---|---|---|
| **1 Pre-close** | Before Sept 15 | PSA, diligence | Entity align, engage QI/EAT | Engagement docs | QEAA TBD | GMP + dev agreements | Land PSA | Term sheet / comfort |
| **2 Belara close** | Sept 15 | **$20M → QI**; deed in | Signs as seller; **no cash** | **Holds $20M** | — | — | — | — |
| **3 NFCC land** | Sept 15 | — | — | **$6.5M → EAT** | **On title** | — | **Paid $6.5M** | — |
| **4 ID letter** | Oct 30 | — | **Identifies NFCC to QI** | Receives ID | — | — | — | — |
| **5 Construction** | Oct–Feb | — | — | **Draws → EAT** | Pays GC | **GMP / builds** | — | Loan later (~60% LTC) |
| **6 Exchange close** | Mar 14, 2027 | — | **Receives deed** via LLC | Closes exchange | **Deeds → Kao LLC** | Still GC | — | — |
| **7 Post-180** | ~Aug 2027 | — | Owns / operates | — | Dissolved | JV path **OPEN** | — | Funds balance |

<!-- TAB:strake -->

## Your role

**Buyer of Belara Apartments only** — **Strake Jesuit**. You purchase the relinquished property so Kao's family can run a §1031 exchange into North Forsyth. You are **not** a party to NFCC, the EAT, Hanover's development, or any exchange filing.

| Role | Party |
|---|---|
| **What you buy** | Belara Apartments — **$20M**, no debt |
| **Seller** | **Titan Management** today (may align to **Kao Management Trust** — not your problem to structure) |
| **Your counsel** | Your attorneys — PSA, diligence, institutional requirements |
| **Escrow / title** | Closing agent per PSA |
| **QI (exchange)** | **Riverway Title** — **your wire destination** at closing |
| **North Forsyth** | **Not involved** — different property, different parties |

## Why your closing matters for the exchange

Kao defers tax only if Belara sale proceeds go **directly to a Qualified Intermediary** — not to the seller. Your purchase price is the **$20M exchange pool** that funds NFCC land and construction. If proceeds wire to Titan/Kao instead of **Riverway Title**, the exchange fails.

You do **not** need to understand EATs or replacement property — but you **must** close with escrow instructions that send **net proceeds to Riverway Title**.

## Key dates (your involvement only)

| Milestone | Date (model) | Your action |
|---|---|---|
| **PSA signed** | Before Sept 15 | Agree price, diligence, closing logistics |
| **Day 0 — Belara close** | **Sept 15, 2026** | Wire **$20M** through escrow → **Riverway Title**; receive Belara deed |
| **After Day 0** | — | **Nothing** on NFCC, construction, or §1031 |

Modeled same day as NFCC land close for Kao's clocks — **your** obligation is only the Belara purchase.

## Step 1 — Pre-close (before Sept 15)

```mermaid
flowchart TB
  ST["Strake\nPSA + diligence"]:::neutral
  K["Kao / Titan\ncounsel"]:::kao
  QI["Riverway Title\nQI engaged"]:::neutral
  ESC["Escrow agent\ndraft instructions"]:::neutral
  ST --> ESC
  K --> QI
  QI --> ESC
  ESC -->|"instructions: proceeds to QI"| ST
  classDef kao fill:#e3edf7,stroke:#1f3a5f,color:#0f2440;
  classDef neutral fill:#eef0f2,stroke:#7a8696,color:#333;
```

| Who | What |
|---|---|
| **Strake** | Complete diligence (title, survey, environmental, gift/institutional items on your side) |
| **Strake counsel** | Review PSA; confirm closing statement |
| **Kao / seller counsel** | Engage **Riverway Title** as QI; draft exchange + escrow language |
| **Escrow** | Instructions: **net sale proceeds wire to Riverway Title**, not seller |
| **Strake** | Approve escrow instructions before close |

**You do not** select the EAT, sign GMP, or approve NFCC identification.

## Step 2 — Day 0: Belara closing (Sept 15, 2026)

This is your **only** day in the transaction.

```mermaid
flowchart LR
  ST["Strake Jesuit"]:::neutral
  ESC["Escrow"]:::neutral
  QI["Riverway Title\nQI"]:::neutral
  SEL["Titan / Kao\nseller"]:::kao
  BEL["Belara deed"]:::asset
  ST -->|"$20M purchase"| ESC
  ESC -->|"$20M net proceeds"| QI
  ESC --> BEL --> ST
  SEL -.->|"signs deed"| BEL
  classDef kao fill:#e3edf7,stroke:#1f3a5f,color:#0f2440;
  classDef neutral fill:#eef0f2,stroke:#7a8696,color:#333;
  classDef asset fill:#e5efe9,stroke:#2d6a4f,color:#14402e;
```

| From | To | $ | Note |
|---|---|---|---|
| **Strake Jesuit** | **Escrow** | **$20M** | Purchase price per PSA |
| **Escrow** | **Riverway Title** | **$20M** (net) | **Required** for §1031 — not to seller |
| **Seller** | **Strake** | — | Deed to Belara |

**You receive** title to Belara. **You do not** send money to North Forsyth, Hanover, or an EAT.

## Step 3 — After closing: what you do not do

| Topic | Strake involvement |
|---|---|
| North Forsyth / NFCC | **None** |
| EAT, construction, 180-day clock | **None** — Kao's exchange |
| Hanover JV, GMP, promote | **None** |
| Form 8824 or IRS filings | **None** — exchanger's return |
| Day 45 identification | **None** |
| Construction loan | **None** |

> Gift-acceptance or other institutional requirements are **your** legal matters — separate from the exchange.

## Escrow checklist (for your counsel)

- [ ] QI (**Riverway Title**) named in escrow instructions as proceeds recipient  
- [ ] Seller does **not** receive sale proceeds at closing  
- [ ] Closing date coordinated with Kao (modeled **Sept 15, 2026**)  
- [ ] No side letter directing proceeds elsewhere  

**Sources:** [Treas. Reg. §1.1031(k)-1](https://www.law.cornell.edu/cfr/text/26/1.1031(k)-1) · [IRS Like-Kind Exchanges](https://www.irs.gov/businesses/small-businesses-self-employed/like-kind-exchanges-real-estate-tax-tips)

<!-- TAB:hanover -->

## Your role

**Hanover Industrial LLC** = **Sponsor** on the unsigned term sheet — development manager, loan/JV guarantor, and target **5% + promote** economics. **Hanover Construction Group** (affiliate) = **GMP contractor** — 4.5% of hard costs; **not** a JV equity holder on the org chart.

**Legal structure is not locked.** Term sheet assumes **LLC JV Day 1**; §1031 requires **restructure** (EAT holds title during build; your equity/promote timing **OPEN**). **Commercial dollars** (fees, promote, guaranties) are what we aim to preserve.

| Role | Entity |
|---|---|
| **Sponsor / developer** | **Hanover Industrial LLC** — 4% dev fee, guaranties, 5% + promote (timing OPEN) |
| **GC / GMP** | **Hanover Construction Group** — contracts with **EAT / project entity**, not Kao directly |
| **Investor side** | **Kao Management Trust** — 95% economics on term sheet |
| **Title during build** | **EAT** (TBD) — legal owner Days 0–180 |
| **Exchange funds** | **Riverway Title (QI)** → EAT — not Hanover's balance sheet |
| **Construction loan** | Third-party lender — **~60% LTC**; you guaranty per term sheet |

## Why §1031 changes your closing sequence

Term sheet: **simultaneous** JV + GMP + loan + land + permit — Kao gets **95% LLC membership** Day 1. That **breaks §1031** (LLC interest ≠ like-kind real property). Restructured model:

1. **EAT** holds NFCC title and borrows during **180-day** exchange window  
2. **You** contract as **developer + GC** to the **EAT** — paid from QI draws, then construction loan  
3. **Your 5% + promote** enters **later** (Day 180 co-ownership, post-exchange §721 JV, or fee-only path) — **counsel picks**

Your fees and guaranties can start in Phase 1; **your equity membership** likely cannot.

## Key dates (Hanover — model)

| Milestone | Date | Hanover role |
|---|---|---|
| **Pre-close** | Before Sept 15 | Execute **GMP** + dev agreements with **EAT**; lender guaranty docs |
| **Day 0** | **Sept 15, 2026** | **GMP effective**; land closes to **EAT** (not to JV LLC); you do **not** close Belara |
| **Construction** | Oct 2026 – Feb 2027 | **Invoice EAT** under GMP; build sitework + foundations |
| **Day 180** | **Mar 14, 2027** | EAT deeds to **Kao LLC**; you remain **GC**; equity path **OPEN** |
| **Full build** | ~**Aug 2027** | Complete building; loan funds balance of ~$50.3M project |

## Step 1 — Pre-close (before Sept 15)

```mermaid
flowchart TB
  HIND["Hanover Industrial LLC\nSponsor"]:::han
  GC["Hanover Construction Group\nGMP draft"]:::han
  EAT["EAT TBD\nproject counterparty"]:::neutral
  LN["Construction lender\n60% LTC"]:::neutral
  K["Kao / QI\nexchange structure"]:::kao
  HIND --> GC
  GC -->|"GMP with"| EAT
  HIND -->|"guaranty package"| LN
  EAT --> LN
  K --> EAT
  classDef han fill:#fbeede,stroke:#9c6b1e,color:#5a3d0e;
  classDef kao fill:#e3edf7,stroke:#1f3a5f,color:#0f2440;
  classDef neutral fill:#eef0f2,stroke:#7a8696,color:#333;
```

| Who | What |
|---|---|
| **Hanover Industrial** | Negotiate restructured economics; dev management agreement (4%) with **EAT** |
| **Hanover Construction Group** | Finalize **GMP** — 4.5% hard, $300K advance, 5% contingency — **contractor to EAT** |
| **Hanover** | Loan completion + overrun **guaranties** per term sheet — lender lends to **EAT** |
| **EAT** | Formed/engaged; signs QEAA with exchanger; holds title |
| **Not yet** | Delaware JV LLC with Kao 95% — **deferred** until structure path chosen |

## Step 2 — Day 0: land close (Sept 15, 2026)

You are **not** at the Belara closing. NFCC land closes **same day** for exchange alignment.

```mermaid
flowchart TB
  QI["Riverway Title"]:::neutral
  EAT["EAT\non title"]:::neutral
  LS["Land seller"]:::neutral
  GC["Hanover Construction Group\nGMP starts"]:::han
  HIND["Hanover Industrial\n4% dev fee"]:::han
  QI -->|"$6.5M"| EAT -->|"$6.5M"| LS
  GC -->|"contract"| EAT
  HIND -->|"DMA"| EAT
  classDef han fill:#fbeede,stroke:#9c6b1e,color:#5a3d0e;
  classDef neutral fill:#eef0f2,stroke:#7a8696,color:#333;
```

| From | To | $ | Hanover |
|---|---|---|---|
| **Riverway Title** | **EAT** | **$6.5M** | — (exchange funds, not your capital) |
| **EAT** | **Land seller** | **$6.5M** | You facilitate development; **EAT** is buyer of record |
| **EAT** | **Hanover Construction Group** | — | **GMP** in place; mobilization per contract |
| **EAT** | **Hanover Industrial** | — | **Dev management** (4%) accrues per DMA |

## Step 3 — Construction: who pays you (Oct 2026 – Feb 2027)

You bill the **EAT** — not Kao, not the QI directly. QI funds flow **QI → EAT → you**.

```mermaid
flowchart LR
  QI["Riverway Title\nexchange draws"]:::neutral
  EAT["EAT\nowner"]:::neutral
  GC["Hanover Construction Group\nGMP pay apps"]:::han
  SUB["Subs"]:::neutral
  QI --> EAT --> GC --> SUB
  classDef han fill:#fbeede,stroke:#9c6b1e,color:#5a3d0e;
  classDef neutral fill:#eef0f2,stroke:#7a8696,color:#333;
```

| Phase | Calendar | Paid from | Hanover receives |
|---|---|---|---|
| Sitework | Oct–Nov 2026 | QI → EAT → **GC** | GMP progress payments (4.5% fee on hard) |
| Foundations | Dec 2026–Feb 2027 | QI → EAT → **GC** | Same |
| Dev management | Ongoing | EAT | **4%** dev fee per DMA |

- **Draw certification:** GC submits pay apps; EAT/QI releases exchange funds per counsel's protocol  
- **After ~$21.5M exchange equity deployed:** **construction lender** advances to EAT — you **guaranty** per term sheet  
- **Controllable overruns:** **100% Sponsor** per term sheet — budget risk is yours during build  

## Step 4 — Day 180 (Mar 14, 2027)

```mermaid
flowchart LR
  EAT["EAT"]:::neutral
  KLLC["Kao acquisition LLC"]:::kao
  GC["Hanover Construction Group\nstill GC"]:::han
  EAT -->|"deed 100% fee"| KLLC
  GC -->|"GMP continues"| KLLC
  classDef kao fill:#e3edf7,stroke:#1f3a5f,color:#0f2440;
  classDef han fill:#fbeede,stroke:#9c6b1e,color:#5a3d0e;
  classDef neutral fill:#eef0f2,stroke:#7a8696,color:#333;
```

| Event | Hanover |
|---|---|
| **EAT → Kao LLC deed** | Exchange completes — **Kao** owns NFCC; you do **not** receive a deed slice yet (unless TIC path — OPEN) |
| **GMP** | Continues through **Kao LLC** as owner |
| **5% + promote** | **Not automatic** — depends on structure path (Overview) |

## Step 5 — After Day 180 (~Aug 2027 full build)

| Structure path (OPEN) | When Hanover gets equity / promote |
|---|---|
| **TIC + EAT** | Possible **5% undivided** co-ownership deed at Day 180 |
| **Exchange then §721** | **12–24+ mo** after deed; loan converts to 5% via contribution |
| **100% + incentive fee** | **Never** equity — promote as ordinary-income fee |
| **Term sheet LLC Day 1** | **Fails §1031** — not viable as written |

Construction to ~**$50.3M** total completes with **loan + remaining draws**; you keep earning **dev + GC fees** and bear **guaranty** exposure per negotiated restructure.

## Hanover entities (roles)

| Entity | Role |
|---|---|
| **Hanover Industrial LLC** | Sponsor — dev fee, guaranties, promote stack |
| **Land acquisition SPV** | May acquire land in non-§1031 deals; here **EAT** buys land (pattern TBD) |
| **Hanover Construction Group** | **GMP only** — 4.5% hard, $300K advance, 5% contingency |
| **Investor LP (95%)** | Kao side — **Phase 2** in most restructure paths |
| **Hanover GP/LP + capital** | 5% + promote — **timing OPEN** |

```mermaid
flowchart TB
  HIND["Hanover Industrial LLC"]:::han
  GC["Hanover Construction Group\nGMP · 4.5% hard"]:::han
  H5["Hanover 5% stack\n+ promote · timing OPEN"]:::han
  PROJ["EAT → then Kao LLC"]:::neutral
  HIND --> H5
  GC -->|"GMP contract"| PROJ
  H5 -.->|"equity later"| PROJ
  classDef han fill:#fbeede,stroke:#9c6b1e,color:#5a3d0e;
  classDef neutral fill:#eef0f2,stroke:#7a8696,color:#333;
```

## Commercial terms (term sheet — unsigned)

| Item | Term |
|---|---|
| Equity | 5% (95% Kao) — **timing restructured for §1031** |
| Promote | 20/30/40 @ 10/14/18 IRR |
| Dev fee | 4% |
| GC / GMP | 4.5% hard · $300K advance |
| Overruns | 100% controllable → Sponsor |
| Guaranties | Lender + JV completion / overrun |

## Term sheet vs §1031 restructure

| Term sheet (as written) | Restructured model (draft) |
|---|---|
| LLC JV **Day 1** | **EAT** holds title **0–180d**; JV or co-ownership **later** |
| Kao 95% **membership** at close | Kao **real property** first; LLC interest **deferred** |
| Simultaneous JV + GMP + loan + land | Land + build via **QI/EAT**; loan to **EAT** |
| Promote **inside LLC** | Fee or **Phase-2** partnership — counsel |

**Intent:** same commercial economics — different legal sequencing and documents.

**Sources:** Term sheet 06.12.2026 · `docs/incoming/Hanover-Org-Chart-Example-Project.pdf`

<!-- TAB:kao -->

## Your role

**Exchangor (our family)** — the taxpayer selling Belara and acquiring North Forsyth to **defer** the Belara capital gain. Not Hanover. Not Strake.

| Role | Party |
|---|---|
| **Relinquished property** | Belara Apartments — legal seller today: **Titan Management** |
| **Preferred exchanger / term-sheet LP** | **Kao Management Trust** — **must align before Belara PSA** |
| **Belara buyer** | **Strake Jesuit** |
| **Qualified Intermediary** | **Riverway Title** — holds $20M; you **never** receive sale proceeds |
| **EAT** | **TBD** — temporary **legal owner** of NFCC during build (up to 180 days) |
| **Developer** | **Hanover Industrial LLC** — dev fee, guaranties; equity timing **OPEN** |
| **GC** | **Hanover Construction Group** — GMP contractor to EAT / project entity |
| **Land seller** | Third party, unaffiliated — **under PSA** |
| **Structure path** | **Not locked** — Overview tab |

## Why a §1031 exchange (not just "buying NFCC")

Selling Belara for **$20M** triggers a large capital gain. **IRC §1031** defers that tax if you reinvest into **like-kind real property** (North Forsyth) and follow IRS rules:

1. **Strake's purchase price** wires to **Riverway Title (QI)** — not to you. Touching the cash = **constructive receipt** = exchange fails.
2. Within **45 days** of Belara close, you **identify** replacement property in a **written notice to the QI** (legal deadline).
3. Within **180 days**, you **complete** the exchange. NFCC is not built yet, so an **Exchange Accommodation Titleholder (EAT)** holds title while **QI funds** buy land and pay construction; on Day 180 the EAT **deeds** the property to **your acquisition LLC**.

The word **"exchange"** means: Belara out → North Forsyth in, same taxpayer, QI in the middle, tax deferred. It is the **tax mechanism** for this deal — not a separate optional step.

## Key dates (model — STATED user)

**Day 0 = Belara close.** Modeled same day as **NFCC land close / construction start.**

| Milestone | Date | What actually happens |
|---|---|---|
| **Day 0** | **Sept 15, 2026** | Strake closes Belara → **$20M to Riverway Title**; QI funds **$6.5M land** to **EAT** on title |
| **Day 45** | **Oct 30, 2026** | **Written identification** of NFCC delivered to QI (IRS rule — see Step 3) |
| **Day 180** | **Mar 14, 2027** | **EAT deeds** land + in-place improvements to **Kao acquisition LLC** — exchange **closes** |
| **Full build** | ~**Aug 2027** | ~11 months from Sept 15; balance funded by **construction loan** (~60% LTC) |

## Step 1 — Pre-close (before Sept 15)

```mermaid
flowchart TB
  K["Kao / counsel\nalign Titan → Kao Trust"]:::kao
  QI["Riverway Title\nQI engagement"]:::neutral
  EAT["EAT provider TBD\nQEAA with exchanger"]:::neutral
  H["Hanover\nGMP + dev agreements"]:::han
  LN["Construction lender\n60% LTC"]:::neutral
  ST["Strake\nBelara PSA + escrow"]:::neutral
  K --> QI
  K --> EAT
  EAT --> H
  EAT --> LN
  ST --> QI
  classDef kao fill:#e3edf7,stroke:#1f3a5f,color:#0f2440;
  classDef han fill:#fbeede,stroke:#9c6b1e,color:#5a3d0e;
  classDef neutral fill:#eef0f2,stroke:#7a8696,color:#333;
```

- **Same taxpayer** from Belara through replacement — resolve **Titan Management vs Kao Management Trust** first
- **Engage Riverway Title**; Belara PSA must wire proceeds **to QI only**
- **Select independent EAT** ([Rev. Proc. 2000-37](https://www.irs.gov/pub/irs-drop/rp-00-37.pdf))
- **Form Kao acquisition SMLLC** (name TBD) — receives Day 180 deed
- **Land PSA** with third-party seller ($6.5M)

## Step 2 — Day 0: Belara sale + NFCC land (Sept 15, 2026)

IRS **clocks start** at Belara close. Two transactions modeled **same day**:

```mermaid
flowchart TB
  subgraph Belara["Belara closing"]
    SK["Strake Jesuit\nbuyer"]:::neutral
    ESC["Escrow"]:::neutral
    QI["Riverway Title\nholds $20M"]:::neutral
    SK -->|"$20M"| ESC --> QI
  end
  subgraph NFCC["NFCC land closing"]
    QI2["Riverway Title\nreleases funds"]:::neutral
    EAT["EAT\nfee simple on title"]:::neutral
    LS["Third-party\nland seller"]:::neutral
    QI2 -->|"$6.5M"| EAT -->|deed| EAT
    EAT -->|"$6.5M"| LS
  end
  QI --> QI2
  classDef neutral fill:#eef0f2,stroke:#7a8696,color:#333;
```

| From | To | $ | Note |
|---|---|---|---|
| **Strake Jesuit** | **Riverway Title** | **$20M** | Exchange proceeds — **not** to Kao/Titan |
| **Riverway Title** | **EAT** | **$6.5M** | Land purchase from exchange pool |
| **Third-party seller** | **EAT** | — | Deeds NFCC land to **EAT**, not to you yet |

**You** sign as exchanger/seller. **You do not** deposit or control the $20M.

## Step 3 — Day 45: identification (by Oct 30, 2026)

Not a construction step — an **IRS deadline**.

| | |
|---|---|
| **Who acts** | Exchangor (Kao / aligned entity), through §1031 counsel |
| **Who receives** | **Riverway Title** (QI) |
| **What** | **Written identification letter** describing North Forsyth Commerce Center — parcel, address, planned improvements, estimated total value **≥ $20M** |
| **Why** | Without valid identification by Day 45, **no exchange** — regardless of construction |

Counsel drafts and QI acknowledges. Consider identifying a **backup** replacement (finished asset or DST) if build slips — **DRAFT**; confirm with counsel.

## Step 4 — Construction: who pays whom (Oct 2026 – Feb 2027)

**"Equity draws"** = **Riverway Title releasing exchange funds** on draw requests. **Not** Kao wiring from a personal account.

```mermaid
flowchart LR
  QI["Riverway Title\n~$20M pool"]:::neutral
  EAT["EAT\nowner · borrower"]:::neutral
  GC["Hanover Construction Group\nGMP"]:::han
  V["Subs / vendors"]:::neutral
  QI -->|"certified draws"| EAT
  EAT -->|"sitework · foundations"| GC --> V
  classDef han fill:#fbeede,stroke:#9c6b1e,color:#5a3d0e;
  classDef neutral fill:#eef0f2,stroke:#7a8696,color:#333;
```

| Phase | Calendar (model) | QI → EAT | Cumulative in-place |
|---|---|---|---|
| Land | Sept 15, 2026 | $6.5M | $6.5M |
| Sitework | Oct–Nov 2026 | $5M | $11.5M |
| Foundations | Dec 2026–Feb 2027 | $10M | **$21.5M** |

- **Who requests draws:** EAT / GC under GMP; **QI pays EAT** per exchange agreement
- **Who is paid:** **Hanover Construction Group** and subs — from **EAT's** account
- **Construction loan** (~60% LTC): lender advances to **EAT** for costs **after** exchange equity is deployed; Hanover guaranties per term sheet — exact routing **OPEN**
- Only improvements **complete and paid within 180 days** count toward exchange value — counsel must document

Remaining ~$30M of ~$50.3M project after exchange equity → **loan**, not additional §1031 proceeds.

## Step 5 — Day 180: what "exchange complete" means (Mar 14, 2027)

Three concrete events — not a label:

1. **EAT deeds 100% fee simple** (land + improvements in place) → **Kao acquisition LLC** (disregarded → Kao Management Trust if aligned)
2. **Riverway Title** closes exchange per final disbursement instructions
3. You file **Form 8824** — gain deferred to extent **≈$20M** qualifying value was reinvested; shortfall = taxable **boot**

```mermaid
flowchart LR
  EAT["EAT\nheld title during build"]:::neutral
  LLC["Kao acquisition LLC\nname TBD"]:::kao
  KT["Kao Management Trust\nexchangor"]:::kao
  EAT -->|"warranty deed"| LLC
  LLC -.->|"disregarded entity"| KT
  classDef kao fill:#e3edf7,stroke:#1f3a5f,color:#0f2440;
  classDef neutral fill:#eef0f2,stroke:#7a8696,color:#333;
```

**Until this deed:** you do **not** own NFCC for §1031 purposes — the **EAT** does. That is why the EAT exists.

## After Day 180

Construction continues toward ~**Aug 2027** full completion. Hanover **95/5 JV and promote** depend on structure path (TIC, exchange-then-§721, fee-only, etc.) — **OPEN**. See Overview.

## Critical rules (exchangor)

- **Same taxpayer** Belara sale → replacement deed — resolve Titan vs Kao Trust **before PSA**
- **Never touch proceeds** — constructive receipt ends the exchange
- **No debt on Belara** at close — no mortgage boot
- **Day 45 identification** and **Day 180 completion** are hard IRS deadlines
- **Form 8824**; boot if documented in-place value **< ≈$20M** at Day 180

## Before Belara closes

- [ ] Lock **exchangor entity** (Kao Trust preferred)  
- [ ] Engage **Riverway Title**; select **EAT**  
- [ ] §1031 counsel + CPA; pick structure path (Overview tab)  
- [ ] Draft Belara PSA — proceeds to QI only  

**Sources:** [IRC §1031](https://www.law.cornell.edu/uscode/text/26/1031) · [Reg. §1.1031(k)-1](https://www.law.cornell.edu/cfr/text/26/1.1031(k)-1) · [Rev. Proc. 2000-37](https://www.irs.gov/pub/irs-drop/rp-00-37.pdf)

<!-- TAB:references -->

## Statute and IRS Guidance

- [IRC §1031 — Like-kind exchanges (real property only)](https://www.law.cornell.edu/uscode/text/26/1031)
- [Treas. Reg. §1.1031(a)-3 — Real property; partnership interest excluded](https://www.law.cornell.edu/cfr/text/26/1.1031(a)-3)
- [Treas. Reg. §1.1031(k)-1 — QI safe harbor](https://www.law.cornell.edu/cfr/text/26/1.1031(k)-1)
- [Treas. Reg. §301.7701-3 — Disregarded entity](https://www.law.cornell.edu/cfr/text/26/301.7701-3)
- [Form 8824](https://www.irs.gov/forms-pubs/about-form-8824)

## Build-to-suit and co-ownership

- [Rev. Proc. 2000-37 — EAT / build-to-suit](https://www.irs.gov/pub/irs-drop/rp-00-37.pdf)
- [Rev. Proc. 2002-22 — TIC guidance (not a safe harbor)](https://www.irs.gov/pub/irs-drop/rp-02-22.pdf)
- [IRC §721 — Contribution to partnership](https://www.law.cornell.edu/uscode/text/26/721)

## Case law

- *Gluck v. Commissioner*, T.C. Memo. 2020-66 — LLC interest / exchange issues

## Disclaimer

Internal working model only — not legal or tax advice. No structure on this site is locked or counsel-approved. Obtain a written §1031 opinion before Belara closes.
