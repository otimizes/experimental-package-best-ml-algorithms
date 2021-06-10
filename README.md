# experimental-package-best-configurations

| Algorithm  | Hidden layers | Learning rate | Training time | Sample Size | Kernel Type | SVM Type | Iterations | Global Bend | Combination Rule | Classifiers |
|---|---|---|---|---|---|---|---|---|---|---|
| MLP (500) | i | 0.3 | 500 | - | - | - | - | - | - | - | - |
| MLP (2500) | i | 0.3 | 2500 | - | - | - | - | - | - | - |
| LMS | - | - | - | 4 | - | - | - | - | - | - | - | - | - |
| LibSVM | - | - | - | 2 | Radial basis | C-SVC |  - | - | - | - |
| RC Random Tree | - | - | - | - | - | - | 100 | - | - | - |
| K* | - | - | - | - | - | - | - | 20 | - | - |
| MCS (Vote) | - | - | - | - | - | - | - | - | Average of Probabilities | LibSVM + KStar + RandomComitte of RandomTree
