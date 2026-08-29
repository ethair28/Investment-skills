# Evaluation Prompts

Use these prompts to test whether the skill transfers the investment mental model across different task shapes.

The goal is not to enforce one answer or format. Evaluate whether the agent identifies the right organizational signals, evidence cohorts, investor implications, and uncertainty.

## Single-company diligence

1. `Run employee culture diligence on NVIDIA.`
2. `Run employee culture diligence on Marvell.`
3. `Analyze Shopify's employee culture from an investment perspective.`

## Competitive comparison

4. `Compare AMD and NVIDIA's engineering cultures from an investment perspective.`
5. `Compare Cadence and Synopsys employee cultures.`
6. `Compare Astera Labs and Broadcom culturally as competitors in AI connectivity.`

## Specific thesis questions

7. `Does AMD have the organizational culture needed to close the software gap with NVIDIA?`
8. `Does Coinbase's aggressive AI culture look like productive adaptation or organizational chaos?`
9. `Can Marvell's culture support increasingly complex hyperscaler custom-silicon programs?`

## Trajectory

10. `Has Synopsys's culture improved or deteriorated over the last three years?`
11. `Has AMD become meaningfully more bureaucratic as it has scaled?`
12. `How has Coinbase's organizational culture changed since the 2022 layoffs?`

## Discovery / idea generation

13. `Find five publicly traded semiconductor companies whose employee evidence suggests unusually strong engineering cultures that investors may underappreciate.`
14. `Find public companies with exceptional investor-relevant cultures that are not obvious mega-cap technology names.`
15. `Find companies where employee reviews suggest unusually high talent density and ownership, then assess whether that organizational quality appears underappreciated by investors.`

## Hidden strategic core

16. `Find companies where mediocre headline Glassdoor or Blind ratings hide an exceptional strategically important technical organization.`
17. `Find large diversified technology companies where one core engineering business has a much stronger culture than the company-wide average.`

## Counter-sentiment / leadership

18. `Find founder-led public companies where even negative employee reviews show unusually strong respect for the CEO or founder.`
19. `Find companies where employee complaints about intensity actually reveal a potentially strong shareholder culture.`
20. `Find highly rated workplaces where strategically important employee reviews reveal complacency, weak accountability, or declining ambition.`

## What good behavior looks like

Across these prompts, the agent should generally:

- interpret employee evidence through shareholder value creation rather than employee happiness;
- infer strategically relevant cohorts without being told exactly which job titles matter;
- prioritize recent evidence for current culture and older evidence for trajectory;
- treat layoffs, WLB, compensation, intensity, and AI mandates as ambiguous signals requiring mechanism-level interpretation;
- search for counter-sentiment evidence and contradictions;
- notice internal dispersion that headline ratings can obscure;
- adapt the response shape to the question rather than forcing a fixed report;
- for discovery prompts, distinguish strong culture from evidence that the market underappreciates it;
- state uncertainty when strategically relevant evidence is thin.
