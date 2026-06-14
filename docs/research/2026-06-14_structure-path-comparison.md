# §1031 Structural Path Comparison — North Forsyth

**Status:** Internal research · **DRAFT** · Not legal advice  
**Date:** 2026-06-14  
**Purpose:** Conversation prep for counsel and Hanover — compare paths honestly; **no winner declared**.

---

## Shared modeling assumptions (this memo)

| Item | Value | Label |
|---|---|---|
| Relinquished | Belara Apartments, **$20M, no debt** | VERIFIED |
| Replacement | North Forsyth Commerce Center, ~**$50.3M** total | TERM SHEET (unsigned) |
| Exchangor (term sheet) | **Kao Management Trust** | TERM SHEET |
| Belara seller (legal today) | **Titan Management** — same family, **different taxpayer** | STATED (user) — **OPEN** |
| QI | **Riverway Title** | STATED (user) |
| EAT | **TBD** | OPEN |
| Land seller | Third party, **unaffiliated**, under **PSA** | STATED (user) |
| Construction loan | **60% LTC** (~**$30.2M** on $50.3M); other loan terms ignored | STATED (user) |
| Commercial economics | 95/5 equity; promote 20/30/40 @ 10/14/18 IRR; 4% dev / 4.5% GC | TERM SHEET (unsigned) |
| **Day 0 (model)** | **Sept 1, 2026** — land close | PROJECT_BRAIN |
| **Day 180 (model)** | ~**Feb 28, 2027** | derived |
| Simplified draw model | Land **$6.5M** Day 0 · sitework mo 1–2 **$5M** · foundations mo 3–5 **$10M** → **~$21.5M** cumulative by ~month 5 | STATED (user) |
| Exchange equity order | **Exchange funds deploy first** (land, then early hard costs) | STATED (user) |
| §1031 clocks | 45-day ID · 180-day completion from **Belara** close | VERIFIED (general law) |

**Boot note (all EAT paths):** Only value **physically in place and paid for** with exchange proceeds by Day 180 counts toward ~$20M. The draw model above *if executed and documented* exceeds $20M by ~month 5 — but **accounting ≠ construction certainty**. Shortfall = taxable boot. Stored materials, deposits, and post-Day-180 work do not count.

**Hanover posture:** Term sheet is **non-binding, unsigned**. User is **flexible on legal wrapper**; Hanover has seen promote/JV shape but signed nothing. **No outside §1031 counsel opinion on any path yet.**

---

## Executive comparison (no rankings)

| Path | Exchange viability (draft view) | Hanover gets equity when? | Promote tax character (Hanover) | Term sheet rewrite | Counsel review |
|---|---|---|---|---|---|
| **1. LLC JV Day 1** (as written) | **Fails** on form | Day 1 | Capital gain (carry) — *if exchange worked, which it doesn't* | None commercially; legally unusable for §1031 | N/A for deferral |
| **2. TIC + EAT + promote-as-fee** | **Uncertain** — site model says yes; Structure A draft cites prior review **likely fail** | Day 180 (5% undivided) | Fee routing attempts to preserve carry; **aggressive** | **Heavy** — JV → co-ownership + fee sidecars | **Required before Belara** |
| **3. Structure A** (100% → §721) | **MLTN at best** — seasoning-dependent | After seasoning + §721 (12–24+ mo post-deed floor in drafts) | Capital gain (carry) in Phase 2 JV | **Very heavy** — split Phase 1 / Phase 2 | **Required before Belara** |
| **4. Structure B** (100% forever + fee) | **Strongest exchange** per drafts | Never (contractual only) | **Ordinary income** on incentive fee | **Heavy** — waterfall → fee schedule; gross-up likely | **Required before Belara** |
| **5. Hybrids** (below) | Varies — generally **inherits worst risks** of parents | Varies | Varies | **Heaviest** | **Required before Belara** |

---

## Path 1 — Term sheet LLC JV Day 1 (as written)

### What it is

Delaware LLC joint venture; **simultaneous** closing of JV definitive docs + GMP + construction loan + land acquisition + land-disturbance permit. Kao receives **95% LLC membership interest**; Hanover **5%** managing member with full promote waterfall inside the LLC.

