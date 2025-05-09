Pattern Mining Project - FOODmart 2025
======================================

This project focuses on pattern mining from supermarket transactions in the Foodmart_2025_DM.csv dataset. It is part of the coursework for the Pattern Discovery class and involves mining frequent itemsets and association rules globally and locally (by store type).

Project Goals
-------------
- Discover global patterns: find frequent itemsets and associations across all stores.
- Discover local/specific patterns: explore differences in product associations between store types.
- Critically analyze and visualize results using association rule metrics (support, confidence, lift, etc.).
- Use semantic labeling (e.g., healthy vs. unhealthy products) to find meaningful insights.

Project Structure
-----------------
PD09/
├── PD_202425_P1.ipynb            # Main Jupyter Notebook (analysis, code, discussion)
├── PD_202425_P1.html             # HTML version of the notebook with outputs
├── Foodmart_2025_DM.csv          # Provided dataset
├── requirements.txt              # Python packages for the project
└── README.txt                    # Project description (this file)

Setup Instructions
------------------
We recommend using Conda to manage the environment.

1. Create and activate a conda environment:

   conda create -n pattern_mining_env python=3.9
   conda activate pattern_mining_env

2. Install dependencies:

   pip install -r requirements.txt

Important: Use mlxtend==0.19 to avoid compatibility issues with frequent pattern mining functions.

Used Libraries
--------------
- pandas, numpy – data manipulation
- mlxtend – frequent itemset mining (Apriori, FP-Growth)
- matplotlib, seaborn, plotly – visualizations
- networkx – graph-based visualization of associations

Techniques Used
---------------
- Frequent Itemset Mining: using apriori and/or fpgrowth
- Association Rules: with support, confidence, lift
- Semantic Grouping: labeling products (e.g., healthy vs unhealthy)
- Store-Type Comparison: analyzing differences across store types

Notes
-----
- Only relevant code and results are presented in the notebook.
- Discussions and visualizations are included for clarity and insight.
- The final notebook is provided both as .ipynb and .html with full outputs.


License
-------
This project is academic work. All rights reserved to the authors.
