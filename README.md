# xfinity-wifi-hack
This project aims to expose Xfinity's backdoor and utilizes a headless browser exploit to achieve it.

## Project Overview
Xfinity is a popular internet service provider, and their Wi-Fi service is used by many users. This project intends to shed light on a backdoor vulnerability in Xfinity's system and how it can be exploited.

## Methodology
This project utilizes a headless browser exploit to gain access to Xfinity's backdoor. The backdoor vulnerability can be accessed through this exploit, and the project will demonstrate how it can be accessed.


## package.json

This is a `package.json` file for a project named `wifi-hack`. It includes metadata such as the project name, version, description, author, license, and dependencies. 

The `main` module of the project is `index.js`. It also has several specified scripts, including `preinstall`, `start`, and `test`. 

The dependencies are listed in two groups, `dependencies` and `devDependencies`, specifying the external packages/modules that the project is dependent on. The `dependencies` group includes packages that are used by the application at runtime, while `devDependencies` are packages used only during development/testing. 

There are several packages included here including `async`, `cron`, and `wifi-control`, among others. These packages provide various functionalities for the project.

## index.js

This is a Node.js script that automates the process of connecting to the Xfinity Wi-Fi service using a headless browser exploit. 

It requires various modules including `CronJob`, `node-cmd`, `wifi-control`, `async`, `Nightmare`, and `macaddress`. The script includes functions for refreshing the wireless interface, spoofing the device's MAC address, and connecting to the Xfinity network using a headless browser. 

The script is initiated by a `CronJob` that triggers every hour to connect to the Xfinity network. A series of asynchronous tasks are executed that handle the various stages of the connection process.

The code also includes a global variable called `RUN_HEADLESS` that is set to `true` by default, and changing it to `false` will cause the script to run in regular environments instead of headless environments. This script is for educational purposes only.


## gitignore

This is a `.gitignore` file that lists the files and directories that should be ignored (not tracked) by git when committing changes to a repository. 

The file includes comments to help explain what each section of the file does. 

The first section, `# Logs`, lists common log files that should be ignored, including `*.log` and `npm-debug.log*`.

The second section, `# Runtime data`, is for files related to runtime data that should be ignored, such as `.pid` files and lock files.

The third section, `# Directory for instrumented libs generated by jscoverage/JSCover`, is for a directory that contains instrumented libraries generated by code coverage tools like jscoverage or JSCover.

The fourth section, `# node-waf configuration`, is for a lock file that is generated by the build tool node-waf during the build process, which can be ignored.

The fifth section, `# Compiled binary addons`, is for compiled binary addons generated by native modules that should be ignored.

The sixth section, `# Dependency directories`, is for directories that contain dependencies, such as `node_modules` and `jspm_packages`.

The seventh section, `# Optional npm cache directory`, is for the optional npm cache directory, `.npm`, which might contain large files that can be ignored.

The last section, `# Output of 'npm pack'`, is for files generated by the `npm pack` command that creates a compressed tar archive of the module. This section includes `*.tgz` files.





## Disclaimer
This project is for educational purposes only. It is not intended to be used for any malicious purposes, and the project creators are not responsible for any misuse of this information.
