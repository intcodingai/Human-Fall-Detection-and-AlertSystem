# Human-Fall-Detection-and-AlertSystem
Computer Vision System to detect person falling down and alerts the care taker


Goal : Detect person falls and notify his/her caretaker or guardian if the person has fallen down.

Model used : MoveNet

MoveNet model by the Google AI Tensorflow team is an ultra fast and accurate model that detects 17 keypoints of a body. 

Here, I have used MoveNet model's Lightning TFLite model format, as it allows us to deploy ML models in mobile and IoT devices and run on-device inference. 
The reason for choosing "Lightning" version to build a Fall Detection system is because of the low latency it offers. Detecting a human being falling down with extremly low latency is critical. As soon as a fall is detected, an alert message is sent to the previously set phone number and email id.

The above Jupyter Notebook file demonstrates the working of the system.

Steps to execute:
----------------
1. Open the ipynb file in Colab.
2. Connect to normal runtime (Hardware Accelerator : None).
3. Upload the given test files to Colab working directory.
4. Select "Run all" from Runtime menu.



![fall detected](https://user-images.githubusercontent.com/103498011/172386295-612f719c-4a64-4cb4-8547-a1a45cd2240b.gif)

![image](https://user-images.githubusercontent.com/103498011/172386393-29fff9ce-0f4e-46e3-a245-ac432a6ebc27.png)

Alert email
![image](https://user-images.githubusercontent.com/103498011/172388396-a660b129-d108-4e37-a07e-bef4e2c0e176.png)