*Source: `docs/incoming/term-sheet-extracted.txt` lines 11–12, 27–36.*

### Timing

| Phase | When | What happens |
|---|---|---|
| Pre-close | Before Sept 1 | PSA, loan commitment, GMP, permit — all aligned to **one close** |
| Day 0 | Sept 1, 2026 (if Belara aligned) | JV forms; JV buys land; loan closes; GMP executes; construction starts |
| Day 45 | ~Oct 16 | ID deadline (if Belara closed) |
| Day 180 | ~Feb 28, 2027 | Exchange completion deadline — but Kao already holds **LLC interest**, not replacement real property |

Term sheet **does not** contemplate EAT parking or a 180-day build-to-suit window before Kao's receipt.

### Parties

| Party | Role |
|---|---|
| Kao Management Trust (via LP) | 95% **membership interest** in JV LLC |
| Hanover Industrial / Sponsor Member | 5% member; managing member; promote; guarantor |
| Construction lender | Loan to **JV** |
| Land seller | Sells to **JV** |
| QI (Riverway) | **Not in term sheet** — proceeds cannot wire to JV membership purchase without breaking exchange mechanics |
| EAT | **Not used** |

### Money flow sketch

```
Belara ($20M) → Strake
Strake → QI ($20M)     [§1031 path NOT in term sheet]
QI → ???               [Cannot buy LLC interest — not like-kind]

Term sheet path (as written):
Kao cash/equity → JV (95%)  } simultaneous
Hanover → JV (5%)           }
Lender → JV (~$30M)         } Day 0
JV → Land seller ($6.5M)    }
JV → GMP draws              }
```

If Kao funds the JV with exchange proceeds routed through QI, the **replacement property received is an LLC interest** — not real property.

### Main tax risks / failure modes

| Risk | Why it matters |
|---|---|
| **Wrong property class** | Post-TCJA §1031(a)(1): like-kind limited to **real property**. LLC/partnership interest excluded (Reg. §1.1031(a)-3). *Gluck v. Comm'r*, T.C. Memo. 2020-66 (LLC interest fails even if LLC holds only real estate). |
| **Promote inside replacement vehicle** | Profit-linked distributions → partnership character from Day 1; Kao's "replacement" is partnership economics, not fee simple. |
| **Simultaneous close vs. build-to-suit** | Ground-up project: ~$13.5M of **in-place** improvements needed in exchange window. Term sheet assumes full JV owns project from Day 0 — no Rev. Proc. 2000-37 EAT parking mechanics. |
| **Constructive receipt** | Any structure where Kao controls or directs proceeds outside QI/EAT chain fails. |
| **Exchangor entity mismatch** | Belara sold by **Titan Management**; term sheet LP is **Kao Management Trust** — same-family ≠ same taxpayer; chain must be fixed regardless of path. |

### Hanover commercial fit

**Best possible for Hanover.** Matches their standard promote/JV playbook, Simi Valley org-chart pattern, simultaneous lender close, and signed waterfall. Dev fee (25% at JV close), GC on GMP, overrun guaranties — all native.

### Term sheet rewrite burden

**Commercial:** None — this *is* the term sheet.  
**Legal/tax:** **Total replacement** of acquisition vehicle for any §1031 attempt. Cannot "tweak" LLC Day 1 into compliance; must restructure **who holds title** and **what Kao receives** at exchange completion while replicating economics elsewhere.

### Bottom line

Useful as the **commercial baseline** ($50.3M, 95/5, promote, fees, guaranties). **Not a §1031 path** without abandoning the Day-1 LLC receipt. Likely outcome if executed as written: **full taxable gain on Belara** (or partial if some boot mechanics attempted) — not informed deferral.

---

## Path 2 — TIC + EAT + promote-as-fee (current site model)

### What it is

Rev. Proc. 2000-37 **build-to-suit / improvement exchange**: EAT holds title Days 0–180. QI advances Kao's ~$20M equity; Hanover funds **5% as co-investor equity** (not loan). Construction loan to EAT (Hanover guaranties). At Day 180, EAT deeds **undivided 95% / 5%** to each party's SMLLC/SPE. Promote economics run through **fee to separate Hanover affiliate**, not TIC distributions. Co-ownership agreement + partition waiver + Development Management Agreement replace LLC operating agreement.

