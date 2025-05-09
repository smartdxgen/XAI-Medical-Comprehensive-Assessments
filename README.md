Title:
Explainable Artificial Intelligence for Predicting Medical Students’ Performance in Comprehensive Assessments

Introduction:
Comprehensive medical assessments are critical for evaluating clinical proficiency in medical education, yet their administration imposes significant institutional burdens, financial costs, and psychological strain on students. While artificial intelligence (AI) holds transformative potential for predictive analytics, existing models lack the interpretability and reliability required for high-stakes educational decision-making. To address this gap, we developed an interpretable machine learning (ML) framework enhanced with explainable AI (XAI), integrating academic metrics, non-academic attributes, and temporal dynamics to predict student performance transparently.
This retrospective cohort study validated the framework across three universities using two sequential, high-stakes assessments: the Comprehensive Medical Pre-Internship Examination (CMPIE; n = 997 students, two-month prediction horizon) and the Clinical Competence Assessment (CCAs; n = 777 students, one-year horizon). A stacking meta-model combining ensemble techniques (Random Forest, Adaptive Boosting, XGBoost) achieved exceptional discriminative performance, with AUC-ROC values of 0.97 (CMPIEs) and 0.99 (CCAs), alongside precision (0.972, 0.993), recall (0.961, 0.987), and F1-scores (0.966, 0.994). 
Shapley Additive exPlanations (SHAP) provided granular insights into model logic, identifying high-impact courses (e.g., Pediatrics, Neurosurgery) as dominant predictors of success, systemic bottlenecks (e.g., underperformance in Pharmacology among passing students, p < 0.001), and individualized risk profiles (e.g., deficits in Ophthalmology). These insights enable educators to prioritize curriculum reforms, implement early interventions for at-risk students, and deliver personalized feedback. The framework offers institutions a scalable tool to optimize resource allocation and reduce redundant assessments. 

Keywords: Artificial Intelligence, Comprehensive Medical Assessments, Artificial Intelligence in Education, Explainable AI, Machine Learning, Medical Licensing Exams.

code:https://colab.research.google.com/drive/1l_T0EwjQGH_npusUcCcjwSYdxiqGLHIV?usp=sharing

Email: Dehghani.toktam@mail.um.ac.ir;
