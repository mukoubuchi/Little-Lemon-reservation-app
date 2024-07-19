# How to run

1. Unzip the uploaded file

2. Launch the Xcode app

3. Set [iPhone 15 (17.5)] on the top navigation bar

4. [StartingProject] -> TARGETS -> [StartingProject] -> [Starting & Capabilities
   1. Team -> Set your Team
   2. Bundle Identifier -> Add the date on the tail of the string

<p align="center">
     <img src="https://github.com/mukoubuchi/Little-Lemon-reservation-app/blob/main/image/howToRun_1.png">
</p>

5. [Build Phases] -> [+] -> [New Run Script Phase] -> [Run Script] -> Shell /bin/sh -> Copy and Paste the following string
   - ```/usr/bin/env xcrun --sdk macosx swift ${SRCROOT}/StartingProject/LitttleLemonLogo.swift ${SRCROOT}/StartingProject/LocationsView.swift ${SRCROOT}/StartingProject/MainView.swift ${SRCROOT}/StartingProject/Model.swift ${SRCROOT}/StartingProject/StartingProjectApp.swift```

<p align="center">
     <img src="https://github.com/mukoubuchi/Little-Lemon-reservation-app/blob/main/image/howToRun_2.png">
</p>

6. Push the Triangle icon located on the top left

7. Congratulations! The simulator will be launched soon.

<p align="center">
     <img src="https://github.com/mukoubuchi/Little-Lemon-reservation-app/blob/main/image/littleLemonReservation.gif">
</p>