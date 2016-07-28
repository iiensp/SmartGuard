#Smart Guard

##Introduction
This is a apk file for our INFOCOM 2017 paper "Personalized Privacy Preservation in Mobile Social Networks: Framework and Application". In this work, we propose a general framework, termed Smart Guard, which comprehensively models the relationships between the current status of user's device, different privacy preserving mechanisms, relative parameters and the resource consumptions, and recommends personalized privacy preserving strategy for mobile users in MSNs.

##Implementation Details
In our implementation, we focusing on the tradeoffs between battery capacity cost, network tariff and privacy requirement. We provide two PPMs(Privacy Preserving Mechanisms) for privacy preservation, Paillier-based and k-anonymity-based approaches, each of them has two parameters. We denote Paillier with 512 bits and 2048 bits key length, k-anonymity with k = 10, 30. 

As a result, based on the current state of the device and the privacy requirement, the apk give a reasonable PPM and parameter.

##Target platforms
* API level 16 or later

##ScreenShots
![Main Window](https://github.com/iiensp/SmartGuard/blob/master/Screenshots/mainlayout.png)
![Get recommendation](https://github.com/iiensp/SmartGuard/blob/master/Screenshots/recommendation.png)
