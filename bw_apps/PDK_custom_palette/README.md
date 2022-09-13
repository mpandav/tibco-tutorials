# Write To Log - Custom Palette

In this example, we will be creating a new palette named WriteToLog having an activity called Log. This activity will take input from the user and print it over the console.

## How to use it?

- Download both plugin_DT and plugin_RT .zip files
- The DT contains desgintime project and RT contains runtime projects and BW application that implements custom palette activity.
- Create empty BustinessWorks Studio workspace and Set the Target PLatform to Design for plugin development 
- Import all the projects from plugnin_DT.zip 
- Make to set Target PLatform to Design -> it will make sure that only design features & model prohects will open in the workspace
- From within studion, click Run > Run Configurations to launch a child TIBCO Business Studio. 
- Now, in Child BusinessStudio -> Import runtime & features bundles priject from plugins_DT.zip
- Review the projects for errors.
- Improt the LogTest BusinessWorks application from plugin_RT.zip
- Review the application for errors and debug it.
- Outcome looks like something below

![custom plugin in action](https://user-images.githubusercontent.com/38240734/188712650-83308723-9bb2-4f0d-a727-c6aea9525202.png)



## Reference
For more details about - **Why PDK? What Does It Take? How To Use It?** check this **[blog](https://walkthrough.so/pblc/mjFqxnepAGZj/how-to-create-custom-tibco-bwce-plugin-using-plug-in-development-kit?usp=sharing)** out!
  
