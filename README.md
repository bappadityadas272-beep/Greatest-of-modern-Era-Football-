# ⚽ Messi vs Ronaldo vs Neymar: Who Is the Greatest of the Modern Era?

**Mini Project: Data Analysis, Visualization and Machine Learning Using Python**
IILM University · B.Tech CSE · Year 2 · Section 2CSE4 · Faculty Guide: Aditya Bangia (Data Visualization)

### 👉 [View the complete notebook as a web page](https://bappadityadas272-beep.github.io/Greatest-of-modern-Era-Football-/)

## Team
| Name | Roll No. |
|---|---|
| Bappaditya Das | 2304 |
| Manya Chauhan | 0422 |
| Kashish Bhambri | 2330 |
| Sanchita Singh | 4093 |
| Tabish Khan | 1092 |

## What the project does
Using **StatsBomb Open Data** (1,002 professional matches, 24,866 shots), the project compares Lionel Messi,
Cristiano Ronaldo and Neymar with the full data-science workflow:

- **Preprocessing** with Pandas and NumPy: missing values, duplicates, data types, outliers, shot distance and angle, per-90 rates
- **EDA and visualization** with Matplotlib and Seaborn, including a football pitch drawn from scratch
- **Classification** (will a shot be a goal?): Logistic Regression, Decision Tree, Random Forest, KNN, SVM, Naive Bayes and Gradient Boosting, tuned with GridSearchCV and evaluated with confusion matrices, precision, recall, F1 and ROC-AUC
- **Linear Regression**: what drives goals + assists
- **K-Means clustering**: four playing styles
- **Ranking**: eight criteria, three weightings, a fair-season check (La Liga 2015/16) and a sensitivity analysis

## Result
| Rank | Player | Final score |
|---|---|---|
| 🥇 1 | Lionel Messi | 9.85 |
| 🥈 2 | Neymar | 7.27 |
| 🥉 3 | Cristiano Ronaldo | 7.03 |

Messi is first in every view; Neymar and Ronaldo are a near tie for second.

## Files
| File | Contents |
|---|---|
| `index.html` | The notebook as a web page (all code, outputs and charts) |
| `Messi_Ronaldo_Neymar_Project.ipynb` | The Jupyter notebook, already run |
| `data/` | The cleaned StatsBomb tables used by the notebook |
| `requirements.txt` | Python packages needed |

## Run it yourself
```bash
pip install -r requirements.txt
jupyter notebook Messi_Ronaldo_Neymar_Project.ipynb
```
Then choose **Kernel → Restart & Run All** (about 2 minutes).

*Data: [StatsBomb Open Data](https://github.com/statsbomb/open-data). Career totals: Wikipedia (November 2026).*
