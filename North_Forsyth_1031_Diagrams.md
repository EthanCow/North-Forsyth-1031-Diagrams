<!-- TAB:overview -->

## North Forsyth §1031 — Structure A

> **Privileged & Confidential — Attorney Work Product.** Illustrative summary only; not legal or tax advice and not a covered opinion. Figures are rounded planning numbers, not verified deal terms. Obtain a written §1031 opinion on the executed documents before Belara closes.

**The deal.** Kao sells **Belara Apartments** (≈$20M, no debt; buyer **Strake Jesuit**) and §1031-exchanges into **North Forsyth Commerce Center** — a ≈$50.3M ground-up industrial project (≈327,600 SF) in Cumming, GA. **Hanover** develops, builds, guarantees the ≈$29M construction loan, and takes **5% + a promote**.

| ≈$20.0M | ≈$50.3M | 95 / 5 | ≈$29M |
|---|---|---|---|
| Belara sale (no debt) → deferred | NFCC project cost | Kao / Hanover economics | Construction loan |

**The problem, and the fix.** A promote is a profit share, which turns a co-ownership into a partnership — and a partnership interest is **not** like-kind real property. Put the promote *inside* the vehicle Kao receives and the exchange fails. Structure A separates the two in time:

1. **Phase 1 — the exchange.** Kao exchanges Belara into **100% fee title** in North Forsyth, through a Qualified Intermediary (QI) and a build-to-suit Exchange Accommodation Titleholder (EAT).
2. **Phase 2 — the JV.** After a **genuine seasoning period**, Kao contributes the property to a promoted Hanover joint venture under **§721** (tax-free). The JV carries the full term sheet: 95/5, the 20/30/40 promote over 10/14/18, the 4% and 4.5% fees, and the guaranties.

> **How strong is this, honestly?** **More likely than not** — not "clean," and not automatic. The main risk is the IRS collapsing the two phases into one (the step-transaction doctrine). The position **strengthens toward "should"** the longer Kao genuinely owns and operates North Forsyth before combining. If the parties want the strongest, simplest exchange, a fallback (**Structure B** — Kao 100% forever + an ordinary-income incentive fee) trades Hanover's capital-gain treatment for a bulletproof exchange.

See **Structure** for how it works and the diagrams; **Kao / Hanover / Strake** for each party's role; **Sources** for the authority.

<!-- TAB:structure -->

## How it works

Legend: **Kao = blue**, **Hanover = amber**, **neutral / third party = grey**, **asset / JV = green**.

### The big picture

```mermaid
flowchart TB
  subgraph P1["PHASE 1 — THE EXCHANGE · Days 0-180"]
    direction TB
    Belara["Belara Apartments<br/>$20M · no debt"]:::asset
    Strake["Strake Jesuit<br/>buyer"]:::neutral
    QI["Compass Exchange Services LLC<br/>Qualified Intermediary"]:::neutral
    EAT["NFCC Parking Title LLC<br/>EAT · holds title 0-180d"]:::neutral
    KaoLLC["Kao NFCC Owner LLC<br/>Kao's disregarded SMLLC"]:::kao
    Belara -->|"Day 0 · $20M"| Strake
    Strake -->|"$20M proceeds"| QI
    QI -->|"funds Kao's ~$20M equity"| EAT
    EAT -->|"Day 180 · deeds 100% fee title"| KaoLLC
  end
  subgraph P2["PHASE 2 — THE JOINT VENTURE · after seasoning"]
    direction TB
    KaoLLC2["Kao NFCC Owner LLC<br/>contributes property"]:::kao
    HanMem["Hanover NFCC Member LLC<br/>5% + promote"]:::han
    JV["North Forsyth Commerce Center JV LLC<br/>partnership for tax"]:::asset
    KaoLLC2 -->|"§721 · 95% · no tax"| JV
    HanMem -->|"§721 · 5% + carry"| JV
  end
  KaoLLC -->|"seasoning gap<br/>Kao owns and operates 100%"| KaoLLC2
  classDef kao fill:#e3edf7,stroke:#1f3a5f,color:#0f2440;
  classDef han fill:#fbeede,stroke:#9c6b1e,color:#5a3d0e;
  classDef neutral fill:#eef0f2,stroke:#7a8696,color:#333;
  classDef asset fill:#e5efe9,stroke:#2d6a4f,color:#14402e;
```