*Source: `North_Forsyth_1031_Diagrams.md` overview tab; labeled **DRAFT**.*

### Timing

| Phase | When | What happens |
|---|---|---|
| Pre-close | Before Belara | Form QI engagement, EAT, tax opinion, **lender TIC approval** |
| Day 0 | Belara close → QI | Proceeds parked; EAT may acquire land ($6.5M) if Belara/NFCC aligned |
| Days 0–180 | Sept 2026 – Feb 2027 | EAT borrower; QI + Hanover 5% + loan fund draws per schedule |
| Day 45 | ~Oct 16 | Identify North Forsyth (+ backup) |
| ~Month 5 | ~Feb 2027 | Draw model: **~$21.5M** in-place if schedule holds |
| Day 180 | ~Feb 28, 2027 | EAT → **95% deed to Kao SMLLC**; **5% deed to Hanover SPE** |
| Post-180 | Construction continues | Co-owners on loan; GMP draws; TIC governance |

### Parties

| Party | Role |
|---|---|
| Riverway Title | QI |
| EAT (TBD) | Title holder, borrower Days 0–180 |
| Kao Management Trust → Kao SMLLC | 95% undivided fee (disregarded) |
| Hanover SPE (affiliate) | 5% undivided fee |
| Hanover Industrial / Construction Group | DMA, GMP/GC — **not** JV member |
| Hanover promote affiliate | **Fee recipient** (promote-as-fee) |
| Construction lender | Loan to EAT, then to co-owners |
| Land seller | Sells to EAT |

### Money flow sketch

```
Day 0:  Belara → Strake → QI ($20M)

Days 0-180 (EAT parking):
  QI ──(~$20M equity draws)──► EAT ◄── Hanover 5% (~$1.1M)
  Lender ──(~$30M)──────────► EAT
  EAT ──► Land seller ($6.5M Day 0)
  EAT ──► GMP sitework ($5M mo1-2) + foundations ($10M mo3-5)
  EAT ──► Dev fee / GC fee (Hanover affiliates)

Day 180:
  EAT ──95% undivided deed──► Kao SMLLC
  EAT ──5% undivided deed───► Hanover SPE

Post-180:
  Operating cash / sale proceeds:
    TIC pro-rata distributions (95/5)
    Promote economics ──► separate fee affiliate (NOT pro-rata TIC dist)
```

### Main tax risks

| Risk | Severity | Notes |
|---|---|---|
| **TIC reclassified as partnership** | **High** | Co-owners with shared development, loan, management, and non-pro-rata economics → IRS may treat as partnership under Reg. §301.7701-3. Rev. Proc. 2002-22 is **not** a safe harbor — violations of §§6.08, 6.11, 6.12, 6.15 (no profit-linked fees to manager) undermine position. |
| **Promote-as-fee challenged** | **High** | Fee mirroring IRR waterfall may be recharacterized as **disguised partnership profits**; fee must be arm's-length, not profit-linked — but promote *is* profit-linked by definition. Site acknowledges "aggressive" and requires opinion. |
| **Partition waiver + tight co-ownership agreement** | **Medium** | Restrictions resembling LLC ops agreement can support partnership classification. |
| **Build-to-suit documentation** | **Medium** | Day-180 appraisal / cost certification for ~$20M in-place; boot if documented shortfall. |
| **Prior internal review** | **Unknown weight** | Structure A draft states prior tax review concluded development-TIC + promote-as-fee was **likely to fail** — **not verified** as outside counsel opinion, but flags this path as contested internally. |

### Hanover commercial fit

**Mixed.**

| Works for Hanover | Friction |
|---|---|
| 5% on title Day 180 — equity not delayed | Must accept **TIC**, not Delaware LLC JV |
| Same dev/GC fees and guaranty package | Promote via **fee affiliate** — different tax reporting; lender may resist |
| Economics "identical" on paper | **Co-ownership** governance, partition waiver, two SPEs on loan |
| | Lender diligence on TIC/EAT — **must confirm before Belara** |
| | More counterparties for lender/title/insurance |

