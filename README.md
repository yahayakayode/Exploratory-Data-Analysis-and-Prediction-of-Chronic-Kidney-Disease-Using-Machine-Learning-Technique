## Exploratory Data Analysis and Prediction of Chronic Kidney Disease Using Machine Learning Technique

### Background 
  Chronic kidney disease (CKD) is a type of kidney disease in which there is gradual loss of kidney function over a period of months to years.  
  Initially there are generally no symptoms; later, symptoms may include leg swelling, feeling tired, vomiting, loss of appetite, and confusion, [source](https://en.wikipedia.org/wiki/Chronic_kidney_disease) 

The human kidney is involved in multiple key functions of the body system which Includes:
  - They help to regulate and filter minerals from blood<br>
  - They help to maintain overall fluid balance<br>
  - They help to filter wastes that are generated from medications, food and toxic substances <br>
  - They also help in creating hormones that help produce red blood cells, promote bone health, and regulate blood pressure

#### So what happens if the kidney is damaged?
  Human have two kidneys. If for any reason one doesn't function as expected, the burdens automatically get carried over to the second kidney. If the patient fails to take   adequate and timely measures to improve his/her condition,
  there is every likelihood that both kidneys will fail, leading to acute renal failure. This can be fatal without artificial filtering (dialysis) or a kidney transplant.
  However, this usuaally occur at the advance stage of chronic kidney disease and symptoms will only show up at a severe stage which often call urget medical attendant.

### Project Overview
The objective of this project is to write a standard code that can be used across biomedical data science project. The dataset used for the proof of concept can help physicians to get better understanding of of Chronic Kidney Disease (CKD) using various measurements and biomakers. The dataset used for this project can be found [here](https://archive.ics.uci.edu/dataset/336/chronic+kidney+disease)

Specifically, the project will help physicians have an in-depth understanding of:

- Risk factors for Chronic Kidney Disease
- Potential Chronic Kidney Disease sub-types
  
### Data Dictionary
The dataset contained 400 insranaces and 25 columns as detailed below.

- age - age
- bp - blood pressure
- sg - specific gravity
- al - albumin
- su - sugar
- rbc - red blood cells
- pc - pus cell
- pcc - pus cell clumps
- ba - bacteria
- bgr - blood glucose random
- bu - blood urea
- sc - serum creatinine
- sod - sodium
- pot - potassium
- hemo - hemoglobin
- pcv - packed cell volume
- wc - white blood cell count
- rc - red blood cell count
- htn - hypertension
- dm - diabetes mellitus
- cad - coronary artery disease
- appet - appetite
- pe - pedal edema
- ane - anemia
- classification - class

### Summary
After an in-depth analysis of the dataset, the dataset revealed the following
  1. There is strong correlation between CKD and the following features, which implies that patients who have them is likely to have CKD.
  - **rbc** - Red blood cell <br>
  - **pc** - Pus Cell <br>
  - **bgr** - Blood glucose (strong negative correlation)
  - **bu** - Blood urea (strong negative correlation)
  - **pe** - Pedal edema
  - **ane** - Anemia
  - **dm** - Diabetes
  - **cad** - Coronary artery disease
  - **age** - age
  2. The Logistics regression algorithm model give an accuracy of 95%.
