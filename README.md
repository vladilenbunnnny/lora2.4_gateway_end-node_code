# Code description

----
## LoRa 2.4 gateway 

 In order to launch the gateway, the user has to follow the steps described in the User Guide pdf document that sits in the main directory of gateway folder. 

 At the same time the SX1280 LoRa end-node folder contains a file name "Modifications and steps" that contains summary of the steps needed to take while launching the gateway in Bash/Terminal

These steps (compilation of the gateway) are needed to take every time the user wants to run the gateway

----
## SX1280 LoRa end-node  

This folder contained all the necessary code needed to launch the end node. However, once the code is uploaded to the microcontroller, it will stay there forever. Once the device is powered, the end-node will emit messages. Putty terminal can be used to see the logs of the end-node.