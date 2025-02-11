# Zephyr RTOS plugin for SEGGER Ozone
A plugin script that expands upon the zephyr rtos plugin shipped default with Ozone, adding extra features such as

 - Thread stack usage

## Installation
Download the script and set the path to the script in the project .jdebug file as such 
```
Project.SetOSPlugin("/absolute/path/to/ZephyrPlugin.js")
```
Alternatively you can replace the `ZephyrPlugin.js` found in Ozones `Plugins/OS` folder with this one and then set the plugin as normal, i.e
```
Project.SetOSPlugin("ZephyrPlugin.js")
```