Read it left-to-right in time: a clean real-property acquisition first, a normal promoted partnership second. The **seasoning gap** between them is what keeps the IRS from collapsing the two steps.

### Phase 1 — the exchange (Days 0–180)

Every dollar and the title movement during the build-to-suit window. Kao never touches the proceeds; the EAT is the borrower and builder; Kao receives **100%** at the end.

```mermaid
flowchart TB
  Belara["Belara Apartments<br/>$20M · no debt"]:::asset
  Strake["Strake Jesuit<br/>buyer"]:::neutral
  QI["Compass Exchange Services LLC<br/>Qualified Intermediary"]:::neutral
  Lender["Construction Lender<br/>~$29M · unrelated bank"]:::neutral
  HanCap["Hanover NFCC Capital LLC<br/>5% funded as a LOAN ~$1.1M"]:::han
  EAT["NFCC Parking Title LLC · EAT<br/>holds title · borrows loan · builds"]:::neutral
  Land["NFCC land<br/>$6.5M"]:::asset
  GC["Hanover Construction Group LLC<br/>GMP draws · 4.5% fee"]:::han
  Dev["Hanover NFCC Developer LLC<br/>4% development fee"]:::han
  KaoLLC["Kao NFCC Owner LLC<br/>disregarded → Kao Management Trust"]:::kao
  Belara -->|"Day 0 sale"| Strake
  Strake -->|"$20M"| QI
  QI -->|"Kao equity draws ~$20M"| EAT
  Lender -->|"loan draws"| EAT
  HanCap -->|"loan draws"| EAT
  EAT -->|"$6.5M"| Land
  EAT -->|"hard-cost draws"| GC
  EAT -->|"fee"| Dev
  EAT -->|"Day 180 · conveys 100% fee title"| KaoLLC
  Ident["Day 45 · Kao identifies NFCC in writing"]:::neutral
  Ident -.-> EAT
  classDef kao fill:#e3edf7,stroke:#1f3a5f,color:#0f2440;
  classDef han fill:#fbeede,stroke:#9c6b1e,color:#5a3d0e;
  classDef neutral fill:#eef0f2,stroke:#7a8696,color:#333;
  classDef asset fill:#e5efe9,stroke:#2d6a4f,color:#14402e;
```

**The build-to-suit math (the hard constraint).** To defer the full ≈$20M of Belara gain, Kao must reinvest ≈$20M in **completed real property by Day 180**:

| Component | Amount | Counts toward the exchange? |
|---|---|---|
| Land (acquired by the EAT) | **$6.5M** | ✅ Yes — real property in place |
| **Completed improvements physically in place by Day 180** | **≈$13.5M** | ✅ Yes — only the portion actually constructed |
| Stored materials, deposits, prepaid contracts, off-site fabrication | — | ❌ No |
| Work performed **after** the EAT→Kao transfer | — | ❌ No |
| **Day-180 reinvestment target** | **≈$20.0M** | This is the number that must be *built and in place* |

For a ≈$50.3M ground-up project, getting **$13.5M of verifiable, in-place improvements** on top of the land within 180 days is the central feasibility risk. **Any shortfall is boot, taxed in 2026.**

**Equity exhaustion (what funds the rest of the build).** Kao's ≈$20M is fully deployed into land + the first ≈$13.5M of improvements **before** Day 180. Everything after that — the remaining ≈$30M of the $50.3M project — is funded by the construction loan (≈$29M) and Hanover's ≈$1.1M, **both as debt with guaranties, never as equity contributed by Hanover.** Treating any of that remaining funding as Hanover *equity* in Phase 1 would create the partnership the exchange cannot have.

**Phase-1 mechanics to nail down (with counsel).** QI and EAT must each be **independent** (not a disqualified person; Reg. §1.1031(k)-1(k)); a **written QEAA within 5 business days** of the EAT taking title; the EAT holds **qualified indicia of ownership** throughout; identify the relinquished property within **45 days**; the **combined parking period ≤ 180 days**; written **lender consent** to lend to the EAT and to the later transfer; Georgia title/transfer-tax handled by local counsel; EAT **bankruptcy-remote** with no agency language.

### Phase 2 — the joint venture (§721, after seasoning)

Once the exchange has closed and seasoned, the parties form the real JV. Both contributions are tax-free under §721, and the promote now sits where it belongs.

