# Surround_document
For better understanidng of surround
# Surround AI
Surround AI  is the python framework which is designed for flexible usage in Artificial Intelligence(AI). It is designed to support data scientist in their progress. Each and every scientist use different algorithm to solve different problems. There are no standard way for them to analyse altogether in a single module. To provide a standard solution surround frame work is built. Evolution of machine learning pipeline  is not possible without re-constructing the coding whereas surround package will provide a pipeline without any alterations.
**There were problems that where addressed at Applied Artificial Intelligence Institute:**

 1. There were same changes required to refactor code again and again,  
    which was written by data scientist to make it ready for implement. 
    That means there was no standard script, no proper way to handle   
    configuration and no standard pipeline architecture.
 2. The models which are existing are serving the model rather than
    end-to-end solution. The model needs to me clubbed with multiple
    models and glue code to tie these models together.
 3. Existing models don’t allow for the evolution of a machine learning
    pipeline without re-engineering the solution. Ex: using a cloud API
    for the first release before training a custom model much later.
 4. Code was commonly being commented out to run other branches.

# Flow-diagram
Here are some components in the library that one can use to build Surround AI solutions.

## Components

 - Surround A group of many stages or maybe it can be one stage only,
   helps to transform the data into more meaningful and explainable
   data. You can set orders of stages directly on your implementation or   you may use configuration file. Configuration file allows you to
   define more than 1 pipeline implementation and then you can switch between them effortlessly.
 - Surround Data A sharable object between stages that holds necessary information for each stage. A stage will read some information from Surround Data then will process it and as rend result will put back new information that will be used by other stage or multiple stages.
 
 - In Surround, when you extend classes, you can add as many variables as you need to help you transform input data into output data. But note that there are **four** core variables that are ready for you to utilise.
	
**stage_metadata:** it is information that can be used to identify a stage.

**execution_time:** it is recorded time to complete a process.

**errors:** it is information to identify failure of a stage.

**warnings:** warnings are information when transformation is not 100% correct.

 - Stage an implementation of data transformation. Here is where
   **Surround Data** is modified to archive the result that you need. Each stage is only aimed to perform a set of related actions. In
   stage one where you prepare data to be processed and last stage can
   be where your populated data to be sent back to user.

**Operate** is a function that you need to override when you extend stage class. It must contain data transformation implementation.
# Why surround?
* It is designed to support data scientist in their progress.
*  Each and every scientist use different algorithm to solve different problems. There are no standard way for them to analyse altogether in a single module.
*   To provide a standard solution surround framework is built. 
*  Every machine learning pipeline can be accessed for getting the appropriate solution instead of reffering many machine learning packages.
# Usage
* Helping the data scientists in analytics instead            
using glue codes for their research.
*  Easy interaction between several machine learning pipelines.
* Provides end-to-end solution instead of providing solution for the models.
# Current
Using cloud API for training models for image recognition.
Developing a pipeline for the surround module using machine learning algorithms.
# Surround Working
# Installation guide:
## Windows
1.) Install the python 3.7.3 in the system  by following the provided link that is given below [https://www.python.org/downloads/](https://www.python.org/downloads/)	

2.) Pip3 is installed in your system by default when you install Python.

3.) Set path in Environment variables for python 3.6.5. There are some steps and essential screenshots are provided for setting paths for python:-

  3.1) Open the properties of your system by right clicking on This Pc.
       
![properties](https://user-images.githubusercontent.com/48539509/57824194-999a1300-77dd-11e9-93ce-9b28be428e6e.PNG)

   3.2) A new page will open which describes about the properties of System.      
      
 ![system](https://user-images.githubusercontent.com/48539509/57824510-9fdcbf00-77de-11e9-831f-439c4712754e.PNG)
  
   3.3) Then go for Advanced System settings. Further it shows properties of system.
       
 ![enviro](https://user-images.githubusercontent.com/48539509/57824204-a159b780-77dd-11e9-9033-421a08ccc1aa.PNG)
       
   3.4) Then go for Enviroment Variables and edit path for python here.
       
![enviro11](https://user-images.githubusercontent.com/48539509/57824207-a4ed3e80-77dd-11e9-94eb-5f32776c6096.PNG)
   
   3.5) set path for python.

![editing 1](https://user-images.githubusercontent.com/48539509/57824906-f72f5f00-77df-11e9-8575-36ff23bb6dbd.jpg)


![editing 2](https://user-images.githubusercontent.com/48539509/57824909-fbf41300-77df-11e9-95db-449085910721.jpg)
  
Path is set for python and move on next step.

4.) Open command prompt.

5.) Type python to ensure that python is successfully installed in your system.

![ensure python installed](https://user-images.githubusercontent.com/48539509/58065978-e8272300-7bca-11e9-99eb-233c9388ee94.PNG)


6.) Then type exit() to get out from python environment.

7.) Then type pip3 install surround

