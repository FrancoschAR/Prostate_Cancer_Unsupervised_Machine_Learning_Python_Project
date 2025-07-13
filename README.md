🧬 TMPRSS2-ERG+ Prostate Cancer Subtype Characterization using miRNA Expression
This project applies unsupervised machine learning techniques to characterize the TMPRSS2–ERG fusion-positive (ERG⁺) molecular subtype of prostate cancer based on miRNA expression profiles. The dataset consists of 498 patient samples, and the goal is to identify ERG-associated molecular signatures and natural groupings in the data without supervision.

🧪 Objectives
Identify molecular patterns associated with the TMPRSS2–ERG fusion subtype in prostate cancer

Use unsupervised clustering to group patients based on miRNA expression

Assign biological labels to clusters to infer subtype-related characteristics

🗃️ Dataset
Source: TCGA PRAD (The Cancer Genome Atlas Prostate Adenocarcinoma project)

Samples: 498 prostate cancer patients

Features: Normalized expression levels of selected miRNAs

🔧 Methodology
📥 1. Data Collection & Wrangling
Loaded miRNA expression and clinical metadata using Pandas and NumPy

📊 2. Exploratory Data Analysis (EDA)
Visualized expression distributions and outliers

Applied PCA for initial dimensionality reduction and variance insight

🧩 3. Unsupervised Clustering
Applied k-means and DBSCAN on reduced feature space

Explored different cluster numbers and evaluated separation visually

🏷️ 4. Cluster Interpretation & Labelling
Mapped clusters back to known ERG fusion status (when available)

Identified enriched features and miRNAs per cluster

📈 Technologies Used
Python 3.x

Pandas, NumPy – Data handling

Matplotlib, Seaborn – Visualization

Scikit-learn – PCA, clustering (k-means, DBSCAN)

📌 Key Results
Clustering revealed distinguishable subgroups in the patient cohort

Some clusters showed strong enrichment for ERG+ expression patterns

Dimension reduction helped expose latent biological structure in the data