Hanover has **not** agreed to TIC in writing. Term sheet is LLC-native.

### Term sheet rewrite burden

**Heavy.**

| Term sheet concept | TIC replacement |
|---|---|
| Delaware LLC JV | Co-Ownership Agreement (GA property law) + two SPEs on title |
| Operating agreement / waterfall | Pro-rata TIC dists + **separate incentive fee agreement** |
| Sponsor Member managing member | DMA + construction contracts |
| JV closing = land closing | **Split**: EAT land close Day 0; **no** JV entity at Day 0; "JV" is contractual |
| Equity funding fee to JLL | May still apply at first capital event — timing unclear |
| Simultaneous JV+loan+permit close | **Stagger**: EAT path allows land before permit if lender/PSA permit; still need lender buy-in |

Expect **full definitive-doc re-draft**, not a schedule to the existing LLC form.

---

## Path 3 — Structure A: 100% fee to exchanger, then §721 JV after seasoning

### What it is

**Phase 1 (Days 0–180):** EAT holds title; QI funds Kao's exchange equity; Hanover's 5% is characterized as **secured, interest-bearing loan** (not equity). Hanover earns **market DMA + GMP** as standalone contracts. Day 180: EAT deeds **100% fee title** to Kao's SMLLC. Exchange completes against **direct real property** — no co-tenant, no partnership interest received.

**Phase 2 (after genuine seasoning):** Kao contributes property to new PropCo JV LLC under **§721**; Hanover converts loan to **5% membership + promote**. Term-sheet waterfall lives **only** in Phase 2 partnership.

*Source: `docs/sources/StructureA-draft.md` — **DRAFT**, AI-drafted, not counsel-reviewed.*

### Timing

| Phase | When | What happens |
|---|---|---|
| Phase 1: Days 0–180 | Sept 2026 – Feb 2027 | Same EAT/build draws as Path 2; **100% deed to Kao** at Day 180 |
| **Seasoning clock starts** | **EAT→Kao deed date** (~Feb 2027) | **Not** Day 0 — counting from Day 0 is a step-transaction red flag per draft |
| Seasoning floor (draft) | Later of **12 mo post-deed** AND **substantial completion** | Earliest JV: ~Feb 2028+ if substantial completion ~11 mo from Sept 2026 |
| Comfort target (draft) | ~**24 mo post-deed** + lease-up/refi | Pushes JV toward 2029 |
| Phase 2 | TBD after seasoning | §721 contributions; promote activates |

**Tension:** Full build ~11 months from Sept 2026 ≈ **Aug 2027** substantial completion — inside the 12-month post-deed window but **overlaps** the seasoning "don't contribute while incomplete" guardrail in the draft. Real calendar is tight; rushing Phase 2 for Hanover comfort **increases** step-transaction risk.

### Parties

| Party | Phase 1 | Phase 2 |
|---|---|---|
| Kao SMLLC | **100% fee owner** | Contributes property → 95% JV |
| Hanover Capital LLC | **Lender** (~$1.1M secured note) | Converts to 5% + promote via §721 |
| Hanover Industrial / Construction | DMA, GMP, guarantor | Same + JV managing member |
| EAT / QI | Parking / proceeds | Exit after deed |
| PropCo JV LLC | **Does not exist** | Partnership for tax; holds property |

### Money flow sketch

```
Phase 1 (Days 0-180):
  Belara → QI ($20M)
  QI ──equity draws──► EAT ◄── Lender (~$30M)
  Hanover Capital ──secured LOAN (~$1.1M)──► EAT   [NOT equity]
  EAT ──► Land ($6.5M) + construction draws ($5M + $10M + ...)
  EAT ──► Hanover DMA (4%) + GC (4.5%) — standalone market contracts
  Day 180: EAT ──100% fee deed──► Kao SMLLC

Seasoning gap (~12-24+ mo):
  Kao SMLLC holds 100% title, bears benefits/burdens
  Construction loan remains (Kao as owner/borrower or assumed)
  Hanover: creditor + contractor only (no promote, no equity dists)

Phase 2 (§721):
  Kao SMLLC ──property──► PropCo JV (95%)
  Hanover ──loan conversion + cash if needed──► PropCo JV (5% + carry)
  Waterfall: term-sheet promote in JV LLC
```

