# Research Memo: Exchangor Entity — Titan Management vs Kao Management Trust

**Date:** 2026-06-14  
**Status:** Internal research — **NOT legal advice**  
**Prepared for:** North Forsyth §1031 planning (Belara → NFCC)  
**Modeling Day 0:** Sept 1, 2026 (Belara close aligned with NFCC land; cushion vs Sept 15)

---

## Executive summary

Belara is sold today by **Titan Management** (STATED user), but the Hanover term sheet names **Kao Management Trust** as LP Partner / economic investor. For a deferred §1031 exchange, the **same taxpayer** that relinquishes Belara must acquire the replacement property (directly or through a disregarded entity). A family relationship between Titan and Kao Trust does **not** substitute for identity of taxpayer. **NEEDS COUNSEL** on trust/LLC classification and any pre-close re-title.

**Working hypothesis (not verified):** The path that best matches user preference — Kao Management Trust as exchanger with modest pre-close work — is likely **(a) align legal seller with Kao Trust before Belara PSA is drafted**, or **(b) a counsel-approved contribution/assignment of Belara from Titan to Kao Trust (or a Kao-owned DRE) before sale**, so the PSA, QI exchange agreement, and EAT→exchangor deed all name the same exchanger. **Titan-as-exchangor** is simpler only if Titan will also hold replacement title through Day 180 and any post-exchange JV step is separately structured (e.g., later transfer to Kao Trust) — that downstream transfer is **not** part of the exchange and may trigger gain unless counsel designs around it. **NEEDS COUNSEL** throughout.

---

## 1. Why entity alignment matters for §1031

### 1.1 Same taxpayer rule

Section 1031 defers gain only when a taxpayer exchanges property held for productive use in trade or business or for investment for like-kind property. **IRC §1031(a)(1).** The exchange is a transaction of the **taxpayer** who owns the relinquished property and the **same taxpayer** who receives the replacement property.

Treasury regulations under the qualified-intermediary safe harbor require that the taxpayer who transfers the relinquished property be the same taxpayer who receives the replacement property. **Reg. §1.1031(k)-1(g)(4).** If sale proceeds are wired to a QI but the **legal seller** on the deed is Entity A while the **transferee** from the EAT at Day 180 is Entity B, the exchange generally **fails** for deferral purposes unless A and B are the same taxpayer for federal income tax (e.g., disregarded entity and its owner). **NEEDS COUNSEL.**

The unreviewed lawyer notes in this repo state: *"ownership has to stay in the same entity."* That is directionally correct for exchange planning: the **ownership/taxpayer chain** from relinquished property through QI/EAT to replacement must be continuous. **UNREVIEWED** — not counsel's opinion on this deal.

### 1.2 Constructive receipt and QI mechanics

Net sale proceeds must go **directly to the QI** (identified: **Riverway Title**, STATED user); the exchanger must not have actual or constructive receipt. **Reg. §1.1031(k)-1(b)(2), (f).** The exchange agreement, assignment of rights in the PSA, and escrow wiring instructions must name the **exchangor** consistently. A mismatch between deed seller and exchange taxpayer invites IRS challenge and may void the QI safe harbor. **NEEDS COUNSEL.**

### 1.3 Disregarded entities — Reg. §301.7701-3

**Reg. §301.7701-3** (entity classification):

| Entity type | Default / election | Federal tax treatment |
|---|---|---|
| Domestic LLC with **one** owner | Can elect corp; default **disregarded** | Activities treated as owner's — **same taxpayer** as sole member if disregarded |
| Domestic LLC with **two+** owners | Partnership (or corp if elected) | **Separate** taxpayer |
| Trust | Depends on type (grantor vs non-grantor) | Grantor trust: **IRC §§671–679** — income taxed to grantor; often treated as **same taxpayer** as grantor for many purposes. Non-grantor trust: **separate taxpayer**. |

**Critical skepticism:** "Same family controls both" ≠ "same taxpayer." Titan Management and Kao Management Trust are **different legal entities** (STATED user). Unless counsel confirms:

- Titan is a **disregarded LLC** wholly owned by the same individual(s) who are grantors/beneficiaries of a **grantor trust** Kao Management Trust, **and**
- The IRS will treat the chain as a single taxpayer for §1031 (not automatic — fact-specific),

…they are **two taxpayers** for exchange purposes. **NEEDS COUNSEL** with actual org charts, trust instruments, and check-the-box elections.

