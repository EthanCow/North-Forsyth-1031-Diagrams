# Structure C-Hybrid — Detailed Legal Review (Claude + Codex pressure-tested)

**Status:** Internal research · **DRAFT** · **NOT a legal/tax opinion** · No structure locked
**Date:** 2026-06-14
**Method:** `grill-me-pro` — Claude interviewed the user to fix requirements, then ran three adversarial rounds with **Codex** (GPT-5.2, skeptical senior tax-structuring attorney + partnership-tax CPA). This memo is the **merged, converged** output. Concerns explicitly sourced to Codex are marked **[Codex]**.
**Opinion target:** **More likely than not (MLTN)** for the §1031 exchange — *not* "should," *not* clean. Success depends less on the diagram than on **disciplined conduct for 12–24 months**. **[Codex]**

> Supersedes nothing on the live site. Feeds the **next session's** diagram/workflow build. Obtain a written §1031 opinion on executed documents before Belara closes.

---

## 0. The problem in one screen

Two hard constraints pull in opposite directions:

1. **Kao's §1031** — post-TCJA §1031(a)(1) + Reg. §1.1031(a)-3 limit like-kind exchanges to **real property**. A partnership/LLC interest is **not** like-kind (*Gluck*, T.C. Memo 2020-66). So Kao must receive **100% real property** at exchange completion — **not** a 95% JV interest.
2. **Hanover's capital-gain carry** — for the promote to be **capital gain**, it must be a **partnership profits interest** (carried interest), which requires a **partnership** that does not exist at exchange completion.

The only reconciliation is **sequencing**: clean real-property acquisition first, promoted partnership second, bridged by a genuine **seasoning gap** that defeats the **step-transaction doctrine**. Everything below is how to do that while (a) keeping Hanover's full commercial economics, (b) giving Hanover capital-gain carry, and (c) making sure the restructure itself creates **no surprise current tax for Kao**.

---

## 1. Client-resolved requirements (from the grill — fixed inputs)

| # | Decision | Resolution |
|---|---|---|
| 1 | **Risk floor for the exchange** | **MLTN acceptable.** We keep Hanover's carry and accept managed step-transaction risk; we do not chase "should." |
| 2 | **What "economically/risk neutral" protects** | **Hanover after-tax parity** (capital-gain carry preserved) + **commercial waterfall preserved** (95/5, 20/30/40 over 10/14/18, fees, overrun split). |
| 3 | **Kao surprise tax** | **HARD requirement.** The wrapper must be tax-silent for Kao at Phase 2 — no §752(b)/§731 deemed-distribution gain, no §707 disguised sale, §704(c) handled. Deferral must survive JV formation. |
| 4 | **Hanover comfort / credit support** | **Negotiation variable** (lean → full): collateralized indemnity/LC for guaranty exposure + cost-based break fee. **Hard cap:** any break fee/make-whole stays **cost-based** — **no promote/IRR-mirroring make-whole** (disguised equity). |
| 5 | **Exchanger / long-term owner** | **Kao Management Trust** (one taxpayer). Belara aligned into a **trust-owned disregarded SMLLC** pre-close. |
| 6 | **Hanover relationship** | User is a **salaried Hanover employee**; family holds **zero equity** in Hanover. High mutual trust makes the non-binding Phase-2 path commercially viable. |

---

## 2. The structure — Structure C-Hybrid

### 2.1 Entity alignment (pre-close, gating)

