• A Seasoned Data Scientist, ML Engineer, Cloud Enthusiast, and Passionate Consultant with 5+ years of experience in deriving valuable insights from complex data using statistical and ML tools in large international teams.

• A calm, committed, open-minded, resilient, and focused individual with a will-do-it mindset looking for real-world exciting challenges and collaborations.


**Tech Skills:** 

• Python data science tools: pandas, numpy, scikit-learn, Keras (TensorFlow), PyTorch, Huggingface, DGL, Llammaindex <br>
• Containerization tools: Docker, Kubernetes<br> 
• Cloud technologies: mainly GCP, AWS <br>
• ML Model Web deployment: Streamlit, Fast API <br>
• Git <br>
• And some web developer skills (HTML, CSS, PHP) and languages (SQL, bash, R, basic C++)

I recently started writing [**AI in Gist**](https://krunalgedia.github.io/AI_in_GIST/) blog, which contains the gist of several data science topics in one place: <br>
* Preprocessing: outliers, missing values, encoding, etc, <br>
* Statistics: Distributions, Hypothesis tests, etc <br>
* Classical ML: Classification, Regression, Time Series, Clustering <br>
* Deep Learning: 40+ Computer Vision and NLP/LLM paper; still updating...

# Experience
## Data Scientist at CERN / ETH 
Feb 2018 - Present

• Lead research scientist in the study to statistically reject the null hypothesis at a very high significance level of 6*10-6 to confirm CERN’s 1st independent Higgs boson observation. 

• Implemented an end-to-end data science pipeline (incl. decision tree ensembles & neural network classifiers) for (~TB) datasets on the distributed HPC cluster. 

• Developed a custom Graph Neural Network Node Classification model with node and edge features, MLP as Message Passing function coupled with Multiplicative Attention to reduce ~60% statistical error in our results.

• Developed a custom Quantile Regression Algorithm to regress data quantiles to reduce systematic error in several associated scientific results.


# Projects

## Explainable Breast tumor classification & semantic segmentation
**Computer Vision, Classification, Segmentation**

► Fine-tuned CNN models like VGG19, ResNet, and EfficientNet as well as transformer models like Vision Transformer to achieve an average recall of 0.81 for classification.

► Segmentation using UNet & its variation with attention and residual connection to achieve mIoU of 0.72.

► Deployed final web application with GradCAM insights for both segmentation and classification.

[More info](https://github.com/krunalgedia/BreastTumourClassificationAndSegmentationWithGradCAM)
![image](/assets/malignant.gif)

## 0-shot Breast tumor detection & semantic segmentation
**Computer Vision, Object Detection, Segmentation**

►  0-shot object (tumor) detection using Grounding DINO.

►  Using it as layout input for segmentation by Meta’s Segment Anything Model and achieved mIoU of 0.69.

![image](/assets/sam.png)

## Extract NER/traveler’s data from Switzerland’s SBB train ticket
**NLP, NER, Multi-modal, CV**

► Performed OCR to extract text and bounding box of SBB tickets using Pytesseract and UBIAI, fine-tuned Meta’s multimodal LayoutLM model to achieve an average accuracy of 0.90 for the NER task. 

► Deployed final web application that saves the traveler’s data from the ticket directly to a database.

[More info](https://github.com/krunalgedia/Extract-NER-data-from-the-Switzerland-SBB-train-ticket-using-Document-AI)
![image](/assets/test1.gif)

## Document Classification of Sweden’s Hexagon Annual Report with CI/CD of FastAPI app to AWS using GitHub Actions
**NLP, Classification, Multi-modal, CV**

► Bounding box and text extracted using EasyOCR, fine-tuned Meta’s multimodal LayoutLMv3 to classify Cash flow, Income statement, and Balance sheet from its Annual Report to achieve an F1 score of 0.9.

► Deployed the ML model using FAST API application in AWS cloud through CI/CD of GitHub Actions.

[More info](https://github.com/krunalgedia/Document_classifier_with_GithubCICD_FASTAPI_AWS)
![image](/assets/docclassify2.gif)

## Fully open-source scalable RAG for general application
**LLM, NLP, RAG**

► Scalable RAG built using open source BAAI general embeddings and Mistral-7B LLM available in huggingface in LlamaIndex framework to obtain a Relevancy score of 0.9 against GPT-4’s score of 1.0.

[More info](https://github.com/krunalgedia/Open_Source_Advanced_RAG_LlamaIndex_Huggingface)
![image](/assets/ip2.png)


## Multi-seasonal Multi-variate forecast of Zurich’s 2023 energy consumption
**Time Series, Regression**

► Multi-seasonal multi-variate energy consumption forecast of Zurich city’s energy consumption using also the weather data (temperature, cloud coverage, humidity, precipitation). 

► Implemented Holt-Winter’s model, SARIMA, Hybrid models (Linear regression to extrapolate trend, XGBoost for seasonality), Meta’s Prophet model, and biLSTM models to achieve R2 score of 0.82.

[More info](https://github.com/krunalgedia/ZurichEnergyConsumption_MultivariateForecast)
![image](/assets/lstm_ci%20(1).png)

## Text Classification and Summarization using LLM for Switzerland’s WWF NGO
**LLM, NLP, Summarization**

► Performed advanced prompt engineering on OpenAI GPT models to classify their articles for constructiveness.

► Bundled the final product in a lightweight web application for their internal use.

[More info](https://github.com/krunalgedia/Text-Classification-using-LLM-for-Switzerland-s-WWF-NGO)
![image](/assets/sample%20(1).gif)

## Context and Popularity based Recommendation System for Switzerland’s COOP Online Website
**Recommendation System, Clustering, NLP**

► Extracted contextualized embeddings using pre-trained distil-RoBERTa model for its products, clustered them using K-means, stored centroids in FAISS, and provided visualization of clusters using PCA. 

► Searched the closest cluster to the test item & recommended the cluster items based on their popularity.

[More info](https://github.com/krunalgedia/COOP_contextual_recommender)
![image](/assets/coop_reco.gif)

## N-Dimensional parameterization of efficiency weights of Jet Classifier threshold using Graph Neural Networks
**Graph Neural Network, Classification**

► Trained a custom Graph Neural Network Classification model having both node and edge features using MLP as Message Passing function, Summation as an Aggregation function, and MLP as an Update function coupled with Graph Attention (GATv2) model leading up to ~60% reduction in simulation statistical error in our analysis.

► Work presented in ML4Jets conference 2022 as well as published as a Detector Performance Note by CMS, CERN.

[More info](https://github.com/krunalgedia/jetClassiferEfficiencywithGNN)
![image](/assets/gnn.png)

## Correct simulated data to real data using a new Custom Quantile Regression
**Regression**

► Developed a new Stochastic Morphing Algorithm (Binary Classification + Quantile Regression) to match quantiles of discontinuous data and simulation leading to the reduction of simulation systematic error in several associated scientific measurements.

► Master thesis at CERN, Geneva. Work presented at the SPS Conference 2018.

![image](/assets/QR.png)


## Predict Risk Rating for Prudential Life Insurance Applicants
**Regression, Combined Actuarial Neural Network, SHAP**

► Performed supervised multi-class classification of risk rating using ML models like Logistic Regression, XGBoost, & Combined Actuarial Neural Network to achieve Mathew’s correlation coefficient score 0.63.

► Interpretability of classical ML models provided using the SHAP values.

[More info](https://github.com/krunalgedia/RiskRating_for_Prudential_Life_Insurance_applicants)
![image](/assets/insurance.gif)

## Strategy Consulting for Switzerland’s HR-Tech Startup
**Strategy Consulting**

► Strategy consulting for an HR-tech firm by creating hypotheses for client's concerns, gathering market data, and generating insights to develop an effective strategy to address the client's needs.

► The project was done in association with the Graduate Consulting Club, Zurich.

## European Loan Risk Prediction Model using Google Cloud Vertex AI, Cloud Run, and FAST API 
**Google Cloud Platform, MLPOps, Docker, Regression**

► ETL raw data and trained a neural network classifier model using Vertex AI Custom training and deployed it on 

● Vertex AI Endpoint: Vertex AI Endpoint for online predictions. 

● Cloud Run & Fast API Endpoint: Containerize the FAST API endpoint of the model and deploy the custom docker image to Cloud Run for online predictions.


## Website deployment on Google Cloud Load Balanced Compute Engine and Kubernetes Engine
**Google Cloud, DevOps, Docker, Kubernetes**

► Sole website developer of the website for file conversion and manipulations. (HTML, CSS, PHP, JS) 

Website deployment using

● Google Compute Engine: Global External HTTP-Proxy Load Balancer to direct HTTP traffic to Managed Instance Groups at the backend created from an instance template with a custom machine image to host the website.

● Google Kubernetes Engine: HTTP traffic directed to an Ingress-managed External Load Balancer Service with backend pods maintained by the Deployment Set/Workloads. A custom docker image of the website is built for the containers managed by the Deployment Set.

[More info](https://github.com/krunalgedia/reliablepdf/tree/master/public_html)
![image](/assets/reliablepdf_website.gif)

## On-premise to hybrid cloud (AWS, GCP) migration of a COVID testing web application
**Google Cloud, AWS, Solution Architect, Terraform, DevOps**

► Migrate a real COVID testing web application to a scalable Hybrid cloud environment using AWS and GCP. 

► Used IaaC Terraform for infrastructure set-up, deployed docker container on Google Kubernetes Engine with access to Cloud SQL database, and migrated data from AWS by syncing AWS S3 bucket with the local folder.

► This project was done as a part of the Intensive Cloud Computing Hands-on Training conducted by The Cloud Bootcamp in Dec 2023
[More info](https://github.com/krunalgedia/CovidTestingApp_MigrateOnPrem_To_HybridCloud)
![image](/assets/solution_architecture.png)



# Education

**Degree** | **Institution** | **Duration**
---|---|---|
Ph.D. in Physics | ETH Zürich | November 2018 - Present
Masters in High Energy Physics | ETH Zürich | September 2017 - September 2018
Masters in High Energy Physics | Ecole Polytechnique, Paris | September 2016 - September 2017
Bachelors in Physics (Honours) | Delhi University | July 2013 - July 2016

# Courses & Certifications

**Certification** | **Institution** | **Date**
---|---|---|
AWS Academy ML Foundation Badge | AWS Academy | December 2023
Intensive Cloud Computing Hands-on Training | The Cloud Bootcamp | December 2023 - December 2024
Tableau Essential Training | LinkedIn | February 2023
Advanced SQL for Data Scientists | LinkedIn | January 2023
Professional Cloud Architect | Google Cloud | August 2022 - August 2024
Associate Cloud Engineer | Google Cloud | August 2022 - August 2025
Tensorflow Developer Certificate | TensorFlow | June 2022 - June 2025
Tensorflow: Advanced Technique Specialization | Coursera | June 2022
Advanced Machine Learning | ETH Zürich | January 2020
Computational Statistics with R | ETH Zürich | September 2019


# Scholarships and Honors

|Date|Achievement|
|---|--|
|2016 - 2018 |Paris-Saclay Scholarship for International Masters Student (1 of ~150 international students)|
|2016 - 2017|Full Masters Charpak (French Government) scholarship (1 of ~30 students all over India)      | 
|2016|Rank 136 out of ~10,000 students in the IIT JAM exam (Admission for masters in India)|
|2016|Highest marks in Bachelors in College Department (of ~150 students).|
|2012 - 2013|5-year Inspire scholarship by the Indian Govt. for being in the top 1% in Class 12 in India.|              
