# Deal Command Center — v1 (Operating Template)

> **STATUS: EMPTY TEMPLATE.** No live deals are populated in this file.
> Live rows must be added **only from deal state Kris explicitly confirms in conversation** — never auto-filled from memory, the README, or deal folders. See *Confidence Rules* below.

---

## Purpose

A single cross-deal command surface so the SE partner can be **proactive, not reactive**: at a glance, what stage each deal is in, how healthy it is (MEDDPICC), what the next action is, who owns it, and which deal needs Kris *this week*. This file is the input surface that the Executive Conversation Kit, ROI framework, and MEDDPICC One-Pager read from on a per-deal basis.

This is an SE working tool, not a CRM. It captures *strategy and risk*, not commercial data. Pricing, ACV, plan tier, and contract status do **not** belong here (AE-owned).

## Usage Rules

- One row per active deal in the pipeline table; one expanded card per deal that needs depth.
- Update at the **end of any session** where a deal was worked.
- Strategy and risk only. No ACV, no plan tier, no discount, no contract terms.
- Every populated field must trace to something Kris confirmed — not inferred.

## Update Rules

- When Kris confirms new deal state, update the row + card and refresh the `Last touch` date.
- When a deal closes (won or lost), move it to *Recently Closed / Win-Loss* and remove it from the active table.
- Keep the `Needs attention this week` section current — it is the first thing read each session.

## Staleness Rules

- Each row carries a `Last touch` date. **Any row older than 7 days is flagged `STALE` and must not be used for advice until Kris re-confirms it.**
- If the whole file is older than 7 days at session start, the SE partner must say so and ask for a deal-state refresh before recommending priorities.
- Stale ≠ deleted. Flag it, don't guess it.

## Confidence Rules

- `Confirmed` — stated by Kris in conversation. Safe to act on.
- `Assumed` — SE partner's working assumption, explicitly labelled; must be validated before it drives a customer-facing decision.
- `Unknown` — gap. Surface it only if it changes the recommendation.
- **Never promote `Assumed` or memory-sourced context to `Confirmed` without Kris saying so.**

## MEDDPICC Score Definition

Health is summarised as a count of components that are **solid (Green)** out of 8, plus the weakest link. Components: **M**etrics, **E**conomic buyer, **D**ecision criteria, **D**ecision process, **P**aper process, **I**dentified pain, **C**hampion, **C**ompetition. Used as a *lens*, not a gate — see the MEDDPICC One-Pager for scoring detail. Express as e.g. `5/8 — weak: Champion`.

## Next-Best-Action Rules

- Every active deal must have exactly one `Next action` — the single highest-leverage move, with an owner and a date.
- If a deal has no clear next action, that itself is the risk — flag it.
- The `Needs attention this week` list is ordered by *deal risk × deal value-to-pipeline*, not by how recently it was touched.

---

## Active Pipeline (template — do not populate without confirmed state)

| Deal | Vertical | Stage | MEDDPICC | Competitor | Next action (owner, date) | Last touch | Confidence |
|------|----------|-------|----------|------------|---------------------------|-----------|------------|
| _‹add only from confirmed state›_ | | | _/8 — weak: ‹x›_ | | | _YYYY-MM-DD_ | Confirmed / Assumed |
| Fontainebleau Las Vegas | Hospitality | Post-first demo; stakeholder demo scheduled June 9 | 2/8 — weak: Decision process / budget authority | Medallia (via ComOps) | Prep June 9 stakeholder demo for Aislinn (Kris/AE, by Jun 9) | 2026-06-01 | Facts Confirmed; budget owner Unknown |
| Marvin | Building materials (windows & doors) | Demo done; stakeholder + technical deep-dive Jun 8 (2pm CT) | 3/8 — weak: Competition (internal SurveyMonkey path) | GetFeedback (incumbent, sunsetting Dec 18–19); SurveyMonkey Enterprise (internal alt) | Prep/run Jun 8 session; confirm NDA executed; surface budget sign-off + lock timeline (Kris/Trent, Jun 8) | 2026-05-29 | Facts Confirmed; budget sign-off + NDA-execution Unknown |
| McAfee | Cybersecurity / consumer SaaS | Active RFI/RFP (multi-vendor); 2 demos done; UXR scope dropped; follow-up materials owed | 1/8 — weak: Economic buyer / Competition | Multi-vendor RFP (Qualtrics / Alida referenced) | Submit RFP follow-up materials + re-establish next session; nail GDPR/SDK security proof (Deshik/Kris, this week) | 2026-05-20 | Facts Confirmed; EB / timeline / competitors Unknown |

