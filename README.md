**AI-Powered Music Recommender System **

This project presents a hybrid AI-driven music recommender system that combines neural collaborative filtering (NCF) and content-based filtering to deliver personalized song recommendations using Spotify listening data and audio features. The system leverages deep learning, feature engineering, and clustering techniques while also addressing the cold-start problem with explainable AI methods.


**Project Highlights**

1. Built a hybrid recommender system integrating NCF (deep learning) and content-based filtering.

2. Engineered novel audio features including energy-loudness ratio, dance valence, and mood score.

3. Applied SHAP (SHapley Additive exPlanations) for model explainability and user insight visualization.

4. Tackled the cold-start problem using cosine similarity on audio feature embeddings.

5. Conducted comprehensive EDA, feature engineering, and clustering (KMeans, UMAP) to explore song patterns and listener preferences.


**Tech Stack**

**1.** **Languages:** Python

**2.** **Libraries:** TensorFlow, Keras, Scikit-learn, SHAP, Matplotlib, Seaborn, UMAP

**3.** **Techniques:** Neural Collaborative Filtering, Autoencoder, Content-based filtering, Clustering, SHAP explanations
   

**Project Structure**

**1. datasets:** Raw and processed Spotify data

**2. src:** Python scripts for model building and evaluation


**Key Results**

1. Hybrid model improved personalization accuracy and reduced overfitting.

2. SHAP helped interpret model predictions, enhancing transparency.

3. Clustering revealed meaningful patterns in user listening behaviors and song audio features.



