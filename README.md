# Project 0_0: Setting Up Your Environment
This is a guide on how to set up your programming environment on your computer to start programming robots in the ***FIRST Robotics Competition (FRC).*** This guide should work for Windows, MacOS, and Linux with the included guides. Please read through this carefully and follow every single instruction.

## ***WPILib***
### What is WPILib?
<!---![](WPILibLogo.png)--->
<img src="images\WPILibLogo.png" alt="drawing" width="200"/>

WPiLib is code library developed by Worcester Polytechnic Institute (WPI) built for the ***FIRST Robotics Competition (FRC).*** This library contains helpful classes starting from direct interaction with motors, pneumatics, LEDs all the way to advanced path planning. Officially supported languages are Java and C/C++. ([Read More](https://docs.wpilib.org/en/stable/docs/software/what-is-wpilib.html#:~:text=The%20WPI%20Robotics%20Library%20(WPILib,and%20used%20by%20other%20software.)))

<!---![](WPILoc.jpeg)--->
<img src="images\WPILoc.jpeg" alt="drawing" width="200"/>

WPILib is the basis of FRC Programming. All other programs and libraries will built around WPILib. Teams start off with WPILib and build upon this central library when they become more advanced. 

WPILib usually has yearly releases parallel to yearly FRC game releases where the library of code is updated to fit new hardware and new features are added. 

### How to Install WPILib?
Please follow [this guide](https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-2/wpilib-setup.html) to install WPILib.

## ***REVLib and REV Hardware Client***
### What is REVLib?
<!---![](REV.png)--->
<img src="images\REV.png" alt="drawing" width="200"/>

***REVLib*** is a 3rd party code library created by REV Robotics. This library is designed specifically to control REV Robotics products and devices such as the SPARKMAX Motor Controller or the REV Color Sensor. Similar to WPILib, REVLib is suppored in Java and C/C++. ([Read More](https://www.revrobotics.com/))

### What is REV Hardware Client?
<img src="images\SparkClient.png" alt="drawing" width="200"/>

Other than REVLib, REV Robotics has a desktop application called ***REV Hardware Client*** This is used to directly control motors without writing any code. You can also direct configure motors, update firmware on the PDH, etc. with this software.

### How to Install REVLib?
1. Please follow [this guide](https://docs.revrobotics.com/sparkmax/software-resources/spark-max-api-information#c++-and-java) to install REVLib .zip file.
2. Extract the files in the downloaded .zip
3. Open up the extracted REVLib folder. You should see maven and vendordeps
4. Drag/Move the files inside the extracted REVLib\\maven folder into 
(Windows) C:\\Users\\Public\\wpilib\\2022\\maven or (MacOS/Linux) ~/wpilib/2022/maven
5. Drag/Move the files inside the extracted REVLib\\vendordeps folder into
(Windows) C:\\Users\\Public\\wpilib\\2022\\vendordeps or (MacOS/Linux) ~/wpilib/2022/vendordeps

### How to Install REV Hardware Client?
Please follow [this guide](https://docs.revrobotics.com/sparkmax/spark-max-client/getting-started-with-the-spark-max-client) to install REV Hardware client.

## ***Phoenix and Phoenix Tuner***
### What is Phoenix?
<!---![](CTRE.png)--->
<img src="images\CTRE.png" alt="drawing" width="200"/>

***Phoenix*** is a 3rd party code library created by Cross The Road Electronics (CTRE). This is specifically used for CTRE devices such as the Falcon500, TalonSRX, and VictorSPX. This is also supported in Java and C/C++. ([Read More](https://store.ctr-electronics.com/))

### What is Phoenix Tuner?
<!---![](PTuner.png)--->
<img src="images\PTuner.png" alt="drawing" width="200"/>

***Phoenix Tuner*** is a tool created by CTRE to directly control motors like REV's SPARKMAX Client. This tool can also be used to assign ID's to devices, calibrate gyros, plot information, and even play music.

### How to Install Phoenix
- (Windows) Please follow [this guide](https://store.ctr-electronics.com/software/) to install Phoenix executable. Click on the downloaded file toe execute and install. 
- (MacOS/Linux) Please follow [this guide](https://store.ctr-electronics.com/software/) to install the Phoenix .zip file. 
	1. Extract the files in the downloaded .zip
	2. Open up the extracted REVLib folder. You should see maven and vendordeps
	3. Drag/Move the files inside the extracted Phoenix\\maven folder into 
(Windows) C:\\Users\\Public\\wpilib\\2022\\maven or (MacOS/Linux) ~/wpilib/2022/maven
	4. Drag/Move the files inside the extracted Phoenix\\vendordeps folder into
(Windows) C:\\Users\\Public\\wpilib\\2022\\vendordeps or (MacOS/Linux) ~/wpilib/2022/vendordeps

### How to Install Phoenix Tuner
The Phoenix Tuner is only available for Windows users. For Windows users, the Phoenix Tuner will be installed along side Phoenix when you ran the executable file. Just hit the windows key and search "Tuner" and you should be able to run it.

## ***Final Notes***
Please note you should update all of these libraries as soon as a new release comes out.

## ***Authors***
- [Team 3647, Edward Sun](https://github.com/EdwardoSunny)


