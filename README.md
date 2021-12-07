# Athlete-Recognition-System
## Motivation
In this semester’s 471 course, I learned and used some new skills and software through class and after class assignments, such as Android studio in Assignment 1, Wit.AI in Assignment 2, and deep learning models in Assignment 3.Also, since I am a sports fan myself, I got the idea
of whether I could combine what I had learned this semester with my favorite field of sports.
In my daily life, I often encounter scenarios where I come across my favorite athlete in a street commercial or on TV, and I often get excited
to introduce them to my family or friends, but sometimes some information related to the athlete often just comes to my lips but I forget it. So
this brings me an idea, can I make an app that can identify the athlete by the picture and at the same time get some honor and information related to the athlete when you search for him.
## Architecture
<img width="919" alt="Athlete Recognition System" src="https://user-images.githubusercontent.com/39178053/144961840-186df605-d242-440f-8c29-02c4a2c90513.png">

## Features
<img width="434" alt="F1" src="https://user-images.githubusercontent.com/39178053/144961886-3f676a18-f9f9-4c46-832e-da96f4f1d8f1.png">
Users can login to the app from this page, and if they have already registered an account, they can enter it directly and then click the login
button to enter the function page.If you are not registered then click the Register button to go to the registration page.
<img width="329" alt="F2" src="https://user-images.githubusercontent.com/39178053/144961935-67e53262-c6c4-408a-b2bc-bc5d2a7c1138.png">
In this step, I used MAMP, which I learned in my first assignment, to store and obtain data by using mysql. When the user has finished filling
in the information, click the register button to complete the registration. After that, click the NEXT button to return to the login page
<img width="337" alt="F3" src="https://user-images.githubusercontent.com/39178053/144961984-f0f54faf-281e-4b4e-9877-01bd8d2f6683.png">
Once you enter the features page, start selecting from two features. Clicking on the Get player button while selecting the sport area of interest will bring up the relevant athlete information.When the search button is clicked, it jumps to the athlete identification function.
<img width="315" alt="F4" src="https://user-images.githubusercontent.com/39178053/144962181-6cba13c9-c5a7-4b73-b983-40a1eae7242d.png">
In this section, the images of the athletes are selected from the phone’s photo album so that the corresponding comparisons can be made and
the relevant information can be output at the same time. In this part, I use mtcnn for face detection and alignment and cropping, and
embedding the cropped face using facenet. And these are the relevant knowledge learned in Lab3.

## Future Extension
Regarding the future optimization and expansion, I have considered two main aspects. On the one hand, optimize the UI interface,
beautify the appearance of the system, and improve the interaction between the app and users. On the other hand, I am ready to enrich
the functions and data of athletes in the future. For example, you can directly find the video of his games through the link provided, or you
can enter the relevant store from the relevant athlete’s interface to buy the peripheral products related to him.
