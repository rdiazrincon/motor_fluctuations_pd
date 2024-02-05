# motor_fluctuations_pd
Using LLMs and NLP for the prediction of Parkinson's disease 

- df: Contains all drug info and notes for PD patients
- drug_exposure: Contains information regarding PD drugs for PD patients

- drug_source_value: Contains information from the drug_source_value column in the df dataframe
- dsv_drug_exposure: Contains information from the drug_source_value column in the drug_exposure dataframe

- pd_drug_info: 'med_display_name' from drug_source_value. Subset of drug_source_value that contains the name of PD drugs
- drug_info_drug_source_value: 'med_display_name' from dsv_drug_exposure

- df_pd: Subset of df whose indexes are the same ones in pd_drug_info. Basically is a subset of df that contains patients taking PD medication