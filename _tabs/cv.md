---
layout: page
icon: fas fa-file-alt
order: 2
title: "CV"
permalink: /cv/
---

## Xiaoyi (Alleria) Gu's CV

## EDUCATION
- M.S., Applied Data Science | University of Southern California, Los Angeles, CA, U.S. (_Dec 2023_)					  
- B.S., Information Management and Information Systems | Beijing Foreign Studies University, Beijing, China (_Jun 2021_)

*Awards: National Scholarship (top 0.2%), Merit Student, Beijing Outstanding Graduates*

## PROFESSIONAL EXPERIENCE
**Machine Learning Engineer (Generative AI, Search Engineering, RAG) @ SylphAI Inc. (_Apr 2024 - Aug 2024_)**
- Developed a GenAI chatbot search engine **(RAG)** by embedding texts, indexing, creating the retriever system, ranking and generating candidate-specific answers.
- Built, trained and fine-tuned **deep learning** classifiers using PyTorch.
- Created high-quality data labels utilizing **Large Language Models**(Mistral-7B, GPT-4, and Gemini) with few-shot Prompt Engineering and designed an efficient ETL pipeline to manage data on AWS RDS.
- Implemented agent framework from research with function calls and contributed to an open-source **LLM library** AdalFlow (GitHub 1k+ stars).

**Data Scientist Intern @ Adobe Inc. (_May 2023 – Aug 2023_)**
- Spearheaded **cancellation analysis** and identify cancellation patterns, optimizing the user journey.
- Innovated a product **marketing strategy** with an estimated 10% conversion rate improvement and an $8.3M annual recurring revenue (ARR) lift by deep diving on 5+ metrics using 5M+ data to support decision-making.
- Built a **Logistic Regression** and an **XGBoost model** with feature engineering to analyze the important and significant factors that lead to cancellation on 3M data processed by SQL.

**Data Scientist Intern @ HireBeat Inc. (_May 2022 – Jul 2022_)**
- Led a project to preprocess candidates’ resumes by extracting key qualifications, and vectorized text features with **TF-IDF**.
- Implemented an end-to-end pipeline for classifying resumes by ensembling **Neural Networks, Tree-Based models, Naive Bayes**, and **SVM** with tuned hyperparameters, boosting accuracy by 15% compared to the KNN baseline.

## Projects
### Los Angeles Restaurant Heath Inspection and Recommendation
[Video](https://www.youtube.com/watch?v=oiM0AO_HvLQ)
- Led a team as the **Project Manager**. Developed a system identifying risky restaurants collaborating closely with stakeholders using **Agile**. Crawled 9K+ restaurants from Yelp, and applied Record Linkage to integrate Yelp records with LA Open Data.
- Established **risk predicting models (SVM/Random Forest/XGBoost)** with 84% accuracy and 0.7 roc_auc, applied clustering models (PCA/KMeans) and topic modeling to find insights from restaurant groups and Yelp reviews.
- Designed a restaurant recommender. Explored a weighted model with Collaborative Filtering and XGBoost and researched Graph embedding for recommendation on the Yelp dataset with 0.977 RMSE.
![LA restaurant APP](img/la_res.jpeg)

### Draft-Based DOTA2 Winning Camp Prediction
[Article](https://medium.com/@xiaoyigu/data-science-for-dota2-part-1-data-collection-55d7d7cb07c1)
- Predicted the winning camps of the video game DOTA2 with 16K+ matches crawled by Selenium and Scrapy.
- Researched on DOTA2 winning prediction papers and applied **HIN2Vec graph embedding** to transform the hero relationships into features. Conducted feature engineering and built a set of predictors such as XGBoost (F1 Score 0.64).
![DOTA2](https://miro.medium.com/v2/resize:fit:4800/format:webp/1*5jntDOf_Lt2lSxMaK0tOAA.jpeg)

### Job Recommendation System Based on Knowledge Graph
[Video](https://www.youtube.com/watch?v=EczX-wm0GMc)
- Extracted required skills and diplomas from 10K+ job descriptions with spaCy and fine-tuned BERT models (F1 score 0.66/0.88), applied **entity resolution** to establish a knowledge graph connected with Neo4j. Applied TF-IDF to vectorize features and constructed job category classifiers to classify each job into 15 categories.
- **Deployed web application** with Knowledge Graph to facilitate job search. Utilized similarity metrics to recommend jobs and suggest skills for users to improve.
![KG APP](img/kg.jpeg)