---

## Per-Deal Card (template)

> Duplicate this block per deal that needs depth. Leave blank until Kris confirms.

### ‹Deal Name›
- **Vertical / region:**
- **Stage:**
- **Buying committee (role → name → champion?/blocker?):**
- **Identified pain (in their words):**
- **Metrics they care about:**
- **Incumbent / competitor:**
- **Key risk:**
- **MEDDPICC:** _/8 — weak: ‹component›_
- **Next best action (owner, date):**
- **Last touch:** _YYYY-MM-DD_
- **Confidence:** Confirmed / Assumed / Unknown per line

---

### Fontainebleau Las Vegas
- **Vertical / region:** Hospitality / casino resort, Las Vegas
- **Stage:** Post-first demo (passed May 29); stakeholder demo scheduled for June 9
- **Upcoming meeting:** June 9 stakeholder demo with Aislinn, Director of Guest Experience
- **Buying committee:**
    - Aislinn — Director of Guest Experience — **DECISION MAKER (Confirmed)**
    - Beck Sundquist — Exec Director of Product — **CHAMPION (Amber)**: active, positive, advanced the stakeholder demo, but influence with the decision maker not yet proven
    - Beck's data team — API / scheduled data feed review
    - Separate cybersecurity team — security/compliance review (not yet engaged)
    - Budget owner / economic buyer — **UNKNOWN**
- **Identified pain (in their words):** Medallia renewal pricing shock via ComOps; wants the right long-term solution; preserve historical reporting continuity; match current functionality; integrate with existing stack; reporting; follow-up on negative scores
- **Metrics they care about:** 300K sends/yr; ~45K responses/yr (~15% RR); ~150K historical responses to migrate
- **Incumbent / competitor:** Medallia via ComOps reseller
- **Key risk:** historical migration continuity (landmine); budget authority + procurement unknown; security/compliance review not yet started (Step 2 after June 9); June 9 is the decision-maker's first exposure
- **MEDDPICC:** 2/8 — weak: Decision process / budget authority
  - M Amber · E Amber (decision maker confirmed, budget authority unknown) · D-criteria Amber · D-process Unknown · Paper Amber · Identified pain Green · Champion Amber · Competition Green
- **Next best action (owner, date):** Prepare the June 9 stakeholder demo for Aislinn (Kris/AE, by Jun 9). Focus: Medallia-via-ComOps displacement; preserving historical reporting continuity; 150K historical response migration; 300K sends / 45K responses scale; API + scheduled data feed readiness; security/compliance readiness as Step 2 after the demo; dashboard parity + executive reporting
- **Last touch:** 2026-06-01 (customer-initiated reschedule of the stakeholder demo to June 9 — Beck OOO this week)
- **Confidence:** facts + Aislinn-as-decision-maker + June 9 schedule = Confirmed; budget owner / procurement / security = Unknown

