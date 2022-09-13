# Write To Log - Custom Palette

In this example, we will be creating a new palette named WriteToLog having an activity called Log. This activity will take input from the user and print it over the console.

## How to use it?

- Download both plugin_DT and plugin_RT .zip files
- The DT contains desgintime project and RT contains runtime projects and BW application that implements custom palette activity.
- Create empty BustinessWorks Studio workspace.
- Import all the projects from plugnin_DT.zip 
- Set the Target PLatform to Design for plugin development. To set the Target Platform, **click File -> New -> Create a new or modify BusinessWorks plugin project -> expand Target Platform and select Design**. 
- Make sure to set Target PLatform to Design -> it will make sure that only design features & model prohects will open in the workspace
- From within studio, **click Run > Run Configurations > Eclipse Application > New configuration (use default settings) to launch a child TIBCO Business Studio**. 
- Now, in Child BusinessStudio -> **Import runtime & features bundles project from plugins_DT.zip**
- Review the projects for errors.
- Import the LogTest BusinessWorks application from plugin_RT.zip Or you can create new BW application, add Timer process starter and our new custom activity that we build. Configure the activitiy and save it.
- Review the application for errors and Debug/Run it.

- Outcome looks like something below

![custom plugin in action](https://user-images.githubusercontent.com/38240734/188712650-83308723-9bb2-4f0d-a727-c6aea9525202.png)



## Reference
For more details about - **Why PDK? What Does It Take? How To Use It?** and more details check this **[blog](https://walkthrough.so/pblc/mjFqxnepAGZj/how-to-create-custom-tibco-bwce-plugin-using-plug-in-development-kit?usp=sharing)** out!
  
