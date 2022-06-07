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






Alert email


![email alert sample](https://user-images.githubusercontent.com/103498011/172390911-ad1ef36c-b9b8-48cb-b335-5e7968b909e3.jpeg)

SMS alert sample


![sms alert sample](https://user-images.githubusercontent.com/103498011/172391029-119d4bd2-5c53-449a-8a38-95a79f814f26.jpeg)