### 1.4 Replacement property form

Post-TCJA, §1031 applies only to **real property**. **IRC §1031(a)(1)** (as amended); **Reg. §1.1031(a)-3.** A **membership interest in a Delaware LLC JV** (as the term sheet contemplates at Day 1) is **not** like-kind real property. That is a **structure** issue separate from exchanger identity, but the **entity that receives replacement real property** at exchange completion (deed from EAT) must still be the exchanger (or its disregarded subsidiary). **NEEDS COUNSEL** on whether Kao Trust should take title directly, through a Kao-owned SMLLC, or through another DRE.

### 1.5 Improvement / build-to-suit exchange

Ground-up NFCC requires an **Exchange Accommodation Titleholder (EAT)** under **Rev. Proc. 2000-37** (build-to-suit / reverse parking). The **exchangor** is the party that ultimately receives the improved property within **180 days** of Belara close. Only improvements **in place and paid for** within that window count toward reinvestment (~$20M target). Entity on the **final deed from EAT** must match exchanger. **NEEDS COUNSEL** on EAT engagement (EAT provider **TBD**).

---

## 2. Structural options (high-level)

**Facts:** Belara ~$20M, no debt (VERIFIED). Buyer: Strake Jesuit. QI: Riverway Title. NFCC land ~$6.5M Day 0; ~$50.3M total project; 95/5 Kao/Hanover economics per **unsigned** term sheet.

### Option (a) — Sell Belara from the entity that will own replacement

**Mechanics:** Identify **one exchanger** (target: **Kao Management Trust** per user preference and term sheet). That entity is:

- Legal **seller** on Belara PSA and deed  
- **Assignor** to QI under exchange agreement  
- Named **exchangor** in QI/EAT documents  
- **Transferee** on deed from EAT at Day 180 (possibly via Kao-owned SMLLC if disregarded)

**If Belara is currently titled in Titan:** Pre-close **deed re-title** or contribution so **Kao Trust (or Kao DRE)** holds Belara before PSA binds. Timing must be before exchange is "initiated" (typically before first leg closes). **NEEDS COUNSEL** on whether re-title triggers property-tax reassessment, transfer tax, or unintended gain (usually not on mere deed to commonly controlled entity if structured correctly — **not relied upon here**).

| Pros | Cons |
|---|---|
| Cleanest §1031 identity — one taxpayer start to finish | Requires confirming **who holds Belara title today** and pre-close legal work |
| Aligns PSA, QI, EAT, and term sheet LP name | If Titan holds contracts/loans on Belara, assignment complexity |
| Matches Hanover investor-LP pattern (Kao side) | Trust vs LLC classification must be confirmed |

**Complexity:** Modest if title can move to Kao Trust (or Kao SMLLC) with simple deed + trust/entity confirmations. **User stated modest Belara-close complexity is acceptable for Kao Trust.**

---

### Option (b) — Contribute Belara to Kao Trust (or Kao DRE) before sale

**Mechanics:** Titan contributes Belara to Kao Management Trust or a wholly owned subsidiary (e.g., "Kao NFCC Holdings LLC" as disregarded SMLLC) **before** Strake closing. Titan (or Kao) then sells as exchanger — **the contributor must not be the exchanger unless the contribution is ignored for tax**.

**Tax angles (research only — NEEDS COUNSEL):**

- **Contribution to grantor trust:** If Kao Trust is a grantor trust as to the family, contribution may be ignored for income tax (grantor trust rules). Sale by trust = sale by grantor for some purposes — but **§1031 exchanger identity** still turns on who is legal owner at sale and who receives replacement. **NEEDS COUNSEL.**
- **Contribution to partnership (LLC with >1 member):** **IRC §721** nonrecognition may apply to partnership contributions, but introduces **partnership** as holder — complicates later exchange and replacement form. Generally **avoid** partnership as holder of relinquished property unless counsel designs full path.
- **Contribution to DRE wholly owned by Kao Trust:** Common pattern: contribute to SMLLC disregarded to Kao Trust; SMLLC sells; still **same taxpayer** as Kao Trust if disregarded. **NEEDS COUNSEL** on state law and trust ownership of LLC.

