# capstone-design
Maker B

Smart home based on voice recognition
![default](https://user-images.githubusercontent.com/40620102/42127824-d76b2714-7c8e-11e8-9603-ae791bde9d94.jpg)

# Used program

ATmega128


App inventor
<br>about App Inventor
http://appinventor.mit.edu/explore/about-us.html

![appinventor3](https://user-images.githubusercontent.com/40620102/42128317-1b059834-7c98-11e8-9d74-9297ec5793f9.png)
![appinventor2](https://user-images.githubusercontent.com/40620102/42127854-88502b60-7c8f-11e8-8830-d5d4699a7bb2.png)



# logic summary
-The app was created through App Inventor.<br>
-It communicates the application with the ATmega via Bluetooth.<br>
-The application receives voice commands with voice recognition tool.<br>
-The input command is converted from the ATmega.<br>
-In ATmega, the input command is output to the circuit.<br>
-LED has three levels of brightness control. Brightness can be controlled by PWM control.<br>
-DOOR has opening and closing function. This controls the angle of the servo motor at the ATmega.<br>
-SPEAKER can turn on and play three songs.<br>
-FAN controls the wind intensity in three steps. The speed of the fan can be controlled by PWM control.<br>

 
# ABSTRACT

We created a smart home based on voice recognition. The ATmega program was used, and the App Inventor was used to create applications that accept voice commands. Voice recognition is performed using the application. Voice recognition controls the door (open, close), LED brightness (weak, medium, strong), electric fans (slow, medium, fast), and speakers (song 1,song 2,song 3). These products may be useful when you have no one to help you in situations where you are feeling uncomfortable or have trouble with other tasks. As smart home products are becoming more common in and out of the country, and the size of the smart home market is also large, there will be positive responses.

# INTRODUCTION
<img width="429" alt="intro1" src="https://user-images.githubusercontent.com/40620102/42127955-e131ad66-7c90-11e8-9e29-e5cd0fb1c4a6.png">

<img width="442" alt="intro2" src="https://user-images.githubusercontent.com/40620102/42127956-e1709512-7c90-11e8-99d1-7a99876cdf4a.png">

Smart Home refers to a technology that can monitor and control household appliances, energy consumption devices, security devices, and everything through telecommunication network. Depending on the characteristics of the user, it can operate automatically or be controlled remotely. 
 With the aging age, the number of single households is increasing. In addition, products that operate without using their own bodies are being developed in many areas. These products are necessary when there is no one to help you in situations where you are physically uncomfortable or have trouble dealing with other tasks. In the case of older adults, it is also difficult to learn and control new electronic devices based on them, so it is designed to be easy and convenient to operate using voice recognition. Voice recognition will also be more convenient because it can be controlled directly by voice without the use of buttons. 
 The home network market is re-entering by introducing smart home services from major players, mobile network operators and others. Due to predictions from Korea's Smart Home market, it started at 6.5 trillion won in 2013 and grew to 14.9 trillion won in 2016. It is estimated that global Smart Home markets will be worth $ 69 billion in 2016. It has continued to grow and is expected to expand to $ 111.5 billion by 2019. As such, smart home products are becoming more common in Korea and other countries. And it is positive reaction to smart home.
 
# The reason why voice recognition is good for real life
Grandparents who have difficulty handling new electronic devices can conveniently use them in their daily lives. Also, since patients in hospitals can operate with minimal movement in uncomfortable conditions, it can also be useful in institutions. Therefore, voice recognition should become popular not only nowadays but also in the future.

# Direction and goal

Smart home production with voice recognition


(1) Set the functions that the main users need within the home. (Ref. Interview material)<br>
(2) Create an application that uses the App Inventor to accept voice commands. Voice recognition is performed using the speech recognition function provided by App Inventor.<br>
(3) Using ATmega, we create code that controls the functions of 1<br>
(4) Make a circuit configuration in which functions of smart home operate with received voice command<br>
(5) Expectations when applied by making actual model

# Key Considerations
In order to increase the utilization rate, the accessibility should be good, but it is necessary to use the functions that are frequently used in the house.

# Target interview

![interview_plan](https://user-images.githubusercontent.com/40620102/42128440-3cafbe4e-7c9b-11e8-96e3-c1a10fa4f261.png)

Before the interview, we prepared our questions to make a question. It is a note taken after the interview.

![interview1](https://user-images.githubusercontent.com/40620102/42127880-a0b4a1d6-7c8f-11e8-8ab8-93518bf827d4.PNG)
![interview2](https://user-images.githubusercontent.com/40620102/42127882-a0f20c1a-7c8f-11e8-9711-090c663dea2c.PNG)

In order to better understand the needs of the target group, we visited the hospital and interviewed the patients. As a result, it helped in the direction of the project.

# Material

The following parts were used.

Application and ATmega Connection: Bluetooth Module HC-06 Firmware v3.0<br>
Speaker: 40mm 8Ohm 1W Speaker, Melody IC<br>
FAN: 10,000 RPM FAN MOTOR<br>
DOOR: Mini Servo-Motor SG-90<br>
LED: LED<br>

![material1](https://user-images.githubusercontent.com/40620102/42127885-a6f9f9f6-7c8f-11e8-9099-de53992758de.PNG)
![material2](https://user-images.githubusercontent.com/40620102/42127886-a7368f42-7c8f-11e8-88c3-ab2d8f90d9ee.PNG)

# Production process

The next image is a block of the application. We made using App Inventor.<br>
![block1](https://user-images.githubusercontent.com/40620102/42128903-7817b432-7ca5-11e8-9555-36ccf4b8f23e.JPG)
![block2](https://user-images.githubusercontent.com/40620102/42128904-78557d30-7ca5-11e8-8b79-949e59ebb6e2.JPG)
![block3](https://user-images.githubusercontent.com/40620102/42128906-788ff41a-7ca5-11e8-9c3c-bfd5612ec1df.JPG)
![block4](https://user-images.githubusercontent.com/40620102/42128907-78c1740e-7ca5-11e8-9973-2a4bc4d90de5.JPG)
<br><br>

The following pictures are operational. However, please refer to the video clips because speakers and fans are hard to distinguish from the pictures. <br>
![app_2ready](https://user-images.githubusercontent.com/40620102/42128915-a3b946fa-7ca5-11e8-9d81-288232cdefda.jpg)

This is the Bluetooth connection process of the application. If you select the Bluetooth named HC-06 and connect it, it changes from Disconnected to Connected(green).<br><br>

![app_3dooropen](https://user-images.githubusercontent.com/40620102/42128916-a3f571fc-7ca5-11e8-8c53-928d811c8932.png)
Press "이곳을 누르고 말하세요" and speak by voice.<br><br>

![app_3dooropen](https://user-images.githubusercontent.com/40620102/42128917-a432ad92-7ca5-11e8-9d9d-bcb0b1aa93ce.jpg)

Voice command: "문 열어줘" -> Operation: The door opens.<br><br>

![app_4doorclose](https://user-images.githubusercontent.com/40620102/42128918-a46c6136-7ca5-11e8-8597-c6e29b9c407b.jpg)

Voice command: "문 닫아줘" -> Operation: The door closes.<br><br>

![app_5fan](https://user-images.githubusercontent.com/40620102/42128919-a4bef1c6-7ca5-11e8-9b5e-153af0ca6e28.jpg)
![app_6fan2](https://user-images.githubusercontent.com/40620102/42128920-a4f47332-7ca5-11e8-8835-fd4fb51d62bb.jpg)

Voice command: "선풍기 약하게" -> Operation: The fan operates at a weak intensity.<br>
Voice command: "선풍기 보통으로" -> Operation: The fan operates at normal speed.<br>
Voice command: "선풍기 강하게" -> Operation: The fan operates with strong intensity.<br>
Voice command: "선풍기 꺼 줘" -> Operation: The fan is off<br><br>

![app_7led1](https://user-images.githubusercontent.com/40620102/42128921-a56065d8-7ca5-11e8-861a-74fae9bab7c0.jpg)

Voice command: "밝기 약하게" -> The brightness of the light turns on with a weak intensity.<br><br>

![app_8led2](https://user-images.githubusercontent.com/40620102/42128922-a5993f20-7ca5-11e8-9afa-84ade8604b55.jpg)

Voice command: "밝기 중간" -> The brightness of the light turns on with a medium intensity.<br><br>

![app_9led3](https://user-images.githubusercontent.com/40620102/42128923-a5cbac26-7ca5-11e8-8614-482801a7ac66.jpg)

Voice command: "밝기 강하게" -> The brightness of the light turns on with strong intensity.<br><br>
 
![app_10ledoff](https://user-images.githubusercontent.com/40620102/42128924-a60633f0-7ca5-11e8-9d0f-503c28b18883.jpg)

Voice command: "불 꺼 줘" -> The lights are off.<br><br>

![app_11spon](https://user-images.githubusercontent.com/40620102/42128925-a646ef62-7ca5-11e8-9e39-8d69e4229683.jpg)
![app_12spoff](https://user-images.githubusercontent.com/40620102/42128926-a697acfe-7ca5-11e8-866d-1c5c738b5c2d.jpg)

Voice command: "첫 번째 노래 켜 줘" -> The first song is turned on.<br>
Voice command: "두 번째 노래 켜 줘" -> The second song is turned on.<br>
Voice command: "세 번째 노래 켜 줘" -> The third song is turned on.<br>
Voice command: "노래 꺼 줘" -> The song is off.<br><br>



# Video clip

https://youtu.be/ZCb0IXo_x6Q

# Conclusion
Our project is to create a system that can be used with minimal action. Also, looking at the prospects of the smart home market, we are on an upward trend. The expected effect of using technology is to make daily life more convenient by minimizing the movement of people with disabilities due to exercise. The principle of operation is that voice commands are entered in the mobile phone application and each motor and device operates according to recognized commands. So people can improve their quality of life through Smart Home built on this voice recognition. It can be applied not only to individual home but also to various public facilities such as hospitals and schools. It will also have a wider range of uses because it can create and delete many necessary functions.





