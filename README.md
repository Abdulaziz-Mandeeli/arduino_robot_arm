# arduino_robot_arm
المهمة الاولى لتدريب الاساليب الذكية

خطوات تنفيذ المهمة

أولا:
 ونعمل نسخ للباكج المدرج في حساب الاساليب الذكية على القيت هب باستعمال الاكواد التالية
	  $ cd ~/catkin_ws/src
	  $ sudo apt install git
	  $ git clone https://github.com/smart-methods/arduino_robot_arm 

ثانيا :
باستعمال الاكواد التاليةROSداخل ال workSpace نخلق 

![image](https://user-images.githubusercontent.com/85806841/123825452-97d13200-d907-11eb-8f1d-ab031a194114.png)
![image](https://user-images.githubusercontent.com/85806841/123825535-a7507b00-d907-11eb-9328-ca81cca8b362.png)

ومن ثم نتأكد من وجود هذه التوابع او تثبيتها من جديد باستعمال الاكواد التالية
	$ cd ~/catkin_ws
	$ rosdep install --from-paths src --ignore-src -r -y
	$ sudo apt-get install ros-melodic-moveit
	$ sudo apt-get install ros-melodic-joint-state-publisher ros-melodic-joint-state-publisher-gui
	$ sudo apt-get install ros-melodic-gazebo-ros-control joint-state-publisher
	$ sudo apt-get install ros-melodic-ros-controllers ros-melodic-ros-control

