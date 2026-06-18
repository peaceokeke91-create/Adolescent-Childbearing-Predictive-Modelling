# Adolescent-Childbearing-Predictive-Modelling
Machine learning prediction models for adolescent childbearing in Nigeria using 2018 and 2024 NDHS data with temporal external validation and SHAP analysis.

Analysis code for:

"Adolescent Childbearing in Nigeria: A Predictive Modelling Analysis of Socioeconomic and Geographic Factors with Temporal Validation"

Peace Chinenye Okeke,  Precious Ifeoma Ugwu, and Ukamaka Ugwu

Overview:

This repository contains the complete Python analysis code used to produce all results, tables, and figures in the above named manuscript.

Data Source and Access:

This analysis uses the 2018 and 2024 Nigeria Demographic and Health Survey (NDHS) Individual Recode file. The data are not included in this repository per the DHS Program data use agreement.

To reproduce this analysis:

1. Register at https://dhsprogram.com
2. Submit a data access request for the 2018 and 2024 Nigeria DHS
3. Download the Individual Recode file (.dta format)
4. Place the file in your working directory
5. Update the data_path variable in the notebook to point to your file

Data Access Authorization: AuthLetter_235023



Usage:

1. Clone this repository:
   
   git clone https://github.com/peaceokeke91-create/Adolescent-Childbearing-Predictive-Modelling.git
   
2. Install dependencies:
   
   pip install -r requirements.txt
   
3. Obtain the NDHS data file from the DHS Program (see above)
4. Open the Jupyter notebook:
   
   jupyter notebook "ADOLESCENT PREDICTIVE MODELLING(2).ipynb"
   
5. Update the data_path variable in Cell (2) to point to your NDHS .dta file
6. Run all cells to reproduce the analysis




Repository Contents:

Data preprocessing scripts
Feature engineering pipeline
Model training scripts
Temporal external validation scripts
SHAP analysis code
Figure and table generation scripts
Reproducibility
Analyses were conducted using Python 3.11.


License

This code is licensed under the MIT License. See the LICENSE file for details.



Citation

If you use this code in your research, please cite the associated manuscript.

Contact

Peace Chinenye Okeke
Email: peaceokeke91@gmail.com
ORCID: 0009-0006-2943-113X
