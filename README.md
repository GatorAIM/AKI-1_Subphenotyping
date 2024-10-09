# Project Description:
Acute Kidney Injury (AKI) can harm multiple organ systems, including the heart, brain, and the immune system. Stage 1 AKI (AKI-1), though mild in presentation, represents a critical subset of AKI patients with distinct outcomes, warranting further investigation into its subphenotypes. In this study, we conducted a clustering analysis on 7-day serum creatinine (SCr) trajectories of AKI-1 patients from eight academic hospitals, revealing three distinct subphenotypes. This repository contains all the code used for analysis. All patient privacy and hospital-related information has been masked.
![image](https://github.com/user-attachments/assets/e4082109-2a24-488f-9039-bb9bab2f7535)


# Requirements:
collections  
lifelines  
matplotlib  
mpl_toolkits  
multiprocessing  
nbimporter  
numpy  
pandas  
pyckmeans  
pylab  
scipy  
seaborn  
sklearn  
string  
time  
tqdm  
warnings  

# Notebook Description
1. A_Label_AKI_Onsets_maksed.ipynb: Compute SCr baseline for each encounter by 3 steps, staging AKI by KDIGO SCr definitions.
2. B_Data_Preprocessing_masked.ipynb: Inclusion and exclusion of patients according to demographics, procedure history, comorbidities and SCr measurements.
3. C_Clustering_Features_masked.ipynb: Extract 4 critical SCr trajectories features and apply consensus k-means to them.
4. D_Matching_masked.ipynb: Match each AKI-1 patient with a similar non-AKI patient by a 3-step framework.
5. E_Outcome_Analysis_masked.ipynb: Analyse demographics, comorbidities, lab test results, outcomes (in-hospital, 30-day and 1-year mortality, 1-year dialysis and RRT rates and CKD incidence).
![image](https://github.com/user-attachments/assets/b049bc92-4599-4030-b219-8d4333bcaf9c)


# Contact
If you have any questions or suggestions please feel free to open an issue on this repo or email me directly at lideyi@ufl.edu.
