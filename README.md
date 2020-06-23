# azure-ml-engineering

## Objective:  Build a Production Machine Learning model on Azure with AutoML

## Workflow

1.  Setup Azure Machine Learning Workspace

![Screen Shot 2020-06-23 at 3 31 27 PM](https://user-images.githubusercontent.com/58792/85450290-a05d9280-b566-11ea-9124-3b6c97e06bcd.png)


2.  Launch Microsoft Azure Machine Learning

![Screen Shot 2020-06-23 at 3 35 19 PM](https://user-images.githubusercontent.com/58792/85450795-2d085080-b567-11ea-9448-a59f0ac592d8.png)


3.  Clone auto-ml-classification notebook

![Screen Shot 2020-06-23 at 3 36 11 PM](https://user-images.githubusercontent.com/58792/85450980-6214a300-b567-11ea-8d0e-85d87076c9aa.png)

4. Create AutoML Compute and Run Notebook inside  when complete

![Screen Shot 2020-06-23 at 3 38 00 PM](https://user-images.githubusercontent.com/58792/85451163-91c3ab00-b567-11ea-8786-27b37930ace1.png)

5.  Edit in Jupyter

![Screen Shot 2020-06-23 at 3 42 30 PM](https://user-images.githubusercontent.com/58792/85451727-2d551b80-b568-11ea-8ea1-98454e1eaa11.png)

6.  Deploy ML Model into production by running this [notebook in Azure Machine Learning](https://github.com/noahgift/azure-ml-engineering/blob/master/auto_ml_classification_bank_marketing_all_features.ipynb)

a. Create an experiment using an existing workspace.

b. Configure AutoML using AutoMLConfig.

c. Train the model using local compute with ONNX compatible config on.

d. Explore the results, featurization transparency options and save the ONNX model

e. Inference with the ONNX model.

f. Register the model.

g. Create a container image.

h. Create an Azure Container Instance (ACI) service.

i. Test the ACI service.


## Passing Project

### What is a fully functional example look like?

* The project is fully operational via step 6.

### What does a student need to pass it?

* Student will do an AutoML end to end solution
* Student will also show how to use the API

* Project using the steps described above
* Project has two-page README explaining the business problem, the steps used to solve the problem and the incremental deployment steps.
[Provide Starter File Template in README: i.e. ## Section One:  Ingestion]

* One to five minute screencast of project showing it working in production
* Model is updated and new model is deployed through MLOps
* Source code for project is in Github.





## Helpful Key Azure Commands

What Azure Subscriptions accounts do I have?

`az account list --output table`

```bash
noah@Azure:~$ az account list --output table
Name                                CloudName    SubscriptionId                        State    IsDefault
----------------------------------  -----------  ------------------------------------  -------  -----------
Visual Studio Enterprise: BizSpark  AzureCloud   xxx                                   Enabled  False
Microsoft Azure Sponsorship 2       AzureCloud   xxx                                   Enabled  True
```


## References


* [Automated ML](https://docs.microsoft.com/en-us/azure/machine-learning/concept-automated-ml)
* [AutoML Python](https://docs.microsoft.com/en-us/azure/machine-learning/tutorial-auto-train-models)
