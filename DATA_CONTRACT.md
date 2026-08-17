# C18 Data Contract

## Purpose

This document defines the data interface required by the
C18 — Showing Uncertainty to People module.

C18 requires prediction and uncertainty-related information
from other calibration/evaluation modules and converts this
information into two presentation conditions:

1. Point prediction
2. Prediction with uncertainty interval

---

## Upstream Dependencies

### C1 — Calibration Check

Expected output:

`calibration_report.csv`

Purpose:

Provides information about the calibration/performance of
prediction confidence that can be used by C18.

Status:

Interface to be confirmed with the C1 team.

---

### C3 — Is the Improvement Real?

Expected output:

`significance_report.csv`

Purpose:

Provides statistical evaluation information associated
with model/prediction comparisons.

Status:

Interface to be confirmed with the C3 team.

---

## C18 Presentation Conditions

### Condition 1 — Point Prediction

The participant receives a prediction represented as a point
estimate.

Example:

Prediction: 78%

---

### Condition 2 — Interval Prediction

The participant receives the prediction together with an
uncertainty interval.

Example:

Prediction: 78%

90% uncertainty interval: 68%–86%

---

## C18 Study Output

The user-study data is expected to contain information such as:

| Column | Description |
|---|---|
| participant_id | Anonymous participant identifier |
| example_id | Identifier for the prediction/example |
| condition | Point or interval presentation |
| decision | Decision made by participant |
| confidence | Participant's stated confidence |

The final schema will be confirmed before data collection.

---

## Data Flow

C1
→ calibration information
→ C18

C3
→ statistical/evaluation information
→ C18

C18
→ prediction presentation
→ participant decision
→ user-study results

---

## Ethics and Privacy

Participant information must be anonymised.

Human participant data must not be collected until the
required informed consent and institutional ethics clearance
are obtained.

---

## Current Status

Week 1:

- Data dependencies identified
- Initial input/output interface defined
- C1 and C3 teams need to confirm their exact CSV schemas
- User-study output structure proposed
