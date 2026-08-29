# Research Modes

Infer the research mode from the user's request. Do not force every task into a generic company report.

## 1. Single-company diligence

Typical prompts:
- `Run employee culture diligence on Marvell.`
- `Analyze NVIDIA's culture from an investment perspective.`

Goal:
Understand what strategically relevant employees reveal about the company's current organizational capability, trajectory, strategic fit, and important organizational risks or advantages.

Approach:
- infer the investment capabilities that matter;
- identify the employee cohorts with visibility into those capabilities;
- build the current view from recent evidence;
- use historical evidence to understand trajectory;
- focus the answer on the few findings that materially change the investment view.

Do not default to a generic workplace summary.

## 2. Competitive comparison

Typical prompts:
- `Compare Cadence and Synopsys employee cultures.`
- `Which organization is better positioned culturally: Astera Labs or Broadcom?`

Goal:
Determine which organization is better suited to the competitive problem and why.

Approach:
- build each company's evidence set independently before comparing;
- use equivalent strategically relevant cohorts when possible;
- apply the same recency standard;
- identify where each culture has a real advantage;
- distinguish current capability from trajectory;
- ask whether the cultural advantage is strategically important, durable, and difficult for the competitor to copy.

Do not infer superiority from overall workplace ratings.

## 3. Specific organizational thesis question

Typical prompts:
- `Does AMD have the culture needed to close the software gap?`
- `Can Marvell coordinate enough specialized teams to win hyperscaler custom-silicon programs?`
- `Is Coinbase's AI push improving engineering or creating chaos?`

Goal:
Use employee evidence to answer the narrow organizational question rather than producing a full company culture review.

Approach:
- identify the specific capability required;
- seek employees closest to that capability;
- search for mechanisms directly relevant to the question;
- compare current evidence with historical change when useful;
- report only adjacent cultural dimensions that materially affect the answer.

## 4. Trajectory / change analysis

Typical prompts:
- `Has Synopsys culture deteriorated over the last three years?`
- `Has AMD become more bureaucratic as it scaled?`
- `Did the acquisition improve or damage the engineering culture?`

Goal:
Determine what changed, when, why, and whether the change matters to future execution.

Approach:
- establish the current state first;
- find comparable historical cohorts or long-tenured employees;
- prioritize explicit longitudinal testimony;
- anchor potential change points to dated corporate events;
- avoid calling a trend from different samples merely because older and newer review averages differ.

Use cautious language when the direction is suggestive but not well established.

## 5. Monitoring / update

Typical prompts:
- `Recheck Synopsys employee culture after the Ansys integration.`
- `Has Coinbase's management flattening improved coordination?`

Goal:
Identify what changed since the prior known state.

Approach:
- focus heavily on the newest relevant reviews;
- compare mechanisms, not just sentiment or ratings;
- test previously identified weak links or advantages;
- surface genuinely new signals rather than rewriting the original diligence.

## 6. Discovery / screening

Typical prompts:
- `Find public companies with exceptional cultures that investors may be overlooking.`
- `Find semiconductor companies where employee evidence suggests unusually strong engineering organizations.`
- `Look for companies where mediocre Glassdoor ratings hide an exceptional core technical culture.`
- `Find founder-led companies where even negative employee reviews show unusual respect for leadership.`

Goal:
Generate investment ideas using organizational quality as a signal.

This is **not** a ranking of the highest workplace scores.

Search for organizational signals such as:
- repeated praise of peer quality from senior relevant employees;
- high ownership and decision autonomy;
- difficult, important work and steep learning;
- unusually credible technical or founder leadership;
- customer obsession;
- rapid adaptation to technological or market change;
- high standards that employees may experience negatively;
- strategically important cohorts that look much stronger than company-wide averages;
- real technological transformation inside a legacy company;
- cultural characteristics that seem unusually well matched to the market.

Then test two additional questions:

### Is the organizational strength strategically important?
A wonderful culture in a non-differentiating function may have little investment relevance.

### Is it plausibly underappreciated?
Use appropriate market, valuation, investor-narrative, or competitive evidence. Do not assume employee culture is overlooked merely because it is strong.

For broad screens, prioritize a smaller number of high-conviction unusual signals over long lists of companies with good ratings.

## 7. Hidden-core search

Typical prompts:
- `Find companies where headline employee ratings obscure a great strategic core.`

Goal:
Find internal dispersion that creates misleading external perception.

Approach:
- identify companies with mediocre or mixed broad sentiment;
- search role-, location-, or business-unit-specific cohorts tied to the thesis;
- look for unusually strong CEO approval, talent, ambition, ownership, customer orientation, or learning in the core group;
- explain why broad employee sentiment differs from the strategically relevant cohort.

## 8. Leadership signal search

Typical prompts:
- `Find companies where negative reviewers still respect the CEO.`

Goal:
Use counter-sentiment evidence to identify leadership credibility that may be unusually robust.

Approach:
- prioritize long-tenured, senior, strategically relevant employees;
- distinguish respect for strategic/technical judgment from simple personality approval;
- seek corroboration across employees and time;
- separately assess whether the CEO's quality propagates through middle management.

## Mode combinations

Requests can combine modes.

Example:
`Find overlooked semiconductor companies with exceptional engineering cultures and compare the top three.`

This combines discovery and comparison. First generate candidates using employee evidence; then independently diligence the finalists and compare strategically relevant organizational capabilities.

Use judgment. The purpose of modes is to help reason about user intent, not to create procedural bureaucracy.
