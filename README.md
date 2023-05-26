# xfinity-wifi-hack
This project aims to expose Xfinity's backdoor and utilizes a headless browser exploit to achieve it.

## Project Overview
Xfinity is a popular internet service provider, and their Wi-Fi service is used by many users. This project intends to shed light on a backdoor vulnerability in Xfinity's system and how it can be exploited.

## Methodology
This project utilizes a headless browser exploit to gain access to Xfinity's backdoor. The backdoor vulnerability can be accessed through this exploit, and the project will demonstrate how it can be accessed.



This is a `package.json` file for a project named `wifi-hack`. It includes metadata such as the project name, version, description, author, license, and dependencies. 

The `main` module of the project is `index.js`. It also has several specified scripts, including `preinstall`, `start`, and `test`. 

The dependencies are listed in two groups, `dependencies` and `devDependencies`, specifying the external packages/modules that the project is dependent on. The `dependencies` group includes packages that are used by the application at runtime, while `devDependencies` are packages used only during development/testing. 

There are several packages included here including `async`, `cron`, and `wifi-control`, among others. These packages provide various functionalities for the project.


This is a Node.js script that automates the process of connecting to the Xfinity Wi-Fi service using a headless browser exploit. 

It requires various modules including `CronJob`, `node-cmd`, `wifi-control`, `async`, `Nightmare`, and `macaddress`. The script includes functions for refreshing the wireless interface, spoofing the device's MAC address, and connecting to the Xfinity network using a headless browser. 

The script is initiated by a `CronJob` that triggers every hour to connect to the Xfinity network. A series of asynchronous tasks are executed that handle the various stages of the connection process.

The code also includes a global variable called `RUN_HEADLESS` that is set to `true` by default, and changing it to `false` will cause the script to run in regular environments instead of headless environments. This script is for educational purposes only.







## Disclaimer
This project is for educational purposes only. It is not intended to be used for any malicious purposes, and the project creators are not responsible for any misuse of this information.
