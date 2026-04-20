# job-salary-prediction

https://huggingface.co/spaces/zsor/BERT-salary // try it

Training History

| Epoch | Training Loss | Validation Loss | MSE | MAE | R² | Accuracy |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | 0.2394 | 0.1127 | 0.1127 | 0.2594 | 0.5797 | 86.75% |
| 2 | 0.1934 | 0.1086 | 0.1086 | 0.2592 | 0.5952 | 88.21% |
| **3** | **0.1620** | **0.0840** | **0.0840** | **0.2182** | **0.6871** | **91.56%** |
| 4 | 0.1543 | 0.0967 | 0.0967 | 0.2398 | 0.6396 | 90.28% |

This (custom) "accuracy" metric measures the percentage of model predictions that fall within a 0.5 log-unit margin (since $e = \sqrt{0.25} = 0.5$) of the true value. In practical terms, it represents the frequency with which the model's salary estimate is correct within a specific, tight error tolerance on the log scale.
