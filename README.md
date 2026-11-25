# RealRisk

Measure your security posture against operational reality, not compliance checklists.

RealRisk is a gamified security assessment based on [OSSTMM 4](https://www.isecom.org/) methodology by ISECOM. 25 questions across 5 operational security dimensions, mapped to actual Trust Controls and Security Controls from the OSSTMM v4 lattice.

## What It Measures

| Dimension | What It Tells You |
|-----------|-------------------|
| **Visibility** | What your environment discloses to observers |
| **Induction** | How context shapes and constrains behavior |
| **Interactions** | Direct force exerted on or by your systems |
| **Intervention** | Resource consumption and operational sustainment |
| **Inquest** | The story of your state and history |

## Features

- **25 calibrated questions** across 5 OSSTMM dimensions (5 per dimension)
- **Dimension explainers** — tap any dimension in results to see the full v4 Trust Control and Security Control breakdown across Intent / React / Resolve phases
- **Gap analysis** — identifies critical gaps and areas needing improvement
- **Results export** — copy formatted results to clipboard for reporting
- **Mobile-first PWA** — install to your home screen, works offline
- **Dark theme** — because staring at white screens during assessments is a security risk to your retinas

## How Scoring Works

Each question maps to a specific OSSTMM concept (Exoanalysis, Throttling, Accountability, Suppression, Channeling, Scrutiny, Commissioning, Surveillance, Validation, Abundance, Confinement, Solidity, Curation, Tethering, Purity). Responses are scored 0-3 and aggregated per dimension.

**Grade Labels:**
- **Operational Security** (85+) — Your controls are measured and tested
- **Measured Posture** (70+) — Solid foundation with known gaps
- **Compliance Theater** (50+) — You pass audits but that's not the same thing
- **Prayer-Based Security** (30+) — Hope is not a control
- **Open Season** (<30) — Attackers send thank-you cards

## Running It

It's a single HTML file. Open `index.html` in any browser.

For mobile install: serve it over HTTPS and tap "Add to Home Screen."

## Methodology

Based on OSSTMM 4 by [ISECOM](https://www.isecom.org/). The Open Source Security Testing Methodology Manual is the only security testing methodology that measures operational security through empirical testing rather than compliance checklists.

The 5-Dimension model (Visibility, Induction, Interactions, Intervention, Inquest) crossed with 3 Phases (Intent, React, Resolve) produces the 15 Trust Controls and 15 Security Controls that form the measurement lattice.

## License

MIT

## Credits

- OSSTMM 4 methodology by [ISECOM](https://www.isecom.org/)
- Assessment engine by [Griffin Cyber Solutions](https://griffincybersolutions.com)