| Pros | Cons |
|---|---|
| Can preserve "Titan historically held Belara" ops while exchanger becomes Kao side | Contribution docs, trust/LLC authority, timing |
| May allow Kao Trust on PSA without public confusion if DRE is seller of record | Wrong form of contribution = taxable event or wrong exchanger |
| Fits later Hanover LP mapping (investor entity owns real property first) | **Step-transaction** risk if contribution immediately before sale with no business purpose — **NEEDS COUNSEL** |

**Complexity:** Moderate — one-time contribution agreement, deed, trust resolutions, updated PSA. Likely **acceptable** under user tolerance if counsel blesses.

---

### Option (c) — Titan sells; Kao Trust on replacement side only

**Mechanics:** Titan Management is seller/exchangor; proceeds to QI; EAT acquires NFCC; at Day 180 EAT deeds to **Titan** (or Titan DRE). Kao Trust enters only via term sheet JV **after** exchange.

**The "???" problem — downstream alignment:**

| Sub-option | What happens | §1031 / tax risk |
|---|---|---|
| **c1. Titan completes exchange; later gifts/contributes NFCC to Kao Trust** | Post-exchange transfer | **Not** part of §1031; likely **taxable** transfer of appreciated property (or installment/partnership rules). Defeats purpose of Kao as economic owner of replacement. **NEEDS COUNSEL** — likely **non-starter** for deferral into Kao's economic bucket. |
| **c2. Titan completes exchange; Kao buys from Titan** | Related-party sale | Taxable sale; boot; possibly **IRC §1031(f)** related-party concerns if structured as exchange between related parties. **NEEDS COUNSEL.** |
| **c3. Titan is exchanger; Kao funds via capital contribution to Titan** | Titan holds replacement | Kao never gets §1031 benefit; Titan bears deferred gain on future exit; economics can be replicated by contract but **not** Kao's exchange. May be "simpler" legally but **wrong economic taxpayer** for family intent. |
| **c4. Both disregarded to same individual** | Titan LLC + grantor trust | If **verified** that both are disregarded to **identical** natural person(s), IRS might treat as same taxpayer — **fact-intensive, not assumed**. **NEEDS COUNSEL** with elections and trust instrument. |

| Pros | Cons |
|---|---|
| No pre-close Belara re-title if Titan already seller of record | **Misaligns** term sheet (Kao LP) with exchange (Titan) |
| PSA may match current legal ownership | Post-exchange drop into Kao Trust/LP is **separate taxable event** unless c4 applies |
| Fewer moving parts **at Belara close only** | "Simpler" at close may mean **more tax cost** overall |

**Assessment:** Option (c) is **materially simpler only if Titan is intended to be the long-term owner of replacement** through Day 180 and beyond. That **conflicts** with user preference for **Kao Management Trust** as exchanger/LP and with the **unsigned term sheet** naming Kao. **Skeptical recommendation:** treat (c) as fallback **only** if counsel confirms (c4) same-taxpayer disregarded chain **or** family accepts Titan as exchanger and renegotiates economic ownership. **NEEDS COUNSEL.**

---

## 3. Recommendation framework (not a legal opinion)

**User preferences (STATED):** Prefer **Kao Management Trust** if §1031-compliant; **Titan** OK if **materially** simpler; modest Belara-close complexity acceptable for Kao Trust.

### Decision tree (for counsel conversation)

```
START: Who holds Belara title today? (OPEN — verify)
│
├─ Kao Trust (or Kao DRE) already holds
│   └─► Option (a): PSA seller = Kao Trust. Lowest friction. Confirm trust can sell & sign QI docs.
│
├─ Titan holds; re-title to Kao Trust/DRE is clean
│   └─► Option (a) or (b): Re-title or contribute before PSA. Modest complexity; aligns term sheet.
│       Priority if user wants Kao as exchanger.
│
├─ Titan holds; re-title blocked (lender, partner, Strake, property tax)
│   └─► Option (b) variant or (c4): Counsel-only paths (DRE chain, grantor trust analysis).
│       If none work → renegotiate who is LP OR accept Titan exchanger + taxable post-transfer (bad).
│
└─ Titan and Kao both disregarded to identical individual(s) — VERIFIED by counsel
    └─► Option (c4): May reduce need for deed hop; still use **consistent** name on PSA/QI/EAT.
        Do not rely on without written opinion. **NEEDS COUNSEL.**
```

### Likely preferred path (hypothesis — **NEEDS COUNSEL**)

