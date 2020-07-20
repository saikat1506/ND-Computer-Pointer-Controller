# Computer Pointer Controller
In this project, you will use a gaze detection model to control the mouse pointer of your computer. You will be using the Gaze Estimation model to estimate the gaze of the user's eyes and change the mouse pointer position accordingly. This project will demonstrate your ability to run multiple models in the same machine and coordinate the flow of data between those models
This is the last Project in order to obtain the Intel Edge AI Nanodegree from Udacity, the objective is to create an application capable of moving the computer pointer using only the movement from the head and eyes.

Watch the video


This involves many considerations:

We need several models working together, each one covering a needed functionality. For example, a face detection model is used to feed a face landmarks model.
We need to control the application logic to create an optimal flow, as the models involved could use a lot of resources.
Regarding the models themselves, it could be interesting to check if we could use different precisions models in order to gain more performance.
In general, the flow looks like this:




# Project Set Up and Installation
TODO: Explain the setup procedures to run your project. For instance, this can include your project directory structure, the models you need to download and where to place them etc. Also include details about how to install the dependencies your project requires.

# Demo
TODO: Explain how to run a basic demo of your model.

# Documentation
TODO: Include any documentation that users might need to better understand your project code. For instance, this is a good place to explain the command line arguments that your project supports.

# Benchmarks
TODO: Include the benchmark results of running your model on multiple hardwares and multiple model precisions. Your benchmarks can include: model loading time, input/output processing time, model inference time etc.

# Results
TODO: Discuss the benchmark results and explain why you are getting the results you are getting. For instance, explain why there is difference in inference time for FP32, FP16 and INT8 models.

# Stand Out Suggestions
This is where you can provide information about the stand out suggestions that you have attempted.

## Async Inference
If you have used Async Inference in your code, benchmark the results and explain its effects on power and performance of your project.

# Edge Cases
There will be certain situations that will break your inference flow. For instance, lighting changes or multiple people in the frame. Explain some of the edge cases you encountered in your project and how you solved them to make your project more robust.