```deal-json
{
  "schema_version": "1.0",
  "deal_id": "fontainebleau-las-vegas",
  "deal_name": "Fontainebleau Las Vegas",
  "industry": "Hospitality",
  "vertical": "Hospitality / casino resort, Las Vegas",
  "stage": "Post-first demo; stakeholder demo scheduled for June 9",
  "last_touch": "2026-06-01",
  "next_meeting": { "date": "2026-06-09", "display": "Jun 9", "label": "Stakeholder demo", "sub": "with Aislinn, Director of Guest Experience", "status": "scheduled" },
  "needs_attention": true,
  "attention": {
    "priority": 1,
    "why_now": "June 9 stakeholder demo with Aislinn, the confirmed decision maker — her first exposure and the highest-stakes moment in the deal.",
    "desired_outcome": "Convert Aislinn from evaluator to sponsor / decision driver.",
    "prep_focus": ["Medallia-via-ComOps displacement", "historical reporting continuity", "150K historical response migration", "dashboard parity + executive reporting"],
    "open_question": "Who owns the spend decision (economic buyer), and what is the decision process?",
    "owner": "Kris / AE",
    "due": "2026-06-09"
  },
  "competitor": { "display": "Medallia (via ComOps reseller)", "tags": ["Medallia", "ComOps"], "status": "incumbent" },
  "decision_maker": { "name": "Aislinn", "title": "Director of Guest Experience", "status": "Confirmed", "status_color": "green", "text": "Aislinn, Director of Guest Experience — Confirmed" },
  "economic_buyer": { "name": "Unknown", "title": "Unknown", "status": "Unknown", "display": "Unknown" },
  "buying_committee": [
    { "name": "Aislinn", "role": "Director of Guest Experience · Decision maker", "status": "green", "status_text": "Confirmed" },
    { "name": "Beck Sundquist", "role": "Exec Director of Product · Champion / coach", "status": "amber", "status_text": "Active; influence with DM unproven" },
    { "name": "Beck's data team", "role": "API / scheduled data feed review", "status": "grey", "status_text": "In evaluation" },
    { "name": "Cybersecurity team", "role": "Security / compliance review", "status": "grey", "status_text": "Step 2 after June 9" },
    { "name": "Economic buyer", "role": "Spend authority", "status": "grey", "status_text": "Unknown" }
  ],
  "metrics": ["300K sends/yr", "~45K responses/yr (~15% RR)", "~150K historical responses to migrate"],
  "identified_pain": ["Medallia delivered via the ComOps reseller and the renewal prompted re-evaluation; wants the right long-term, self-service solution;", "preserve historical reporting continuity; match current functionality; integrate with existing stack;", "reporting; follow-up on negative scores."],
  "risks": {
    "technical_security": ["Security/compliance review not yet started — Step 2 after the June 9 demo."],
    "migration_data": ["~150K historical responses to migrate — continuity is the landmine."],
    "decision_process": ["Decision process undocumented; economic buyer / spend authority unknown.", "June 9 is the decision-maker's first exposure."],
    "competition": ["Medallia incumbent, supplied via ComOps reseller — like-for-like displacement."]
  },
  "meddpicc": {
    "summary": "2/8 — weak: Decision process / economic buyer",
    "green_count": 2,
    "weakest": "Decision process / economic buyer",
    "components": {
      "metrics": { "status": "Amber", "evidence": "Volume known (300K/45K/150K); no business-outcome target." },
      "economic_buyer": { "status": "Amber", "evidence": "Decision maker (Aislinn) confirmed; spend authority unknown." },
      "decision_criteria": { "status": "Amber", "evidence": "Continuity, functionality parity, integration known; not formally weighted." },
      "decision_process": { "status": "Unknown", "evidence": "No documented path to signature." },
      "paper_process": { "status": "Amber", "evidence": "Security/compliance review required (Step 2); rest undefined." },
      "identified_pain": { "status": "Green", "evidence": "Senior and clear: ComOps dependency + continuity + reporting." },
      "champion": { "status": "Amber", "evidence": "Beck active; influence with the decision maker unproven." },
      "competition": { "status": "Green", "evidence": "Medallia via ComOps clearly identified; displacement underway." }
    }
  },
  "next_best_action": {
    "action": "Prepare the June 9 stakeholder demo for Aislinn. Focus: Medallia-via-ComOps displacement; historical reporting continuity; 150K historical response migration; 300K/45K scale; API + scheduled data feed readiness; dashboard parity + executive reporting (security/compliance is Step 2 after the demo).",
    "owner": "Kris / AE",
    "due": "2026-06-09"
  },
  "confidence": "Facts + Aislinn-as-decision-maker + June 9 schedule = Confirmed; economic buyer / procurement / security = Unknown.",
  "commercial_context": {
    "internal_only": true,
    "price_sensitivity": "Elevated — the ComOps reseller renewal prompted re-evaluation (prospect signal, not a customer-facing claim).",
    "budget_signal": "Unknown",
    "renewal_or_contract_timing": "Medallia-via-ComOps renewal was the trigger event; exact renewal dates Unknown.",
    "procurement_status": "Unknown; security/compliance review is Step 2 after the June 9 demo.",
    "commercial_risk": "Displacing a tightly-integrated Medallia + ComOps platform-plus-services duo; reseller dependency.",
    "demo_implication": "Lead on self-service control, ownership, reporting continuity and migration confidence; avoid unsupported cost-advantage claims unless the AE confirms.",
    "ae_alignment_needed": true
  },
  "flags": { "security_pending": true, "migration_risk": true },
  "source_notes": [],
  "excluded_commercial_fields_notice": "Commercial fields intentionally excluded: pricing, ACV, budget targets, discounts, plan tiers, contract terms, commercial promises.",
  "updated_at": "2026-06-05"
}
```

