# COVID-19-Data-Product

Data analysis, visualization, and prediction on COVID-19 medical data.

## Description

In this project we analyzed COVID-19 medical data and developed a logistic regression model using Python, Scikit Learn, and Jupyter Notebook to determine the likelihood of a patient getting hospitalized, getting admitted to an ICU (Intensive Care Unit), recovering, or dying.

## Data Source

This project analyises a confidential dataset provided by [Vodafone Group Plc](https://www.vodafone.com/), it contains 322 entries and 121 columns that can be structured in 11 groups.

#### Demographic and Clinical Characteristics

Age, Sex, Occupation, Smoker, Active Smoker, Temperature, Symptoms Onset to Medical Visit.

#### Symptoms Shown

Coughing, Fatigue, Myalgia or Arthralgia, Dyspnea, Diarrhoea, Headache, Ansomia, Dysgeusia, Sore Throat, Blocked Nose, Nausea or Vomiting, Sputum Production, Chills, Asthenia, Chest Pain, Disorientation, Conjunctivitis, Hemoptysis, Cutaneous Lesions.

#### Comorbidities

Any, Hypertension, Diabetes, Obesity, Dyslipidemia, Cancer, Chronic Kidney Disease, Heart Disease, Autoimmune Disease, Chronic Pulmonary, Depression, Arrhythmia, Thyroid Alterations, Asthma, Liver Disease,  Cerebrovascular Disease, Alzheimer, Bronchiectasis, Fibromyalgia, Anemia, Arthritis, HIV, Syphilis, Tuberculosis.

#### Exams Done

Auscultatory Alterations, Tachypnoea, Tachycardia, Pharyngitis, Cutaneous Lesions, Tonsillopharyngitis, Oxygen Saturation.

#### X-Ray

Bilateral Pulmonary Infiltrates, Interstitial/Ground Glass Pattern, Lobar Pulmonary Infiltrate, Pneumothorax, Pleural Effusion, Bilateral Pulmonary Infiltrates.

#### CT

Interstitial/Ground Glass Pattern, Pulmonary Thromboembolism, Emphysema, Lobar Pulmonary Infiltrates, Pneumonia, Atelectasis, Pleural Effusion. 

#### Laboratory Done

Leukocytes, Lymphocytes, Platelets, Hemoglobin, C-Reactive Protein, Procalcitonin, Lactate Dehydrogenase, Aminotransferase Aspartate, Alanine aminotransferase, Total Bilirubin, Creatine Kinase, Creatine, D-Dimer, Sodium, Potassium. 

#### Complications

Any, Pneumonia, Adult Respiratory Distress Syndrome, Renal Failure, Pulmonary Thromboembolism, Sepsis, Multiorgan Failure, Electrolyte Alterations, Hematologic Alterations, Lung Cancer.

#### Treatments

Hydroxychloroquine, Azithromycin, Lopinavir/Ritonavir, Oxygen Therapy, Intravenous Antibiotics, Glucocorticoids, Tocilizumab, Cephalosporins, Low Molecular Weight Heparin, Remdesivir, Amoxicillin, Interferon, Rituximab, Darunavir, Entecavir.

#### Infected By

Any Cohabitant, Any Work Colleague, Any Contact Person in Other Settings.

#### Outcome

Death, ICU Admission, Hospitalization, Recovered, Monitored at Home, Phone Follow Up, Work Disability. 

## Results

| Model  | Accuracy |
| ------------- | ------------- |
| Deaths  | 95% |
| ICU Admission  | 83% |
| Hospitalization  | 85% |
| Recovered  | 66% |

## Technologies Used

* Python 
* Scikit-Learn
* Numpy
* Matplotlib
* Pandas
* Jupyter Notebook

## Contributors

* [Kennedy Nguyen](https://github.com/TypicalEDIt)
* [Fredi Garcia](https://github.com/f-garci)
* [John Grover Rodriguez](https://www.linkedin.com/in/jgrover9841/)
* [Abubakir Siedahmed](https://www.linkedin.com/in/abubakir-siedahmed-684ba3170/)


