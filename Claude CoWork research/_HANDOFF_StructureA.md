# North Forsyth §1031 — Context Handoff (load this first in a new chat)

> Purpose: lets a fresh session continue without re-reading the whole history. This captures the deal, the locked decisions, the Codex review, the merged blueprint, and the exact next steps. Status as of 2026-06-13.

## What we're doing
Running grill-me-pro on the recommended legal structure for the Belara → North Forsyth §1031 exchange: I (Claude in Cursor) grilled the user, drafted a candidate, had **Codex** attack it, and merged the result. **Next step = rewrite the docs to match the merged blueprint below.** Output is the blueprint; the rewrite has NOT been done yet.

## The deal (one line)
Kao (Kao Management Trust / "Titan Management", the family/LP) sells **Belara Apartments** (~$20M, no debt; buyer = Strake Jesuit) and 1031-exchanges into **North Forsyth Commerce Center** (~$50.3M ground-up industrial, ~327,600 SF, Forsyth County / Cumming, GA). Land $6.5M, construction loan ~$29M, equity ~$21.3M (Kao 95% ≈ $20.2M / Hanover 5% ≈ $1.1M). Hanover = developer + GC + 5% + promote (20/30/40 over 10/14/18 IRR), 4% dev fee, 4.5% GC fee, loan guaranties.

## The recommended structure — "Structure A: Exchange Clean, Then Combine"
- **Phase 1:** Kao exchanges into **100% fee title** via QI + EAT build-to-suit (Rev. Proc. 2000-37). Clean — single owner, no partnership question.
- **Phase 2:** After **genuine seasoning**, parties form the promoted Hanover JV by tax-free **§721** contribution (Magneson/Bolker). Hanover gets 5% + capital-gain carry.
- **Structure B (fallback):** Kao 100% forever + promote-mirroring **ordinary-income incentive fee** (gross up). Bulletproof exchange, but Hanover loses capital-gain character.

