# ab-testing-game-analysis
# 📊 A/B Testing Analysis on Mobile Game User Behavior


# A/B Testing Analysis: Impact of Feature Change on User Retention

## Objective
Evaluate whether shifting the first difficulty gate from level 30 to level 40 improves user retention and engagement.

---

## Approach
- Split users into two cohorts:
  - Control: gate_30
  - Variant: gate_40
- Compared Day 1 and Day 7 retention across cohorts
- Measured engagement using total game rounds played
- Performed statistical testing to validate observed differences

---

## Key Findings
- Day 1 and Day 7 retention are slightly higher in the control group (gate_30)
- The variant (gate_40) does not show improvement in short-term or long-term retention
- Engagement levels (game rounds) remain comparable across both groups
- Statistical testing suggests that the difference is *(update: significant / not significant)*

---

## Interpretation
Delaying the difficulty gate appears to reduce early friction but does not translate into improved retention. This indicates that the original gating point may better balance challenge and user progression.

---

## Recommendation
Retain the current implementation (gate_30).  
Future experiments should focus on improving early-game experience (onboarding, rewards, progression pacing) rather than shifting difficulty gates.

---

## Tools
Python (Pandas), Matplotlib, SciPy, Google Colab

---

## Author
Krrish


