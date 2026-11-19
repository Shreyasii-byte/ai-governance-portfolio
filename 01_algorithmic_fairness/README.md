# Project 01: Algorithmic Fairness Audit of AI-Driven Recruitment Systems

## 1. Overview

This project examines fairness, accountability, and governance risks in AI-driven recruitment systems.

AI recruitment tools can help organisations screen large volumes of applications. However, models trained on biased historical hiring decisions may reproduce or amplify discriminatory patterns.

This project uses a synthetic recruitment dataset to evaluate how different modelling approaches affect hiring outcomes across demographic groups.

## 2. Research Question

Can an AI-driven recruitment system produce unfair selection outcomes across gender groups, and how can fairness evaluation and mitigation methods support more responsible deployment?

## 3. Objectives

- Examine potential gender bias in recruitment decisions.
- Compare model performance and fairness outcomes.
- Evaluate demographic parity across gender groups.
- Examine intersectional selection outcomes.
- Investigate false-negative outcomes.
- Map identified risks to AI governance practices.
- Develop recommendations for responsible AI deployment.

## 4. Dataset

The project uses a synthetically generated recruitment dataset containing applicant characteristics and simulated hiring outcomes.

**Important:** The dataset is artificial and does not contain real applicant information or represent an actual employer's recruitment decisions.

## 5. Methodology

The analysis follows these stages:

1. Synthetic dataset generation.
2. Data preprocessing and feature selection.
3. Baseline model development.
4. Biased historical decision simulation.
5. Fairness-aware model experimentation.
6. Model performance evaluation.
7. Demographic fairness analysis.
8. Intersectional and false-negative audits.
9. Governance and regulatory analysis.

## 6. Evaluation Metrics

### Model performance
- Accuracy
- Precision
- Recall
- F1-score

### Fairness evaluation
- Demographic Parity Difference
- Demographic Parity Ratio
- Group-level selection rates
- Intersectional selection analysis
- False-negative rates

Performance and fairness are assessed separately because a model can achieve acceptable predictive performance while still producing unequal outcomes.

## 7. Governance Framework

The project connects its findings to:

- **NIST AI Risk Management Framework:** AI risk identification, measurement, management, and governance.
- **NYC Local Law 144:** An illustrative regulatory reference concerning automated employment decision tools.

This project is an educational analysis, not a legal compliance assessment.

## 8. Key Governance Considerations

- Regular demographic fairness audits.
- Documentation of training data and model decisions.
- Human review of consequential hiring decisions.
- Clear accountability for AI-assisted screening.
- Candidate transparency and mechanisms to challenge decisions.
- Ongoing monitoring after deployment.

## 9. Repository Structure

```text
01_algorithmic_fairness/
├── README.md
├── notebook/
│   └── Recruitment_AI_Fairness_Audit_v2.ipynb
└── results/
    ├── synthetic_recruitment_dataset.csv
    ├── recruitment_test_predictions.csv
    ├── model_comparison.csv
    ├── gender_fairness_results.csv
    ├── intersectional_audit.csv
    ├── false_negative_audit.csv
    ├── nist_governance_mapping.csv
    └── regulatory_governance_analysis.csv
```

## 10. Limitations

- The dataset is synthetic and cannot establish real-world discrimination.
- Results depend on the assumptions used to generate simulated hiring decisions.
- Fairness metrics capture specific dimensions of fairness and do not establish overall ethical acceptability.
- Mitigation methods may involve trade-offs between different performance and fairness objectives.
- Regulatory references require independent legal verification before being used for compliance decisions.

## 11. Conclusion

This project demonstrates a practical approach to examining algorithmic fairness in recruitment systems. It highlights why model evaluation should extend beyond predictive performance to include demographic outcomes, accountability, transparency, and human oversight.

**Project Type:** Independent AI Governance Research  
**Domain:** Algorithmic Fairness | Responsible AI | AI Risk Management  
**Tools:** Python, Pandas, Scikit-learn, Fairlearn, Matplotlib, Seaborn
