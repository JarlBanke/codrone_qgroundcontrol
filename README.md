# QGroundControl Ground Control Station
```
git clone --recursive -j8 git@github.com:JarlBanke/qgroundcontrol.git
```
```
cd qgroundcontrol
```
```
git submodule update --recursive
```
```
./deploy/docker/run-docker.sh
```
Copy "CODRONE_QGroundControl.desktop" to desktop.<br/>
Edit file and change Exec path.<br/>
Select icon from "codrone_qgroundcontrol/resources/icons".<br/>
Allow Run as a program.<br/>
Allow Launching.<br/>
[![Releases](https://img.shields.io/github/release/mavlink/QGroundControl.svg)](https://github.com/mavlink/QGroundControl/releases)

*QGroundControl* (QGC) is an intuitive and powerful ground control station (GCS) for UAVs.

The primary goal of QGC is ease of use for both first time and professional users.
It provides full flight control and mission planning for any MAVLink enabled drone, and vehicle setup for both PX4 and ArduPilot powered UAVs. Instructions for *using QGroundControl* are provided in the [User Manual](https://docs.qgroundcontrol.com/en/) (you may not need them because the UI is very intuitive!)

All the code is open-source, so you can contribute and evolve it as you want.
The [Developer Guide](https://dev.qgroundcontrol.com/en/) explains how to [build](https://dev.qgroundcontrol.com/en/getting_started/) and extend QGC.

[New features in this release](https://github.com/mavlink/qgroundcontrol/blob/master/ChangeLog.md)

Key Links:
* [Website](http://qgroundcontrol.com) (qgroundcontrol.com)
* [User Manual](https://docs.qgroundcontrol.com/en/)
* [Developer Guide](https://dev.qgroundcontrol.com/en/)
* [Discussion/Support](https://docs.qgroundcontrol.com/en/support/support.html)
* [Contributing](https://dev.qgroundcontrol.com/en/contribute/)
* [License](https://github.com/mavlink/qgroundcontrol/blob/master/COPYING.md)
