# The Accuracy and Transparency of EBM and Random Forests

## Notebooks
All of the results in our project report are calculated and presented in the notebooks: Correlation_Analysis.ipynb and Machine_Learning_Project_Group_40.ipynb. 
* Correlation_Analysis: Contains a correlation analysis to find out which features have the highest correlation.
* Machine_Learning_Project_Group_40: Presents the accuracy and transparency of the EBM and random forest models.
To run the notebooks one has to be logged in with a Google account.

## Installation

By using an iPython notebook most of the necessary installation are built in. The exception is interpret, which is used in Machine_Learning_Project_Group_40.ipynb, but it is added in the notebook through the following code:

```bash
!pip install interpret
```
## Structure

All sections of code in Machine_Learning_Project_Group_40.ipynb is marked with one of the following: 'General', 'EBM' or 'Random forest'. Below is a brief overview some of the elements included in each section.
* General
	* Imports and installations
	* Retrieval and splittingof data
* EBM
	* Training with default and RSCV hyperparameters
	* Accuracy of model
	* Global explanations and relative importance of attributes
	* Local explanations
* Random Forest
	* Training with default and RSCV hyperparameters
	* Accuracy of model
	* Relative importance of attributes



## Usage

Run all to get all results in both notebooks. If the random forest and EBM model are run separately in Machine_Learning_Project_Group_40.ipynb, all 'General' code should be run before 'EBM' and 'Random forest' code, since they are dependent on code from 'General'.
