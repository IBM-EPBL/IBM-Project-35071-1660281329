# A Gesture-Based Tool For Sterile Browsing Of Radiology Images

<p align="center">
<a href="https://www.ibm.com/in-en">
<img src="https://img.shields.io/badge/IBM-052FAD.svg?style=for-the-badge&logo=IBM&logoColor=white"> 
</a>
   <a href="https://www.python.org/g">
    <img src="https://forthebadge.com/images/badges/made-with-python.svg" width =182 >
  </a>

  <a href="https://www.ibm.com/cloud">
      <img src="https://img.shields.io/badge/IBM%20Watson-BE95FF.svg?style=for-the-badge&logo=IBM-Watson&logoColor=white" width=130>
  </a>
  <a href="https://opencv.org/">
    <img src="https://img.shields.io/badge/OpenCV-5C3EE8.svg?style=for-the-badge&logo=OpenCV&logoColor=white">
   </a>
 
  <a href="https://pandas.pydata.org/">
    <img src="https://img.shields.io/badge/pandas-150458.svg?style=for-the-badge&logo=pandas&logoColor=white">
    </a>
</p></p>

<div>
   <h2><picture>
  <source srcset="https://fonts.gstatic.com/s/e/notoemoji/latest/1f31f/512.webp" type="image/webp">
  <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f31f/512.gif" alt="🌟" width="32" height="32">
</picture><h2>$\color[RGB]{168,109,156} TEAM:$</h2></div>

    1. Madhumitha R[TL] -312819104044
    
    2. Mrithula V[TM1] -312819104051
    
    3. Nandhini Devi N[TM2] - 312819104053
    
    4. Sowmiya T[TM3] - 312819104073

<div>
 <h2><picture>
  <source srcset="https://fonts.gstatic.com/s/e/notoemoji/latest/1f31f/512.webp" type="image/webp">
  <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f31f/512.gif" alt="🌟" width="32" height="32">
</picture>$\color[RGB]{168,109,156} INTRODUCTION:$</h2></div>

        ⦿ Humans are able to recognize body and sign language easily. This is possible due to the combination of vision
    and synaptic interactions that wereformed along brain development . In order to replicate this skill in computers, 
    some problems need to be solved: how to separate objects of interest in images and which image capture technology and 
    classification technique are more appropriate, among others.

        ⦿ In this project Gesture based Desktop automation ,First the model is trained pre trained on the images of different
    hand gestures, such as a showing numbers with fingers as 1 ,2,3,4 . This model uses the integrated webcam to capture the video
    frame. The image of the gesture captured in the video frame is compared with the Pre-trained model and the gesture is identified. 
    If the gesture predictes is 1 then images is blurred;2, image is resized;3,image is rotatedm etc.

<div>
 <h2><picture>
  <source srcset="https://fonts.gstatic.com/s/e/notoemoji/latest/1f31f/512.webp" type="image/webp">
  <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f31f/512.gif" alt="🌟" width="32" height="32">
</picture>$\color[RGB]{168,109,156} PROJECT \ OBJECTIVE:$</h2></div>
**By the end of this project you will**

    ➼ Know fundamental concepts and techniques of Convolutional Neural Network.

    ➼ Gain a broad understanding of image data.

    ➼ Know how to pre-process/clean the data using different data preprocessing techniques.

    ➼ Know how to build a web application using Flask framework.
    
<div>
 <h2><picture>
  <source srcset="https://fonts.gstatic.com/s/e/notoemoji/latest/1f31f/512.webp" type="image/webp">
  <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f31f/512.gif" alt="🌟" width="32" height="32">
</picture> $\color[RGB]{168,109,156} PROBLEM \ STATEMENT:$</h2></div>

       ⦿ In this project we have used Convolutional Neural Network to frst train the model on the images of
      different hand gestures, like showing numbers with fngers as 0,1,2,3,4,5. Then we made a web portal
      using Flask where user can input any image on which he wants to perform the operations. After
      uploading the image, our portal uses the integrated webcam to capture the video frame using
      OpenCV. The gesture captured in the video frame is compared with the Pre-trained model and the
      gesture is identifed. If the prediction is 0 - then images is converted into rectangle, 1 - image is blurred
      , 2 - image is rotated by -45॰, 3 - image is resized in (400,400) , 4 - image is Resized in (200,200)  , 5 -
      image is converted into grayscale, but in real time we use of doctor-computer interaction devices in
      the operation room (OR) requires new modalities that support medical imaging manipulation while
      allowing doctors' hands to remain sterile, supporting their focus of attention, and providing fast
      response times.
   