---

### Marvin
- **Vertical / region:** Building materials — windows & doors (brands: Marvin, Infinity by Marvin, Infinity Replacements, True Style); ~90% dealer/distribution, ~10% DTC
- **Stage:** Demo completed (May 26); stakeholder + technical deep-dive scheduled Jun 8, 2pm CT
- **Upcoming meeting:** Mon Jun 8, 2:00 PM CT (= Jun 9, 12:30 AM IST) — stakeholder + technical deep-dive. Host Trent Ward (AE); SE Kris; Toby Hoskins + Marvin stakeholders/technical team (PM, tech lead)
- **Buying committee:**
    - Toby Hoskins — Manager, Digital Technology — **CHAMPION w/ decision authority** (strength 4; driving NDA + scheduling; can move without extensive internal consultation)
    - Marvin stakeholders + technical team (PM, tech lead) — joining Jun 8 for technical validation
    - Trent Ward — Director NA — AE (internal); Varshini Saravanan — NDA review (internal)
    - Budget owner / formal sign-off — **UNKNOWN** (stakeholders Jun 8 = chance to confirm)
- **Identified pain (in their words):** GetFeedback sunsetting Dec 18–19, 2026 ("our drop-dead date"); needs low-disruption migration ("it's working just fine, but with them going away we have to find a solution"); maintain "set it and forget it" surveys; keep Salesforce-triggered workflow + Marketing Cloud distribution via API; replicate GetFeedback branching logic on Salesforce data
- **Metrics they care about:** under 10K responses/yr; 2 surveys — (1) post in-home consultation feedback (higher priority, low volume), (2) internal design-consultant feedback (lower priority); scope = dealer/distribution only, not DTC; revenue ~90% dealer / ~10% DTC
- **Incumbent / competitor:** GetFeedback (incumbent, sunsetting — acquisition-driven); SurveyMonkey Enterprise (internal alternative — already used by Marvin brand, separate renewal in Sept, kept due to change fatigue); Qualtrics (ruled out — complexity/cost). *[Trent's email/agenda say "Senseti" — likely a transcription artifact for GetFeedback; confirm]*
- **Key risk:** internal SurveyMonkey consolidation (path of least resistance); hard Dec 18–19 cutover deadline; NDA not yet executed (gates deep Salesforce API config); SF + Marketing Cloud integration to be validated Jun 8; budget sign-off owner unconfirmed
- **MEDDPICC:** 3/8 — weak: Competition (internal SurveyMonkey path)
  - M Amber · E Amber (Toby has decision authority; formal budget sign-off unconfirmed) · D-criteria Green · D-process Amber · Paper Amber (NDA in review) · Identified pain Green · Champion Green · Competition Amber
- **Next best action (owner, date):** Prep/run the Jun 8 session (Kris/Trent). Prove Salesforce API trigger + Marketing Cloud distribution + replicate GetFeedback branching; out-frame "just consolidate onto SurveyMonkey"; confirm NDA executed before deep API config; surface budget sign-off + lock decision/timeline to beat the Dec 18–19 sunset. Play land-the-2-surveys-now, consolidate-later
- **Last touch:** 2026-05-29 (Toby email — NDA sent, stakeholder times proposed)
- **Confidence:** facts Confirmed (call transcript + email + invite); budget sign-off owner + NDA-execution = Unknown

```deal-json
{
  "schema_version": "1.0",
  "deal_id": "marvin",
  "deal_name": "Marvin",
  "industry": "Building materials",
  "vertical": "Building materials — windows & doors · ~90% dealer/distribution, ~10% DTC",
  "stage": "Demo done; stakeholder + technical deep-dive Jun 8 (2pm CT)",
  "last_touch": "2026-05-29",
  "next_meeting": { "date": "2026-06-08", "display": "Jun 8", "label": "Stakeholder + technical deep-dive", "sub": "2:00 PM CT (= Jun 9, 12:30 AM IST) · Host Trent (AE), SE Kris, Toby Hoskins + Marvin team", "status": "scheduled" },
  "needs_attention": true,
  "attention": {
    "priority": 2,
    "why_now": "Confirmed June 8 (2pm CT) stakeholder + technical deep-dive against a hard Dec 18-19 GetFeedback sunset.",
    "desired_outcome": "Win vs consolidating onto the SurveyMonkey Enterprise they already own; prove integration + low-disruption migration; land the two dealer surveys.",
    "prep_focus": ["Salesforce API trigger", "Marketing Cloud distribution", "replicate GetFeedback branching", "out-frame consolidate-onto-SurveyMonkey"],
    "open_question": "Is the mutual NDA executed, and who is the economic buyer / spend sign-off owner?",
    "owner": "Kris / Trent",
    "due": "2026-06-08"
  },
  "competitor": { "display": "GetFeedback (sunsetting Dec 18-19); SurveyMonkey Enterprise (internal alt)", "tags": ["GetFeedback", "SurveyMonkey Enterprise", "Qualtrics"], "status": "incumbent-leaving" },
  "decision_maker": { "name": "Toby Hoskins", "title": "Manager, Digital Technology", "status": "Confirmed", "status_color": "green", "text": "Toby Hoskins — Champion w/ decision authority" },
  "economic_buyer": { "name": "Unknown", "title": "Unknown", "status": "Unknown", "display": "Unknown" },
  "buying_committee": [
    { "name": "Toby Hoskins", "role": "Manager, Digital Technology · Champion w/ decision authority", "status": "green", "status_text": "Driving NDA + scheduling" },
    { "name": "Marvin technical team", "role": "PM + tech lead · technical validation", "status": "grey", "status_text": "Joining Jun 8" },
    { "name": "Trent Ward", "role": "Director NA · Account Executive (internal)", "status": "grey", "status_text": "Host / AE" },
    { "name": "Varshini Saravanan", "role": "NDA review (internal)", "status": "grey", "status_text": "NDA in review" },
    { "name": "Economic buyer", "role": "Spend sign-off", "status": "grey", "status_text": "Unknown" }
  ],
  "metrics": ["under 10K responses/yr", "2 surveys (post in-home consult [higher priority]; design-consultant follow-up [lower])", "scope = dealer/distribution only, not DTC", "revenue ~90% dealer / ~10% DTC"],
  "identified_pain": ["GetFeedback sunsetting Dec 18-19, 2026 (the drop-dead date);", "needs low-disruption migration; maintain set-and-forget surveys;", "keep Salesforce-triggered workflow + Marketing Cloud distribution via API;", "replicate GetFeedback branching logic on Salesforce data."],
  "risks": {
    "technical_security": ["Salesforce + Marketing Cloud integration to validate Jun 8.", "NDA not yet executed — gates the deep Salesforce API config."],
    "migration_data": ["GetFeedback to SurveySparrow low-disruption migration required.", "Parallel-run de-risk before the Dec 18-19 cutover deadline."],
    "decision_process": ["Toby has decision authority; spend sign-off owner unconfirmed.", "Wants a decision within ~1 month; go-live targeting September."],
    "competition": ["GetFeedback sunsetting (acquisition-driven).", "SurveyMonkey Enterprise = internal alternative (real threat; already used by Marvin brand, renews September).", "Qualtrics ruled out (complexity)."]
  },
  "meddpicc": {
    "summary": "3/8 — weak: Competition (internal SurveyMonkey path)",
    "green_count": 3,
    "weakest": "Competition (internal SurveyMonkey path)",
    "components": {
      "metrics": { "status": "Amber", "evidence": "Volume known; no outcome target." },
      "economic_buyer": { "status": "Amber", "evidence": "Toby has decision authority; spend sign-off unconfirmed." },
      "decision_criteria": { "status": "Green", "evidence": "Clear and SurveySparrow-confirmed fit." },
      "decision_process": { "status": "Amber", "evidence": "Decision within ~1 month; go-live targeting September." },
      "paper_process": { "status": "Amber", "evidence": "Mutual NDA in review (Varshini)." },
      "identified_pain": { "status": "Green", "evidence": "Hard sunset compelling event." },
      "champion": { "status": "Green", "evidence": "Toby driving NDA + scheduling + has decision authority." },
      "competition": { "status": "Amber", "evidence": "SurveyMonkey Enterprise internal alternative already owned." }
    }
  },
  "next_best_action": {
    "action": "Prep/run the Jun 8 session. Prove Salesforce API trigger + Marketing Cloud distribution + replicate GetFeedback branching; out-frame consolidating onto SurveyMonkey; confirm NDA executed before deep API config; surface the economic buyer + lock decision/timeline to beat the Dec 18-19 sunset.",
    "owner": "Kris / Trent",
    "due": "2026-06-08"
  },
  "confidence": "Facts Confirmed (call transcript + email + invite); economic buyer / NDA-execution = Unknown.",
  "commercial_context": {
    "internal_only": true,
    "price_sensitivity": "Unknown",
    "budget_signal": "Prospect-stated budget preference from raw notes; internal-only context, not AE-approved pricing or a SurveySparrow commitment. Toby Hoskins: \"Ideally, we'd like to keep it under $10,000 a year.\" Internal SE context only. Not customer-facing positioning. Not a pricing commitment. Requires AE alignment.",
    "renewal_or_contract_timing": "GetFeedback incumbent sunsetting Dec 18-19, 2026 — a hard cutover deadline (prospect signal).",
    "procurement_status": "Mutual NDA in review (Varshini); decision sought within ~1 month; go-live targeting September.",
    "commercial_risk": "Consolidation onto the SurveyMonkey Enterprise they already own (renews September) is the path-of-least-resistance threat.",
    "demo_implication": "Lead on low-disruption migration, Salesforce + Marketing Cloud continuity, technical validation, and out-framing the SurveyMonkey consolidation; avoid unsupported cost-advantage claims unless the AE confirms.",
    "ae_alignment_needed": true
  },
  "flags": { "security_pending": false, "migration_risk": true },
  "source_notes": [],
  "excluded_commercial_fields_notice": "Commercial fields intentionally excluded: pricing, ACV, budget targets, discounts, plan tiers, contract terms, commercial promises.",
  "updated_at": "2026-06-05"
}
```

---

### McAfee
- **Vertical / region:** Cybersecurity / consumer SaaS (US)
- **Stage:** Active RFI/RFP, multi-vendor. Two scope demos delivered (VOC/CX + Market Research). UXR scope eliminated mid-call. Now: VOC/CX + Consumer/Market Research (quant). Follow-up materials owed via procurement portal.
- **Upcoming meeting:** None scheduled (TBD — follow-up session to coordinate with Marina)
- **Buying committee:**
    - Marina Mikhaleva — Global Strategic Sourcing Manager — **process champion (Amber)**: manages procurement flow; not the economic buyer
    - Carolina Thomsen — VOC — **primary CX technical evaluator (Amber)**: left Call 1 early (tornado warning); concerns unaddressed
    - Kara Kalivoda — Global Director, VOC Insights & Analytics — senior stakeholder (Carolina reports to her)
    - Tiffanie Williams — Director, Market Intelligence — MR influencer / end-user (engaged on MaxDiff)
    - Engineering / security — Sridhar Matta, Shuborno Biswas, Sachin Jadhav (SDK / Java / security)
    - Compliance / infosec — heavily involved gatekeepers
    - Economic buyer / budget owner — **UNKNOWN**
- **Identified pain (in their words):** [VOC/CX] GDPR / security & privacy + data anonymization pipeline; no-code complex campaign triggering; advanced AI text analytics; native app integration beyond JavaScript (strict Java restrictions); Adobe custom-event triggering gap. [Market Research] premium-tier feature prioritization via MaxDiff; SPSS (.sav) export to internal stats tools; multilingual; panel flexibility (vendor + bring-your-own)
- **Metrics they care about:** large engaged audience (31 invited Call 1 / 12 Call 2); no customer volumes, budget, or decision date surfaced (Unknown)
- **Incumbent / competitor:** multi-vendor RFI/RFP (other vendors largely unnamed); Qualtrics + Alida referenced as benchmarks
- **Key risk:** stale (16d) vs aggressive "coming weeks" procurement clock with no next session booked; contested multi-vendor RFP; UXR scope lost (~50% of MR); unresolved GDPR / SDK / security; infosec/compliance gatekeepers; demo tech failures in Call 2; economic buyer unidentified
- **MEDDPICC:** 1/8 — weak: Economic buyer / Competition
  - M Unknown · E Red · D-criteria Amber · D-process Amber · Paper Amber · Identified pain Green · Champion Amber · Competition Red
- **Next best action (owner, date):** Submit RFP follow-up materials via the procurement portal + re-establish a next session with Marina; deliver GDPR/SDK/security proof (VOC) and a fixed, populated MR demo; identify the economic buyer + formal eval criteria. Owner: Deshik/Kris, this week
- **Last touch:** 2026-05-20 (two demo sessions; UXR cancelled mid-call)
- **Confidence:** facts Confirmed (both call notes); EB / timeline / competitor set / portal-submission status = Unknown
- **Verify-with-product:** CogniView three-level taxonomy timeline; multilingual report generation (English-only today); native app integration beyond JavaScript; SPSS export timeline

```deal-json
{
  "schema_version": "1.0",
  "deal_id": "mcafee",
  "deal_name": "McAfee",
  "industry": "Cybersecurity",
  "vertical": "Cybersecurity / consumer SaaS (US)",
  "stage": "Active RFI/RFP (multi-vendor); 2 demos done; UXR scope dropped; follow-up materials owed",
  "last_touch": "2026-05-20",
  "next_meeting": null,
  "needs_attention": true,
  "attention": {
    "priority": 3,
    "why_now": "Large multi-vendor RFP gone quiet — stale 16 days against a coming-weeks procurement clock, with follow-up materials owed and no next session booked.",
    "desired_outcome": "Re-establish position: submit the procurement-portal package, lock a next session with Marina, identify the economic buyer + eval criteria, and fix the demo environment.",
    "prep_focus": ["GDPR/SDK/security proof", "fixed populated MR demo", "identify economic buyer", "formal eval criteria"],
    "open_question": "Who owns the spend decision, what are the formal scoring criteria, and was the portal package submitted?",
    "owner": "Deshik / Kris",
    "due": "this week"
  },
  "competitor": { "display": "Multi-vendor RFI/RFP (competitors largely unnamed); Qualtrics + Alida referenced as benchmarks", "tags": ["Qualtrics", "Alida"], "status": "competitive-rfp" },
  "decision_maker": { "name": "Unknown", "title": "Unknown", "status": "Unknown", "status_color": "grey", "text": "Not identified (multi-stakeholder RFP)" },
  "economic_buyer": { "name": "Unknown", "title": "Unknown", "status": "Unknown", "display": "Unknown" },
  "buying_committee": [
    { "name": "Marina Mikhaleva", "role": "Global Strategic Sourcing Manager · process champion", "status": "amber", "status_text": "Sourcing/procurement, not economic buyer" },
    { "name": "Carolina Thomsen", "role": "VOC · primary CX technical evaluator", "status": "amber", "status_text": "Left Call 1 early; concerns unaddressed" },
    { "name": "Kara Kalivoda", "role": "Global Director, VOC Insights & Analytics", "status": "grey", "status_text": "Senior stakeholder" },
    { "name": "Tiffanie Williams", "role": "Director, Market Intelligence · MR influencer", "status": "grey", "status_text": "Engaged on MaxDiff" },
    { "name": "Engineering / security", "role": "Sridhar Matta, Shuborno Biswas, Sachin Jadhav · SDK / Java / security", "status": "grey", "status_text": "Technical validation" },
    { "name": "Compliance / infosec", "role": "Security & compliance review", "status": "grey", "status_text": "Heavily involved gatekeepers" },
    { "name": "Economic buyer", "role": "Spend authority", "status": "grey", "status_text": "Unknown" }
  ],
  "metrics": ["Large engaged audience (31 invited Call 1 / 12 Call 2)", "no customer volumes or decision date surfaced (Unknown)"],
  "identified_pain": ["[VOC/CX] GDPR / security & privacy + data anonymization pipeline; no-code complex campaign triggering; advanced AI text analytics; native app integration beyond JavaScript (strict Java restrictions); Adobe custom-event triggering gap.", "[Market Research] premium-tier feature prioritization via MaxDiff; SPSS (.sav) export; multilingual; panel flexibility (vendor + bring-your-own)."],
  "risks": {
    "technical_security": ["GDPR / security & privacy + data anonymization pipeline — must prove.", "SDK integration + whitelisting/firewall requirements.", "Native app integration beyond JavaScript (strict Java restrictions on assets/form factors).", "Verify-with-product: CogniView three-level taxonomy timeline; multilingual report generation (English-only today); SPSS export timeline."],
    "migration_data": [],
    "decision_process": ["Economic buyer unidentified in a late-stage RFP.", "Formal eval criteria / scoring unknown; multi-stakeholder (eng, compliance, CX, MR).", "Aggressive coming-weeks procurement clock; no next session booked."],
    "competition": ["Contested multi-vendor RFP (competitors largely unnamed).", "UXR scope lost (~50% of MR) to capability gaps — risk a rival bundles UXR + consumer insights.", "Qualtrics + Alida referenced as benchmarks."]
  },
  "meddpicc": {
    "summary": "1/8 — weak: Economic buyer / Competition",
    "green_count": 1,
    "weakest": "Economic buyer / Competition",
    "components": {
      "metrics": { "status": "Unknown", "evidence": "No customer metrics/volumes/targets surfaced." },
      "economic_buyer": { "status": "Red", "evidence": "Not identified; Marina is sourcing/procurement, not spend owner." },
      "decision_criteria": { "status": "Amber", "evidence": "Themes clear; formal RFP scoring unknown." },
      "decision_process": { "status": "Amber", "evidence": "Formal RFI/RFP, multi-stakeholder, coming-weeks." },
      "paper_process": { "status": "Amber", "evidence": "Procurement portal + mandatory security/infosec review known." },
      "identified_pain": { "status": "Green", "evidence": "Clear, multiple, senior across both tracks." },
      "champion": { "status": "Amber", "evidence": "Marina engaged on process; no champion with decision power." },
      "competition": { "status": "Red", "evidence": "Contested multi-vendor RFP; UXR half already lost." }
    }
  },
  "next_best_action": {
    "action": "Submit RFP follow-up materials via the procurement portal + re-establish a next session with Marina; deliver GDPR/SDK/security proof (VOC) and a fixed, populated MR demo; identify the economic buyer + formal eval criteria.",
    "owner": "Deshik / Kris",
    "due": "this week"
  },
  "confidence": "Facts Confirmed (both call notes); economic buyer / timeline / competitor set / portal-submission status = Unknown.",
  "commercial_context": {
    "internal_only": true,
    "price_sensitivity": "Unknown",
    "budget_signal": "Unknown — no budget was discussed despite the late-stage RFI/RFP.",
    "renewal_or_contract_timing": "Unknown",
    "procurement_status": "Active multi-vendor RFI/RFP via the procurement portal; coming-weeks vendor-response clock; mandatory security/infosec review.",
    "commercial_risk": "Contested multi-vendor RFP; UXR scope already lost (~50% of MR) to capability gaps.",
    "demo_implication": "Re-establish position fast: submit portal materials, identify the economic buyer + eval criteria, prove GDPR/SDK/security. Two-best-in-class positioning is at risk if a rival bundles UXR + consumer insights.",
    "ae_alignment_needed": true
  },
  "flags": { "security_pending": true, "migration_risk": false },
  "source_notes": [],
  "excluded_commercial_fields_notice": "Commercial fields intentionally excluded: pricing, ACV, budget targets, discounts, plan tiers, contract terms, commercial promises.",
  "updated_at": "2026-06-05"
}
```

---

## Needs Attention This Week

> Ordered by deal risk × pipeline impact. Empty until populated from confirmed state.

1. **Fontainebleau Las Vegas — June 9 stakeholder demo with Aislinn (confirmed decision maker).** First decision-maker exposure and the highest-stakes moment in the deal — the demo must convert Aislinn from evaluator to sponsor/decision driver. Prep the displacement + continuity + migration + integration + dashboard-parity story now; use it to surface the budget owner and decision process (security/compliance is Step 2 after the demo).
2. **Marvin — June 8 (2pm CT) stakeholder + technical deep-dive.** Confirmed session against a hard Dec 18–19 GetFeedback sunset. The win isn't vs the incumbent — it's vs consolidating onto the SurveyMonkey Enterprise they already own. Prove Salesforce API trigger + Marketing Cloud distribution + replicate GetFeedback branching; out-frame "just move to SurveyMonkey"; confirm the NDA is executed before deep API config; surface the budget sign-off owner and lock the timeline.
3. **McAfee — RFP re-engagement (stale 16d, "coming weeks" procurement clock).** Large multi-vendor RFP gone quiet with follow-up materials owed and no next session booked. Re-establish position: submit the procurement-portal package, lock a next session with Marina, identify the economic buyer + formal eval criteria, fix the demo environment, and deliver the GDPR/SDK/security proof. Owner: Deshik/Kris.

---

## Recently Closed / Moved to Win-Loss

> When a deal closes, log a one-liner here and feed it to the (future) win-loss log.

| Deal | Outcome (Won/Lost) | Competitor | One-line reason | Date |
|------|--------------------|------------|-----------------|------|
| _‹add on close›_ | | | | |

---

*v1 — operating template. Populate only from Kris-confirmed current deal state.*
