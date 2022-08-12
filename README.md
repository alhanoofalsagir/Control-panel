# IOT Task 🗣:

## Description 📄: 
*The aim of this project is to control a robot's move remotely without the need for direct intervention. In order to achieve this, a web interface has been designed to helps the user control the robotic arm. Moreover, this project relied on databases in the process of communication between hardware components and commands sent from a web page by PHP.*

## tools 🛠:
○ HTML <br />
○ CSS <br />
○ JavaScript <br />
○ PHP <br />
○ MYSQL <br />

## interface ⭐:
*The interface is designed in a simple way for ease of use.Figure 1 for the large screen and Figure 2 for the mobile web interface (small screen).*
<p align="center">
    <img src="image/interfaceA.png" alt="interface" width="700">
    <p align="center">
        figure 1: Interface.
    </p>
</p>
    <br>
<p align="center">
    <img src="image/mobileInterface.png" alt="mobile interface" width="375">
    <p align="center">
        figure 2: Mobile web interface.
    </p>
</p>
<br>
In the interface, the gif and image are used to make the current state of the robot visible to the user. see figure 3,4,5,6,7, and 8
<p align="center">
    <img src="image/stop.gif" alt="Stop state" width="150"><br>
    figure 3: Stop state.<br>
    <img src="image/start.png" alt="Start stat (English)" width="150"><br>
    figure 4: Start stat.<br>
    <img src="image/forward.gif" alt="Forward move" width="150"><br>
    figure 5: Forward move.<br>
    <img src="image/left.gif" alt="Left move" width="150"><br>
    figure 6: Left move.<br>
    <img src="image/right.gif" alt="Right move" width="150"><br>
    figure 7: Right move.<br>
    <img src="image/backward.gif" alt="Backward move" width="150"><br>
    figure 8: Backward move.<br>
</p>

## database :mag_right: :
*This project only needs to design two tables. One is to save the current state for the robot (Table 1) and the other is to save the last action performed (Table 2).*
<br/>
<p align="left"> Table 1: Moves table.
</p>

| Attribute |                   Description                      | Datatype |  PK |
|:---------:|:--------------------------------------------------:|:--------:|:---:|
|    id     |       This id used to determine which robot        |  integer | yes |
|    run    | Used to check whether the robot has started or not |  string  | no  |
|    move   |      Used to store the direction of movement       |  string  | no  |
<br/>
<p align="left"> Table 2: Last move table.
</p>

| Attribute |              Description              | Datatype |  PK |
|:---------:|:-------------------------------------:|:--------:|:---:|
|    id     | This id used to determine which tobot |  integer | yes |
|   action  |     Used to store the last action     |  string  | no  |
