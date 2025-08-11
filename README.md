
# Elevate Labs AI/ML Internship — Task 5  
**Topic:** Decision Trees & Random Forests (Classification)  
**Dataset:** Heart Disease Dataset (`heart.csv`)  

## Objective
Implement and analyze tree-based models for classification using **Decision Tree** and **Random Forest**.  
Explore overfitting control, feature importance, visualization, and cross-validation.


##  Installation & Setup
1. **Clone repository:**
```bash
git clone https://github.com/Pavan-Reddy93/elevate-labs-aiml-task-5.git
cd elevate-labs-aiml-task-5
````

2. **Install dependencies:**

```bash
pip install -r requirements.txt
```

> If you want to render `.dot` tree files, install Graphviz binary as well:
> `sudo apt-get install graphviz` (Linux) or [Graphviz official site](https://graphviz.org/download/).



##  How to Run

### Option 1: Python script

```bash
python decision_trees_random_forests_heart.py
```

### Option 2: Jupyter Notebook

```bash
jupyter notebook step_by_step_decision_trees_rf.ipynb
```


##  Results Summary

* Baseline Decision Tree → Very high train accuracy, lower test accuracy (signs of overfitting).
* Pruned Decision Tree (`max_depth` tuned) → Balanced train/test performance.
* Random Forest → Best generalization accuracy among tested models.
* Top features (by RF):

  1. `cp` (Chest Pain Type)
  2. `thalach` (Max Heart Rate)
  3. `oldpeak` (ST Depression)
  4. `ca` (Number of Major Vessels)
  5. `thal` (Thalassemia Type)


pandas
numpy
scikit-learn
matplotlib
graphviz


##  Author

Pavan Reddy (Elevate Labs AI/ML Internship)

