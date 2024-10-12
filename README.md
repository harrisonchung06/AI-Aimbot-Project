# Free Fire AI-Aimbot-Project 

## An aimbot which uses OpenCV and YOLOV7 to track enemy player's head positions on screen and a PID control loop to approximate the position of the player's aim 

## Use Instructions:[^bignote]
1. Install requirements in requirements.txt 
2. Install the included YOLOV7 model for player head positions 
3. Run the Free Fire Game on LDPlayer  
4. Run the included script 
5. Resize the Free Fire Game window until the center of the aim dot matches the detection window 

## Project Goals: 
* Track enemy player head positions on screen in real time with an object detection model 
* Change the position of the player's aim using mouse commands 
* Activate the shoot command once the aim coordinate matches with the head position 

## Project Results: 
* Accurately shoots enemy players standing still 
* Tracks and semi-accurately shoots moving enemy players 
* Semi-accurately tracks and shoots multiple moving enemy players 

![ScreenRecording2024-10-12093457-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/24b1877f-c067-417e-8e7c-c6905d1c13a5)

[^bignote] Important Author's Note: 
This program is to be used for educational purposes only. 
I do not endorse cheating in any way. 
Parties who decide to misuse the program are responsible for any disciplinary action taken against them. 
