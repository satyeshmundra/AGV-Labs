# docs
This repository contains all the related information related to the testing conducted at AGV (IIT Kharagpur)

Plots
This file contains the localization plots of the different trajectories tested on the bot.
The names of the plot signifies the shape of the trajectory.
For each shape, results from different sensors are plotted like:
->only GPS
->Odometry + IMU
->GPS+Odometry+IMU
->setting different values for the covariance matrix
etc.

It can be seen that for smaller trajectories, the odometry data from encoders give accurate value while GPS data is erroneous.
On the other hand, for bigger trajectories the GPS data is consistent while encoders' data deviate greatly.
Therefore, the covariance matrix was set in such a way that the plot gives the best possible trajectory.

Bagfiles:
Here is the link for bagfiles whose name defines the trajectory of the bot.
It contains GPS, Odometry, IMU and final robot localization data.

link->https://drive.google.com/folderview?id=0BzLobSqOGGAhfmV2SXY1VHhPUkJGbnR2WmhrSTQtT2tMZHlWWW9NRGh5ckRXeDNTa1ZSSlk&usp=sharing

For bagfiles with no frame id:

link->https://drive.google.com/folderview?id=0BzLobSqOGGAhfk1NOHBMQVV6SUNaN21pM0phUE9ZeElHX19CRTlzNWlIWWhrZEpsOEdaaGc&usp=sharing
