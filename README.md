<div align="center">

# Ruthvik Mandapalli

**Data Science & AI · IIIT Dharwad · B.Tech 2025**

*I build things at the intersection of machine learning, biomedical NLP, and computer vision.*

[![Email](https://img.shields.io/badge/ruthvikrudra@gmail.com-333?style=flat-square&logo=gmail&logoColor=white)](mailto:ruthvikrudra@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/ruthvik-mandapalli)
[![Phone](https://img.shields.io/badge/+91--7842842912-333?style=flat-square&logo=whatsapp&logoColor=white)](tel:+917842842912)

</div>

---

I'm a Data Science and AI grad from IIIT Dharwad. Most of my work lives somewhere between healthcare data and ML pipelines — I've spent time building NLP chatbots for clinical domains, classifying facial skin types with CNNs, and co-authoring a paper that got published in a Scopus-indexed journal.

I like problems that are messy in the real world: noisy data, domain-specific language, limited labels. That's where the interesting engineering happens.

---
## Publication

**Impact of Internet Derived Information Obstruction Treatment (IDIOT) Syndrome — A Student Cohort Study**  
*Tuijin Jishu / Journal of Propulsion Technology · Scopus Indexed · Vol. 47, 2026*  
Chava Srinivasa Sai, **Mandapalli Ruthvik**, Ramesh Athe

---

## Education

**B.Tech in Data Science and Artificial Intelligence** · IIIT Dharwad · 2021–2025 · CGPA: 7.13  
**Intermediate** · Aditya IIT Junior College, Kakinada · 2019–2021 · 93.6%

---
## Projects

### Glaucoma Domain Chatbot
A retrieval-based chatbot for answering glaucoma-related clinical questions. Uses **BioBERT** and **BioWordVec** in parallel — returns two answers with confidence scores so you can compare semantic match quality across both embedding spaces. Dataset: 1,679 curated Q&A pairs. Similarity computed via cosine distance on precomputed embeddings (serialized for fast inference).

`Python` `HuggingFace Transformers` `Gensim` `BioBERT` `BioWordVec` `Scikit-learn`

---

### Facial Skin Type Classification
End-to-end ML pipeline for classifying skin as oily, dry, or normal from facial images. Built a hybrid feature extraction approach — HOG descriptors for texture + MobileNetV2 for deep features — then ran classification through ResNet50 and VGG16. Preprocessing chain: Gaussian Blur → Bilateral Filtering → CLAHE.

**ResNet50: 84.16% avg accuracy (±4.58) across 5-fold CV.** Dataset was 166 manually curated images, ages 9–40, captured at 50MP.

`Python` `TensorFlow/Keras` `OpenCV` `ResNet50` `VGG16` `MobileNetV2` `HOG` `Scikit-learn`

---

### IDIOT Syndrome Risk Prediction *(Published)*
ML-driven cohort study on "Internet Derived Information Obstruction Treatment" syndrome — a pattern of excessive health-related searching that drives anxiety. Surveyed 450 technical students, built a Random Forest classifier (68% accuracy) and Multi-linear Regression risk scorer (R² = 0.62, MSE = 1.35). Feature engineering via TF-IDF + StandardScaler normalization. Statistical validation: Cronbach's Alpha 0.83–0.87.

**Published in Tuijin Jishu / Journal of Propulsion Technology (Scopus Indexed), Vol. 47, 2026.**

`Python` `Pandas` `NumPy` `Scikit-learn` `Random Forest` `TF-IDF` `Matplotlib`

---

### LinkedIn UI Clone
A responsive LinkedIn-inspired front-end, built from scratch. Covers navigation, profile panels, content feeds, and dynamic DOM interactions. No frameworks — just vanilla HTML, CSS, and JS.

`HTML` `CSS` `JavaScript` `DOM Manipulation` `Responsive Design`

---

## Skills

**Languages:** Python · C · C++  
**ML/DL:** Random Forest · ResNet50 · VGG16 · MobileNetV2 · CNN architectures · cross-validation  
**NLP:** BioBERT · BioWordVec · Word2Vec · TF-IDF · cosine similarity · Transformers  
**Data:** Pandas · NumPy · Matplotlib  
**Frameworks:** TensorFlow/Keras · PyTorch  
**Web:** HTML · CSS · JavaScript · responsive design  
**CS Fundamentals:** DSA · OOPs · DBMS

---

<div align="center">
<sub>IIIT Dharwad · Dharwad, Karnataka · India</sub>
</div>
