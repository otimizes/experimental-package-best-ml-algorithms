## Investigating the use of Machine Learning algorithms to represent the Decision Maker profile in Search-Based Product Line Design

### Table of Machine Learning Algorithms Properties

| Algorithm  | Hidden layers | Learning rate | Training time | Sample Size | Kernel Type | SVM Type | Iterations | Global Bend | Combination Rule | Classifiers |
|---|---|---|---|---|---|---|---|---|---|---|
| MLP (500) | i | 0.3 | 500 | - | - | - | - | - | - | - | - |
| MLP (2500) | i | 0.3 | 2500 | - | - | - | - | - | - | - |
| LMS | - | - | - | 4 | - | - | - | - | - | - | - | - | - |
| LibSVM | - | - | - | 2 | Radial basis | C-SVC |  - | - | - | - |
| RC Random Tree | - | - | - | - | - | - | 100 | - | - | - |
| K* | - | - | - | - | - | - | - | 20 | - | - |
| MCS (Vote) | - | - | - | - | - | - | - | - | Average of Probabilities | LibSVM + KStar + RC RandomTree

The other parameters not shown here were used according to the default weka values. The parameters of algorithms into the MCS are the same as those shown indivually.