| Priority | Path | Why |
|---|---|---|
| **1** | **(a)/(b) Kao Trust (or Kao disregarded SMLLC) as seller and exchanger** | Aligns term sheet LP, user preference, Hanover org chart investor side, and same-taxpayer rule |
| **2** | **(c4) Disregarded chain** only if counsel confirms same taxpayer without deed hop | Saves a deed; rare to rely on without opinion |
| **3** | **(c) Titan sells** | Only if pre-close alignment is impossible **and** family accepts Titan as tax owner of replacement |

**Cost/complexity tradeoff (qualitative):**

| Item | Kao as exchanger (a/b) | Titan as exchanger (c) |
|---|---|---|
| Pre-Belara legal | Deed + trust/entity docs (+/- contribution) | Minimal |
| PSA/QI consistency | Straightforward once seller fixed | Straightforward |
| Term sheet alignment | **High** | **Low** — Kao not exchanger |
| Post-Day 180 | Matches Structure A or TIC hypotheses with Kao receiving real property | Taxable transfer to Kao likely required |
| Counsel time | Moderate upfront | Lower upfront, higher downstream risk |

**Not chosen here:** Which of TIC vs Structure A (exchange-first then §721) — exchanger identity is **prerequisite** to both. **NEEDS COUNSEL** on whether replacement is deeded to Kao Trust directly vs Kao SMLLC.

---

## 4. What must be true before Belara PSA drafts

All items require counsel/QI sign-off. **NEEDS COUNSEL** unless marked STATED/VERIFIED.

| # | Requirement | Status |
|---|---|---|
| 1 | **Exchangor entity locked** — single name on PSA seller, exchange agreement, and EAT transferee | **OPEN** |
| 2 | **Belara title verified** — recorded owner matches exchanger (or re-title completed) | **OPEN** |
| 3 | **Entity classification memo** — Titan, Kao Trust, any SMLLC; grantor trust? disregarded? | **OPEN** |
| 4 | **QI engaged** — Riverway Title exchange agreement, fee schedule, improvement-exchange capability | STATED user; engagement **TBD** |
| 5 | **No constructive receipt** — escrow wires net proceeds **only** to QI; Strake buyer not involved in replacement | STATED user |
| 6 | **Assignment language** — seller assigns PSA rights to QI per **Reg. §1.1031(k)-1(g)(4)** | Not drafted |
| 7 | **Identification strategy** — NFCC land + improvement description for 45-day letter (~Oct 16, 2026 if Day 0 = Sept 1) | Planning |
| 8 | **180-day calendar** — Belara close → ~Feb 28, 2027 completion; aligns with NFCC Sept 1 Day 0 model | STATED |
| 9 | **EAT provider selected** — build-to-suit parking before land close | **TBD** |
| 10 | **Coordination with Hanover** — replacement acquisition **not** structured as 95% LLC interest at Day 1 (term sheet conflict) | **OPEN** — separate from exchanger memo but same timeline |
| 11 | **Trust authority** — Kao Management Trust trustee (term sheet: William Kao) authorized to sell Belara, sign PSA, engage QI | **NEEDS COUNSEL** |
| 12 | **No related-party exchange traps** — Strake unaffiliated (VERIFIED); verify land seller unaffiliated (STATED user) | Partial |

**Do not draft PSA** with Titan as seller while planning Kao as exchanger — Strake escrow will follow the deed. Fixing seller name after PSA circulation wastes leverage and risks exchange failure.

---

## 5. Mapping to Hanover org chart pattern (investor LP side)

Source: `docs/incoming/Hanover-Org-Chart-Example-Project.pdf` (Simi Valley) — **illustrative roles only**.

### Hanover template (Simi Valley)

```
Investor LP (~95%)  ←  CH REALTY … INVESTOR, L.P.
Hanover promote stack (~5%)  ←  GP/LP + THC CAPITAL LP
Land / project LLC  ←  HCI DP LAND ACQUISITION LLC → HCI SIMI VALLEY LLC
Sponsor  ←  HANOVER INDUSTRIAL LLC
GC  ←  NOT on chart; separate GMP (Hanover Construction Group on NFCC term sheet)
```

### NFCC mapping (hypothesis — entity names **TBD**)

