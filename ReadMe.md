# Observium Network Checker
___

## Description
Observium is a network monitoring and management platform that provides 
real-time insight into network health and performance. It can automatically 
discover network devices and services, collect performance metrics, and generate
alerts when problems are detected.

Observium includes a web-based interface that allows suers to view network 
status and performance metrics in real time, as well as historical data. It is 
designed to be easy to use and maintain, with a focus on providing the 
information that network administrators need to quickly identify and resolve 
issues

Observium supports a wide range of device types, platforms and operating systems
including Cisco, Windows, Linux, HP, Juniper, Dell, FreeBSD, Brocade, Netscaler,
NetApp and many more.

Professionally developed and maintained by a team of experienced network 
engineers and systems administrators, Observium is a platform designed and built
by its users.
___

## Installation

There are tree ways to roll out a Observium instance.
Method one and two are based on an ubuntu 20.04 server-based image. and the last
method is based on a docker image/docker compose file.

### Method 1:
get the installation script of the official website wit wget
```bash 
wget http://www.observium.org/observium_installscript.sh
```
now make script executable
```bash 
chmod +x observium_installscript.sh
```
run the script (you probably have to execute the script with sudo in-front)
```bash 
./observium_installscript.sh
```

### Method 2:
to install Observium manually please visit their website and look into 
the documentation for further instructions.

### Method 3:

Steps for this method are pending.
