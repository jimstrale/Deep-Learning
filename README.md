# Deep-Learning
Deep Learning Homework 21

#### 1. Overview of the analysis
This analysis is to help identify applicants that will be successful in their business ventures. This analysis will ultimately help Alphabet Soup, a nonprofit foundation, choose successful investments based on the data captures from more than 34,000 organizations that have already received funding from Alphabet Soup.

#### 2. Results:

##### Data Preprocessing

The "IS_SUCCESSFUL—Was the money used effectively" variable is the target of this model.

The following variables are included in the data :
* EIN and NAME—Identification columns
* APPICATION_TYPE—Alphabet Soup application type
* AFFILIATION—Affiliated sector of industry
* CLASSIFICATION—Government organization classification
* USE_CASE—Use case for funding
* ORGANIZATION—Organization type
* STATUS—Active status
* INCOME_AMT—Income classification
* SPECIAL_CONSIDERATIONS—Special consideration for application
* ASK_AMT—Funding amount requested

The following variable(s) were removed from the input data to help optimize the model
* EIN and NAME—Identification columns


##### Compiling, Training, and Evaluating the Model

The neural network was comprised of two hiddlen layers. The first with 100 neurons and the second with 25 neurons totaling 87,151 parameters. The relu activation function was used for the hidden layers and the sigmoid activation function was used for the output layer.  

The target performance was acheived after optimization techniques were applied.  

To optimize the model to over 75% accuracy I increase the volume of neurons in the hidden layers. I also kept some previously removed variables, NAME, in the model that helped identify specific applicants that have a history of success for failure. Lastly I broaded the range of APPLICATION_TYPE and NAME variables to reduce the number of those variable being categorized in an 'OTHER' bucket.

The optimization efforts did take a little longer to run.
