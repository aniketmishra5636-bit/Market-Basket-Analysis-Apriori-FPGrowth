#  Market Basket Analysis (Apriori & FP-Growth)

##  Project Overview
This project focuses on **Association Rule Learning** to analyze retail transaction data. The goal is to identify hidden relationships between products, commonly known as **Market Basket Analysis**. By understanding what customers buy together, businesses can optimize product placement and marketing strategies.

##  Algorithms Implemented
I have implemented and compared two major algorithms to find frequent itemsets:
* **Apriori Algorithm:** A classic iterative approach that uses a bottom-up search logic.
* **FP-Growth (Frequent Pattern Growth):** A faster, tree-based structure that finds patterns efficiently without candidate generation.

##  Key Metrics Explained
To evaluate the strength of the association rules, the following metrics were used:
* **Support:** Indicates how frequently an itemset appears in the dataset.
* **Confidence:** Measures the likelihood that item B is purchased when item A is purchased.
* **Lift:** Determines the strength of the association (Lift > 1 indicates a strong relationship).

##  Tech Stack
* **Language:** Python 
* **Libraries:** Pandas, Mlxtend, NumPy
* **Environment:** Jupyter Notebook

##  Business Impact
* **Product Placement:** Strategic positioning of related items.
* **Combo Offers:** Designing attractive bundles based on purchase history.
* **Recommendation Engines:** Suggesting "Frequently Bought Together" items.
**Developed by**
aniketmishra5636-bit
