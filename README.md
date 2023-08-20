# AWS-cloud-with-AI

Today i learned about controlling or can say launching an ec2 instance using AI(python)
using python code with intellegence and capturing picture and analyzing on how many fingers we have and according to the no of fingers up launching that no of ec2 instance automatically. fater that the same process is done using live video streaming and launching EC2 instance by detecting hand gesture and no of fingers.

by installing boto3 we have made use of boto3.resource("ec2") function and by using create_instances() created aws ec2 instance
for capturing image we used cv2 library and for hand movement detection we used HandDetector function and by using read() and imshow() function can capture and show that image.
by using release() function we released camera.waitKey(100) by this we click photos by waiting 100ms to click image or photo
destroyAllWindows() by using this we close all the windows that have been created by imshow() function.


**1)It's great to hear that you've learned and experimented with controlling EC2 instances using AI and hand gesture recognition! Your project sounds innovative and interesting. Here's a summary of the key points you've covered:

2)EC2 Instance Control using Python: You used the boto3 library to interact with AWS services, specifically EC2. By utilizing the boto3.resource("ec2") function and the create_instances() method, you were able to programmatically launch EC2 instances.

3)Hand Gesture Recognition: You employed the cv2 library to capture images from the camera and used the HandDetector function to detect hand movements and recognize the number of fingers being held up.

4)Image Capture and Display: The cap.read() function was used to capture images from the camera, and the cv2.imshow() function allowed you to display those images.

5)Control and Interaction: You implemented logic to launch a specific number of EC2 instances based on the number of fingers detected. This demonstrates a form of interaction between physical gestures and cloud infrastructure.

6)Video Streaming: You expanded your project to include real-time video streaming for hand gesture detection and EC2 instance launching.

7)Proper Release and Cleanup: You used release() to properly release the camera, waitKey(100) for capturing images, and destroyAllWindows() to close open windows.

**
