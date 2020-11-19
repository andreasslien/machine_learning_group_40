# The Accuracy and Transparency of EBM and Random Forests

All of the results in our project report are calculated and presented in this notebook. 
## Installation

By using an iPython notebook most of the necessary installation are built in. The exception is interpret, but it is added by in the notebook us through:

```bash
!pip install interpret
```
## Structure

All sections of code is marked with one of the following: 'General', 'EBM' or 'Random forest'. Below is a brief overview some of the elements included in each section.
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

Run all to get all results regarding accuracy and transparency. If they are run separately, all 'General' code should be run before 'EBM' and 'Random forest', since they are dependent on code from 'General'.
