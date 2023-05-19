# ML---Cardiovascular-Risk-Prediction
Heart disease is the major cause of morbidity and mortality globally: it accounts for more deaths annually than any other cause. According to the WHO, an estimated 17.9 million people died from heart disease in 2016, representing 31% of all global deaths. Doctors and scientists alike have turned to machine learning (ML) techniques to develop screening tools and this is because of their superiority in pattern recognition and classification as compared to other traditional statistical approaches.

Cardiovascular diseases (CVDs) are the major cause of mortality worldwide. According to WHO, 17.9 million people died from CVDs in 2019, accounting for 32% of all global fatalities. Though CVDs cannot be treated, predicting the risk of the disease and taking the necessary precautions and medications can help to avoid severe symptoms and, in some cases, even death. As a result, it is critical that we accurately predict the risk of heart disease in order to avert as many fatalities as possible. The goal of this project is to develop a classification model that can predict if a patient is at risk of coronary heart disease (CHD) over the period of 10 years, based on demographic, lifestyle, and medical history.

# Problem Statement:
The dataset is from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts. The classification goal is to predict whether the patient has a 10-year risk of future coronary heart disease (CHD). The dataset provides the patients’ information. It includes over 3390 records and 17 attributes.

# EDA Summary:
The dependent variable is unbalanced, with only ~15% of the patients who tested positive for CHD.

All the continuous variables are positively skewed except age (which is almost normally distributed)

Majority of the patients belong to the education level 1, followed by 2, 3, and 4 respectively.

There are more female patients compared to male patients.

Almost half the patients are smokers.

100 patients under the study are undertaking blood pressure medication.

22 patients under the study have experienced a stroke.

1069 patients have hypertension.

87 patients have diabetes.

The risk of CHD is higher for older patients than younger patients.

18%, 11%, 12%, 14% of the patients belonging to the education level 1, 2, 3, 4 respectively were eventually diagnosed with CHD.

Male patients have significantly higher risk of CHD (18%) than female patients (12%)

Patients who smoke have significantly higher risk of CHD (16%) than patients who don't smoke (13%)

Patients who take BP medicines have significantly higher risk of CHD (33%) than other patients (14%)

Patients who had experienced a stroke in their life have significantly higher risk of CHD (45%) than other patients (14%)

Hypertensive patients have significantly higher risk of CHD (23%) than other patients (11%)

Diabetic patients have significantly higher risk of CHD (37%) than other patients (14%)

Above is the correlation heatmap for all the continuous variables in the dataset.

The variables ‘systolic BP’ and ‘diastolic BP’ are highly correlated.

To handle high correlation between two independent variables, we can introduce a new variable ‘pulse_pressure’




# Results
Predicting the risk of coronary heart disease is critical for reducing fatalities caused by this illness. We can avert deaths by taking the required medications and precautions if we can foresee the danger of this sickness ahead of time.

It is critical that the model we develop has a high recall score. It is OK if the model incorrectly identifies a healthy patient as a high risk patient because it will not result in death, but if a high risk patient is incorrectly labelled as healthy, it may result in fatality.

We were able to create a model with a recall of just 0.77 because of lack of data and limitations in computational power availability.

Recall of 0.77 indicates that out of 100 individuals with the illness, our model will be able to classify only 77 as high risk patients, while the remaining 33 will be misclassified.

Future developments must include a strategy to improve the model recall score, enabling us to save even more lives from this disease.

This may include more such studies, and collect more data. Include more people with hypertension, diabetes, BP medication, etc to better understand the effect of these disease on the risk of CHD. Also, with better computational abilities, it will be possible to get the best hyperparameters that yield the best predictions. years.
