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


**There were problems that where addressed at Applied Artificial Intelligence Institute:**

1. There were same changes required to refactor code again and again, which was written by data scientist to make it ready for implement. That means there was no standard script, no proper way to handle configuration and no standard pipeline architecture.
2. The models which are existing are serving the model rather than end-to-end solution. The model needs to me clubbed with multiple models and glue code to tie these models together.

3. Existing models don’t allow for the evolution of a machine learning pipeline without re-engineering the solution. Ex: using a cloud API for the first release before training a custom model much later.

4. Code was commonly being commented out to run other branches.

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

## Linux:-

To install surround in linuxfirstle ensure you download the python and   in linux pip3 comes automatically. 

1.) open Terminal in linux and type python3.

![ensuring python](https://user-images.githubusercontent.com/48539509/58250571-0d6f8900-7da5-11e9-84e1-07ffe983fe80.PNG)

and then type exit() to come out from the environment of python.

2.) Type pip3 install surround. and to ensure type surround-h.

![collecting surround in linux](https://user-images.githubusercontent.com/48539509/58250578-119ba680-7da5-11e9-9e4e-45d82d30b19a.PNG)


![installed successfully in linux](https://user-images.githubusercontent.com/48539509/58250587-16605a80-7da5-11e9-9a98-b181f0371756.PNG)


# Working of Surround:
****
**_Pre-created files:_**

There will be some files created as you install surround. Some default files that are generated are listed as below:

**_Creating New File:_**

To create a new file for surround can be explained in few simple steps:

**Step 1:** Just jump to “Command Prompt” after successful installation of surround into system, move to your choose surround directory and hit these commands.


[**Note:** the project name should be lowercase.]
![to create a new file for surround](https://github.com/surround-deakin-team/Surround_document/blob/master/Collection/step1.png)

**Step 2:** After performing “surround init” command it will ask for **name of project** and **what is the purpose of this project?**


![providing project details](https://github.com/surround-deakin-team/Surround_document/blob/master/Collection/step2.png)


**Step 3:** Now when user is done with creating project, user can go the respective directory where a folder with specified project name will be created. That folder will contain files like this:

![created files](https://github.com/surround-deakin-team/Surround_document/blob/master/Collection/step3.png)

**Step 4:** You can see that a folder name yolosample is created into this project. This folder contains some pre-created files that will look like this:
![pre-generated files ](https://github.com/surround-deakin-team/Surround_document/blob/master/Collection/step4.png)

1. **.surround** _folder_ will have  config.yaml file which is the main file to deploy your project.
2. **data** _folder_ is used to store the datasets or other input files for the project.
3.  **docs** folder is to store your document of your project.
4. **models** _folder_ used to store the predefined  models for the analysis.
5.  **notebooks** folder is used to store your scrap or rough coding or flowchart of the project.
6. **output** _folder_ used to store the output of the processed input file from data folder.
7. **scripts** folder used to store your code for the project
8. **spikes** folder will store the output of spikes tool in the project.
9. **tests** folder is used to store the tested file of the project.
10. **Dockerfile**  is used to tell which environment to use and which command should be used to run the file.
11. **dodo** _file_ will have configuration file. It will run the main task in docker file container for the production.
12. **README.md**  _file_ is used to provide the information of the project. It also explains how the input is processed for output in a project.
13. **requirements** text file shows the surround project neccessaries.
14. **created_project_name** is your created project folder with your project name.

## Built in files
After creating a surround project. List of files are genrated as built in.
They are:
-  \_init\_
- \_main\_
- \_stages\_
- Wrapper
- config.yaml

**_init_:** It contains initialization and path where the project will be executed.

**_main_:**  This file contains all the imported files and classes required for the project.

**_stages_:** In this file user can define one or more than one stages to process for your project. 

**_wrapper_:** It conatains pipeline of surround which will interfere with other containers from input to processed output.

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
 # Yolo with Surround AI
 From the above we can say that yolo used to provide object detection in images. In this we going to explain the working of yolo in surround with examples.
Using this object detection in image we can predict the traffic of an area and we can calculate the number of people in the region for providing better service.
# Flow chart of Yolo working in surround
![Flow chart](https://github.com/surround-deakin-team/Surround_document/blob/master/Collection/yolo_flow_chart_Diagram.png)
 
# Prerequisites
1. **Numpy**
2. **OpenCV**
3. **Clone** the repo of surround with yolo in git hub. [click here](https://github.com/surround-deakin-team/YoloImplementation)
4. **Predefined weight** [download](https://pjreddie.com/media/files/yolov3.weights)
## Install Numpy
**Windows**
>  pip3 install  numpy

**MAC**
> pip3 install  numpy

## Install openCV
**Windows**
>  pip3 install  openCV

**MAC**
> pip3 install openCV

## Clone the repo of surround
1. Go to the surround repository of yolo [click here](https://github.com/surround-deakin-team/YoloImplementation%29)
![Clone_repo_yolo](https://github.com/surround-deakin-team/Surround_document/blob/master/Collection/Clone_surround_repo.png)
2. Click the clone button and copy the url.
**Use git bash for cloning**
> **git clone** _<paste url of the repository using shift+insert key or right click>_
[click here ](https://git-scm.com/book/en/v2/Git-Basics-Working-with-Remotes) to know more about cloning in Git.

## Install Predefined weights
Change the directory to the project folder
**Windows** 
>  cd   <_set path to project folder_>
>  curl _https://pjreddie.com/media/files/yolov3.weights_ -o yolov3.weights

**MAC**
>  cd   <_set path to project folder_>
>  curl _https://pjreddie.com/media/files/yolov3.weights_ -o yolov3.weights

**Note:** _ Make sure the name of the yolov3.weights is similar to the weight file in yolo project._
## How to run the code to detect objects in image 
After the above steps change the directory to project directory.

**Windows:** 
>  python -m surroundyolo

**MAC Terminal:** 
> python3 surroundyolo.py

A new window will open with objects detected in an image.
![Object_detected](https://github.com/surround-deakin-team/Surround_document/blob/master/Collection/object-detection.jpg)

Press any key to close the window.


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
Surround is under development which as goals to satisfy the needs of data scientists. It completely turns the view of analysing in machine learning and other concepts of AI(Artificial Intelligence). The sample yolo in surround shows the working of object detection in image and video. The future scope is to identify the number plate in vehicle using the google cloud api.