| Hanover pattern role | NFCC analog (term sheet / user) | Exchangor memo implication |
|---|---|---|
| **Investor LP (~95%)** | **Kao Management Trust** as LP Partner | Economic owner should match **§1031 exchanger** or wholly owned DRE of exchanger |
| **Land acquisition LLC** | Future **NFCC land SPV** (e.g., HCI DP-style) | During exchange, **EAT** holds title — not Kao's JV LLC. Post-180, deed to Kao (or DRE), **not** 95% LLC membership |
| **Project LLC** | Delaware JV LLC in term sheet | **Cannot** be Day-1 recipient of exchange if goal is full deferral — LLC interest ≠ real property. JV forms **after** exchange path (Structure A §721, etc.) |
| **Sponsor** | Hanover Industrial LLC | Outside exchanger; guarantor/GC/dev fee |
| **5% capital** | Sponsor Member / THC analog | Funded **after** exchange window or as **loan** during Phase 1 (Structure A draft) — **NEEDS COUNSEL** |

**Alignment principle:** On the Simi Valley chart, the **investor LP** is a **partnership** receiving economic interest in the **project LLC**. For §1031, the investor cannot receive that partnership interest **as replacement property**. The compliant sequence is:

1. **Kao (exchangor)** receives **real property** (via EAT) by Day 180.  
2. **Later**, Kao contributes property into JV structure mirroring term sheet economics (**§721** in Structure A draft — **DRAFT, NEEDS COUNSEL**).

Exchangor entity choice **upstream** determines who can be the **Investor LP** without a taxable hop: **Kao Management Trust** (or its DRE) should own the real property before it becomes the 95% JV member.

---

## 6. Open questions for counsel

1. **Who is the recorded owner of Belara today** — Titan Management, Kao Trust, or another entity?  
2. **What is Titan Management** — LLC, corp, trust? Check-the-box election? Single-member disregarded to whom?  
3. **What is Kao Management Trust** — grantor or non-grantor under **IRC §§671–679**? Who is grantor/settlor/beneficiary?  
4. If both are disregarded to the **same individual(s)**, will counsel opine they are the **same taxpayer** for **Reg. §1.1031(k)-1(g)(4)** without a pre-sale deed?  
5. **Preferred form of pre-close transfer** (if needed): direct deed to trust vs deed to Kao SMLLC vs contribution agreement? Property tax / transfer tax consequences in Belara jurisdiction?  
6. **Step-transaction risk** if contribution/re-title occurs shortly before Strake closing?  
7. Should exchanger take replacement title **in trust name** or **Kao SMLLC** (disregarded)? Any lender/EAT preference?  
8. **Trustee authority** and Strake/Kao requirements for PSA signature block?  
9. **Riverway Title** — improvement exchange experience, standard docs, timing with Sept 1 model?  
10. **EAT selection** — who forms EAT, relationship to QI, **Rev. Proc. 2000-37** compliance?  
11. How does exchanger identity interact with chosen **Structure A vs TIC** hypothesis?  
12. **Related-party** issues if any Titan→Kao transfer occurs between family entities? **IRC §1031(f)** if applicable.  
13. State law implications (GA replacement, TX trust?) — beyond federal §1031.  
14. Does Hanover or construction lender require a **specific** LP entity name in definitive docs that conflicts with exchanger entity?

---

## 7. Citations referenced (research level)

| Authority | Relevance |
|---|---|
| **IRC §1031(a)(1)** | Like-kind exchange; real property only (post-TCJA) |
| **Reg. §1.1031(a)-3** | Definition of real property for §1031 |
| **Reg. §1.1031(k)-1** | QI safe harbor; same taxpayer; constructive receipt |
| **Reg. §301.7701-3** | Entity classification; disregarded entities |
| **IRC §§671–679** | Grantor trust rules (if Kao Trust is grantor trust) |
| **IRC §721** | Partnership contribution nonrecognition (if partnership in chain) |
| **IRC §1031(f)** | Related-party exchange rules |
| **Rev. Proc. 2000-37** | Build-to-suit / parking with EAT |

---

## 8. Labels used in this memo

| Label | Meaning |
|---|---|
| **VERIFIED** | Confirmed in term sheet or multiple repo sources |
| **STATED (user)** | User-provided; recorded in `ai_rules.md` / `PROJECT_BRAIN.md` |
| **DRAFT** | Structure hypothesis not reviewed by counsel |
| **OPEN** | Not yet determined |
| **NEEDS COUNSEL** | Requires qualified §1031 attorney before reliance |

---

*This memo is internal planning material for the North Forsyth §1031 diagram project. It is not a legal opinion and must not be shared with Strake or Hanover as advice.*
