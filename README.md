# Data-Ingestion-and-Acquisition
This repository has been created for the academic assignment.

The data has been read from URL - "https://raw.githubusercontent.com/nthammadi-uncc/DataAcquisition/main/Data/patient_data.csv" into the dataframe and has been dumped to
local MySQL server using SQLAlchemy.

**Visualization** of the data is done using plotly and tableau. The public link for the tableau viz:
1. https://public.tableau.com/views/VisualizationforPatientsData/RatioofDeathbyNaturalandUnnaturalforeachstate?:language=en-US&:display_count=n&:origin=viz_share_link
2. https://public.tableau.com/views/VisualizationforPatientsData/State-wiseaverageage?:language=en-US&:display_count=n&:origin=viz_share_link

Exploratory Data analysis, finding suitable categorical features using Chi-Square and classification techniques - Gradient Boosting, Random Forest, Decision Tree and Logistic Regression has been applied on the dummy patient dataset.

## Running the Notebook
The notebook requires certain Python packages. It can be installed by the following command:
```
pip install -r requirements.txt
```
