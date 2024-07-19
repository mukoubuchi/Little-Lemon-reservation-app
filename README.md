# How to run

1. Unzip the uploaded file

1. Launch the Xcode application

1. Select [iPhone 15 (17.5)] from the top navigation bar

1. `StartingProject` -> TARGETS -> `StartingProject` -> `Starting & Capabilities`
   1. Team -> Set your team
   1. Bundle Identifier -> Add the date to the end of the string

<p align="center">
     <img src="https://github.com/mukoubuchi/Little-Lemon-reservation-app/blob/main/image/howToRun_1.png">
</p>

1. `Build Phases` -> `+` -> `New Run Script Phase` -> `Run Script` -> Shell /bin/sh -> Copy and Paste the following string
   - `/usr/bin/env xcrun --sdk macosx swift ${SRCROOT}/StartingProject/LitttleLemonLogo.swift ${SRCROOT}/StartingProject/LocationsView.swift ${SRCROOT}/StartingProject/MainView.swift ${SRCROOT}/StartingProject/Model.swift ${SRCROOT}/StartingProject/StartingProjectApp.swift`

<p align="center">
     <img src="https://github.com/mukoubuchi/Little-Lemon-reservation-app/blob/main/image/howToRun_2.png">
</p>

1. Press the triangle icon in the upper left corner.

1. Congratulations! The simulator will start soon.

<p align="center">
     <img src="https://github.com/mukoubuchi/Little-Lemon-reservation-app/blob/main/image/littleLemonReservation.gif">
</p>