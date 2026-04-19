# Player Performance Forecasting – Analytics Support for the Front Office

## Project Overview
This project proposes a **Player Performance Forecasting Tool** for a professional basketball organization (NBA). The tool uses historical player data to predict individual player performance trends over the upcoming season, helping the front office make smarter roster, contract, and trade decisions. Rather than relying solely on last season's stats, this tool forecasts a player's likely trajectory — identifying players who are trending up, plateauing, or declining.

---

## Decision-Making Problem
Front office executives and coaches frequently face high-stakes decisions — signing free agents, trading players, or extending contracts — with incomplete information about a player's future performance. Current approaches rely heavily on recent statistics and subjective scouting, which may miss underlying trends. This tool is designed to reduce uncertainty in those decisions by providing data-driven performance projections.

---

## Proposed Analytics Approach
The tool would draw on the following types of data:
- **Historical player statistics** (points, assists, rebounds, shooting efficiency, defensive metrics) across multiple seasons
- **Age and career trajectory data** to model typical performance curves by position
- **Injury history and workload data** to adjust projections for wear-and-tear risk
- **Advanced metrics** such as PER (Player Efficiency Rating), Win Shares, and RAPTOR scores

The analysis would involve trend modeling across seasons to project a player's expected performance range for the next 1–3 years. Outputs would be presented as a simple dashboard showing projected stats with confidence intervals — no complex equations visible to the end user.

---

## Use by Decision Makers
- **General Managers** would use the tool during trade deadline and free agency periods to compare projected value versus contract cost
- **Coaches** would consult it during pre-season planning to anticipate which players may need reduced minutes or different roles
- **Scouts** would use it to flag undervalued players whose projections exceed current market perception
- The dashboard is designed to be visual and non-technical — a simple color-coded forecast card per player (green = trending up, yellow = stable, red = declining)

---

## Connection to Chapter 7
This idea currently represents the **Creative Phase** of the innovation framework. The concept has been identified and defined — there is a clear problem (roster decision uncertainty), a proposed solution (performance forecasting), and an intended audience (front office and coaching staff). However, no prototype has been built yet, no stakeholder feedback has been gathered, and the tool has not been tested in a real decision-making scenario. The next step would be to move into the Prototyping Phase by building a simplified version for evaluation.

---

---

## Prototype Enhancement
**What is being changed:**
The original tool forecasts performance using traditional box-score statistics. This enhancement proposes adding **biometric and workload tracking data** as an additional data source — specifically, data from player wearables (e.g., heart rate variability, sleep quality scores, practice intensity load) integrated alongside game statistics.

**Why this change could improve decision-making:**
Box-score stats alone are lagging indicators — they tell you what already happened. Biometric and workload data are leading indicators that can signal early fatigue, injury risk, or peak physical readiness *before* it shows up in game performance. For example, a player showing declining sleep quality and high training load over six weeks may be at risk of a performance dip even if their recent game stats look fine.

By incorporating this layer, the forecasting tool becomes more proactive. A general manager evaluating a contract extension would not only see projected stats but also a physical readiness score — making it a more complete picture for high-stakes decisions.
## Prototype Evaluation
**Should the prototype enhancement be integrated into the main project?**
Yes — the addition of biometric and workload tracking data represents a meaningful improvement to the original concept. It shifts the tool from reactive (describing past performance) to proactive (anticipating future performance dips or peaks), which directly strengthens the value for front office decision makers evaluating contracts and roster moves.

**What type of feedback from decision makers would influence this decision?**
Before full integration, the following feedback would be essential:
- **From the General Manager:** Does the physical readiness score feel interpretable and trustworthy? Would they actually factor it into a contract decision?
- **From the coaching staff:** Is the workload data granular enough to be actionable, or does it feel like noise?
- **From the analytics team:** Is biometric data available, reliable, and consistently tracked across the organization? Are there privacy or player-union considerations?

If decision makers find the biometric layer confusing or untrustworthy, the enhancement should be refined further before merging. If feedback is positive and data access is confirmed, the prototype is ready to be adopted into the main project.

