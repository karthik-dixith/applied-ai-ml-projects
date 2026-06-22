# Applied AI & Machine Learning — Coursework Projects

Hands-on machine learning, deep learning, and NLP notebooks developed across the AI/ML coursework of my M.Eng. in Sustainable Technology and Management (SRH Hochschule Berlin, Industry 4.0 focus). Covers supervised deep learning, unsupervised learning, transformer-based NLP, and dimensionality reduction — all implemented in Python.

## Notebooks

| Notebook | Topic | Stack |
|---|---|---|
| [`Transformers.ipynb`](Transformers.ipynb) | **Zero-shot text classification** of customer reviews using `facebook/bart-large-mnli` + Hugging Face sentiment pipeline + TF-IDF / KMeans thematic clustering | Hugging Face Transformers, scikit-learn, pandas |
| [`CNN.ipynb`](CNN.ipynb) | **Convolutional Neural Network** for multi-class human-emotion image classification; full train → save → reload → infer pipeline | TensorFlow / Keras |
| [`ANN.ipynb`](ANN.ipynb) | **Feed-forward Artificial Neural Network** on the same emotion dataset; baseline for the CNN comparison | TensorFlow / Keras |
| [`Clustering.ipynb`](Clustering.ipynb) | **Unsupervised clustering** — KMeans, DBSCAN, MeanShift, and agglomerative hierarchical clustering compared on the same dataset | scikit-learn, SciPy |
| [`Dimensionality_Reduction.ipynb`](Dimensionality_Reduction.ipynb) | **PCA** with `StandardScaler` preprocessing and 3D visualization of latent structure | scikit-learn, matplotlib, plotly |
| [`SEM.ipynb`](SEM.ipynb) | **Structural Equation Modeling** for statistical analysis | semopy, graphviz |

## Tech stack

Python · Hugging Face Transformers · TensorFlow / Keras · scikit-learn · SciPy · pandas · NumPy · matplotlib · plotly · semopy

## Highlighted project — zero-shot classification

The `Transformers.ipynb` notebook deploys `facebook/bart-large-mnli` to classify 150 customer reviews across 7 business categories (product quality, delivery, price, customer service, usability, food, packaging) **without any labeled training data**, then augments each record with sentiment polarity and groups results into 5 thematic clusters using TF-IDF + KMeans. The pattern — define candidate labels, classify intent, post-process, return structured output — is directly applicable to skill/intent routing in conversational AI systems.

---

**Karthik Dixith Kumar** · M.Eng. Sustainable Technology and Management (Industry 4.0 + AI/ML), SRH Hochschule Berlin · Oracle Certified AI Foundations Associate · Berlin, Germany
