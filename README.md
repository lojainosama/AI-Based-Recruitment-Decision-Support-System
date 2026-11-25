# AI-Based-Recruitment-Decision-Support-System
The increasing reliance on online recruitment platforms coupled with the adoption of AI technologies has highlighted the critical need for efficient resume similarity methods.However large volume of resumes, inconsistent CV
formats, and the difficulty of manually identifying the most suitable
candidates for specific job roles so we designe automate resume screening
and improve candidate-job matching accuracy. The system integrates
multiple resume datasets collected from PDF and text-based sources, along
with structured job description datasets. Extensive preprocessing was
performed, including PDF text extraction using OCR, text cleaning,
duplicate removal, experience years extraction, and normalization of job
titles into four major job groups: Software Engineering, Data & AI, IT
Systems, and Infrastructure & Security. To measure semantic similarity
between resumes and job descriptions, the system uses the
SentenceTransformer model based on all-MiniLM-L6-v2 embeddings ,
NLP and MPNET with cosine similarity scoring. A ranking mechanism was
developed to recommend the top candidates for each job role, supported by
explanation labels such as semantic similarity level and experience strength.
Results showed strong recommendation performance, achieving high
Precision@5, Recall@5, and Mean Reciprocal Rank (MRR), demonstrating
that semantic embedding-based ranking significantly improves recruitment
decision support compared to manual filtering. The proposed system offers a
scalable, efficient, and explainable solution for intelligent hiring processes.
dataset CV: https://www.kaggle.com/datasets/haidermaseeh/resume-dataset هاhttps://www.kaggle.com/datasets/haidermaseeh/resume-dataset https://www.kaggle.com/datasets/muqaddasejaz/resume-cv-skills-extraction-dataset https://www.kaggle.com/datasets/snehaanbhawal/resume-dataset https://www.kaggle.com/datasets/souptikghosh/resume-dataset
DATASET OF JOB DESCRIPTION: https://www.kaggle.com/datasets/souptikghosh/resume-dataset 