### Main tax risks

| Risk | Severity | Notes |
|---|---|---|
| **Step-transaction doctrine** | **High** — central risk | IRS collapses Phase 1 + 2 if mutual interdependence, binding commitment, or pre-arranged end result. Draft targets **MLTN**, not "clean." |
| **Binding Phase 2 commitment** | **High** | Signed contribution agreement, fixed-price equity option, or promote-mirroring walk-away fee **strengthens** attack. Draft requires **non-binding LOI only**. |
| **§707 disguised sale** | **Medium** | Hanover cash in + Kao benefits out within 2 years — sequence carefully. |
| **Magneson / Bolker reliance** | **Limited** | Pre-1984 Ninth Circuit; **Bolker not a §721 case**; Eleventh Circuit (Georgia) not bound. |
| **Boot / build-to-suit** | **Medium** | Same as all paths — document in-place value by Day 180. |
| **Hanover Phase 1 = disguised equity** | **Medium** | If loan lacks market terms, security, and independence, creditor characterization fails → partnership from Day 1 argument. |

Phase 1 is **strong on entity classification** (100% sole owner cannot be partnership). That is **necessary, not sufficient**.

### Hanover commercial fit

**Weakest on ownership timing; strongest on promote tax character (if Phase 2 happens).**

| Hanover concern | Reality in Structure A |
|---|---|
| 5% equity Day 1 | **No** — loan until §721 |
| Promote during construction | **No** — only DMA/GC fees Phase 1 |
| Guaranties / overrun risk | **Same or worse** — Hanover guarantees loan, funds debt, takes construction risk **before** equity |
| Exit if Kao walks | Needs **cost-based termination fee** — not promote-mirroring (draft) |
| Familiar LLC JV docs | **Delayed** 12–24+ months; Phase 1 is different animal |

Hanover must trust **non-binding** Phase 2 path or rely on secured loan + indemnity/LC (draft neutrality package). That is a **negotiation leap** from unsigned term sheet.

### Term sheet rewrite burden

**Very heavy — two-document architecture.**

1. **Phase 1 package:** EAT/QI agreements, PSA to EAT, loan to EAT then assumption by Kao, Hanover **loan docs** (not equity), DMA, GMP, guaranties, Kao indemnity/LC for Hanover exposure, **non-binding** Phase 2 LOI.
2. **Phase 2 package (later):** LLC JV operating agreement with full waterfall — essentially the current term sheet, but contribution-triggered.
3. **Closing choreography:** Term sheet simultaneous JV+loan+land+permit **cannot** be Day 1 literal. Land may close into EAT; **JV close moves**.

Commercial numbers can stay; **legal sequence inverts**.

---

## Path 4 — Structure B: 100% forever + incentive fee

### What it is

Same **Phase 1 exchange** as Structure A (EAT, 100% fee to Kao at Day 180). **No §721 JV ever.** Kao retains **100%** through construction, lease-up, and sale/refinance. Hanover compensated via:

- 4% development fee, 4.5% GC fee (unchanged)
- **Incentive fee** contractually mirroring promote IRR hurdles — paid as **ordinary income** to Hanover (gross-up likely)

*Source: Structure A draft scorecard / fallback — **DRAFT**.*

### Timing

| Phase | When | What happens |
|---|---|---|
| Exchange window | Days 0–180 | Identical to Structure A Phase 1 |
| Post-180 | Indefinite | Kao 100% owner; Hanover **vendor + guarantor** |
| Exit | Sale/refi per Kao | Incentive fee calculated at liquidity event |

**No seasoning-to-JV clock** — but Hanover never receives equity.

### Parties

| Party | Role |
|---|---|
| Kao SMLLC | **100% owner** throughout |
| Hanover | Contractor, guarantor, **incentive fee payee** — not member |
| Lender | To EAT, then Kao as sole owner |

### Money flow sketch