```mermaid
flowchart TB
  KaoLLC["Kao NFCC Owner LLC<br/>contributes property (subject to loan)"]:::kao
  HanMem["Hanover NFCC Member LLC<br/>contributes 5% / converts loan"]:::han
  JV["North Forsyth Commerce Center JV LLC<br/>Delaware LLC · partnership for tax"]:::asset
  Rent["Operating cash flow<br/>rents"]:::neutral
  KaoD["Kao — 95% distributions"]:::kao
  HanD["Hanover — 5% + promote<br/>20/30/40 over 10/14/18"]:::han
  KaoLLC -->|"§721 · 95% interest · no tax"| JV
  HanMem -->|"§721 · 5% + carried interest · no tax"| JV
  Rent --> JV
  JV -->|"pro-rata first"| KaoD
  JV -->|"pro-rata + promote above hurdles"| HanD
  classDef kao fill:#e3edf7,stroke:#1f3a5f,color:#0f2440;
  classDef han fill:#fbeede,stroke:#9c6b1e,color:#5a3d0e;
  classDef neutral fill:#eef0f2,stroke:#7a8696,color:#333;
  classDef asset fill:#e5efe9,stroke:#2d6a4f,color:#14402e;
```

**The guardrails that make Phase 2 safe:** no binding obligation at the exchange (non-binding LOI only — **no fixed-price equity option**); **season the gap** (real time, no same-closing mechanics); Kao **operates as 100% owner** in the interim; document an **independent business purpose** for combining later; and watch the **§707 disguised-sale** rule (Hanover cash in plus a Kao distribution out within ≈2 years can be recharacterized as a sale).

**Seasoning is the whole ballgame.** The clock runs from the **EAT→Kao deed date**, not Day 0. Working floor ≈ the later of **12 months** after the deed and **substantial completion**; about **24 months** plus lease-up and/or a refinance supports a path to "should."

