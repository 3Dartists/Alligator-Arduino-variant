# Alligator-Arduino-variant

*Variant files to add support of Alligator Board in your arduino IDE Software*

### Install Alligator support on Arduino 1.5.8

1. Install Arduino 1.5.8
2. Navigate on your Arduino install directory and copy Alligator variant files:

  ##### For Windows:
  - Copy *alligator_r2* directory to 
  **C:\Program Files (x86)\Arduino\hardware\arduino\sam\variants\**

  - Replace the file **C:\Program Files (x86)\Arduino\hardware\arduino\sam\boards.txt**
    with the file **variant-Arduino-1.5.8\boards.txt**

  ##### For Mac OSX:
  - Copy **alligator_r2** directory to
  
    **/Arduino.app/Contents/Resources/Java/hardware/arduino/sam/variants/**

  - Replace the file **/Arduino.app/Contents/Resources/Java/hardware/arduino/sam/boards.txt**
    with the file **variant-Arduino-1.5.8/boards.txt**

3. run Arduino software and select : 

  Tools -> Board -> Alligator 3D Printer Board R2 ( Native USB Port)

