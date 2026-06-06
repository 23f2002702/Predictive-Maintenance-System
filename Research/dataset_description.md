# Dataset Description

## Dataset Name

AI4I 2020 Predictive Maintenance Dataset

---

## Source

* UCI Machine Learning Repository
* AI4I 2020 Predictive Maintenance Dataset

### Citation

Matzka, S. (2020). *Explainable Artificial Intelligence for Predictive Maintenance Applications*. Third International Conference on Artificial Intelligence for Industries (AI4I), 69–74.

---

## Dataset Purpose

The AI4I 2020 dataset is a synthetic predictive maintenance dataset modeled after a real industrial milling machine process. It was developed to simulate realistic manufacturing operating conditions and machine failure scenarios while supporting research in predictive maintenance and explainable artificial intelligence.

The dataset is intended for machine learning applications involving:

* Predictive Maintenance
* Failure Prediction
* Equipment Health Monitoring
* Explainable Artificial Intelligence (XAI)
* Industrial Analytics

---

## Dataset Overview

* Total Records: 10,000
* Total Features: 14
* Target Variable: Machine Failure
* Domain: Manufacturing and Industrial Equipment

Each row represents the operating condition of a machine at a specific point in time.

---

## Variables

| Variable                | Description                        |
| ----------------------- | ---------------------------------- |
| UDI                     | Unique record identifier           |
| Product ID              | Product identifier                 |
| Type                    | Product quality category (L, M, H) |
| Air Temperature [K]     | Ambient operating temperature      |
| Process Temperature [K] | Internal process temperature       |
| Rotational Speed [rpm]  | Machine rotational speed           |
| Torque [Nm]             | Applied torque                     |
| Tool Wear [min]         | Tool wear duration                 |
| Machine Failure         | Overall failure indicator          |
| TWF                     | Tool Wear Failure                  |
| HDF                     | Heat Dissipation Failure           |
| PWF                     | Power Failure                      |
| OSF                     | Overstrain Failure                 |
| RNF                     | Random Failure                     |

---

## Product Categories

The dataset contains three machine quality categories:

| Type | Description    | Proportion |
| ---- | -------------- | ---------- |
| L    | Low Quality    | 50%        |
| M    | Medium Quality | 30%        |
| H    | High Quality   | 20%        |

These categories simulate variations in manufacturing quality and operating behavior.

---

## Failure Mechanisms

The target variable **Machine Failure** is activated whenever one or more failure modes occur.

### Tool Wear Failure (TWF)

Failure caused by excessive wear of the cutting tool during operation.

### Heat Dissipation Failure (HDF)

Failure caused by inadequate heat dissipation under operating conditions.

### Power Failure (PWF)

Failure occurring when operating power falls outside acceptable process limits.

### Overstrain Failure (OSF)

Failure resulting from excessive mechanical strain caused by combinations of torque and tool wear.

### Random Failure (RNF)

Rare failures occurring independently of measured operating conditions.

---

## Target Variable

### Machine Failure

* 1 = Failure occurred
* 0 = No failure occurred

This variable serves as the primary prediction target for all machine learning models developed in this project.

---

## Dataset Suitability for Predictive Maintenance

The dataset contains several variables commonly monitored in industrial maintenance systems, including:

* Temperature
* Rotational Speed
* Torque
* Tool Wear
* Machine Type

These measurements provide information about machine operating conditions and equipment health, making the dataset suitable for predictive maintenance research and failure prediction modeling.

---

## Project Objectives Using This Dataset

This dataset will be used to:

1. Analyze operating conditions associated with machine failures.
2. Identify the most important failure-related variables.
3. Develop machine learning models for failure prediction.
4. Compare the performance of multiple classification algorithms.
5. Generate machine health risk assessments.
6. Estimate the potential business impact of predictive maintenance strategies.
7. Explore how data-driven maintenance can reduce downtime and operational costs.

---

## Expected Challenges

* Class imbalance due to relatively few failure events.
* Potential relationships among sensor measurements.
* Multiple failure mechanisms contributing to a single target variable.
* Balancing predictive performance with model interpretability.
* Translating technical model outputs into actionable maintenance decisions.

---

## Importance of the Dataset

Predictive maintenance has become a critical component of modern manufacturing systems because unexpected failures can result in significant financial losses, production delays, and reduced equipment availability.

This dataset provides a controlled environment for investigating how machine learning techniques can be applied to maintenance planning, risk assessment, and operational decision-making. The insights generated from this project may help demonstrate how data-driven maintenance strategies can improve both engineering performance and business outcomes.

---

## Notes

Although synthetic, the dataset was designed to closely resemble real industrial operating conditions and failure scenarios. It is widely used in predictive maintenance research, machine learning experimentation, and educational projects related to industrial analytics.





