# 🏥 AI101-MiniProject-CKD-Logistic-Regression (Group-26)
> **Predicting Chronic Kidney Disease (CKD)** using advanced Logistic Regression modeling.  
> *An AI101 Mini-Project | IIT Ropar*

---

## 👥 Team Members & Roles

| Team Member | GitHub | Role | Core Responsibility |
| :--- | :--- | :--- | :--- |
| **SUDA TANISHQ REDDY** | [@STanishqReddy](https://github.com) | 📝 Documentation Lead | Dataset exploration, README architecture, & notebook integration |
| **ABHISHEK** | [@WebDevbyAbhi](https://github.com) | ⚙️ Execution Lead | Conda environment setup, dependency management, & preprocessing |
| **PRABHNOOR KATARIA** | [@prabhnoor-wml](https://github.com) | 📊 PPT Lead | Logistic Regression model architecture, training, & deck preparation |
| **DAVULURI VINOD** | [@Vinod-Davuluri](https://github.com) | 🎬 Video Lead | Model evaluation (ROC/PR curves), metrics analysis, & video demo |

---

## 📂 Project Structure

```text
AI101-MiniProject-CKD-Logistic-Regression/
├── 📁 docs/                         # Project blueprint & documentation
│   ├── problem_statement.md
│   ├── demo_plan.md
│   └── model_evaluation_plan.md
├── 📁 presentation/                 # Slide decks & presentation materials
│   └── CKD_Project_Presentation.pptx
├── 📁 results/                      # Performance visualization exports
│   ├── precision_recall_curve.png
│   └── roc_curve.png
├── 📁 video/                        # Final video demonstration output
├── 📊 Chronic_Kidney_Disease_data.csv
├── 📓 CKD_Logistic_Regression.ipynb
├── 📦 environment.yml
├── 📋 requirements.txt
└── 📝 README.md
```

---

## 🏆 Team Contributions

> Detailed operational breakdown of specific milestones achieved by each member during the lifecycle of the project.

* **📝 Documentation Lead**
  * Explored and mapped raw dataset structural traits.
  * Authored clean, readable repository documentation.
  * Formatted and integrated individual notebook sections.
* **⚙️ Execution Lead**
  * Built and verified the stable Conda pipeline environment.
  * Tracked, pinned, and managed package dependencies.
  * Configured data imputation and pipeline preprocessing.
* **📊 PPT Lead**
  * Engineered the production-ready Logistic Regression model.
  * Computed data predictions and hyperparameter balances.
  * Structured the conceptual logic for the mid-review deck.
* **🎬 Video Lead**
  * Extracted precision-recall tables and classification metrics.
  * Exported performance plots (ROC curve / Confusion Matrix).
  * Edited and recorded the final 5-minute project showcase video.

  ## ⚙️ Setup and Installation

### Python Version

This project uses **Python 3.13.16**.

### Requirements

All the required Python libraries are listed in the `requirements.txt` file.

The main libraries used in this project are:

- **Pandas** – Data loading and manipulation
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical data visualization
- **Scikit-learn** – Data preprocessing and Logistic Regression model
- **Jupyter Notebook** – Running the project notebook

### Prerequisites

Before running the project, make sure you have installed:

- [Miniconda](https://www.anaconda.com/docs/getting-started/miniconda/install)
- Git

## ▶️ Steps to Run the Project

Follow these commands in the given order.

**Step 1: Clone the GitHub repository**

```bash
git clone https://github.com/STanishqReddy/AI101-MiniProject-CKD-Logistic-Regression.git
```

**Step 2: Navigate to the project directory**

```bash
cd AI101-MiniProject-CKD-Logistic-Regression
```

**Step 3: Create a Conda environment with Python 3.13.16**

```bash
conda create -n ckd-ai101 python=3.13.16
```

**Step 4: Activate the environment**

```bash
conda activate ckd-ai101
```

**Step 5: Install all required dependencies**

```bash
pip install -r requirements.txt
```

**Step 6: Launch Jupyter Notebook**

```bash
jupyter notebook
```

**Step 7: Open and run the project**

1. Open `CKD_Logistic_Regression.ipynb` in Jupyter Notebook.
2. Make sure `Chronic_Kidney_Disease_data.csv` is present in the project directory.
3. Select **Kernel → Restart Kernel and Run All Cells**.
4. Wait for all cells to execute successfully and view the model results and evaluation graphs.

### ✅ Expected Result

After successfully executing the notebook, you should be able to see:

- Dataset exploration and preprocessing results.
- Logistic Regression model training and predictions.
- Model evaluation metrics such as Accuracy, Precision, Recall and F1-score.
- Confusion Matrix and Classification Report.
- ROC Curve and Precision-Recall Curve.

**Note:** Run the notebook from the project directory so that the dataset's relative file path works correctly.

### ✅ Evaluation Visualizations

The following graphs are saved in the results/ directory:

- roc_curve.png
- precision_recall_curve.png

These visualizations help understand the classification performance of the trained model.

### 📊 Project Presentation

Our project presentation contains the problem statement, dataset overview, methodology, model results, team contributions and key learnings.

 Presentation: https://gamma.app/docs/Chronic-Kidney-Disease-prediction-using-Logistic-Regression-gokp4hfrabke7q6

### 🎬 Project Demonstration Video

The demonstration video explains the project workflow, model execution, evaluation results and team contributions.

 Video: [Add accessible video link here]

### 🤖 AI Tools Usage and Disclosure
AI tools were used as supporting resources during the development of this project.

Purpose of AI usage:

- Understanding Python programming and machine learning concepts.
- Getting explanations of pandas and scikit-learn functions.
- Assistance with debugging and improving code.
- Organizing project documentation and presentation content.

#### ⚠️ Verification:

The team reviewed and tested the code and project outputs. Each team member is responsible for understanding their contributions and the overall project workflow.

AI tools were used to support learning and development, not to replace the team's understanding and implementation.
