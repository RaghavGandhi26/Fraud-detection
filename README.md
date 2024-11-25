# Fraud-detection

Fraud Detection With Machine Learning
This program allows a user to manage a real database of credit card transactions of which some have been classified as fraud.

How it works
On the server at launch, a logistic regression method is used to estimate the probability of fraudulency for each transaction;the parameters for this method are tuned by the gradient descent algorithm. Any probabilities less than 40% are non-fraudulent and any above 60% are.
It is up to the user (analyst) to classify the transactions in the uncertainty region on the decision boundary using the scatter plots and timeseries visualizations. The actual results can be revealed by pressing the red reset button in the top right hand corner of the page.
Setup
Make sure Python and pip are installed prior to setup.

Clone this repository.

Go to Web App\Dataset directory on file explorer, extract creditcard.zip, and move the file creditcard.csv into the 'dataset' folder. This file was compressed so the repository didn't exceed Github's maximum file size limit of 100mb.

Open the command line (Windows) or terminal (Mac OS)

Pip install the 'virtualenv' package.

Navigate to the directory where you cloned the repository using "cd ...\Fraud Detection\Web App"

Activate the virtual environment using the command: "env\Scripts\activate". If this fails pip install the following packages:
numpy, matplotlib, seaborn, pandas, time, BytesIO

Launch the webapp with "python app.py".

Wait until the url for the webapp to display in the command line, copy it into the browser.
Note this might take some time as the ML model trains for the first time on launch.

The Webapp will be loaded in the browser ready for use. Make sure you have JavaScript enabled in the browser.
