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
  2. The model give a good prediction performance of 95% accuracy
