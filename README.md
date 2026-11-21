# Geojit Wealth Story — Experience Lab v0.9

An interactive, self-contained experience prototype for the **Geojit Adaptive Relationship Experience** concept.

## Explore

Open `index.html` in a modern browser. No build step or dependencies required.

### Customer experience
- **My Wealth Story:** Editorial, scenario-sensitive narrative with on-demand demo refresh, progress and goal perspectives.
- **Wealth Map:** Responsive five-area compass (desktop) and tappable mobile list, with known, explore and unassessed states, an Understand → Shape → Explore pathway, contextual next step and demo relevance feedback.
- **30-day journey:** Five chapters showing evolving customer experience, independent essential notices and optional communication decisions.
- **Preferences:** Demonstration of frequency and channel controls. No actual consent is recorded.

### Internal Marketing Studio
- **Decision centre:** Customer-state priority, communication eligibility and traceable rationale.
- **Communication lab:** Essential versus optional communication handling, consolidation and suppression.
- **Opportunity desk:** Needs-led discovery with service-first safeguards.

## New in v0.9 — Customer Relationship Intelligence Layer
- New **Marketing Studio → Customer intelligence** panel with a fictional signal registry.
- Six signal categories: product relationship, transaction status, digital behaviour, declared goals, service context and optional-content permission.
- Source, permitted purpose, freshness, data quality and eligibility status displayed for each signal.
- Interactive failure tests for stale evidence, withheld permissions and poor-quality data.
- Explainable decision trail and a fallback to non-personal financial education when the selected context cannot be used.
- Portfolio values and relationship milestones are withheld if portfolio evidence fails its governance gate.
- CSV download of fictional signal metadata and a conceptual data-lake integration blueprint.
- No real customer records, analytics, data lake, consent service or message delivery are connected.

### Test v0.9
1. Open **Marketing Studio → Customer intelligence**.
2. Change customer profiles or events; inspect the eligibility and decision explanation.
3. Make portfolio data stale, then return to **My Wealth Story** to check that values and portfolio hints are withheld.
4. Test permission and quality failures, restore the data and download the sample report.
5. Check service-first prioritisation for a failed SIP or complaint.

**Production caution:** Signal contracts must define identity, lineage, purpose, permission, freshness, data quality, retention and audit requirements. This frontend simulation is not a consent engine, an investment recommendation engine, or a secure account environment.

## Earlier improvements (v0.8)
- Mobile-first Wealth Map area list with accessible tap targets and selection state.
- Three-step wealth journey: Understand, Shape, Explore.
- Clear separation of known holdings, unexplored areas and unassessed financial needs.
- Contextual next-step copy, customer relevance feedback and transparent caveats.
- No manufactured wealth score or assumption that product ownership equals financial wellbeing.

## Demo instructions
1. Switch among Regular SIP Investor, Active Equity Trader, MF + Protection, and New Investment Explorer.
2. Change context to SIP payment failed or open service complaint and observe service-first prioritisation.
3. Explore the Wealth Map nodes and customer-declared goal.
4. Use the mode toggle to inspect the decisions behind the customer experience.
5. Change optional communication frequency to None and inspect the Communication Lab.

## Deploy on GitHub Pages
Repository Settings → Pages → Build and deployment → Deploy from a branch → `main` / `/(root)` → Save.

The expected public Pages URL, **once enabled and deployed**, is:
https://sajankjose.github.io/wealthstory/

## Important limitations
**Design concept only.** Customer profiles, values and operational metrics are fictional. The app has no authentication, live customer data, real market prices, data-lake integration, AI model, outbound communication integration or financial advice engine. No actual communications are sent.

All classifications of essential and optional communication are illustrative and require compliance validation before production. Never put real customer portfolio information on an unprotected public page.

## Future roadmap
- Usability test on mobile and desktop, including accessibility review.
- Deepen Wealth Map with goal milestones, customer-edited assumptions, and an explicit data-quality layer.
- Add customer-to-RM handoff and scenario-based commercial discovery.
- Validate secure page access, messaging permissions, editorial governance, data contracts and audit trails.
- Connect verified data and a governed narration service only after those controls are established.
