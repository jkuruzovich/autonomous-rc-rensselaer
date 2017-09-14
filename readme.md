# Autonomous RC Car@Rensselaer
*This proposal is to be submitted to the Burt Swersey Challenge Studio Call for Proposals, Due Oct15, 2017*

[https://www.dropbox.com/s/ehl6jfmq7dkx318/Lemelson-RFP%20v03.pdf?dl=0](https://www.dropbox.com/s/ehl6jfmq7dkx318/Lemelson-RFP%20v03.pdf?dl=0)

## **Team**
----------

Jason Kuruzovich (Faculty)

-insert your name here


## **Problem Statement**
----------

Self-driving cars are about to change the world, transforming everything from commerce and supply chain to durable goods ownership.  Traffic related deaths in the US alone are estimated at 33,000, potential benefits around self-driving cars

These benefits have made the demand for self-driving car engineers staggering.  However, because self-driving cars require mechanical systems, deep learning, hardware, sensors innovations, traditional technical education at places other than a few institutions have been unable to incorporate the wide array of technologies and skills required for these complex systems into traditional academic preparation.

In order to allow autonomous vehicles to have the safety and economic impact on society we need to improve the access to opportunities to incorporate these systems into formal and informal education.

## **Solution Approach**
----------

Rensselaer has a long history of integrative education through hands-on interdisciplinary project teams around transportation, with existing groups including  [RPI formula Hybrid](https://urchinz.github.io/FH_Web/), [RPI ChemE Car Team](http://union.rpi.edu/clubs/academic-professional/606-cheme-car-team), [Rensselaer Electric Vehicle](http://union.rpi.edu/clubs/hobby-special-interest/187-rensselaer-electric-vehicle), and [Rensselaer Motorsports](http://union.rpi.edu/clubs/hobby-special-interest/16-rensselaer-motorsport) just to name a few.

**This proposal outlines a plan for the development of an Autonomous RC Car group at Rensselaer, with the ultimate goal of hosting the first** ***International Intercollegiate Autonomous RC Racing Event*** **right here in Troy, NY at** [**Full Throttle RC Park**](http://www.fullthrottlercpark.com)**.**

There are four existing projects which represent powerful technological infrastructure which can facilitate great access to Autonomous Vehicle Education.  These include the [Microsoft AirSim Project](https://github.com/Microsoft/AirSim), [Ardupilot Rover](http://ardupilot.org/rover/), [MIT Racecar](https://mit-racecar.github.io/hardware/),  and [f1/10](http://f1tenth.org).  While each of these projects incorporates potential technical innovations, by establishing a group with collective intelligence in each we believe that we will be able to establish a solid platform of open software and hardware which can facilitate an intercollegiate competition.

*Microsoft AirSim.* The Microsoft AirSim project will provide the foundational  simulated environment in which students can learn concepts even if they don’t have access to the hardware.  Built on the Unreal Gaming Engine, the AirSim project provides a realistic environment for training drones and ground based vehicles.  However, a limitation is that there is no clear way of linking the AirSim software to RC vehicles.

*Ardupilot Rover.  The* Ardupilot Rover project incorporates GPS and route planning for complex route navigation, with control situated at a base station.  The system also works directly with an RC transmitter, which can be used to incorporate *human-in-the-loop* training. While powerful, the lack of onboard computer limits the degree to which high bandwidth data can effectively be used as a control.

*MIT Racecar.* The MIT racecar incorporates the latest hardware and sensor technology, incorporating both a NVIDIA Jetson GPU unit as well as LIDAR sensor technology.  These technologies (along with a few others) facilitate rapid steering and response to obstacles.  However, unlike the Ardupilot Rover there is not GPS for Route planning or incorporation of controller for *human-in-the-loop* training.

**Table 1. Summary of Existing Projects and Capabilities**

|                 | Realistic Simulation Envirnment | Physical Vehicle | Human-in-the-Loop | GPS Nav | On-Board Computing | Advanced Sensors |
| --------------- | ------------------------------- | ---------------- | ----------------- | ------- | ------------------ | ---------------- |
| AirSim          | X                               |                  | X                 | X       |                    | X                |
| Ardupilot Rover | X                               | X                | X                 |         |                    |                  |
| MIT Racecar     |                                 | X                |                   |         | X                  | X                |
| RPI AV          | X                               | X                | X                 | X       | X                  | X                |




## **Project Plan**
----------

While the vision is for Rensselaer impact on global autonomous vehicle education, the goals of the *Burt Swersey Challenge Studio* proposal are to create community of students, faculty, external mentors, and organizations with access to resources enabling autonomous vehicle education through the use of RC cars @Rensselaer.

Plan
TBD



## **Budget**

The budget allows for the creation of 2 1/10th scale


| Item                                      | Quanity | Cost       | Total  |                                                                                                                                                                                                                                                |
| ----------------------------------------- | ------- | ---------- | ------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Traxxas 1/10th Car platform               | 2       | $300       | $600   | [http://www.jegs.com/i/Traxxas/430/74054-6/10002/-1](https://www.google.com/url?q=http://www.jegs.com/i/Traxxas/430/74054-6/10002/-1&sa=D&ust=1505407940051000&usg=AFQjCNEO73PO5foV8ZMTAr_SWHP3XNfKqw)                                         |
| Picostation                               | 2       | $73        | $146   | [http://amzn.to/29QPlq8](https://www.google.com/url?q=http://amzn.to/29QPlq8&sa=D&ust=1505407940051000&usg=AFQjCNGmS9-Ml8vnsE6sR65SE1UXcV-aYg)                                                                                                 |
| Energizer Battery Pack                    | 2       | $159       | $318   | [http://amzn.to/2aaBmHu](https://www.google.com/url?q=http://amzn.to/2aaBmHu&sa=D&ust=1505407940051000&usg=AFQjCNFExMLRKGLO6SWoCjbFcGmsxo8qJQ)                                                                                                 |
| Nvidia Jetson                             | 2       | $193       | $386   | [http://amzn.to/29EI3C2](https://www.google.com/url?q=http://amzn.to/29EI3C2&sa=D&ust=1505407940052000&usg=AFQjCNGkhFr-T7P7-VIqbiZeKklvyd7duQ)                                                                                                 |
| USB Hub                                   | 2       | $30        | $60    | [http://amzn.to/29D7kKG](https://www.google.com/url?q=http://amzn.to/29D7kKG&sa=D&ust=1505407940052000&usg=AFQjCNHM2tmFI_NRwG3MxC504R4wJfOkSg)                                                                                                 |
| FTDI                                      | 2       | $15        | $30    | [https://www.sparkfun.com/products/9873](https://www.google.com/url?q=https://www.sparkfun.com/products/9873&sa=D&ust=1505407940052000&usg=AFQjCNHhZIqmSOlDECNiDN3JjpJgeYSFLw)                                                                 |
| Sensors                                   | 2       | $0         | $0     |                                                                                                                                                                                                                                                |
| SparkFun 9DoF Razor IMU M0                | 2       | $50        | $100   | [https://www.sparkfun.com/products/14001](https://www.google.com/url?q=https://www.sparkfun.com/products/14001&sa=D&ust=1505407940052000&usg=AFQjCNELBq-DtWxxyfzL0EaD0Zs60QBj0Q)                                                               |
| LIDAR                                     | 2       | $1,775     | $3,550 | [https://acroname.com/products/HOKUYO-UST-10LX-LASER?sku=R359-UST-10LX](https://www.google.com/url?q=https://acroname.com/products/HOKUYO-UST-10LX-LASER?sku%3DR359-UST-10LX&sa=D&ust=1505407940053000&usg=AFQjCNF4gsoHzu9I-kmF-MBGDvVVvqAv4w) |
| Structure Sensor                          | 2       | $379       | $758   | [https://store.structure.io/store](https://www.google.com/url?q=https://store.structure.io/store&sa=D&ust=1505407940053000&usg=AFQjCNFDlvhjAydvy5RQExQcd1kiAL3xww)                                                                             |
| ZED Camera                                | 2       | $449       | $898   | [https://www.stereolabs.com/](https://www.google.com/url?q=https://www.stereolabs.com/&sa=D&ust=1505407940053000&usg=AFQjCNGZIGc-GvL59XNQ7qmfgBzqhP2TmA)                                                                                       |
| Mechanical                                | 2       | $0         | $0     |                                                                                                                                                                                                                                                |
| Traxxas 3769 Spring Preload Spacers       | 2       | $5         | $10    | [http://amzn.to/2aazUF7](https://www.google.com/url?q=http://amzn.to/2aazUF7&sa=D&ust=1505407940053000&usg=AFQjCNE_4hkD1YsGKqTDNN2f6FV2pBiNQg)                                                                                                 |
| Allen Key Set                             | 2       | $9         | $18    | [http://amzn.to/29PazD5](https://www.google.com/url?q=http://amzn.to/29PazD5&sa=D&ust=1505407940054000&usg=AFQjCNHmdAaKq0as9L8lNfRdzV0DkFx7_g)                                                                                                 |
| 3mm ABS                                   | 2       | $6         | $12    | [http://amzn.to/29E6CTy](https://www.google.com/url?q=http://amzn.to/29E6CTy&sa=D&ust=1505407940054000&usg=AFQjCNE-d8Gl75ggzlcoGeVtS6CWWfAzkg)                                                                                                 |
| 6mm ABS                                   | 2       | $10        | $20    | [http://amzn.to/29PayPj](https://www.google.com/url?q=http://amzn.to/29PayPj&sa=D&ust=1505407940054000&usg=AFQjCNEswg3ry3XhlYW2J05FfIXdcSE-4A)                                                                                                 |
| Pixhawk Mini                              | 2       | $230       | $460   | http://goo.gl/QiK5D1                                                                                                                                                                                                                           |
| FrSky 2.4GHz ACCST TARANIS X9D  RC Remote | 2       | $230       | $460   | https://goo.gl/QdRjtY                                                                                                                                                                                                                          |
| Unbudgeted Hardware Allowance (10%)       |         | $0         | $783   |                                                                                                                                                                                                                                                |
| Food Support for Team Meetings            |         | $1,200     | $1,200 |                                                                                                                                                                                                                                                |
|                                           |         | **Total:** | $9,809 |                                                                                                                                                                                                                                                |
