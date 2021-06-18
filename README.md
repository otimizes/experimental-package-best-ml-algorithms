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


\multirow{2}{*}{\textbf{DM}} & \multirow{2}{*}{\textbf{Escolaridade}}  & \multirow{2}{*}{\textbf{Estudante de}} & \multirow{2}{*}{\textbf{Trabalha em}} & \multicolumn{2}{c}{\textbf{Conhecimento}}  
### Table of participants

| DM | Scholarity | Graduate Student | Works in industry | Knowledge in UML | Knowledge in PLA
|---|---|---|---|---|---|
| DM 1 | Master's degree | Yes | Yes | Intermediary | Intermediary |
| DM 2 | Graduate | No | No | Basic | Basic |
| DM 3 | Master's degree | Yes | No | Advanced | Advanced |
| DM 4 | Master's degree | Yes | No | Advanced | Advanced |
| DM 6 | Graduate | Yes | No | Intermediary | Intermediário |
| DM 7 | Graduate | Yes | No | Intermediary | Intermediário |
| DM 8 | Specialization | No | Yes | Intermediário | Intermediary |
| DM 9 | Master's degree | Yes | Yes | Basic | Basic |
| DM 10 | Master's degree | No | No | Advanced | Intermediary |
| DM 11 | Specialization | Yes | No | Intermediary | Intermediary |


