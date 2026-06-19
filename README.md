# Fashion-MNIST Neural Network Comparison

A portfolio machine-learning project comparing Dense Neural Networks, Convolutional Neural Networks, and optimizer / learning-rate choices on the Fashion-MNIST image classification dataset.

## Project Snapshot

This project trains and evaluates ten controlled TensorFlow/Keras experiments on Fashion-MNIST:

- 3 Dense Neural Network models without convolutional layers
- 4 Convolutional Neural Network models with different depth, filter, normalization, and dropout choices
- 3 optimizer / learning-rate comparison runs using a fixed finalist CNN architecture

The best-performing model in the executed run was `OPT_03_FINAL_CNN_ADAM_LOW_LR`, reaching **92.05% test accuracy**.

## Why This Project Matters

The project demonstrates a full experimental machine-learning workflow:

- Dataset loading and validation
- Image normalization and reshaping for Conv2D models
- Controlled model comparison
- Training and validation tracking
- Test-set ranking
- Per-class performance analysis
- Misclassification analysis
- Architecture and result visualization
- Reproducible result exports to CSV

## Repository Contents

```text
.
├── computational_intelligence_assignment.ipynb
├── csv/
│   ├── experiment_registry.csv
│   ├── final_ranking.csv
│   ├── training_histories.csv
│   ├── per_class_performance.csv
│   ├── ablation_summary.csv
│   └── misclassification_summary.csv
└── report/
    ├── report_draft.docx
    ├── architecture_diagrams/
    └── figures/
```

## Final Ranking

| Rank | Experiment | Task | Test Accuracy | Test Loss |
|---:|---|---:|---:|---:|
| 1 | `OPT_03_FINAL_CNN_ADAM_LOW_LR` | 3 | 0.9205 | 0.2228 |
| 2 | `CNN_04_TUNED_FINALIST` | 2 | 0.9185 | 0.2335 |
| 3 | `OPT_01_FINAL_CNN_ADAM` | 3 | 0.9185 | 0.2335 |
| 4 | `CNN_03_DEEPER` | 2 | 0.9104 | 0.2467 |
| 5 | `OPT_02_FINAL_CNN_SGD` | 3 | 0.9100 | 0.2420 |

## Tools Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Notes

This repository is prepared as a portfolio-friendly machine-learning project. Private assignment documents and internal planning files are intentionally excluded from the public repository.


## LinkedIn Summary

This project is a good portfolio example because it shows more than a single model score. It demonstrates controlled experimentation, fair model comparison, error analysis, and clear result communication.