**Partnership-tax overlays to model before signing.** The §721 contribution is nonrecognition, but watch **§707** (disguised sale; 2-year window), **§752** (Hanover's guaranties can shift the loan off Kao and trigger gain), and **§704(c)** (keeps the deferred Belara gain with Kao).

### Timeline

```mermaid
flowchart LR
  A["Pre-close<br/>QI · EAT · entities<br/>lender consent · opinion"]:::neutral
  B["Day 0<br/>Belara → QI<br/>$20M parked"]:::asset
  C["Day 45<br/>Identify NFCC<br/>+ backup DST"]:::neutral
  D["Days 0-180<br/>EAT builds<br/>QI + loan fund draws"]:::neutral
  E["Day 180<br/>EAT deeds 100%<br/>to Kao SMLLC"]:::kao
  F["Seasoning<br/>Kao owns and operates<br/>file Form 8824"]:::kao
  G["Phase 2<br/>§721 into the JV<br/>Hanover 5% + promote"]:::han
  H["Exit / refi<br/>promote paid<br/>§1061 > 3-yr hold"]:::asset
  A --> B --> C --> D --> E --> F --> G --> H
  classDef kao fill:#e3edf7,stroke:#1f3a5f,color:#0f2440;
  classDef han fill:#fbeede,stroke:#9c6b1e,color:#5a3d0e;
  classDef neutral fill:#eef0f2,stroke:#7a8696,color:#333;
  classDef asset fill:#e5efe9,stroke:#2d6a4f,color:#14402e;
```

<!-- TAB:kao -->

## Your Role — Kao (the Exchanger)

You sell Belara and acquire the replacement. Everything runs on the **45-day** and **180-day** clocks, and you must **never** touch the proceeds.

```mermaid
flowchart TB
  Kao["Kao<br/>the Exchanger / taxpayer"]:::kao
  Belara["Belara Apartments<br/>$20M · no debt"]:::asset
  QI["Qualified Intermediary<br/>holds proceeds — Kao never touches"]:::neutral
  Own["Kao NFCC Owner LLC<br/>disregarded SMLLC<br/>receives 100% fee title"]:::kao
  Season["Seasoning gap<br/>hold + operate as 100% owner<br/>non-binding LOI only"]:::kao
  JV["North Forsyth JV<br/>Kao = 95% member · §704(c)"]:::asset
  Kao -->|"owns"| Belara
  Belara -->|"Day 0 · sells via QI"| QI
  QI -->|"funds ~$20M exchange equity"| Own
  Own -->|"Day 180 · 100% title · file Form 8824"| Season
  Season -->|"Phase 2 · §721 · 95%"| JV
  classDef kao fill:#e3edf7,stroke:#1f3a5f,color:#0f2440;
  classDef neutral fill:#eef0f2,stroke:#7a8696,color:#333;
  classDef asset fill:#e5efe9,stroke:#2d6a4f,color:#14402e;
```

**Before Belara closes**
- Engage the QI and the EAT provider; engage §1031 counsel + CPA and obtain the written opinion on the final documents.
- Form `Kao NFCC Owner LLC`; the sole member must be the **exact taxpayer** that sells Belara. Admit no second member before the exchange completes.
- Confirm you have never owned North Forsyth (Rev. Proc. 2004-51); confirm the land seller is unrelated.
- Model boot, §752, and §707; line up a specific, named backup DST.

**During the exchange (Days 0–180)**
- Day 0: Belara closes; proceeds wire to the QI (never to you).
- Day 45: identify North Forsyth (and the backup DST) in writing.
- Day 180: the EAT deeds **100% fee title** to `Kao NFCC Owner LLC`. **Extend the 2026 return**; commission a Day-180 in-place valuation; file Form 8824.

**After (Phase 2)**
- Let the exchange **season** from the deed date; hold and operate as the genuine **100% owner**; **do not** pre-sign the JV contribution (non-binding LOI only).
- Contribute the property to the JV under §721; you become the **95%** member. Your deferred Belara gain stays with you under §704(c).

<!-- TAB:hanover -->

## Your Role — Hanover (Developer, GC, and 5% Promoted Partner)

Your economics are identical to the term sheet: 5% ownership, the 20/30/40 promote over 10/14/18, the 4% development fee, the 4.5% GC fee, and the guaranties. Only the **sequencing** changes — you take your ownership and promote in **Phase 2**, after Kao's exchange closes.

```mermaid
flowchart TB
  subgraph PH1["PHASE 1 — builder + creditor (NOT on title)"]
    direction TB
    Dev["Hanover Developer LLC<br/>Development Mgmt · 4% fee"]:::han
    GC["Hanover Construction Group<br/>GMP contract · 4.5% fee"]:::han
    Cap["Hanover NFCC Capital LLC<br/>5% as a SECURED LOAN ~$1.1M"]:::han
    Guar["Loan guaranties<br/>completion · carry · overrun · carve-out"]:::han
  end
  EAT["EAT builds · Days 0-180"]:::neutral
  Mem["Hanover NFCC Member LLC<br/>5% equity + promote"]:::han
  JV["North Forsyth JV<br/>partnership for tax"]:::asset
  Dev -->|"services"| EAT
  GC -->|"hard-cost draws"| EAT
  Cap -->|"loan draws"| EAT
  Guar -.->|"supports the ~$29M loan"| EAT
  Cap -->|"Phase 2 · converts via §721"| Mem
  Mem -->|"5% + carried interest"| JV
  classDef han fill:#fbeede,stroke:#9c6b1e,color:#5a3d0e;
  classDef neutral fill:#eef0f2,stroke:#7a8696,color:#333;
  classDef asset fill:#e5efe9,stroke:#2d6a4f,color:#14402e;
```

**Phase 1 (during the build)**
- Build under a standalone, market **Development Management Agreement (4%)** and a **GMP contract (4.5%** of hard costs).
- Provide the loan guaranties (completion, carry, overrun, carve-out), backed by a collateralized Kao indemnity.
- Fund your 5% **now as a secured, interest-bearing loan** (`Hanover NFCC Capital LLC`) — **not** a "preferred return." It converts to equity in Phase 2. You are **not** on title during the exchange.
- If Kao chooses not to proceed to Phase 2, you are made whole by a **fixed / cost-based break fee** (not a promote-mirroring payment).

**Phase 2 (the JV)**
- Contribute / convert into the JV under §721; receive your **5% membership + the promote** (carried interest).
- Your promote is **capital gain** because it is a partnership **profits interest** (not because of §1061). §1061 doesn't create capital gain — it just requires a **> 3-year hold** for long-term rates. Your dev and GC fees remain ordinary income.

> Prefer to avoid the Phase-2 sequencing? See **Structure B**: you stay a fee-based developer with a promote-replicating **incentive fee** — same pre-tax dollars, but the promote becomes **ordinary income** (gross it up to stay whole).

<!-- TAB:strake -->

## Your Role — Strake Jesuit (Buyer of Belara only)

You are the buyer of Belara and nothing else. You are not involved in North Forsyth, the EAT, the construction loan, or the joint venture.

```mermaid
flowchart LR
  Strake["Strake Jesuit<br/>buyer of Belara only"]:::neutral
  Esc["Closing escrow"]:::neutral
  QI["Qualified Intermediary<br/>(Kao's exchange)"]:::neutral
  Belara["Belara Apartments<br/>title to Strake"]:::asset
  Strake -->|"purchase price"| Esc
  Esc -->|"proceeds to QI, NOT to Kao"| QI
  Esc -->|"deed"| Belara
  Belara -->|"owned by"| Strake
  classDef neutral fill:#eef0f2,stroke:#7a8696,color:#333;
  classDef asset fill:#e5efe9,stroke:#2d6a4f,color:#14402e;
```

- **Close on the agreed date.** Funds go through escrow to the **Qualified Intermediary**, not to Kao directly. This is required for Kao's §1031 exchange.
- **Coordinate logistics** with Kao and the QI on closing date, escrow instructions, and title.
- **Complete your own diligence** (title, survey, environmental, and any institutional / gift-acceptance items). Those are your own concerns, separate from the exchange.

<!-- TAB:references -->

## Sources

**Statute & regulations**
- [IRC §1031](https://www.law.cornell.edu/uscode/text/26/1031) — like-kind exchanges; real-property only post-TCJA (§1031(a)(1)), so a partnership interest cannot qualify.
- [Treas. Reg. §1.1031(a)-3](https://www.law.cornell.edu/cfr/text/26/1.1031(a)-3) — definition of "real property" (excludes a partnership interest).
- [IRC §721](https://www.law.cornell.edu/uscode/text/26/721) — nonrecognition on contributing property to a partnership.
- [IRC §704(c)](https://www.law.cornell.edu/uscode/text/26/704) — built-in gain stays with the contributing partner (Kao).
- [IRC §707(a)(2)(B)](https://www.law.cornell.edu/uscode/text/26/707) · [Reg. §1.707-3](https://www.law.cornell.edu/cfr/text/26/1.707-3) — disguised-sale rule (2-year presumption).
- [IRC §752](https://www.law.cornell.edu/uscode/text/26/752) · [Reg. §1.752-2](https://www.law.cornell.edu/cfr/text/26/1.752-2) — partnership liabilities; guaranties shifting debt off Kao.
- [IRC §1061](https://www.law.cornell.edu/uscode/text/26/1061) — 3-year hold for carried-interest long-term rates.
- [Treas. Reg. §1.1031(k)-1](https://www.law.cornell.edu/cfr/text/26/1.1031(k)-1) — QI / constructive-receipt safe harbor.
- [Treas. Reg. §301.7701-3](https://www.law.cornell.edu/cfr/text/26/301.7701-3) — disregarded entity.
- [IRS — About Form 8824](https://www.irs.gov/forms-pubs/about-form-8824) — reporting like-kind exchanges.

**Revenue procedures**
- [Rev. Proc. 2000-37](https://www.irs.gov/pub/irs-drop/rp-00-37.pdf) — QEAA / build-to-suit "parking" safe harbor.
- [Rev. Proc. 2004-51](https://www.irs.gov/pub/irs-drop/rp-04-51.pdf) — no safe harbor if the taxpayer pre-owned the replacement.
- [Rev. Proc. 2002-22](https://www.irs.gov/pub/irs-drop/rp-02-22.pdf) — TIC co-ownership guidance (advance-ruling guidance, **not** a safe harbor).

**Case law** *(read with their limits: both are pre-1984, Ninth Circuit; Georgia is in the Eleventh Circuit)*
- [Magneson v. Commissioner](https://openjurist.org/753/f2d/1490/magneson-v-commissioner-of-internal-revenue), 753 F.2d 1490 (9th Cir. 1985) — a post-exchange §721 contribution can still satisfy "held for investment."
- [Bolker v. Commissioner](https://law.justia.com/cases/federal/appellate-courts/F2/760/1039/), 760 F.2d 1039 (9th Cir. 1985) — supports "held for investment" despite a planned later step (**not** itself a §721 case).

---

*Illustrative summary only; entity names are placeholders. This is a conditional, more-likely-than-not position (not "clean"). Not a covered opinion — obtain a written §1031 opinion on the executed documents before Belara closes. The full analysis and the companion memos contain the detail behind this summary.*