```
Days 0-180:  [Same as Structure A Phase 1 — 100% to Kao at Day 180]

Post-180:
  Project cash / sale proceeds ──► Kao (100%)
  Kao ──► Hanover: dev fee, GC fee, incentive fee (IRR mirrors promote)
  Hanover: NO equity distribution, NO carry character
```

Hanover's 5% capital may be **eliminated** or restructured as additional lending/fees — economics need repricing.

### Main tax risks

| Risk | Severity | Notes |
|---|---|---|
| **Exchange qualification** | **Lowest** among alternatives | Kao receives only real property; no partnership interest; no co-tenant — per drafts, strongest §1031 |
| **Disguised equity** | **Low–Medium** | If incentive fee is purely formulaic on Kao's return, IRS could argue **hidden partnership** — lower risk than TIC+promote but not zero |
| **Fee deductibility / capitalization** | **Medium** (Kao side) | Incentive fee treatment for Kao's tax basis / capitalization — counsel item |

### Hanover commercial fit

**Worst pre-tax economics for Hanover** unless repriced.

| Issue | Impact |
|---|---|
| Promote → ordinary income | Higher tax cost; likely **gross-up** negotiation |
| No equity upside character | Carry treatment lost |
| No JV governance seat | Managing-developer role via contract only |
| Guaranties unchanged | Hanover still on hook for lender |

