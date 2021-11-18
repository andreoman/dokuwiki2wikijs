---
title: "How to use Fleet Configuration"
---
# How to use Fleet Configuration

This guide is a step-by-step overview of the **Fleet Configuration** page on RoscoLive.  
  
The **Fleet Configuration** page allows the user to create and define custom fleet profiles to apply to the cameras in the fleet.

## Step 1. Navigate to the Fleet Configuration Page

Locate and select the **Fleet Administration** option in the side-bar menu. <img src="/rosco/product/roscolive2.0/how_to_guide/fleet_administration/rlmanage_vehicles_menuoptionclosed.jpg" class="align-center" width="200" />  
  
Select the **Fleet Configuration** option in the now revealed drop-down menu under **Fleet Administration**. <img src="/rosco/product/roscolive2.0/how_to_guide/fleet_administration/rlfleetconfiguration_menuoption.jpg" class="align-center" width="200" />  
  

## Step 2. Fleet Configuration Page

This is the **Fleet Configuration** page. Notice there are three tabs to navigate the different menus on this page with the **General Settings** menu displayed first. <img src="/rosco/product/roscolive2.0/how_to_guide/fleet_administration/rlfleetconfiguration_pagetabemphasis.jpg" class="align-center" width="800" />  
  

The sections below will detail the different tab menus associated with the **Fleet Configuration** page.

### General Settings

The **General Settings** menu is the first menu displayed when inside the **Fleet Configuration** page. This menu allows the user to control the backlight intensity on the DVXC4 in both day and night mode as well as toggle the option to display the speed on the LCD screen.  
<img src="/rosco/product/roscolive2.0/how_to_guide/fleet_administration/rlfleetconfiguration_generalsettings_systemsettings.jpg" class="align-center" width="800" />

1.  To adjust the brightness intensity on the LCD backlight, drag the slider left to decrease the intensity or right to increase the intensity for the respective mode.
2.  Selecting this toggle enables or disables the speed display on the LCD of the DVXC4.

### Channel Settings

The **Channel Settings** menu is used to customize the channel settings for the DV camera. <img src="/rosco/product/roscolive2.0/how_to_guide/fleet_administration/rlfleetconfiguration_channelsettings.jpg" class="align-center" width="1000" />

1.  **Channel Toggles** - These toggle the corresponding channels of the camera on or off. When disabled, the camera associated with that channel will not record any audio or video.

```{=html}
<!-- -->
```
       - Channel 0 is the front facing camera on the DV.
       - Channel 1 is the inward facing camera on the DV.
       - Channel 2 & 3 are external camera channels.\\ \\ 
    - **FPS Settings** - These boxes customize the frame rate of the DV camera when in **Driving Mode** and **Parking Mode**. The values can range from 1 to 30 //frames per second// (FPS). The higher the frame rate the smoother the playback of the video will be, but this will also cause file sizes to become larger. It is recommended to have parking mode at a lower FPS than Driving FPS.\\ \\ 
    - **Video Quality Settings** - These boxes customize the video quality of the DV camera when in **Driving Mode** and **Parking Mode**. The quality settings range from 1 (lowest quality) to 5 (best quality). The higher the quality, the better resolution the DV will have, but this will also increase file sizes of the recordings. It is recommended to have the parking quality to be set low in order to preserve more space while the vehicle is idle. Channel 0 is capable of recording up to 720p quality, while the other channels are capable of recording up to 960H quality.\\ \\ 
    - **Audio Settings** - These options control if the corresponding channel records audio or not. Since the DV camera is equipped with a microphone, channels 0 and 1 are capable of recording audio when these options are turned to **ON**. Channels 2 and 3 are external cameras and will only record audio if those cameras are equipped with microphones.\\ \\ 

### Event Settings

The **Event Settings** menu allows for the customization and control of what events are triggered on the DVXC4 camera. This tab is separated into three sections with the first being **Event Settings**. <img src="/user/product/roscolive2.0/how_to_guide/fleet_administration/rlfleetconfiguration_eventsettings_eventsettings.jpg" class="align-center" width="800" />

1.  **Event Notification Toggles**
    1.  **Lock Event Files** - When enabled, this prevents event video files from being overwritten on the SD card. This setting is off by default.
    2.  **Audible Event Notification** - When enabled, an audible tone will be emitted from the DV camera when an event occurs.
    3.  **Driver Event Button Enabled** - When enabled, the *Driver Event* button on the DV will generate an event when pressed.
    4.  **External Driver Event Button** - When enabled, the *External Driver Event* button will generate an event when pressed.
    5.  **Speed Event Enabled** - When enabled, the DV will generate an event when it detects the vehicle exceeding the *Speed Threshold*. The speed threshold can be set in the box below the speed event toggle and MPH or KPH can be selected by the toggle next to it.  
          
2.  **Send Clip To Cloud** - When enabled, these send a video clip to the cloud when the corresponding event occurs.

#### G-Sensor Settings

The **G-Sensor Settings** options are used to enable, disable, or adjust the parameters of the G-Force sensor on the DVXC4. The two kinds of alerts generated are **Basic G-Sensor** and **Critical G-Sensor**. <img src="/rosco/product/roscolive2.0/how_to_guide/fleet_administration/rlfleetconfiguration_eventsettings_gsensorsettings.jpg" class="align-center" width="1200" />

1.  **G-Sensor Enabled / Trigger Output** - The G-Sensor Enabled toggle enables and disables the g-sensor in the DVXC4. The Trigger Output boxes can be configured for both *Basic* and *Critical* g-sensor events.
2.  **Send Clip To Cloud** - When enabled, these send a video clip to the cloud when either a *Basic* or *Critical* g-sensor event occurs.
3.  **G-Sensor Axis Settings** - These settings are used to enable, disable, and adjust the individual axes of the g-sensor. Each axis is labeled and can be enabled or disabled individually. The axis g-force sensitivity can be adjusted by using the input boxes in each of the three columns. The higher the setting, the less sensitive the sensor will be.
    1.  **Basic** - This column is for the basic g-sensor event sensitivity.
    2.  **Parking** - This column is for the g-sensor sensitivity when the DVXC4 is in parking mode.
    3.  **Critical** - This column is for the critical g-sensor event sensitivity.

### Step 3. Saving Configuration Settings

To save these settings to a custom fleet configuration profile, Click **Save** <img src="/rosco/product/roscolive2.0/how_to_guide/fleet_administration/rlfleetconfiguration_customprofile_save.jpg" class="align-center" width="1000" />

The **Fleet Profile** save dialog will appear. The configuration settings can be saved as a new configuration setting <img src="/rosco/product/roscolive2.0/how_to_guide/fleet_administration/rlfleetconfiguration_customprofile_newconfigdialog.jpg" class="align-center" width="600" /> Enter a new name for the configuration in the top field and select **Confirm** to save the new profile.

<img src="/rosco/product/roscolive2.0/how_to_guide/fleet_administration/rlfleetconfiguration_customprofile_availconfigdialog.jpg" class="align-center" width="600" /> To modify an existing custom fleet profile, select the profile from the **Available Profiles** drop down list and select confirm to save the new changes to the selected profile.