8.) Surround is installed in system.

![python](https://user-images.githubusercontent.com/48539509/57619660-d2619e80-75c9-11e9-9868-c87f85216c26.PNG)

9.) To ensure type surround –h. It shows all necessary commands of surround.

![surround](https://user-images.githubusercontent.com/48539509/58065988-efe6c780-7bca-11e9-8151-52bb8b9b295b.PNG)


It successfully installed in windows.

## Mac:-

To install surround in mac follow first three steps similar as windows that are installing python3 and setting environment path.


![python install](https://user-images.githubusercontent.com/48539509/58065981-eb221380-7bca-11e9-8004-80e6f543e082.png)

1.) Open Terminal and type !pip3 install surround.

![mac](https://user-images.githubusercontent.com/48539509/57827791-22b84680-77ec-11e9-9d95-69eabe5b017c.png)

2. surround sucessfully installed in mac. To ensure type surround -h.

![mac insatll](https://user-images.githubusercontent.com/48539509/57827784-1e8c2900-77ec-11e9-88fc-b32b0667f5a3.png)

# How to create a project
After installation of surround using pip3
* **Type** surround -h
* You can see list of help option in surround with **commands** 

![Surround_help](https://github.com/surround-deakin-team/Surround_document/blob/master/Collection/Surround%20help1.PNG)

## create a project
* **Type** surround init
* Enter the project name and enter the purpose of the project

![Surround_init](https://github.com/sundararaman9608/sundararaman.github.io/blob/surround/project_created.PNG)

[**Note:** the project name should be lowercase.]

# Built in files
After creating a surround project. List of files are genrated as built in.
They are:
-  \_init\_
- \_main\_
- \_stages\_
- Wrapper
- config.yaml

# Sample for Surround using Yolo 9000:
## Yolo 9000
> Yolo is the object detection system on a Pascal Titan X it processes images at 30 FPs and has a map of 57.9%. It can identify more than 9000 objects using image net classification and COCO detection dataset. 
## Yolo in surround
**Object detection in Image can be done in surround using Yolo 9000.**
> **Note:** we can use yolo in python with the help of openCV DNN(Deep Neural Networks).
### Installing dependencies: 
1.	Python 3.
2.	Numpy.
3.	OpenCV.
4.	Surround.
### Input arguments for image detection:
1.	Read image.
2.	Config file of Yolo.
3.	Use pre trained yolo weights.
4.	Text file containing class names.

**Sample Logo:**

![Surround logo](https://github.com/sundararaman9608/sundararaman.github.io/blob/surround/logo.adobe.png)

# Frequently Asked Questions

## Query 1

During the installation process after typing pip3 install surround it throws an syntax error. Can anyone help?

### Screenshot: This is my syntax error.
![Pip not recognised](https://github.com/surround-deakin-team/Surround_document/blob/master/Collection/FAQ1.PNG)

### Solution
Probably the path for pip3 is not set in your system. Just find the pip3 in your system. If it is not available just reinstall your python 3. Since, it has pip3 by default. Then retry the pip3 install surround without using ‘!’ in front of the command. 

## Query 2

After typing the  pip3 install surround it shows an invalid syntax. I have set path to python and pip as well then also it shows the same error.

### Screenshot: Error in syntax
![Invalid syntax](https://github.com/surround-deakin-team/Surround_document/blob/master/Collection/faq2.png)

### Solution
Don’t give the !pip3 install surround inside python. Just set the path for the pip and type pip3 install surround in the command prompt itself.

## Query 3
When I was creating a project name, I would like to give the name as yolo_9000 and I am unable to create it, also tried with different name as YOLO9000, it was given in uppercase letters, underscore, and space and also alphanumeric.

![FAQ3](https://github.com/surround-deakin-team/Surround_document/blob/master/Collection/Query3.PNG)


## Solution: 

In surround, the project name must be only in lowercase letters without inclusion of any numbers, underscore and space in it.

![FAQ3 solution](https://github.com/surround-deakin-team/Surround_document/blob/master/Collection/Query3%20soln.PNG)

## Query 4
Issues while installing surround in MAC, I am not able to install surround and unable to set a path

![FAQ4](https://github.com/surround-deakin-team/Surround_document/blob/master/Collection/Query4.jpg)

## Solution: 

Python path should be set with this packages:

`PYTHONPATH="/usr/local/lib/python3.7/site-packages:$PYTHONPATH"`

`export PYTHONPATH`

To cross check

1. python3

2. import surround

3. surround.__file_

Do restart your terminal and if you still get the same error please do restart your system.

![FAQ4 soln](https://github.com/surround-deakin-team/Surround_document/blob/master/Collection/Query4%20soln.jpg)

# Conclusion:
Surround is under development which as goals to satisfy the needs of data scientists. It completely turns the view of analysing in machine learning and other concepts of AI(Artificial Intelligence).





