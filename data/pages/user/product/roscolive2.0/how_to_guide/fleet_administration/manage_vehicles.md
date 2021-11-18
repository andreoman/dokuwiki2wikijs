---
title: "How to Manage Vehicles"
---
# How to Manage Vehicles

This page is a step-by-step overview of the **Manage Vehicles** page on RoscoLive.  
  
The **Manage Vehicles** page allows the user to see and manage fleet vehicles within the groups they have access to.

## Step 1: Navigate to the Manage Vehicles page

Locate and select the **Fleet Administration** option in the side-bar menu. <img src="/user/product/roscolive2.0/how_to_guide/fleet_administration/rlmanage_vehicles_menuoptionclosed.jpg" class="align-center" width="200" />  
  
Select the **Manage Vehicles** option in the now revealed drop-down menu under **Fleet Administration**. <img src="/user/product/roscolive2.0/how_to_guide/fleet_administration/rlmanage_vehicles_menuoptionopen.jpg" class="align-center" width="200" />

## Step 2: Manage Vehicles page

This is the **Manage Vehicles** page. From here, the user is able to see the fleet vehicles for the groups they have access to.  
*NOTE: The options available to the user may vary depending on user permissions.*  
  
<img src="/user/product/roscolive2.0/how_to_guide/fleet_administration/rlmanage_vehicles_page.jpg" class="align-center" width="800" />  
  

### Vehicle Name

This column consists of the names of vehicles within the fleet. This can only be changed by the "Fleet Manager" or higher roles. If any assistance is needed, please contact us [here](/contact_us).

### Vehicle ID

This column consists of the serial numbers of the DV440 cameras provisioned for their respective vehicles. For help with provisioning or to re-provision a vehicle, please contact RoscoLive customer support [here](/contact_us).

### Connection Status

This column shows the connection status for **Live Video**, **Tracking Server**, and **Video Storage**.  
If the icon is \<color #ed1c24>RED\</color>, the service is *off*. If the icon is \<color #22b14c>GREEN\</color>, the service is *on*.  
  

### Enable/Disable toggle

Selecting this toggle enables or disables the vehicle's service features. This does **NOT** enable or disable the local event recording from the DV440.

### Actions

This column consists of actions that are available to the current user for managing vehicles. The options in this column vary with user's permissions.

## Step 3: Editing Vehicle Info

Select the **Edit** icon in the **Actions** column of the **Manage Vehicles** page for the desired vehicle to open the **Edit Vehicle** window. <img src="/user/product/roscolive2.0/how_to_guide/fleet_administration/rlmanage_vehicles_editicon.jpg" class="align-center" width="200" />

## Step 4: Edit Vehicle Window

The **Edit Vehicle** window should look similar to this page. <img src="/user/product/roscolive2.0/how_to_guide/fleet_administration/rlmanage_vehicles_editvehiclewindow.jpg" class="align-center" width="800" />  
  

### Group Assigning

At the top left corner of this page, the vehicle's associated *device ID* and *company name* is displayed. The section below this is where the vehicle can be assigned to a group within the fleet. The box labeled **Potential group(s)** is where all of the fleet's active groups are. The box labeled **Active assigned group** is where the group that the selected vehicle is assigned. Groups can be interchanged between the boxes by using the arrow buttons in-between the boxes. Vehicles can only be active in one group at a time. <img src="/user/product/roscolive2.0/how_to_guide/fleet_administration/rlmanage_vehicles_groupassign.gif" class="align-center" width="800" />

### Vehicle Info

This section has the **Vehicle Name**, **Driver Name**, and **Vehicle Icon**. Enter the driver's name for the selected vehicle into the text box, and select an icon from the icon drop-down menu. This icon is what will represent the vehicle on the Google Map overlay on the **GPS Tracking & Live Stream** page. The vehicle names can be changed by simply input it here and click the "Save" button at the bottom. The change will update the corresponding config settings on the device automatically. \<color #ed1c24>This name change function only available for the fleet manager or higher roles.\</color> If you experience any issues or difficulties, please contact [us](/contact_us). <img src="/user/product/roscolive2.0/how_to_guide/fleet_administration/rlmanage_vehicles_vehnamedrivernamevehicon.jpg" class="align-center" width="600" />

### User Assigning

This section is used to assign particular users to the vehicle. This feature can be used to customize what vehicles users can see. The box labeled **Potential Users** is the list of all the users within the fleet. The box labeled **Active Assigned User(s)** is the user or users assigned to this particular vehicle. Users can be interchanged between the boxes using the arrow buttons located in-between the boxes. <img src="/user/product/roscolive2.0/how_to_guide/fleet_administration/rlmanage_vehicles_userassign.gif" class="align-center" width="600" />

### Enable/Disable Toggle

This toggle performs the same function as the //Enable / Disable // toggle on the **Manage Vehicles** page. This toggle enables or disables the vehicle's service features. This does **NOT** enable or disable the local camera hardware. <img src="/user/product/roscolive2.0/how_to_guide/fleet_administration/rlmanage_vehicles_enabledisabletoggle.jpg" class="align-center" width="200" />

### Save Changes

After adding or editing the vehicle information, select the **Save** button at the bottom of this page. Select the **Back** button to return to the **Manage Vehicles** page.  
<u>**NOTE**: Remember to click SAVE before clicking BACK to save any unsaved information.</u> <img src="/user/product/roscolive2.0/how_to_guide/fleet_administration/rlmanage_vehicles_savebackicons.jpg" class="align-center" width="400" />

