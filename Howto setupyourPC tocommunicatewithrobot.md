## Overview
## 概览
### This section describes how to connect your PC to the robot controller.
#### 这一章节描述如何让你的PC连接机器人控制器
You can either connect the PC to the controller through an Ethernet network or directly to the controller service port. When using the controller service port, you can either obtain an IP address for the PC automatically, or you can specify a fixed IP address.

你可以选择使用以太网或者直接通过控制器服务端口连接PC。当时用控制器的服务端口，你可以自动获取IP地址或者指定一个。

When the PC and the controller are connected correctly, the controller is automatically detected by RobotStudio.

当PC与控制器正确的连接好后，控制器会自动的被Robotstudio检测到。

Note Note

A PC SDK application requires RobotStudio or ABB Robot Communications Runtime to connect to a controller in run-time. The latter is included in the RobotStudio installation.

PC SDK应用需要Robotstudio或者ABB Robot Communications Runtime来连接控制器在运行时间中。后者是包括在Robotstudio中的。

Why is a connection needed?

为什么需要连接？

Connecting the PC to the controller is necessary for all online tasks performed in RobotStudio. For example, downloading a robot system or files to the controller, editing configuration files, programming and so on.

连接PC至控制器在Robotstudio中进行在线任务中操作很有必要。举个栗子，从机器人控制器中下载机器人系统或者文件，编辑配置文件，编程等等。

It is necessary for executing PC applications targeting a real robot controller.

目标为机器人控制器为执行PC应用很有必要。

It also enables you to communicate with the controller by means of a console window on the PC and get valuable information about controller status, FlexPendant memory consumption and so on.

同时也能使你与机器人控制器通信借助于PC上的控制台窗口和获得关于控制器状态的有价值的信息、示教器存储用量等等。

Ethernet network connection

以太网连接

If the controller is connected to an Ethernet network, you can connect the PC to that network as well. The settings to use on the PC depends on the network configuration. To find out how to set up your PC, contact the network administrator.

如果控制器通过以太网络连接，你也可以通过PC和网络连接。这些在PC上用的设置以来网络配置。

Service port connection with automatic IP address

An alternative to network connection is using the controller service port. It has a DHCP server that automatically gives your PC an IP address if it is configured for this. For more information about configuring the PC to obtain an IP address automatically, see Windows Help on Configure TCP/IP settings.

Note Note

Obtaining an IP address automatically might fail if the PC already has an IP address from another controller or Ethernet device. To make sure that you get a correct IP address if the PC has already been connected to an Ethernet device, do one of the following:

如果PC已经通过其他控制器或者一台网络设备获得一个IP地址，那么它自动获得IP地址可能会失败。如果PC已经连接至一个以太网设备，为了确保你能获得一个正确的IP地址请做以下事项：

Restart the PC before connecting to the controller.

在连接控制器前重启PC。

Run the command ipconfig /renew from the command prompt after connecting the PC to the controller.

在ＰＣ连接控制器之后在ＣＭＤ中运行 ipconfig /renew 。

> [原文出处](http://developercenter.robotstudio.com/BlobProxy/devcenter/RobotCommunication/html/136d8d89-be7a-4c7d-9f50-ea9f11029aa7.htm)

> 翻译仅供参考
