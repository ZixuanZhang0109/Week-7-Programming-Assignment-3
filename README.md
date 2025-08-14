# Week-7-Programming-Assignment-3

##  Overview
This repository contains all deliverables for **Week 7 Programming Assignment 3**, including:
- **Research Report** (PDF)
- **Jupyter Notebook (.ipynb)**
- **HTML export of the notebook**

The project demonstrates the full workflow of **problem understanding, data preparation, research design, programming, and exposition**, following the provided grading rubric.

---

##  Repository Structure
```
├── README.md                           # Project documentation
├── Week 7 Programming Assignment 3.pdf # Research report (PDF)
├── Week 7 Programming Assignment 3.ipynb # Jupyter Notebook with code and outputs
├── Week 7 Programming Assignment 3.html # HTML export of the notebook
├── requirements.txt                    # Python dependencies
```

---

## Problem Description
The goal of this assignment is to **analyze financial market data** using Python, applying a well-structured data pipeline, conducting exploratory and statistical analysis, and presenting findings in a research report.  
Key aspects include:
- Understanding the problem and research question.
- Preparing and cleaning the dataset.
- Designing the research and analysis methodology.
- Implementing the solution in Python.
- Documenting the process and results.

---

## Data Preparation & Pipeline
- Data loading using **Yahoo Finance API** (`yfinance`).
- Cleaning and formatting data for analysis.
- Calculating derived metrics for evaluation.
- Visualizing results using charts.

---

## Research Design
- Define analysis objectives and evaluation criteria.
- Collect historical asset price data.
- Evaluate trading strategies based on performance metrics.
- Compare against a buy-and-hold benchmark.

---

## Programming
The **Jupyter Notebook** (`.ipynb`) includes:
1. **Imports & Environment Setup**  
   Libraries: `pandas`, `numpy`, `matplotlib`, `yfinance`.
2. **Data Loading**  
   Fetching price data from Yahoo Finance.
3. **Data Cleaning**  
   Ensuring correct data types and removing missing values.
4. **Exploratory Data Analysis (EDA)**  
   Time series plots, performance summaries.
5. **Strategy Evaluation**  
   Comparing portfolio strategy vs. benchmark.
6. **Visualization**  
   Graphs illustrating performance.

---

## How to Run
### **Option 1 – Run in Jupyter Notebook**
1. Clone this repository:
   ```bash
   git clone <REPO_URL>.git
   cd Week-7-Programming-Assignment-3
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook:
   ```bash
   jupyter notebook "Week 7 Programming Assignment 3.ipynb"
   ```
4. Run cells sequentially to reproduce results.

### **Option 2 – View HTML Export**
Simply open `Week 7 Programming Assignment 3.html` in a browser to view a static version of the notebook.

---

## Testing the Program
- Ensure Python 3.x is installed.
- Install packages with:
  ```bash
  pip install -r requirements.txt
  ```
- Run all notebook cells and verify outputs match the HTML/PDF report.

---

## Research Report (PDF)
The `Week 7 Programming Assignment 3.pdf` contains:
- Problem description.
- Data preparation details.
- Research design explanation.
- Key results and discussion.
- Conclusion and future work suggestions.

---

## Use of AI Assistants
During the completion of this assignment:
- AI tools (such as ChatGPT) were used **for structuring the README, generating documentation templates, and verifying Python library dependencies**.
- All code was reviewed and executed by the author to ensure correctness and understanding.
- AI-generated suggestions were adapted and validated against the dataset.

---

