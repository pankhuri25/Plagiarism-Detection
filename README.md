**Plagiarism Detection**

Notebook 1: Data Exploration

Load in the corpus of plagiarism text data.
Explore the existing data features and the data distribution.
This first notebook is not required in your final project submission.


Notebook 2: Feature Engineering

Clean and pre-process the text data.
Define features for comparing the similarity of an answer text and a source text, and extract similarity features.
Select "good" features, by analyzing the correlations between different features.
Create train/test .csv files that hold the relevant features and class labels for train/test data points.


Notebook 3: Train and Deploy Your Model in SageMaker

Upload your train/test feature data to S3.
Define a binary classification model and a training script.
Train your model and deploy it using SageMaker.
Evaluate your deployed classifier.

*Setup Instructions*
The notebooks provided in this repository are intended to be executed using Amazon's SageMaker platform. The following is a brief set of instructions on setting up a managed notebook instance using SageMaker, from which the notebooks can be completed and run.

Log in to the AWS console and create a notebook instance
Log in to the AWS console and go to the SageMaker dashboard. Click on 'Create notebook instance'.

The notebook name can be anything and using ml.t2.medium is a good idea as it is covered under the free tier.
For the role, creating a new role works fine. Using the default options is also okay.
It's important to note that you need the notebook instance to have access to S3 resources, which it does by default. In particular, any S3 bucket or object, with “sagemaker" in the name, is available to the notebook.
Use the option to git clone the project repository into the notebook instance by pasting https://github.com/udacity/ML_SageMaker_Studies.git
Open and run the notebook of your choice
Now that the repository has been cloned into the notebook instance you may navigate to any of the notebooks that you wish to complete or execute and work with them. Additional instructions are contained in their respective notebooks.