May be acceptable only as **fallback** if Paths 2–3 fail opinion, or if fee gross-up makes Hanover whole on an after-tax basis (increases Kao's cost).

### Term sheet rewrite burden

**Heavy on economics, medium on form.**

- Replace entire **equity/waterfall** article with **incentive fee schedule**
- Remove or redefine 5% capital call mechanics
- Guaranty and GC/DMA sections largely portable
- May need **higher fee percentages** to offset tax drag — commercial re-trade, not just legal re-label

---

## Path 5 — Hybrids worth naming

No hybrid eliminates the core trade-off: **direct real property to Kao at exchange completion** vs. **Hanover promote + 5% equity at term-sheet timing**. Hybrids mostly **stack complexity** without clearing both hurdles.

### 5A — TIC at Day 180 → §721 LLC later ("delayed JV")

| Element | Detail |
|---|---|
| **Mechanics** | Path 2 through Day 180 (95/5 TIC deeds); operate as TIC through construction; after stabilization/seasoning, both co-tenants contribute undivided interests to LLC via §721 |
| **Timing** | Hanover has **5% equity earlier** than Structure A; LLC JV **later** than Path 2 |
| **Tax** | **Inherits TIC partnership risk** during entire Phase 1 *and* step-transaction risk on later LLC drop-down. Promote still cannot run in TIC — still needs fee sidecar until LLC forms. |
| **Hanover fit** | Better than A on Day-180 equity; worse than Path 1 on simplicity |
| **Rewrite burden** | **Heaviest** — full TIC docs **plus** future JV docs **plus** §721 contribution mechanics |

**Assessment:** Combines Path 2's contested Day-180 co-ownership with Path 3's delayed partnership. Only worth discussing if counsel believes **TIC classification is defensible** but **100% deed is unnecessary** — we have **no such opinion**.

### 5B — Structure A with Hanover as nominal TIC co-owner (5% deed) instead of lender

| Element | Detail |
|---|---|
| **Mechanics** | Day 180: 95/5 deeds like Path 2, but **no promote in TIC**; seasoning; then §721 to JV |
| **Tax** | Gives up Structure A's main Phase 1 advantage (sole ownership). Reintroduces **co-tenant partnership classification** risk for the entire seasoning period. |
| **Hanover fit** | Slightly better "equity feel" at Day 180 |
| **Rewrite burden** | TIC docs + §721 — similar to 5A |

**Assessment:** Trades away Structure A's strongest argument for marginal Hanover comfort. **Hard to justify** without lender requiring co-borrowers on title (operational constraint, not tax optimization).

### 5C — Fee-only Hanover through construction; optional §721 at exit only

| Element | Detail |
|---|---|
| **Mechanics** | Structure B through construction; if both parties want LLC for **sale**, form JV at exit via §721 contribution immediately before marketed sale |
| **Tax** | Exchange strong early; **exit-time §721** may still draw step-transaction if always planned |
| **Hanover fit** | Ordinary-income fee during life; brief equity at exit may not deliver carry economics meaningfully |
| **Rewrite burden** | Structure B + exit JV option language |

**Assessment:** Possible **conversation stub** — not a substitute for term-sheet promote during hold period.

---

## Cross-cutting constraints (all viable paths)

### 1. Belara ↔ NFCC timing

Term sheet wants **one simultaneous close**. Any EAT path **decouples**:

- Belara close (Day 0 clocks) may precede or align with NFCC land into EAT
- **JV LLC close** (if any) is **not** Day 0
- Permit timing may lag land — term sheet ties permit to close; EAT path may need **PSA/Lender** flexibility

### 2. Lender

60% LTC ≈ $30.2M. Lender must lend to **EAT**, then **TIC co-owners** or **sole Kao owner**. Hanover guaranties likely unchanged. **Written lender approval of wrapper** is a gating item — not yet obtained.

### 3. Exchangor entity chain

**Titan Management** sells Belara; **Kao Management Trust** is term-sheet LP. Must resolve **before** any path — likely contribution/DST/re-title so **one taxpayer** owns replacement and sells relinquished. Open on all paths.

### 4. Hanover Construction Group

Sits **outside** JV as GC on GMP in term sheet — **same in all paths**. Not a JV equity holder by default.

### 5. Draw model vs. Day 180

| Month | Draw | Cumulative |
|---|---|---|
| 0 (Sept 1) | Land $6.5M | $6.5M |
| 1–2 | Sitework $5M | $11.5M |
| 3–5 | Foundations $10M | **$21.5M** |

If Belara closes **with** Sept 1 Day 0, cumulative **exceeds** $20M target by ~month 5 ≈ Day 180. **If Belara slips to mid-Aug** without moving NFCC, clocks and draws **misalign** — boot risk rises.

### 6. Opinion gate

All non–Path-1 options require **written §1031 counsel opinion on executed docs** before Belara. AI memos in `docs/sources/` are **DRAFT** — not reliance-grade.

---

## Conversation prep — questions for counsel (not answered here)

1. **Path 2 vs. 3 at Day 180:** Is 95/5 TIC deed or 100% fee deed required for defensible exchange given promote economics?
2. **Promote-as-fee:** Can IRR-linked fee ever be arm's-length, or does it always poison TIC?
3. **Structure A seasoning:** Minimum defensible gap given ~11-month build — can substantial completion and 12-month floor be reconciled without farcical delay?
4. **Hanover loan vs. equity** in Phase 1: What documentary and pricing requirements satisfy creditor vs. equity characterization?
5. **Exchangor:** Titan → Kao Trust chain — what pre-close restructure is cleanest?
6. **Lender:** TIC vs. sole-owner post-180 — which is financeable in current market?
7. **Boot:** What documentation standard at Day 180 for partially complete foundations?

---

## What we should **not** tell Hanover (yet)

- That we have chosen a path (we have not)
- That any path is "clean" or counsel-approved
- That promote-as-fee or §721 seasoning is standard/off-the-shelf

## What we **can** tell Hanover (factually)

- Term sheet economics are directionally understood; **legal acquisition wrapper must change** for §1031
- Simultaneous LLC JV close as written **conflicts** with exchange mechanics for ground-up replacement
- We are modeling **alternatives** with the same dollars; need their **principled flexibility** on timing of equity/promote and entity form
- **Lender conversation** on EAT/TIC/sole-owner should start early

---

## Sources used

| File | Role |
|---|---|
| `docs/PROJECT_BRAIN.md` | Dates, draws, parties, user stance |
| `docs/DIGEST.md` | Synthesis, path summaries |
| `docs/incoming/term-sheet-extracted.txt` | LLC JV commercial terms |
| `docs/sources/StructureA-draft.md` (first ~320 lines) | Structure A/B mechanics, risks, seasoning |
| `North_Forsyth_1031_Diagrams.md` (overview) | TIC + EAT + promote-as-fee model |
| `ai_rules.md` | User-stated facts, open items |

---

*Internal working paper. Update when counsel weighs in or Hanover responds.*
