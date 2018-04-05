# The Evening Brew !
Evening brew session 05/04/2018 - TIQRI
## Learn something collaboratively - Machine Learning

__Machine learning__
Building a model from example inputs to make data driven prediction vs. following strictly static program instructions. Mainly system learns how to solve a problem from example data rather than following a specific logic written with branching statements.
## In traditional programming
__We__ carefully analyses the problem and __write code__, this program then reads data then __uses control logic__ we wrote carefully and determines correct part of the program to execute, which eventually produce end results.

__Traditional control logic__

If, switch case, for, while, etc…

## In Machine learning
__We__ gather a dataset from a problem domain, and __pre-process__ it in to a form where machine learning algorithm can understand. Then we feed the data to an __algorithm__ which analyses the data and produce a __model__ . This __model__ implements the solution to resolve the problem based on the data.
__the initial data we used drives the prediction logic, not a logic written by a programmer.__
## How can an Algorithm learn it self ?
[check the video](https://github.com/rangasurendra/evening-brew-ml/blob/master/files/learining.mp4)

## We will be useing Azure ML Studio to get-in to basics
[https://studio.azureml.net/](https://studio.azureml.net/)

Some example flow diagram,

![Expiriment](https://github.com/rangasurendra/evening-brew-ml/blob/master/files/images/interview-two-class-prediction.PNG)

__Why ML studio__

Azure Machine Learning Studio is a __collaborative, drag-and-drop tool__ you can use to __build, test, and deploy__ predictive analytics solutions on your data. Tutorials, videos, and example models show you how to use Studio to build and deploy machine learning models.

## We will be focusing mainly on machine learning flow, and the algorithm selection

__What is 'Machine learning flow' means ?__

__Asking the right question > Preparing data > Selecting the algorithm > training the model > testing the model__


[check the video](https://github.com/rangasurendra/evening-brew-ml/blob/master/files/workflow-guide.mp4)


![Expiriment](https://github.com/rangasurendra/evening-brew-ml/blob/master/files/images/guide.png)

We have prepared some data sets here to begin with, Each team will be assigned a data set which they needs to analyse using ML studio, and present findings to the crowed with appropriate demonstration.

1. ![Diabetes-dataset](https://github.com/rangasurendra/evening-brew-ml/blob/master/files/datasets/blood-suger/diabetes.csv)
This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage. [More](https://www.kaggle.com/uciml/pima-indians-diabetes-database)

2. ![Function-approximation-dataset-1](https://github.com/rangasurendra/evening-brew-ml/blob/master/files/datasets/function-approximation-cos/cos-function.csv)
This is some common trignometry function :)

3. ![Function-approximation-dataset-2](https://github.com/rangasurendra/evening-brew-ml/blob/master/files/datasets/function-approximation-velocity/velocity.csv)
This is S = ut + 1/2* at^2

4. ![kickstarter-projects-success-dataset](https://github.com/rangasurendra/evening-brew-ml/blob/master/files/datasets/kickstarter-projects/kick-2016.csv)
Data are collected from [Kickstarter Platform](https://www.kickstarter.com/) try to predict success/failure out come of a project. [More](https://www.kaggle.com/kemical/kickstarter-projects)

5. ![interview-attendence-dataset](https://github.com/rangasurendra/evening-brew-ml/blob/master/files/datasets/will-they-come-to-interview/Interview.csv)
The data pertains to the recruitment industry in India for the years 2014-2016 and deals with candidate interview attendance for various clients. The details are largely self explanatory. [More](https://www.kaggle.com/vishnusraghavan/the-interview-attendance-problem)

Try few algorithms to determine outcome of each data set,

![Expiriment](https://github.com/rangasurendra/evening-brew-ml/blob/master/files/images/pick-an-algo.PNG)



## At the end of the session

Try to figure out diffrent types of evaluation 

![Expiriment](https://github.com/rangasurendra/evening-brew-ml/blob/master/files/images/evaluate.PNG)

![Expiriment](https://github.com/rangasurendra/evening-brew-ml/blob/master/files/images/some-output.PNG)
 

## How do I ?
__Begin__ 

[Azure Machine Learning Studio Documentation](https://docs.microsoft.com/en-us/azure/machine-learning/studio/)

__Find data sets__

[https://www.kaggle.com](https://www.kaggle.com)
This is only one in many good chioces... why don't you try google!

__Algorithm Selection__ 

[Machine learning algorithm cheat sheet](https://docs.microsoft.com/en-us/azure/machine-learning/studio/algorithm-cheat-sheet)

[How to choose algorithms for Microsoft Azure Machine Learning](https://docs.microsoft.com/en-us/azure/machine-learning/studio/algorithm-choice)

__Capabilities__ 

[Overview diagram of Azure Machine Learning Studio capabilities](https://docs.microsoft.com/en-us/azure/machine-learning/studio/studio-overview-diagram)

__Try some serious s#!t__

[Create text analytics models in Azure Machine Learning Studio](https://docs.microsoft.com/en-us/azure/machine-learning/studio/text-analytics-module-tutorial)
