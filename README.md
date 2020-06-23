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
