# data-cleaning
Code to clean up data to hand over to researchers for analysis

The code will be fine grained and modular, meaning that all properties are cleaned by a separate piece of code.
They can be combined by data source into files, e.g. several columns of one table can be cleaned by several functions from the same file.

For now, without code to do so, here is a short list of variables with ranges outside of which data has been deemed an outlier in previous studies:

- Lengte: 100-250 cm
- Gewicht: 30-250 kg
- BMI: 15-65 kg/m2
- SBP: 60-250 mmHg
- Total cholesterol: 1.29-12.95 mmol/L
- HDL cholesterol: 0.6-3.5 mmol/L
- eGFR: 0-400 ml/min/1,73m2
- Glucose nuchter: 1.5-50mmol/L
- Glucose niet nuchter: 1.5-50mmol/L 
- DBP: 40-180 mmHg
- LDL: 0.9-9 mmol/L
- ACR: 0-1000 mg/mmol
- Triglyceride: 0.2-10 mmol/L


This has been made by Jonne ter Braake, Janet Kist, Micha Jongenjan, Camila Caram-Deelder et al.
