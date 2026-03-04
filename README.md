ERIP — Emotion Recognition using In-Game Parameters
ERIP is an experimental project focused on emotion recognition based on in-game behavioral parameters.
The repository contains dataset files and source code used to analyze gameplay metrics and build a basic emotion classification model.

This project demonstrates foundational work in data analysis, feature extraction, and applied machine learning within a gaming context.

**Project Overview**

The goal of ERIP is to:
* Collect and process gameplay parameters
* Extract meaningful behavioral features
* Train a classification model to predict emotional states
* Provide a structured foundation for further ML development

The project combines data processing in **Python** with gameplay-related components in **C#**.

**Tech Stack**

* **Python** — Data analysis and modeling
* **C#** — Game-related logic / metric collection
* **CSV Dataset** — Structured input data
* **Git & GitHub** — Version control

**Repository Structure**

```
ERIP/
│
├── DATASET.csv        # Dataset containing gameplay parameters
├── (Python scripts)   # Data processing and ML models
├── (C# files)         # Game-side parameter logic
└── README.md
```

**Installation**
**1. Clone the repository**

```bash
git clone https://github.com/mereken/ERIP.git
cd ERIP
```
**2. (Optional) Create a virtual environment**

```bash
python -m venv venv
venv\Scripts\activate     # Windows
source venv/bin/activate  # macOS/Linux
```

**3. Install dependencies (if applicable)**

```bash
pip install -r requirements.txt
```

**Usage**

1. Review `DATASET.csv` to understand the structure of the data.
2. Run the Python scripts to preprocess the data.
3. Train and evaluate the emotion classification model.
4. Modify and improve the model architecture as needed.


**Future Improvements**

* Implement advanced ML models (Random Forest, SVM, Neural Networks)
* Add data visualization and performance metrics reporting
* Improve feature engineering
* Introduce automated testing or CI/CD
* Integrate real-time emotion detection into gameplay


**Project Purpose**

This project was developed as part of an academic exercise involving Git, data analysis, and machine learning fundamentals.
It serves as a foundation for further research and development in emotion-aware interactive systems.


If you’d like, I can also help you refine it for a stronger portfolio impact — especially if you're positioning this for graduate school or internships.
