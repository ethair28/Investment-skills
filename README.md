# Investment Skills

Reusable agent skills for investment research workflows.

This repository captures research methods that have been tested in real company analysis so a fresh agent can reproduce the methodology without relying on prior conversation context.

## Skills

### Employee Culture Diligence

`skills/employee-culture-diligence/`

Investor-oriented analysis of employee reviews and discussions. The skill is designed to infer organizational capability, cultural trajectory, leadership quality, talent density, execution strengths, and organizational weak links rather than summarize employee satisfaction or headline workplace ratings.

Example prompts:

- `Run employee culture diligence on Marvell.`
- `Compare employee culture at Cadence and Synopsys.`
- `Run employee culture diligence on Broadcom, focusing on the semiconductor networking organization.`

## Design principles

- Investment perspective first.
- Current evidence and historical trajectory are analyzed separately.
- Strategically relevant employee cohorts matter more than company-wide averages.
- Specific, recent, corroborated evidence outweighs generic sentiment.
- Employee-positive and employee-negative statements are translated independently into shareholder implications.
- Conclusions state evidence quality and uncertainty rather than manufacturing precision.
