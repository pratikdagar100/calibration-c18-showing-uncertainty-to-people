# Uncertainty-Aware Prediction Dashboard

## C18 — Showing Uncertainty to People

### Team 33

* Trish Dalal — Team Leader / Project Definition
* Pratik Dagar — Repository and System Architecture
* Deepesh Phalswal — Data and Integration
* Jatin — Evaluation and Experiment Design

---

## 1. Problem Statement

Machine learning systems often provide predictions as a single value or probability. However, a single prediction may not clearly communicate how uncertain the prediction is.

For example, a system may provide a prediction of 78%. A user may make a different decision if the system also shows an uncertainty interval such as 68%–86%.

This project investigates whether the way uncertainty is presented affects the decisions made by people.

---

## 2. Project Objective

The objective of this project is to develop an interactive dashboard that presents predictions in two different formats:

1. Point prediction
2. Prediction with an uncertainty interval

The project will then study whether the presentation format affects the decisions made by users.

---

## 3. Research Question

**Does presenting a prediction using an uncertainty interval change people's decisions compared with presenting only a point prediction?**

---

## 4. Hypotheses

### Null Hypothesis (H0)

Presenting an uncertainty interval does not change people's decisions compared with presenting only a point prediction.

### Alternative Hypothesis (H1)

Presenting an uncertainty interval changes people's decisions compared with presenting only a point prediction.

---

## 5. System Overview

The dashboard will provide two presentation conditions.

### Condition 1 — Point Prediction

The user sees the prediction as a single value.

Example:

**Prediction: 78%**

### Condition 2 — Prediction with Uncertainty

The user sees the prediction together with an uncertainty interval.

Example:

**Prediction: 78%**

**Uncertainty interval: 68%–86%**

The user will then make a decision based on the information shown.

The planned study will expose participants to both presentation conditions using different examples.

---

## 6. Measurements

### Primary Outcome

The primary outcome is the **decision made by the participant**.

### Secondary Outcome

The secondary outcome is the **confidence stated by the participant**.

The main focus of the study is whether showing uncertainty changes participant decisions.

---

## 7. Dependencies

The C18 module will integrate with outputs from other project modules, including:

* C1 — Calibration Check
* C3 — Is the Improvement Real?

The exact data interfaces will be coordinated with the respective teams.

---

## 8. Ethics

Participant data will only be collected after the required informed consent and institutional ethics clearance.

No participant study results are being claimed at this stage.

---

## 9. Current Status

### Phase 1 — Project Setup

* [x] Team formed
* [x] Project topic selected
* [x] GitHub repository created
* [x] Project structure created
* [x] Research question defined
* [x] Initial project objectives defined
* [ ] Dataset exploration
* [ ] Baseline model
* [ ] Dashboard implementation
* [ ] User study
* [ ] Final evaluation