## Files & locations
- **Source of truth:** `North_Forsyth_1031_StructureA.md` (this folder) — drives the tabbed GitHub Pages site (mermaid + tables).
- **Companion docs (this folder):** `North Forsyth 1031 - Tax Memo (Legal Analysis).docx`, `North Forsyth 1031 - Recommended Structure.docx`, `North Forsyth 1031 - Structure A Diagrams.html`.
- **Live site repo (separate):** `C:\Users\Ethan\Downloads\North-Forsyth-1031-Diagrams` (git, GitHub Pages from `master`, https://ethancow.github.io/North-Forsyth-1031-Diagrams/). NOTE: that repo still has the OLD development-TIC content that a tax review concluded FAILS §1031; StructureA.md is the intended replacement.
- **Older inputs:** structuring memo `C:\Users\Ethan\Downloads\North_Forsyth_1031_Structuring_Memo.md`; term sheet PDF in `%TEMP%` ("…Equity Term Sheet - Kao Management Trust (06.12.2026)…").

## Locked decisions (from grilling + post-Codex merge gate)
1. **Structure A primary, B explicit fallback.**
2. **Minimal legal bridge** Phase 1→2: NO pre-signed contribution; non-binding LOI + attached (non-binding) JV term sheet only.
3. **Neutrality via commercial leverage + adopted Codex fix:** standalone market Phase-1 contracts (DMA 4%, GMP/GC 4.5%, reimbursement, lien rights, default remedies); Hanover 5% = **true secured LOAN bearing interest (NOT "preferred return")**, converts via §721 in Phase 2; **Kao guaranty-indemnity backed by collateral/LC**; **fixed/cost-based termination fee if Kao walks** (not promote-mirroring); LOI expressly non-binding, no fixed-price equity option.
4. **Opinion target = MLTN base case, path to "should"** — do NOT promise "should" in writing.
5. **Land seller = unrelated third party** (cleanest); document non-affiliation, flag must-verify.

## Codex hostile review — verdict + punch-list (gpt-5.5, xhigh; exit 0; raw at `C:\Users\Ethan\.cursor\projects\c-Users-Ethan-Downloads-North-Forsyth-1031-Diagrams\terminals\969930.txt`)
Verdict: A is NOT "clean"; realistically **MLTN** unless seasoning is long; memo overstates Magneson/Bolker, understates step-transaction risk, treats Hanover's leverage as neutral (it isn't). Codex argued B should be primary — **overridden** (keep A primary per user's informed choice, but harden + present B honestly).

Kept punch-list (all to be written into docs):
1. Delete "immediately after"/"clean" — reframe as conditional/MLTN.
2. Add Magneson/Bolker **limitations** section (pre-1984 9th Cir.; **Bolker isn't a §721 case**).
3. **Season from the EAT→Kao DEED date, not Day 0.** Floor = later of 12 mo after deed AND substantial completion; ~24 mo + lease-up/refi for any "should."
4. **Build-to-suit math:** need ~**$13.5M of COMPLETED improvements in place by Day 180** (land $6.5M); stored materials/prepaids/post-transfer work don't count. Add a Day-180 valuation/boot schedule. Extend the 2026 return. Backup DST identified ≤45 days, closable ≤180.
5. **Add the missing tax work:** §707 disguised-sale (2-yr presumption; how Hanover's loan→equity conversion is treated); **§752** (Hanover guaranties shift recourse debt → Kao deemed distribution → possible gain); §704(c) method (recommend remedial); basis/depreciation (carryover, unrecaptured §1250, §263A, later-sale waterfall).
6. Resolve land seller (unrelated — keep arm's length; if ever Hanover affiliate → §1031(f)/Rev. Proc. 2004-51).
7. Tighten Phase-1 mechanics: QI/EAT disqualified-person/independence, QEAA agreement + timeline, lender consent (EAT + later transfer), due-on-sale, title endorsements, guaranty routing, EAT bankruptcy-remoteness, no agency language.
8. Georgia local counsel: transfer tax, intangibles/security-deed tax, deed chain, recording, entity authority.
9. **Equity-exhaustion:** define what funds remaining work after Kao's $20M is deployed pre-Day-180 — loan + Hanover loan as DEBT+guaranty, never equity.
10. Citations: cite current **§1031 + Reg. §1.1031(a)-3** (partnership-interest exclusion); keep "(a)(2)(D) repealed by TCJA" note; add Reg. §1.707-3 and §1.752-2. (Doc already correctly demotes Rev. Proc. 2002-22 to non-safe-harbor.)

Discarded as noise: Codex's flags that the doc cites dead (a)(2)(D) / treats 2002-22 as safe harbor — the doc already corrects both.

## Edit map for the rewrite (StructureA.md, by tab)
- Thesis/overview: strip "immediately after"+"clean"; reframe MLTN/conditional.
- Structure tab: add honest step-transaction + Magneson/Bolker-limitations; add Reg. §1.1031(a)-3.
- New "Seasoning" detail: deed-date clock, 12-mo floor + milestone, path to "should."
- New "Neutrality & Hanover protection" section: the 5-part fix.
- Money-flow: fix loan/interest terminology; add equity-exhaustion para; add Day-180 valuation/boot schedule.
- New "Tax mechanics" appendix/tab: §707, §752, §704(c), basis/depreciation.
- Entities: land seller = unrelated; Hanover 5% = secured loan (interest), not preferred return.
- References: add Reg. §1.1031(a)-3, §1.707-3, §1.752-2.
- Open items: Georgia tax, land non-affiliation, §752/§707 models, QI/EAT independence.
Then align the two `.docx` memos + diagrams HTML to match. Recommended order: StructureA.md first.

## Environment notes (important for the shell)
- **Shell sandbox is unsupported on this machine** (`workspace_readwrite` fails silently). Run shell commands with the sandbox disabled (full permissions) or they return no output.
- **Codex CLI** works: `Get-Content -Raw prompt.md | codex exec -s read-only --skip-git-repo-check -C "<dir>" -` (needs `--skip-git-repo-check` for non-git folders). Authenticated to user's ChatGPT (gpt-5.5).
- **GitHub:** `gh` authenticated as EthanCow (repo scope); the Downloads repo is on `master`, pushes work; pushing to master triggers an approval card (user has approved it before).
- The NFCC Dropbox folder is **not** a git repo, so `move_agent_to_root` fails on it.

## Immediate next actions (pending user "go")
1. Rewrite `North_Forsyth_1031_StructureA.md` per the edit map.
2. Align `Tax Memo (Legal Analysis).docx`, `Recommended Structure.docx`, `Structure A Diagrams.html`.
3. Optional: 2nd Codex pass on the rewritten StructureA.md to confirm punch-list closed.
4. (Separately) decide whether/when to rebuild the GitHub Pages site from the new StructureA.md.
