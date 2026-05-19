# Aurora EV Install

A local lead-generation site for EV charger installation in Aurora, Colorado.

**Live domain:** `auroraevinstall.com` *(planned)*
**Redirect domain:** `auroraevcharger.com` → `auroraevinstall.com`

---

## What this is

A SEO-focused lead-gen site that connects Aurora homeowners with a licensed local electrician for Tesla Wall Connector, Level 2, and NEMA 14-50 EV charger installations. The site routes phone calls and quote-form submissions to a single partner electrician on a flat monthly rental.

## V1 page set

| Page | Path | Status |
|---|---|---|
| Homepage | `index.html` | ✅ Built |
| EV Charger Installation Cost in Aurora | `cost.html` | ✅ Built |
| Tesla Wall Connector & Level 2 Installation | `tesla.html` | ⏳ Planned |
| Aurora EV Charger Permits & Inspection Guide | `permits.html` | ⏳ Planned |
| Xcel & Colorado EV Rebate Guide | `rebates.html` | ⏳ Planned |
| Panel Upgrade for EV Charger | `panel.html` | ⏳ Planned |
| Commercial / Multifamily EV Charging | `commercial.html` | ⏳ Planned |

## Verification standard

Every factual claim about permits, code, rebates, credits, and pricing is sourced from a primary or authoritative source. Inline citation links. Time-sensitive content carries a "Last verified [date]" stamp.

### Verified facts (master ledger)

- **Aurora has adopted 2023 NEC** — effective Aug 1, 2023. Source: [City of Aurora Building Division](https://www.auroragov.org/business_services/building_division/adopted_building_codes)
- **Electrical permit required for EV charger installs in Aurora** — must be pulled by a licensed electrical contractor. Source: [Aurora City Code §22-213](https://aurora.municipal.codes/Code/22-213)
- **Aurora Building Permit Center:** 303.739.7420 · 15151 E. Alameda Parkway, Aurora, CO 80012 · aurora4biz.org
- **Federal §30C credit terminates June 30, 2026** (changed by P.L. 119-21, July 2025). Source: [IRS Form 8911 (2025) Instructions](https://www.irs.gov/pub/irs-prior/i8911--2025.pdf)
- **§30C residential credit:** 30% of cost, up to $1,000 per port, eligible census tract required
- **Colorado state EV vehicle credit (Jan 1, 2026):** $750 base (down from $3,500) + $2,500 adder for sub-$35K EVs. Source: [Colorado Energy Office](https://energyoffice.colorado.gov/transportation/grants-incentives/zero-emission-vehicle-tax-credits)
- **VXC rebate (effective Nov 3, 2025):** $9,000 new / $6,000 used for income-qualified Coloradans. Source: [Colorado Energy Office VXC](https://energyoffice.colorado.gov/vehicle-exchange-colorado)
- **Xcel CO EV Home Wiring Rebate:** $500 standard / up to $1,300 enhanced (income-qualified). Requires Optimize Your Charge enrollment. Source: [Xcel Energy CO program application PDF](https://www.xcelenergy.com/staticfiles/xe-responsive/Marketing/21-07-530_CO-EV-HomeWiring_app_P03.pdf)
- **Tesla Wall Connector (Gen 3):** 200-240V single-phase, 12-48A programmable, hardwired only, integrated GFCI (CCID20), IP54, cULus E351001. Source: [Tesla Wall Connector Manual](https://www.tesla.com/sites/default/files/downloads/J1772-Wall-Connector-48A-Manual-EN.pdf)
- **Colorado average install cost:** $2,398 (excluding equipment). Source: [EnergySage / Qmerit (2025)](https://energysage.com/ev-charging/how-much-does-ev-charger-installation-cost/)
- **Cost tier distribution:** ~60% Tier 1 ($500-$1,500 circuit add) · ~15% Tier 2 sub-panel · ~15% Tier 3 panel replacement · ~10% Tier 4 full service upgrade. Source: [ChargeRight - Master Electrician data (2026)](https://evchargeright.com/blog/ev-charger-installation-cost)

## Update calendar

Time-sensitive content reverification cadence:

- **Every 30 days:** Xcel Energy CO Home Wiring Rebate status
- **Every 90 days:** Federal §30C credit status (monthly as we approach June 2026 deadline)
- **Every 90 days:** Colorado state EV credits and VXC amounts
- **Every 6 months:** Aurora adopted codes, cost data benchmarks
- **Annually:** Equipment spec pages
- **As needed:** Aurora Building Division contact info

## Tech stack (planned)

- Static HTML/CSS — no JS framework needed for V1
- Plausible analytics or GA4 (decide before launch)
- CallRail Lite for call tracking
- Form handler: Formspree or Netlify Forms
- Host: Cloudways managed or Netlify static
- Domain: AuroraEVInstall.com primary, AuroraEVCharger.com 301 redirect to primary

## Design system

- **Deep navy `#0A1F3D`** — primary brand
- **Electric blue `#0066FF`** — primary CTA
- **Cyan accent `#00B7E0`** — subtle accents and glow
- **Eco green `#10B981`** — sparingly, for verified badges and EV/sustainability micro-accents
- **Amber `#F59E0B`** — urgency callouts only (June 30, 2026 deadline)
- Inter typeface throughout (Google Fonts)
- Custom outlined SVG icons (no stock icons, no cartoon lightning bolts)

## License

All rights reserved. © 2026 Aurora EV Install.

Not affiliated with Tesla, Inc., Xcel Energy, or the City of Aurora.