<div>
 <h2><picture>
  <source srcset="https://fonts.gstatic.com/s/e/notoemoji/latest/1f31f/512.webp" type="image/webp">
  <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f31f/512.gif" alt="🌟" width="32" height="32">
</picture> $\color[RGB]{168,109,156} PROJECT \ FLOW:$</h2></div>

    ⦿ User interacts with the UI (User Interface) to upload the image as input

    ⦿ Depending on the different gesture inputs different operations are applied to the input image.

    ⦿ Once model analyses the gesture, the prediction with operation applied on image is showcased on the UI.

**To accomplish this, we have to complete all the activities and tasks listed below**

    ➼ Data Collection.

        ⦿ Collect the dataset or Create the dataset

    ➼ Data Preprocessing.

        ⦿ Import the ImageDataGenerator library
        ⦿ Configure ImageDataGenerator class
        ⦿ Apply ImageDataGenerator functionality to Trainset and Testset

    ➼ Model Building

        ⦿ Import the model building Libraries
        ⦿ Initializing the model
        ⦿ Adding Input Layer\
        ⦿ Adding Hidden Layer
        ⦿ Adding Output Layer
        ⦿ Configure the Learning Process
        ⦿ Training and testing the model
        ⦿ Save the Model

    ➼ Application Building

        ⦿ Create an HTML file
        ⦿ Build Python Code


<div>
 <h2><picture>
  <source srcset="https://fonts.gstatic.com/s/e/notoemoji/latest/1f31f/512.webp" type="image/webp">
  <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f31f/512.gif" alt="🌟" width="32" height="32">
</picture>$\color[RGB]{168,109,156} PROJECT \ STRUCTURE:$</h2></div>
**Create a Project folder which contains files as shown below**


