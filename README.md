# Topic Modeling Thesis Titles LDA Python

## 📌 Project Overview
This project applies **Latent Dirichlet Allocation (LDA)** to perform topic modeling on academic-related text data, with the objective of identifying dominant research themes and supporting **decision-making in thesis topic selection and academic supervision**. The analysis focuses on extracting latent topics from Indonesian-language text data using **TF-IDF feature extraction and coherence-based model evaluation**.

## 🎯 Objectives
- Identify dominant thematic patterns in academic-related text data
- Determine the optimal number of topics using quantitative evaluation
- Provide data-driven insights to support thesis topic recommendation and academic planning

## 📊 Dataset
- Source: Twitter (academic-related discussions)
- Keywords: pendidikan kuliah
- Time Range: January 2023 – January 2024
- Language: Indonesian
- Total Documents: 370 text records

## ⚙️ Methodology
1. Data Collection
   - Crawling Twitter data using keyword-based filtering
2. Text Preprocessing
   - Case folding
   - Punctuation removal
   - Tokenization
   - Token normalization
   - Stopword removal
3. Feature Extraction
   - TF-IDF (Term Frequency–Inverse Document Frequency)
4. Topic Modeling
   - Latent Dirichlet Allocation (LDA)
   - Evaluated multiple topic configurations (k = 1–5)
5. Evaluation & Visualization
   - Coherence Score
   - WordCloud per topic
   - pyLDAvis interactive visualization

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Gensim
- pyLDAvis
- Matplotlib / WordCloud

## 🔍 Key Quantitative Insights
- **Optimal number of topics: 4**, achieving the **highest coherence score of 0.9967**, indicating strong semantic consistency between topic keywords.
- **Average coherence score across all topics: 0.5674**, confirming overall model interpretability and topic relevance.
- Extracted topics capture **distinct academic dimensions**, including:
  - Education costs and financial accessibility
  - Academic workload and student performance (IPK)
  - Language and departmental specialization
  - Socioeconomic factors affecting higher education
- High-frequency TF-IDF terms (kuliah, pendidikan, jurusan) consistently appear across dominant topics, validating the relevance of the extracted themes to higher education discourse.
