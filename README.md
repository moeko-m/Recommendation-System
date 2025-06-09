# Personalized Recommendation System – RECHEIO (POC)

This project presents a comprehensive approach to building a **Personalized Recommendation System** for **RECHEIO**, a Portuguese wholesale supermarket serving business clients. It addresses two main challenges: creating a meaningful **Customer Segmentation** and designing **Multiple Recommendation Strategies** that can be used across various purchase contexts.

---

## Project Objectives

- Enrich customer datasets to enhance recommendation quality
- Segment customers using clustering techniques to support personalization
- Build multiple recommendation models tailored to business clients
- Support RECHEIO’s digital transformation strategy through AI integration

---

## Methods & Techniques

- Followed the **CRISP-DM framework** for structured analysis
- Applied clustering algorithms:
  - **K-Means** (chosen for best R² value - 6 optimal clusters)
  - **Self-Organizing Maps (SOM)**
  - **DBSCAN**
- Feature engineering for customer behavioral profiling
- Recommendation models built:
  - **Usual Basket / Last Purchase**
  - **Smart Basket Recommendations** using:
    - **Simple Cluster-Based**
    - **Apriori + Association Rules**
    - **Hybrid Collaborative Filtering with Clustering** (User- and Item-based)
    - **Hybrid Collaborative Filtering without Clustering**
  - **Substitute Product Recommender** (RECHEIO-specific alternatives)

---

## Evaluation & Validation

- Recommendation quality validated using **Monte Carlo Cross-Validation**
- Clusters profiled and interpreted without PCA to preserve transparency
- Recommendation scenarios illustrated through **Mock Interface Prototypes**
- Selected by the academic team to **present project results directly to RECHEIO**

---

## Tools & Technologies

- Python  
- pandas, NumPy  
- scikit-learn, mlxtend  
- matplotlib, seaborn   
- Jupyter Notebook

---

## Key Outcomes

- Identified 6 interpretable customer segments using K-Means clustering  
- Provided tailored product recommendations per cluster and user profile  
- Integrated multiple techniques to optimize coverage and diversity  
- Developed realistic mockups of user interfaces for product deployment  
- Proposed a **development and maintenance plan** for sustainable rollout

---

## Note on Data

Due to data protection policies, datasets used in this project are not publicly available. All modeling and evaluations were conducted within a secure environment and used anonymized purchase data.

---

## Developed By

- **Moeko Mitani** [LinkedIn](https://www.linkedin.com/in/moeko-mitani-437205163/)  
- Ana Caleiro
- Duarte Marques
- Oumaima Ben Hfaiedh 
- Sarah Leuthner