![image](https://user-images.githubusercontent.com/70817219/194914420-9ef53158-9413-447b-a7f3-846d5ed567cb.png)

    ⦿ Dataset folder contains the training and testing images for training our model.
    ⦿ We are building a Flask Application which needs  HTML pages stored in the templates 
       folder and a python script app.py for server side scripting
    ⦿ we need the model which is saved and the saved model in this content is gesture.h5
    ⦿ The static folder will contain js and css files.
    ⦿ Whenever we upload a image to predict, that images is saved in uploads folder.

<div>
 <h2><picture>
  <source srcset="https://fonts.gstatic.com/s/e/notoemoji/latest/1f31f/512.webp" type="image/webp">
  <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f31f/512.gif" alt="🌟" width="32" height="32">
</picture>$\color[RGB]{168,109,156} TECHNICAL \ ARCHITECTURE:$</h2></div>

![image](https://user-images.githubusercontent.com/70817219/194914841-4fc230f1-53f9-4b5a-8d9a-e902d9fc3581.png)


<div>
 <h2><picture>
  <source srcset="https://fonts.gstatic.com/s/e/notoemoji/latest/1f31f/512.webp" type="image/webp">
  <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f31f/512.gif" alt="🌟" width="32" height="32">
</picture> $\color[RGB]{168,109,156} PROJECT \ WORKFLOW:$</h2></div>

>       ➼ Ideation phase
>           
>           ⦿ [Brainstroming- Idea Generation] -https://github.com/IBM-EPBL/IBM-Project-35071-1660281329/blob/main/Project%20Design%20%26%20Planning/Ideation%20Phase/Brainstroming-Idea%20Generation-Prioritization.pdf

            ⦿ [Problem statement] -https://github.com/IBM-EPBL/IBM-Project-35071-1660281329/blob/main/Project%20Design%20%26%20Planning/Ideation%20Phase/Define%20Problem%20Statements.pdf
>           
>           ⦿ [Empathy Map Canvas] - https://github.com/IBM-EPBL/IBM-Project-35071-1660281329/blob/main/Project%20Design%20%26%20Planning/Ideation%20Phase/Empathy%20Map%20(1).pdf

            ⦿ [Literature Survey] -https://github.com/IBM-EPBL/IBM-Project-35071-1660281329/blob/main/Project%20Design%20%26%20Planning/Ideation%20Phase/Literature%20Survey.pdf
>           
>       ➼ Project Design Phase – I
>            
>           ⦿ [Proposed Solution Fit] -https://github.com/IBM-EPBL/IBM-Project-35071-1660281329/blob/main/Project%20Design%20%26%20Planning/Project%20Design%20Phase%20I/Problem%20solution%20fit.pdf
>           
>           ⦿ [Prepare Solution] -https://github.com/IBM-EPBL/IBM-Project-35071-1660281329/blob/main/Project%20Design%20%26%20Planning/Project%20Design%20Phase%20I/Proposed%20Solution.pdf
>           
>           ⦿ [Solution Architecture] -https://github.com/IBM-EPBL/IBM-Project-35071-1660281329/blob/main/Project%20Design%20%26%20Planning/Project%20Design%20Phase%20I/Solution%20Architecture.pdf
>           
>       ➼ Project Design Phase – II
>           
>           ⦿ [Data Flow Diagrams]-https://github.com/IBM-EPBL/IBM-Project-35071-1660281329/blob/main/Project%20Design%20%26%20Planning/Project%20Design%20Phase%20II/Data%20Flow%20Diagrams%20and%20User%20Stories.pdf
>           
>           ⦿ [Solution Requirement] -https://github.com/IBM-EPBL/IBM-Project-35071-1660281329/blob/main/Project%20Design%20%26%20Planning/Project%20Design%20Phase%20II/Solution%20Requirements.pdf
    
            ⦿ [Technical Stack] -https://github.com/IBM-EPBL/IBM-Project-35071-1660281329/blob/main/Project%20Design%20%26%20Planning/Project%20Design%20Phase%20II/Technology%20Stack.pdf
            
            ⦿ [Customer Journey Map] -https://github.com/IBM-EPBL/IBM-Project-35071-1660281329/blob/main/Project%20Design%20%26%20Planning/Project%20Design%20Phase%20II/Customer%20Journey%20Map.pdf
>           
>       ➼ Project Planning Phase
>       
>           ⦿ [Prepare Milestone & Activity List] - https://github.com/IBM-EPBL/IBM-Project-35071-1660281329/blob/main/Project%20Design%20%26%20Planning/Project%20Planning/IBM%20Milestone%20and%20Activity%20List.pdf
>           
>           ⦿ [Sprint Delivery Plan] - https://github.com/IBM-EPBL/IBM-Project-35071-1660281329/blob/main/Project%20Design%20%26%20Planning/Project%20Planning/Project%20Planning%20Template%20(3).pdf
>           
>       ➼ Project Development Phase
>       
>           ⦿ [Project Development - Delivery Of Sprint-1] - https://github.com/IBM-EPBL/IBM-Project-35071-1660281329/tree/main/Project%20Development%20Phase/Sprint%201
>           
>           ⦿ [Project Development - Delivery Of Sprint-2] - https://github.com/IBM-EPBL/IBM-Project-35071-1660281329/tree/main/Project%20Development%20Phase/Sprint%202    
>               
>           ⦿ [Project Development - Delivery Of Sprint-3]- https://github.com/IBM-EPBL/IBM-Project-35071-1660281329/tree/main/Project%20Development%20Phase/Sprint%203
>           
>           ⦿ [Project Development - Delivery Of Sprint-4] -https://github.com/IBM-EPBL/IBM-Project-35071-1660281329/tree/main/Project%20Development%20Phase/Sprint%204
>                
[![Watch the video](https://img.youtube.com/vi/T-D1KVIuvjA/maxresdefault.jpg)](https://youtu.be/T-D1KVIuvjA)

### IBM Project | Dept of Computer Science and Engineering | <img src="https://user-images.githubusercontent.com/83297844/194126327-5c9091a6-f2ab-4793-9444-9a07f37aafe0.png" alt="InfiniteGraph Logo" width="20"> Agni College of Technology 
