# Indian EV Two-Wheeler Market Entry Strategy

A self-initiated case study evaluating market entry options for a new electric two-wheeler OEM in India. Built over the summer using publicly available data from SIAM, the Vahan Dashboard, company annual reports, and industry publications.

## Context

India sold roughly 18 million two-wheelers in FY24. Of that, about 5.6% were electric. EV penetration crossed one million units for the first time in FY24, driven by FAME-II incentives, falling battery costs, and state-level subsidies. The market is still structurally young: three players (Ola Electric, TVS, Bajaj Chetak) command over 70% of monthly registrations, and supply chain economics for new entrants remain unproven.

The question I set out to answer: if a new OEM with ₹500 crore of initial capital were entering this market today, what entry strategy would maximise the probability of breakeven within four years?

## Approach

I broke the analysis into three stages:

1. Market sizing to validate the opportunity (TAM/SAM/SOM)
2. Competitive landscape using Porter's Five Forces
3. Financial model to stress-test entry economics across three pricing scenarios

## Market Sizing

| Metric | Value | Method |
|---|---|---|
| TAM (FY27 projection) | ₹85,000 Cr | Top-down: total 2W market × projected 18% EV share |
| SAM (urban, ₹80k–₹1.5L band) | ₹38,000 Cr | Filtered for income tier (top 40% urban households) |
| SOM (5-year target, ~3% of SAM) | ₹1,140 Cr | Bottom-up: 5 metros × dealership rollout × avg ticket |

Methodology notes: TAM was scaled using SIAM's FY24 baseline of ₹65,000 Cr at current penetration. SAM was filtered using Vahan registration data showing 78% of EV two-wheeler sales concentrated in urban districts. The SOM number was cross-checked against Ather Energy's reported FY24 revenue of ~₹1,789 Cr at roughly 10% market share.

## Competitive Landscape (Porter's Five Forces)

**Rivalry: High.** Ola Electric, TVS iQube, Bajaj Chetak, Ather Energy collectively hold around 72% share. Price wars in the ₹85k–₹1.2L band have already compressed margins.

**Buyer power: Moderate to High.** Subsidies make buyers very price-sensitive. Switching cost for a first-time EV buyer is essentially zero.

**Supplier power: High.** Battery cells (mostly imported from China and Korea) account for around 40% of BOM. Domestic cell production from Reliance, Ola, and Exide is still 2 to 3 years away from scale.

**Threat of substitutes: Moderate.** ICE two-wheelers still sell ~17M units a year. In metros, public transport and shared mobility cap upside.

**Threat of new entry: Decreasing.** The PLI scheme rewards incumbents with scale. New entrants without ₹500Cr+ in capital and locked-in supplier contracts will struggle.

The structural read: a pure OEM play is hard to defend. A service-and-asset model (battery swap, fleet leasing) faces less direct rivalry.

## Financial Model

I built a unit-economics model in Excel across three pricing scenarios.

Inputs:
- BOM cost per unit: ₹62,000 (battery 40%, motor + controller 18%, chassis 22%, other 20%)
- Dealer margin: 8%
- Marketing + overhead: ₹6,500 per unit at scale
- FAME-II subsidy: assumed phased out by FY27

| Scenario | Retail price | Unit margin | Break-even units/yr | Break-even year |
|---|---|---|---|---|
| Premium (Ather-positioned) | ₹1,35,000 | ₹19,500 | 38,000 | Year 4 |
| Mass-market (Ola-positioned) | ₹1,05,000 | ₹8,200 | 90,000 | Year 5+ |
| Battery-swap leasing | ₹65,000 + ₹2,000/mo | ₹14,000 NPV/unit | 25,000 active subs | Year 3 |

The battery-swap leasing model reaches break-even fastest because it cuts the upfront price barrier, creates recurring revenue, and shifts battery degradation risk away from the consumer.

## Recommendation

A phased rollout across 5 metros (Bengaluru → Hyderabad → Pune → Delhi NCR → Mumbai), positioned as a battery-swap subscription play partnered with an established swap infrastructure provider such as Sun Mobility or Bounce Infinity.

Three reasons:
1. Battery swap sidesteps the BOM cost trap that's compressing margins for direct OEMs.
2. Subscription revenue is more defensible than one-time sales in a subsidy-dependent market.
3. Metro-first rollout matches where existing swap stations are already deployed (1,200+ stations across these 5 cities as of 2024).

Projected outcome: break-even by Year 3 at 25,000 active subscribers, scaling to 75,000 by Year 5.

## Risks

- Battery-swap standardisation isn't enforced yet (BIS draft is still pending). A major swap player failing would strand the network.
- Post-FAME-II, the sub-₹1L price point gets much harder. The model assumes subsidies are gone by Year 3, so this is partially baked in.
- Cell import dependency means a geopolitical shock (Taiwan, Korea) could directly hit unit economics. Worth flagging but hard to model.

## Sources

- SIAM annual reports, FY22–FY24
- Vahan Dashboard (parivahan.gov.in) for state-wise EV registration data
- Ola Electric DRHP, August 2024
- Ather Energy annual report, FY24
- NITI Aayog, "India's Electric Mobility Transformation" (2023)
- CRISIL, "Battery Swapping in India" (2024)

---

Work in progress. Numbers in the financial model are best-effort estimates from public data — happy to take corrections.
