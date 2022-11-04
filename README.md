
# babybuddydisplay
WT32-SC01 openHasp device to control Baby Buddy

Using this project to create a touchscreen device able to control [BabyBuddy](https://github.com/babybuddy/babybuddy) . At the moment just using basic controls to add feeds and diaper changes. I am using openHASP to run the plate and Home Assistant to interface with Baby Buddy.

I'm only expecting one baby at the moment, so it only supports one child. 

WT32-SC01 is a small device powered by a ESP32 chip with a ST7796S TFT screen and a FT6336U touch controller. It has a 320x480 screen and 4mb of ROM. 

**Example screenshot:**

![main_screen](https://user-images.githubusercontent.com/2961896/199961223-c59fdbec-482c-4211-b197-599c01bfdbbc.png)

![feed_screen](https://user-images.githubusercontent.com/2961896/199961227-22856b8a-266f-4ebe-a4f8-4817b7ff48b5.png)

**To Do:**

 - [x] Food 
	 - [x] Basic
	 - [ ] Volume?
 - [x] Diaper 
	 - [x] Wet
	 - [x] Solid
	 - [x] Wet and Solid
 - [ ] Sleep 	
	 - [ ] Sleep 	
	 - [ ] Nap 
 - [ ] Measurements 	
	 - [ ] BMI
	 - [ ]  Circumference 	
	 - [ ] Length 	
	 - [ ] Temperature 	
	 - [ ] Weight
