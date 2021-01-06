# Operationalizing Machine Learning

This is the second project from the Machine Learning Engineer with Microsoft Azure Nanodegree program. In this project we will run an Auto ML on Bankmarketing dataset. This dataset can be found here: https://automlsamplenotebookdata.blob.core.windows.net/automl-sample-notebook-data/bankmarketing_train.csv

This is a sample dataset provided by Microsoft. According to their documentation, the y column indicates if a customer subscribed to a fixed term deposit. The dataset contains information about customers - their job, marital status, education, loan, etc.
This is a classification problem, where we tried to predict whether a customer is subscribed to a fixed-term deposit, or not. Therefore, later on, when we start an Automated ML experiment, **"y"** will be our target field. 

## Architectural Diagram
The whole project can be depicted as following:

<div align="center">
  <img src="images/1_Project_Architecture.png" height="500" />
</div>

We will go through each step in a higher level of detail, staring with the basics. 

## Key Steps

### Step 1: Dataset registration
As the first option, we can register a dataset from URI link. The gif below shows all steps. 

![Alt text](images/Step1_Option1.gif "Optional Title")
Alternatively, we can upload data from the local csv file. In this case, the file will be stored in an Azure Blob Storage.

![Alt text](images/Step1_Option2.gif "Optional Title")
Now we can use this data for our Automated ML analysis.

### Step 2: AutoML experiment

![Alt text](images/Step2_AutoML.gif "Optional Title")

### Step 3: Best model deployment

![Alt text](images/Step3_Deployment.gif "Optional Title")

### Step 4: Logging enablement

![Alt text](images/Step4_Logging.gif "Optional Title")

### Step 5: Model consumption

![Alt text](images/Step5_Consumption.gif "Optional Title")

## Creating, Publishing and Consuming a Pipeline

## Screen Recording
The whole project is summarized in the following short video. 
<div align="center">
  <a href="https://drive.google.com/file/d/1XU4UQ5OgIuSlD06CzA4EFjF7Y8i11u6r/view?usp=sharing"><img src="https://images.pexels.com/photos/1626481/pexels-photo-1626481.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" alt="IMAGE ALT TEXT"></a>
</div>

## Standout Suggestions
*TODO (Optional):* This is where you can provide information about any standout suggestions that you have attempted.