- **Kao Management Trust** is the exchanger and long-term owner. The taxpayer that **sells Belara** must be the taxpayer that **acquires North Forsyth** — same taxpayer, start to finish; a disregarded SMLLC under that taxpayer is fine, a different entity is not.
- **Belara sits in Titan Management today** (the parents' company). The trust and Titan are **probably different taxpayers**. Belara must therefore be moved into a **trust-owned disregarded SMLLC before the Belara PSA**.
- **CPA-gating classifications (change whether the move is even tax-free):**
  - **Grantor vs. non-grantor trust.** Grantor (disregarded to the parents) + Titan owned by the parents → the alignment may be between disregarded entities of the same taxpayer = **tax-neutral**. Non-grantor (its own taxpayer) → moving ~$20M of Belara in is a **gift (gift-tax exposure) or a sale (current income tax)**. **Huge fork — confirm first.**
  - **Titan's classification** — disregarded SMLLC / partnership / corporation.

### 2.2 Phase 1 — The Exchange (Days 0–180)

| Element | Detail |
|---|---|
| **Proceeds** | Belara → **Strake** → **QI (Riverway Title)**. Kao never touches the cash (avoid constructive receipt, Reg. §1.1031(k)-1). |
| **Title/build vehicle** | Independent **EAT** under a written **QEAA** (Rev. Proc. 2000-37) takes title to NFCC, borrows the **nonrecourse** construction loan, and builds. |
| **Clocks** | Day 45 — identify NFCC **+ a real, closable backup DST**. Day 180 — EAT deeds **100% fee title** to **Kao NFCC Owner SMLLC** (disregarded → trust). **Extend the 2026 return** to preserve the full 180 days. |
| **Hanover's four Phase-1 roles** | (1) **Developer** under a market **4% DMA**; (2) **GC** under the **GMP at 4.5%** ($300K advance); (3) **secured, interest-bearing LENDER** of its ~$1.1M (a real note — **not** equity, **not** a "preferred return"); (4) **guarantor** (completion/carry/overrun/carve-out — all **auto-terminating at Substantial Completion** per the term sheet). **Hanover is not on title.** |
| **Control line [Codex]** | Hanover runs the **build** (permits, design team, schedule, GC/subs, draw packages, day-to-day, *recommend* budgets/leasing). **Kao retains all owner Major Decisions** during Phase 1 and seasoning: approve budget & material changes, debt/refi, leases above thresholds, sale, **JV formation**, GMP amendments/major change orders, **final draw approval / bank-account control**, terminate developer for cause — and **bears upside/downside as 100% owner**. The line is crossed when Hanover has unilateral authority over sale/refi/leasing/budget, economic upside beyond fees+interest, loss-sharing, or owner-only vetoes. |
| **Hanover comfort package** | Negotiable lean→full: collateralized indemnity / **LC sized to Hanover's actual lender-guaranty exposure**, market fees (real margin), market interest on the loan, **cost-based** break fee. **No promote-mirroring make-whole.** Any forward understanding is a **non-binding LOI only** — either party can walk for any reason, cost-based consequences only. **[Codex]** |

### 2.3 Seasoning — the clock that makes or breaks it

- Runs from the **EAT→Kao deed date** (~Day 180), **not** Day 0.
- **Floor:** later of **12 months post-deed** and **substantial completion**. **Comfort / path toward "should":** ~**24 months** + meaningful **lease-up** and ideally a **refinance** to nonrecourse permanent debt.
- During the gap Kao **operates as a genuine 100% owner** (title, loan, leases, insurance, cash flow, depreciation, funds shortfalls via debt — never Hanover equity). **No binding contribution obligation; no fixed-price option; non-binding LOI only.** Document an **independent business purpose** for combining later, contemporaneously.
- **Why the gap also fixes §752 (below):** by the time PropCo forms, the **guaranties have expired** and **§263A-capitalized construction costs have built Kao's basis** well above the suppressed carryover figure.

### 2.4 Phase 2 — The §721 JV (the hybrid)

**This is the key innovation from the Codex rounds.** Hanover's economics are **bifurcated** for tax character:

1. **Real ~$1.1M cash 5% CAPITAL interest.** Hanover contributes **fresh cash** for a genuine 5% capital interest that participates **95/5** in the baseline waterfall — preserving the *literal* term-sheet economics (return of capital + the pro-rata tier up to LP's 10% IRR). **Do NOT convert the Phase-1 loan into capital** — the loan is **repaid separately** (re-opening a conversion re-creates §707/valuation problems). **[Codex]**
2. **Separate, zero-liquidation-value PROFITS interest** for the **20/30/40 promote over 10/14/18 IRR** (Rev. Proc. 93-27 as clarified by Rev. Proc. 2001-43) — a clean **carried interest = capital gain**. Must receive **nothing on a hypothetical immediate FMV liquidation** at grant to qualify.

| Phase-2 mechanic | Treatment |
|---|---|
| Kao contributes NFCC to **PropCo JV LLC** (DE, partnership for tax) | §721 nonrecognition; **95%** member |
| **§704(c) — remedial method** | Keeps Belara's built-in gain allocated to **Kao** |
| **§752** | Loan **nonrecourse at PropCo**, no surviving Hanover principal/completion/carry guaranty → **Reg. §1.752-3** tiers (minimum gain → §704(c) gain → excess by profits) keep the built-in-gain debt layer with Kao |
| **§707** | **No Kao distribution within 2 years** unless separately cleared (Reg. §1.707-3/-5); trace loan proceeds to NFCC capex (qualified-liability treatment) |
| **§1061** | Hold **> 3 years** for Hanover's carry to be long-term |
| **Documentation** | Written **§752 outside-basis schedule** before/after; separate valuation establishing the profits interest has **zero** liquidation value at grant |

---

## 3. Why this satisfies each requirement

**Hanover gets capital gains.** The promote is a **profits interest**, which is capital-gain by nature (§1061 limits the *rate*, it doesn't create the character). Bifurcating it from the small real capital interest keeps the Rev. Proc. 93-27/2001-43 analysis clean — the promote is unambiguously a service profits interest with no capital component to muddy it. **[Codex: a pure profits interest would have silently stripped Hanover's capital layer; the hybrid is the right reconciliation if full commercial parity is non-negotiable.]**

**Commercial waterfall preserved.** Hanover really co-invests 5% and gets it back pro-rata, exactly like the term sheet; the 20/30/40-over-10/14/18 promote sits above. Only the **legal wrapper and timing** move.

**Kao incurs no surprise tax.** The §752(b)/§731 deemed-distribution gain — the silent killer that can tax the very gain you deferred — is defused primarily by **timing**: form PropCo **after substantial completion**, when the recourse-creating guaranties have expired and only nonrecourse debt remains, with basis built up by capitalized construction. **[Codex: timing is the real fix; guaranty-engineering is second-best cleanup. Do NOT use a Kao bottom-dollar guaranty — disregarded under Reg. §1.752-2(b)(3) since the 2016/2019 regs; if Kao liability allocation is needed, use a capped first-loss/top-dollar guaranty or a real collateralized indemnity.]**

---

## 4. The relationship / employment analysis

**Bright-line related-party statutes do NOT bite. [Codex]** Salaried employment without equity/control does not make Kao and Hanover related under **§267(b)**, **§707(b)**, or **§1031(f)** (which cross-references §267(b)/§707(b)(1)) — those key off family, fiduciary/trust, and **ownership/control**, not employment. Family holds **zero Hanover equity** → clean.

**QI/EAT independence — a narrower concern. [Codex]** Reg. §1.1031(k)-1(k) disqualifies a person who acted as **the taxpayer's** employee/attorney/accountant/broker within 2 years (plus 10% related-party tests). So:
- Employee of **Hanover**, standing alone, does **not** taint the QI/EAT.
- The employee acting as **Kao's** agent/broker/advisor **could**. Keep the employee out of that role.
- The **QI and EAT must not be Hanover affiliates**, and Hanover must not select/control/fund/indemnify/direct them beyond normal transaction coordination.

**Step-transaction is AMPLIFIED by the trust relationship. [Codex]** The closeness that makes Hanover accept a non-binding path also makes the IRS's **end-result / mutual-interdependence** story easier to tell ("Kao always intended NFCC as a parking step before joining Hanover's promoted partnership"). It does **not** destroy MLTN if the **legal rights and conduct preserve genuine uncertainty** — it **does** destroy MLTN if the file says, in substance, "we all know Phase 2 will happen."

**Documentation & conduct rules (non-negotiable): [Codex]**
- No signed contribution agreement, option, put/call, fixed-price admission, or enforceable exclusivity.
- LOI states **either party can walk for any reason**, cost-based consequences only.
- **No** emails/texts saying "done deal," "guaranteed promote," "temporary 1031 wrapper," "Hanover already owns 5%," or "we'll paper it after seasoning."
- **Employee recuses** from all Hanover-side decisions on this deal (investment committee, pricing, guaranty, credit, approval). Hanover-side terms set by **disinterested executives**; Kao-side by **trustee/family advisors**, not the employee. **Separate counsel** for each side.
- **Independent benchmarking** of the DMA fee, GMP fee, loan interest, guaranty fee/indemnity, and break fee (arm's-length pricing support).
- Hanover approval memo: **Phase-1 economics stand alone**. Kao memo: **prepared to own NFCC 100% indefinitely** if Phase 2 is not optimal.
- Conduct during seasoning must **match sole ownership** (Kao approves budgets, leases, refi, sale, capital plan, insurance, bank accounts).

**Conflict is an evidentiary, not a doctrinal, problem. [Codex]** It doesn't blow up §1031 by itself; it lets the IRS argue the terms weren't arm's-length / the loan-fees-guaranty package was really equity / the LOI was a sham. Neutralize with **corporate process** (written conflict disclosure, disinterested decision-makers, independent pricing, board minutes stating the employee did not approve Hanover's terms).

---

## 5. Entity map (all to-be-formed placeholders)

| Entity | Side | Type | Role | Tax status |
|---|---|---|---|---|
| **Kao Management Trust** | Kao | Family trust (grantor vs non-grantor **TBD**) | Exchanger & ultimate taxpayer | Pass-through / TBD |
| **Belara Seller SMLLC** | Kao | Trust-owned SMLLC | Holds & sells Belara (Belara aligned in pre-close) | Disregarded |
| **Kao NFCC Owner SMLLC** | Kao | Trust-owned SMLLC | Receives 100% fee at Day 180; contributes to PropCo → 95% member | Disregarded → partner |
| **Strake Jesuit** | Neutral | Institution | Buyer of Belara only | n/a |
| **Riverway Title (QI)** | Neutral | Qualified Intermediary | Holds proceeds; safe harbor | Unrelated; independent of both sides |
| **NFCC Parking Title LLC (EAT)** | Neutral | SMLLC (EAT) | Parks title, borrows loan, builds (Rev. Proc. 2000-37) | Beneficial owner; **independent of Kao AND Hanover** |
| **Construction Lender** | Neutral | Bank | ~$29–30M **nonrecourse** loan, ~60% LTC | Arm's-length |
| **NFCC Land Seller** | Neutral | LLC | Sells land to EAT | **Unrelated third party — verify** |
| **Backup DST** | Neutral | DST interest | Boot backstop, identified ≤ Day 45 | Real, closable ≤ Day 180 |
| **Hanover Industrial LLC** | Hanover | LLC | Sponsor (term-sheet counterparty) | — |
| **Hanover NFCC Developer LLC** | Hanover | LLC | DMA (4%) | Ordinary fee income |
| **Hanover Construction Group LLC** | Hanover | LLC | GC on GMP (4.5%) — **not on equity chart** | Ordinary fee income |
| **Hanover NFCC Capital LLC** | Hanover | LLC | Phase-1 secured lender (~$1.1M); **repaid before Phase 2** | Interest income |
| **Hanover NFCC Member LLC** | Hanover | LLC | Phase 2: **fresh-cash 5% capital member** + **separate promote profits interest** | Partner; promote = carried interest (cap gain, §1061) |
| **North Forsyth Commerce Center PropCo JV LLC** | Asset/JV | DE LLC, partnership for tax | Operating JV (Phase 2) | Partnership (pass-through) |

---

## 6. Boot / build-to-suit feasibility

Only **real property physically in place and paid for by Day 180** counts toward ~$20M. $6.5M land + ~$13.5M in-place improvements on a $50.3M ground-up project is **plausible but not bankable**. **[Codex]**

**Levers, ranked: [Codex]**
1. **Align/delay the Belara closing** so Day 180 lands after enough construction is in place (user controls Belara timing — strongest lever).
2. EAT acquires NFCC only when **permits/GMP/loan are ready for immediate draws**.
3. Identify a **real DST backup** by Day 45; close it ≤ Day 180 if NFCC lags.
4. **Model acceptable boot** (recognize a known, quantified shortfall as 2026 capital gain + unrecaptured §1250).
5. Reverse/improvement parking helps **only** if NFCC must close before Belara — the QEAA **180-day cap does not extend** the window, so parking early just avoids a Belara-too-early mismatch, it does not buy extra statutory time. **[Codex]**

Confirm **clean title history** — if Kao ever owned NFCC within 180 days, Rev. Proc. 2004-51 blows the safe harbor.

---

## 7. Ranked failure points (honest residual risk) [Codex]

1. **Same-taxpayer failure** — Titan/Kao-Trust alignment is taxable, or the wrong taxpayer sells Belara.
2. **Binding or de facto Phase-2 commitment** — option, fixed admission right, mandatory contribution, or emails proving "done deal."
3. **Hanover treated as owner in Phase 1** — title, equity, capital account, capital calls, profit rights, or sale/refi/managing-member conduct before seasoning.
4. **QI/EAT disqualification or constructive receipt** — non-independent accommodator, bad escrow rights, or taxpayer access to proceeds.
5. **Build-to-suit shortfall** — insufficient in-place real property by Day 180 and no DST backstop.
6. **§707 disguised sale** — refi/distribution to Kao or liability assumption treated as consideration.
7. **§752 gain** — surviving guaranties or a debt-allocation shift exceeding Kao's basis.
8. **Profits-interest contamination** — promote has immediate liquidation value or is bundled with the capital interest.
9. **Conflict/process failure** — employee appears to control both sides, or Hanover gives non-market terms because of the relationship.

> Codex's closing line: *"Proceed with Structure C-hybrid, but call it what it is — a carefully papered MLTN structure whose success depends less on the diagram and more on disciplined conduct for 12–24 months."*

---

## 8. Open items / gating diligence (before relying on this)

- [ ] **CPA: trust classification** (grantor vs non-grantor) + Titan classification + tax-neutrality of the Belara alignment move.
- [ ] **CPA: written §752 outside-basis model** (drawn debt only, not full commitment) — Kao's basis & liability share before/after the §721 contribution.
- [ ] **§707 timeline** — map the loan repayment + any distributions against the 2-year window (Reg. §1.707-3/-5).
- [ ] **§704(c) method** — confirm remedial against the actual basis/FMV spread.
- [ ] **EAT & QI independence** — neither a Hanover affiliate nor a disqualified person; QEAA executed ≤ 5 business days; parking ≤ 180 days.
- [ ] **Land non-affiliation** — confirm the land seller is unrelated; confirm Kao never owned NFCC (Rev. Proc. 2004-51).
- [ ] **Lender consent (twice)** — to lend to the EAT, and to the later transfers to Kao and to PropCo (due-on-sale); nonrecourse perm-debt path.
- [ ] **Independent arm's-length pricing** — DMA, GMP, loan interest, guaranty fee/indemnity, break fee.
- [ ] **Conflict governance** — written disclosure; disinterested Hanover decision-makers; employee recusal; separate counsel; board minutes.
- [ ] **Georgia local counsel** — transfer tax, intangibles/security-deed tax, EAT→Kao deed chain & recording, title endorsements.
- [ ] **Build-to-suit feasibility** — Day-180 in-place valuation; named, closable backup DST; extend the 2026 return.
- [ ] **Written §1031 opinion** on executed documents before Belara closes — **target MLTN; do not promise "should" in writing.**

---

## 9. What changed vs. the draft Structure A (this session's value-add)

| Draft Structure A (`docs/sources/StructureA-draft.md`) | Structure C-Hybrid (this memo) |
|---|---|
| Hanover "converts its loan into a 5% interest + promote" | **Bifurcated:** loan **repaid**; **fresh-cash** 5% capital interest **+ separate zero-liquidation-value profits interest** for the promote — cleaner carry, kills the §707 conversion vector **[Codex]** |
| §752 managed by "nonrecourse + bad-boy guaranties" | §752 managed primarily by **timing** — contribute **post-substantial-completion** after guaranties expire + basis built by §263A costs; **bottom-dollar Kao guaranty rejected** (disregarded under Reg. §1.752-2(b)(3)) **[Codex]** |
| Step-transaction discussed generally | **Relationship/employment amplification** analyzed; concrete documentation/conduct + conflict-governance rules added **[Codex]** |
| Related-party noted as an open item | **Resolved:** employment-without-equity does not trigger §267(b)/§707(b)/§1031(f); QI/EAT independence framed precisely **[Codex]** |
| Boot mitigation = "backup DST" | Ranked levers; **Belara-timing alignment** identified as the strongest lever; reverse-parking myth (180-day cap) corrected **[Codex]** |
| Exchanger "Titan vs Kao Trust — OPEN" | **Decided:** Kao Management Trust; align Belara into a trust-owned disregarded SMLLC pre-close; grantor/non-grantor fork flagged as gating |

---

## 10. Next session (not now)

Build the GitHub Pages workflows/diagrams from this memo: two-phase money-flow, the entity map in §5, the seasoning timeline, the boot/Day-180 schedule, and party-by-party step diagrams (Kao / Hanover / Strake / EAT-QI). Keep every claim labeled DRAFT/OPEN until counsel opinion.

---

## Authorities cited

**Statute/reg:** §1031(a)(1), (a)(3), (f) · Reg. §1.1031(a)-3 · Reg. §1.1031(k)-1 (incl. (k) disqualified person) · §721 · §704(c) · §707(a)(2)(B); Reg. §1.707-3, §1.707-5 · §752; Reg. §1.752-2, §1.752-3 · §1061 · §267(b) · §707(b) · §263A · Reg. §301.7701-3
**Rev. procs:** 2000-37 (QEAA/parking) · 2004-51 (prior-ownership limit) · 93-27 & 2001-43 (profits interest) · 2002-22 (TIC guidance — why the old TIC failed)
**Cases:** *Magneson* (753 F.2d 1490, 9th Cir. 1985) — pre-1984, 9th Cir., not binding in the 11th · *Bolker* (760 F.2d 1039) — **not** a §721 case · *Bergford* (12 F.3d 166) · *Gluck* (T.C. Memo 2020-66)

*Prepared 2026-06-14. Claude + Codex pressure-tested; NOT counsel-reviewed; not a covered opinion.*
