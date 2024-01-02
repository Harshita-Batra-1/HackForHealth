# HackForHealth

Project Name - Dr. Tech

Tagline - SHE Builds, SHE Wins!

Problem Statement:

Menstrual hygiene is a pervasive issue affecting girls in South Asia, with over a third of them missing school during their periods due to inadequate access to toilets and pads, coupled with a lack of proper education about menstruation. Globally, 1.2 billion women face challenges related to basic sanitation and hygiene, contributing to period poverty and perpetuating societal stigma. The existing healthcare system does not effectively address the physical and psychological needs of women during their menstrual cycles, further exacerbating the problem.

Solution:

![image](https://github.com/Harshita-Batra-1/HackForHealth/assets/101546087/acaf2d41-a8aa-438d-97e2-d220f5f683ba)

Comprehensive Menstrual Education Programs: Implement educational initiatives to raise awareness about menstruation, hygiene practices, and debunk myths. Collaborate with schools, community centers, and local authorities to integrate comprehensive menstrual education into curricula.

Infrastructure Improvement: Work towards providing better sanitation facilities in schools, including the availability of toilets and sanitary pads. Advocate for policies that address menstrual hygiene in educational institutions.

Technology-Driven Healthcare Platform: Develop a user-friendly platform offering personalized feedback, period cycle tracking, and mood analysis. This platform should facilitate easy access to healthcare information, enabling women to make informed decisions about their well-being.

Telemedicine Services: Integrate telemedicine services into the platform, allowing women to schedule appointments with gynecologists and receive consultations from the comfort of their homes. This ensures privacy and convenience.

Community Engagement through Blogging: Establish a blogging platform for women (Shewinners) to share experiences, knowledge, and insights on menstruation, breaking stereotypes. Encourage open discussions to foster a supportive community that contributes positively to societal change.

Collaboration with Healthcare Providers: Partner with hospitals and healthcare professionals to ensure that women have access to quality healthcare services. Facilitate workshops and awareness programs conducted by healthcare providers to empower women with accurate information.

By addressing these aspects comprehensively, the proposed solution aims to tackle menstrual hygiene issues, break societal taboos, and empower women to take charge of their health and education.

FUTURE SCOPE:
http://www.ijpe-online.com/EN/10.23940/ijpe.23.03.p5.193202 - My research paper on PCOS detection, the model in future can be linked with Period tracker cycle and predict the probability of registered women' suffering from PCOS.


Challenges:
Limited Access to Toilets and Pads: Many girls lack access to essential sanitary facilities and products in schools, hindering their education during menstruation.

Insufficient Menstrual Education: Inadequate information and education about menstruation contribute to the perpetuation of myths, taboos, and stigma surrounding periods.

Lack of Personalized Healthcare: Women often face challenges in seeking personalized healthcare, including period tracking, mood analysis, and access to healthcare professionals.

Social Stigma: Long-standing social stigma surrounding menstruation hinders open discussions and contributes to the reluctance of women in seeking proper healthcare and education.

![logo](https://github.com/Harshita-Batra-1/HackForHealth/assets/101546087/cbd35075-a98d-419d-a8c2-4b46c98234e6)

# Project - DCADPCOS: 
Data-driven Computer Aided Diagnostic system for Polycystic Ovary Syndrome using Machine Learning Techniques 
## About PCOS -
PCOS is a  common hormonal disorder among women of reproductive age. Factors that might play a role include: excess insulin, low-grade inflammation, excess androgen, or it can be hereditary. The signs and symptoms of PCOS may vary woman to woman; some signs of PCOS include irregular periods, excess androgen and polycystic ovaries. 
## Diagnosis Techniques -
There is no test to definitively diagnose PCOS. Disease prediction is a challenging task in healthcare applications. However, the test requires the patient to report back to the hospital or test-centre. Often, due to inconveniences the women patients fail to visit the hospital to get the diagnostic details. Machine learning is an emerging approach that helps in the prediction, diagnosis of a disease.
## Technologies
Python
Pandas, Numpy, Sklearn, Seaborn, Matplotlib, Colab notebook, 
ML Algo's - Random Forest, Support Vector Machine, Logistic Regression & k-cross fold validation
## Methods Used
Machine Learning
Data Visualization
Predictive Modeling
etc.

Dataset - contains 43 features from 541 women, 177 of whom have PCOS. 


Input features - Age (yrs), Weight (Kg), Height(Cm), BMI,
       Blood Group, Pulse rate(bpm), RR (breaths/min), Hb(g/dl),
       Cycle(R/I), Cycle length(days), Marriage Status (Yrs),
       Pregnant(Y/N), No. of abortions, I   beta-HCG(mIU/mL),
       II    beta-HCG(mIU/mL), FSH(mIU/mL), LH(mIU/mL), FSH/LH,
       Hip(inch), Waist(inch), Waist:Hip Ratio, TSH (mIU/L),
       AMH(ng/mL), PRL(ng/mL), Vit D3 (ng/mL), PRG(ng/mL),
       RBS(mg/dl), Weight gain(Y/N), hair growth(Y/N),
       Skin darkening (Y/N), Hair loss(Y/N), Pimples(Y/N),
       Fast food (Y/N), Reg.Exercise(Y/N), BP _Systolic (mmHg),
       BP _Diastolic (mmHg), Follicle No. (L), Follicle No. (R),
       Avg. F size (L) (mm), Avg. F size (R) (mm), Endometrium (mm)

output label - 0 for non pcos & 1 for pcos patient


## System framework-
Data cleaning -> Feature Selection -> Normalization
AUC-ROC curve- 

The Receiver Operator Characteristic (ROC) curve is an evaluation metric for binary classification problems. It is a probability curve that plots the TPR against FPR at various threshold values and essentially separates the ‘signal’ from the ‘noise’. The Area Under the Curve (AUC) is the measure of the ability of a classifier to distinguish between classes and is used as a summary of the ROC curve.
When 0.5<AUC<1, there is a high chance that the classifier will be able to distinguish the positive class values from the negative class values. This is so because the classifier is able to detect more numbers of True positives and True negatives than False negatives and False positives.
ROC Scores -
0.9479166666666666 - for Random forest
0.9452030812324929 - for Logistic regression
This proves that Random Forest has a higher chance (than Logistic Regression) that the classifier will be able to distinguish the positive class values from the negative class values.
## Conclusion
RF classification approach is best for DCADPCOS