## Step 5: Remote Management

Select the **Remote Management** icon in the **Actions** column of the **Manage Vehicles** page for the desired vehicle to open the **Remote Management** window. <img src="/user/product/roscolive2.0/how_to_guide/fleet_administration/rlmanage_vehicles_remotemanagementicon.jpg" class="align-center" width="200" />

This is the **Remote Management Window**. This window allows for remote device management of the DV440 installed in the vehicle.

<img src="/user/product/roscolive2.0/how_to_guide/fleet_administration/rlmanage_vehicles_remotemanagementwindow.jpg" class="align-center" width="600" />

### Download / Upload Device Configuration

\<color #ed1c24><u>**WARNING**: CHANGES TO THE DEVICE'S CONFIGURATION FILE CAN ADVERSELY AFFECT DEVICE PERFORMANCE IF CONFIGURED INCORRECTLY. PLEASE CONTACT ROSCOLIVE CUSTOMER SUPPORT TO HANDLE ANY DEVICE CONFIGURATION FILE CHANGES.</u>\</color>  
  

The **Download Device Configuration** section and **Upload Configuration** section is used to manage device configuration files.

<img src="/user/product/roscolive2.0/how_to_guide/fleet_administration/rlmanage_vehicles_remotemanagementicon_configuploaddownload.jpg" class="align-center" width="600" />  
  

To download the current device configuration file, select the **DOWNLOAD** button.

<img src="/user/product/roscolive2.0/how_to_guide/fleet_administration/rlmanage_vehicles_remotemanagementicon_configdownloadarrow.jpg" class="align-center" width="600" />  
  

The download request will be sent to the server and the last known configuration will be downloaded to your browser with the filename "config.txt".

<img src="/user/product/roscolive2.0/how_to_guide/fleet_administration/rlmanage_vehicles_configdownloadfile.jpg" class="align-center" width="400" />

***NOTE**: If the device never connected to the server before, this popup notification will appear in the top right corner of the page:*

<img src="/user/product/roscolive2.0/how_to_guide/fleet_administration/rlmanage_vehicles_remotemanagement_deviceconfigdoesntexist.jpg" class="align-center" width="200" />  
  

To upload a new configuration file to the device, click **Select a file** to open up the file browser.

<img src="/user/product/roscolive2.0/how_to_guide/fleet_administration/rlmanage_vehicles_remotemanagementwindow_selectafile.jpg" class="align-center" width="600" />  
  

Navigate to the folder where the "config.txt" file is to upload and select it. In this example picture, the file was located in the "Downloads" folder.

<img src="/user/product/roscolive2.0/how_to_guide/fleet_administration/rlmanage_vehicles_remotemanagement_fileconfig.jpg" class="align-center" width="800" />  
  

After the configuration file has been selected, select the **Reboot** toggle to enable or disable device auto-reboot to install new config. If **Not Reboot** is selected then the device will update the next time the camera is powered on.

<img src="/user/product/roscolive2.0/how_to_guide/fleet_administration/rlmanage_vehicles_remotemanagementwindow_reboottoggle.jpg" class="align-center" width="800" />  
  

Select **Upload** to upload the configuration file to the device. The next time the device is within network range the server will push the new configuration file to the device.

\<color #ed1c24><u>**NOTICE**: The device must remain powered until new configuration installation is complete.</u>\</color>

## Step 6: Current Firmware & Log Requests

The current firmware version installed onto the device is displayed on this page. For more information about vehicle and fleet firmware settings see:  
[How to use Fleet Firmware Update](/rosco/product/roscolive2.0/how_to_guide/fleet_administration/fleet_firmware_update)

<img src="/user/product/roscolive2.0/how_to_guide/fleet_administration/rlmanage_vehicles_firmwarerequestlogs_arrow.jpg" class="align-center" width="600" />  
  

Logs for the specific vehicle may also be requested for download on this page. Select a **Start Date** and **End Date** then click **REQUEST**. When the vehicle is in network range the server will request the logs of the selected date range from the device.

<img src="/user/product/roscolive2.0/how_to_guide/fleet_administration/rlmanage_vehicles_remotemanagement_requestlogs.jpg" class="align-center" width="600" />  
  

When the log is available, the **DOWNLOAD** button will appear. Click **DOWNLOAD** and the log files will be downloaded through the browser into the directory specified for downloads on your computer. The files will be in .zip file format.

<img src="/user/product/roscolive2.0/how_to_guide/fleet_administration/rlmanage_vehicles_firmwarerequestlogs.jpg" class="align-center" width="600" />  
  

Extract the files into the desired folder.

<img src="/user/product/roscolive2.0/how_to_guide/fleet_administration/rlmanage_vehicles_remotemanagement_unzipedlogfiles.jpg" class="align-center" width="600" />

## Step 7: Remote Format

The remote format function will allow certain users on RoscoLive to format the SD card remotely. **\<color #ed1c24>Please note that the formatting will erase all the corrupted files as well as everything else on the card. Unless the configuration file is corrupted, check the "Keep Configuration" box.\</color>** <img src="/user/product/roscolive2.0/how_to_guide/fleet_administration/remote_format.png" class="align-center" width="800" />
