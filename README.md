# capstone-design
Maker B

Smart home based on voice recognition
![default](https://user-images.githubusercontent.com/40620102/42127824-d76b2714-7c8e-11e8-9603-ae791bde9d94.jpg)

# Used program

ATmega128


App inventor


about App Inventor
http://appinventor.mit.edu/explore/about-us.html

![appinventor2](https://user-images.githubusercontent.com/40620102/42127854-88502b60-7c8f-11e8-8830-d5d4699a7bb2.png)



# logic summary
-The app was created through App Inventor.

-It communicates the application with the ATmega via Bluetooth.

-The application receives voice commands with voice recognition tool.

-The input command is converted from the ATmega.

-In ATmega, the input command is output to the circuit.




-LED has three levels of brightness control. Brightness can be controlled by PWM control.

-DOOR has opening and closing function. This controls the angle of the servo motor at the ATmega.

-SPEAKER can turn on and play three songs.

-FAN controls the wind intensity in three steps. The speed of the fan can be controlled by PWM control.

 
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


(1) Set the functions that the main users need within the home. (Ref. Interview material)

(2) Create an application that uses the App Inventor to accept voice commands. Voice recognition is performed using the speech recognition function provided by App Inventor.

(3) Using ATmega, we create code that controls the functions of 1

(4) Make a circuit configuration in which functions of smart home operate with received voice command

(5) Expectations when applied by making actual model

# Key Considerations
In order to increase the utilization rate, the accessibility should be good, but it is necessary to use the functions that are frequently used in the house.

# Target interview

![interview_note1](https://user-images.githubusercontent.com/40620102/42127872-a03efc7e-7c8f-11e8-8677-b3f4e22bfe2d.jpg)
![interview_note2](https://user-images.githubusercontent.com/40620102/42127876-a07af580-7c8f-11e8-9c3d-8af4c15cc9dc.jpg)

![interview1](https://user-images.githubusercontent.com/40620102/42127880-a0b4a1d6-7c8f-11e8-8ab8-93518bf827d4.PNG)
![interview2](https://user-images.githubusercontent.com/40620102/42127882-a0f20c1a-7c8f-11e8-9711-090c663dea2c.PNG)

# Material

The following parts were used.

Application and ATmega Connection: Bluetooth Module HC-06 Firmware v3.0

Speaker: 40mm 8Ohm 1W Speaker, Melody IC

FAN: 10,000 RPM FAN MOTOR

DOOR: Mini Servo-Motor SG-90

LED: LED

![material1](https://user-images.githubusercontent.com/40620102/42127885-a6f9f9f6-7c8f-11e8-9099-de53992758de.PNG)
![material2](https://user-images.githubusercontent.com/40620102/42127886-a7368f42-7c8f-11e8-88c3-ab2d8f90d9ee.PNG)

# Production process

![app_block1](https://user-images.githubusercontent.com/40620102/42127855-8bce594c-7c8f-11e8-979e-4842828356bf.png)
![app_block2](https://user-images.githubusercontent.com/40620102/42127856-8c0c4d88-7c8f-11e8-93da-c0e4edc9c4a1.png)
![app_block3](https://user-images.githubusercontent.com/40620102/42127857-8c3bd0bc-7c8f-11e8-9cc2-f016b362be8a.png)

![d_all](https://user-images.githubusercontent.com/40620102/42127889-b3cb850a-7c8f-11e8-9a15-9e1086c5a98e.jpg)
![d_top](https://user-images.githubusercontent.com/40620102/42127891-b4052d8c-7c8f-11e8-816f-c53b5eea13ca.jpg)
![d_circuit](https://user-images.githubusercontent.com/40620102/42127859-9118ba64-7c8f-11e8-9ce8-33d7063a62ed.jpg)

# Video clip

https://youtu.be/ZCb0IXo_x6Q

# Conclusion
Our project is to create a system that can be used with minimal action. Also, looking at the prospects of the smart home market, we are on an upward trend. The expected effect of using technology is to make daily life more convenient by minimizing the movement of people with disabilities due to exercise. The principle of operation is that voice commands are entered in the mobile phone application and each motor and device operates according to recognized commands. So people can improve their quality of life through Smart Home built on this voice recognition. It can be applied not only to individual home but also to various public facilities such as hospitals and schools. It will also have a wider range of uses because it can create and delete many necessary functions.





