# Dimentionality_Reduction_StudentGradeAnalysis_TMP

## Author:
**Prithujit Ghosh**
---

## 📌 Project Overview & Problem Statement
In educational environments, raw grade data often hides complex relationships between subjects and student learning behaviors. This project applies **Principal Component Analysis (PCA)** and **t-SNE (t-distributed Stochastic Neighbor Embedding)** to a dataset of 100 students across 8 subjects:
* **STEM:** Math, Science, Computer Science (CS)
* **Humanities:** English, History, Spanish
* **Creative/Physical:** Band, Physical Education (PhysEd)

**The Objective:** To reduce the 8-dimensional grade space into a 2D visualization to identify "Academic Archetypes," understand subject difficulty correlations, and provide data-driven recommendations for curriculum improvement.

---

## 📊 Summary of Findings

### 1. PCA: Global Trends & Interpretability
* **PC1 (Academic Core):** Captures proficiency in traditional subjects like Math and English. It serves as a primary metric for identifying "at-risk" students.
* **PC2 (Specialized Proficiency):** Separates students based on their performance in Band and Physical Education, distinguishing between "academic-heavy" and "all-rounder" profiles.

### 2. t-SNE: Local Groupings & Archetypes
* **Cluster Identification:** t-SNE successfully revealed hidden clusters of students with nearly identical performance profiles that were not visible in raw tables.
* **Specialist Outliers:** Small, isolated groups were identified at the periphery of the plot, likely representing students with highly specialized talents (e.g., excelling in CS but struggling in Humanities).

---

## 💡 Actionable Recommendations
## 🎯 Subgroup Insights

### 1. Academic Core Cluster
**Profile**: Strong in math, science, CS, languages, and history.  
**Actionable Insight**:  
- Encourage advanced coursework or enrichment programs (STEM clubs, debate, coding competitions).  
- Provide opportunities for interdisciplinary projects to keep them challenged and engaged.  

### 2. Creative/Physical Cluster
**Profile**: High proficiency in music, arts, and physical education, less emphasis on traditional academics.  
**Actionable Insight**:  
- Offer leadership roles in extracurriculars (school band, sports teams).  
- Integrate creative/kinesthetic learning methods into academic subjects to leverage their strengths.  
- Consider pathways in performing arts, athletics, or event management.  

### 3. Balanced Cluster
**Profile**: Competent in both academics and creative/physical domains.  
**Actionable Insight**:  
- Encourage exploration — these students may benefit from exposure to diverse subjects before specialization.  
- Provide mentorship to help them identify areas of passion and potential career direction.  

### 4. Lower‑Performance Cluster
**Profile**: Struggling in both traditional academics and creative/physical subjects.  
**Actionable Insight**:  
- Identify underlying challenges (study habits, motivation, external factors).  
- Provide targeted support: tutoring, counseling, or personalized learning plans.  
- Focus on building confidence through small, achievable goals.  

---

## 📂 Repository Structure
* `PCA_Implementation.ipynb`: Detailed notebook covering feature scaling and PCA.
* `t_SNE_Implementation.ipynb`: Exploration of t-SNE.
* `student_grades.csv`: The original dataset containing 100 student records.
* `Dimensionality_Reduction.pptx`: A summary presentation.
* `README.md`: Project documentation.

---

## 🛠️ How to Run
1. Clone the repository: `git clone https://github.com/Prithujit-Ghosh/Dimensionality_Reduction_TMP.git`
2. Install dependencies: `pip install pandas matplotlib seaborn scikit-learn`
3. Run the Jupyter Notebooks to reproduce the visualizations.
