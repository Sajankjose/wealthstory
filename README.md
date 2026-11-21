# Geojit Wealth Story — Experience Lab v1.1

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

## New in v1.1 — Financial Context & Business Value
- **Customer Story → financial perspective:** The same customer can view **My whole picture**, **Investing**, or **Trading**, rather than being classified permanently as one type.
- Four informative, *fictional* numerical summary cards respond to the selected perspective and scenario: portfolio value, contributed capital, SIP regularity, exposure or trading activity where appropriate.
- An interpretation card highlights one relevant observation, with a service-first override.
- The established customer-intelligence evidence gate withholds numbers if supporting portfolio evidence is stale, restricted or unreliable.
- **Marketing Studio → Business case:** An interactive first-year ROI model using optional reach, genuinely avoidable paid messages, cost per message, incremental attributable conversions, incremental retained customers, their net contributions and full first-year project cost.
- Formula: first-year ROI = (communication cash savings + incremental commercial net contribution + non-overlapping retention net contribution − full first-year cost) / full first-year cost.
- The default illustration assumes 4 lakh reachable customers, five avoided paid messages/customer/month, ₹0.20 avoidable cost/message, 1,500 incremental conversions at ₹2,000 net contribution, 400 additional retained customers at ₹2,500 contribution and ₹80 lakh first-year total investment. These are not observations or forecasts.
- A downloadable CSV exports the current business-case inputs and computed results.
- Marketing productivity, customer trust and relationship usefulness are proposed as separate pilot KPIs; salary capacity released is not automatically booked as cash savings.

### Recommended v1.1 review
1. In **Client experience → My Wealth Story**, compare the three financial perspective options, especially for **Active equity trader**.
2. Check that an investor with no recorded trading activity is not incorrectly shown as an active trader.
3. In **Marketing Studio → Customer intelligence**, simulate stale portfolio data; return to the customer view and confirm numbers are withheld.
4. In **Marketing Studio → Business case**, vary reach, delivery costs, conversions, retention and first-year cost. Observe the three value streams and first-year ROI.
5. Export the scenario CSV. Obtain Finance-approved net contribution and campaign baseline values before proposing an actual ROI.
6. Test the existing **End-to-end demo**, service-first handling and communication governance.

**Caution:** The interface and calculations are an exploratory model only. All customer figures and business-case assumptions are fictional. No live positions, costs, P&L, research calls, actual consent, CRM, Data Lake, marketing delivery or AI narrative generation is connected. Production metrics require verified data contracts, valuation timestamps, privacy and suitability gates.

## Earlier improvements (v1.0) — End-to-End Experience Demonstration

The **End-to-end demo** tab is available in both **Client experience** and **Marketing studio**. It connects seven previously separate concepts into one guided, management-ready walkthrough:

1. Customer moment: a meaningful signal rather than a product broadcast.
2. Customer intelligence: source, purpose, quality, freshness and eligibility.
3. Next Best Experience: a governed priority and content decision.
4. Personal edition: a short narrative, context hint and at most one optional article/video.
5. Coordinated channel: one story across alternative email/WhatsApp/push presentations, with optional delivery rules.
6. Journey continuity: conceptual preview, mock app verification, Wealth Story, Wealth Map or RM assistance.
7. Outcomes: customer usefulness, marketing efficiency, governance and measurement hypotheses.

### Walkthrough scenarios
- **SIP investor:** an investment habit evolves into goal exploration.
- **Active trader:** research relevance is considered but a specific call is blocked until an approved current research feed exists.
- **SIP payment failure:** resolution outranks commercial discovery; required service messages remain independently governed.
- **Retirement interest:** an explicitly declared customer goal provides contextual guidance.

Select the optional channel and simulated permission to observe how outbound decisions change. Each step offers links to existing functional prototype screens. Download a **fictional review CSV** from the summary area.

**Important:** All evidence, customer events and outcomes are fictitious. The verification step is a UI simulation, not real authentication. The system sends no communications and has no live AI, research feed, customer data, consent, customer identity or transaction service. Production architecture, security, suitability and legal/compliance validation are still required.

### Suggested review
Run the SIP investor flow end-to-end first, then try a failed SIP and optional permission withheld. Review the customer story and Wealth Map on mobile, and the Decision Centre / Orchestration Lab from the marketing perspective. Capture feedback on utility, clarity, prioritisation and trust before connecting live systems.

## Earlier improvements (v0.9) — Customer Relationship Intelligence Layer
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
