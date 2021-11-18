---
title: "How to use Fleet Firmware Update"
---
# How to use Fleet Firmware Update

ref: RoscoLive v2.3.0

------------------------------------------------------------------------

This page is a step-by-step overview of the **Fleet Firmware Update** page. The **Fleet Firmware Update** page is available to those users with permissions of **Fleet Maintainer** and above.  
  
The **Fleet Firmware Update** page is where the firmware on the DV440 cameras installed on the fleet vehicles can be monitored, upgraded, or changed.  
  
\<color #ed1c24><u>**IMPORTANT NOTE**:It is HIGHLY RECOMMENDED that you contact RoscoLive customer support before applying any firmware updates. If firmware update is done incorrectly, camera failure is highly likely.</u>\</color>

## Step 1: Navigate to the Firmware Update page

Locate the **Fleet Administration** option in the side-bar menu.

<img src="/rosco/product/roscolive2.0/how_to_guide/fleet_administration/rlmanage_vehicles_menuoptionclosed.jpg" class="align-center" width="200" />

Select the **Fleet Firmware Update** option in the now revealed drop-down menu under **Fleet Administration**.

<img src="/rosco/product/roscolive2.0/how_to_guide/fleet_administration/rlfleetfirmware_menuoption.jpg" class="align-center" width="200" />

## Step 2: Fleet Firmware Update page

This is the **Fleet Firmware Update** page. From here, the user is able to see the firmware versions on all DV cameras in the fleet assorted by Group. Firmware upgrades / downgrades may also be done from this page, however it is <u>recommended to contact RoscoLive customer support to do so.</u>

<img src="/rosco/product/roscolive2.0/how_to_guide/fleet_administration/rlfleetfirmware_page.jpg" class="align-center" width="800" />

### Fleet Groups Firmware pages

The table displayed on this page is where the fleet groups are displayed. Next to each Group name is a (+) that when selected expands that Group category to reveal all of the vehicles in that Group.

<img src="/rosco/product/roscolive2.0/how_to_guide/fleet_administration/rlfleetfirmware_groupexpandtable.jpg" class="align-center" width="900" />

The columns of this page are the following:

1.  **Vehicle** - This is the name of the vehicle.
2.  **Current Firmware** - This is the firmware version currently installed onto the DV440 in that vehicle.
3.  **Firmware Selection** - This drop-down menu displays the available firmware versions for download to the DV440.
4.  **Reboot** - This toggle when enabled causes the DV440 to automatically reboot after a firmware is uploaded to the device. If disabled, the camera must be manually rebooted to finish firmware installation.
5.  **Upgrade** - When this button is pressed, a request is sent to RoscoLive servers to push the selected firmware version to the DV440 of that particular vehicle for upload.
6.  **Cancel Upgrade** - If a request for a firmware update has been sent, this button will become available. **BEFORE THE UPDATE HAS BEGUN**, this button can be pressed to cancel any request for a firmware update sent to that vehicle.
7.  **Status** - displays the status of the firmware version currently installed on that vehicle.

### Searching for Vehicles

The search bar at the top of this page can be used to search for vehicles with similar names or individual vehicles. As the user is entering the vehicle name in the search bar, the Groups list actively narrows down the vehicle names according to how specific the name entered is. In the example below, all the vehicles with '661' in their name can be seen generated. As the search gets more specific with the name '661455', the results narrow to only one vehicle with that name.

<img src="/rosco/product/roscolive2.0/how_to_guide/fleet_administration/rlfleetfirmware_searchexample.gif" class="align-center" width="800" />

### Fleetwide Firmware Update

\<color #ed1c24><u>**IMPORTANT NOTE**:It is HIGHLY RECOMMENDED that you contact RoscoLive customer support before applying any firmware updates. If firmware update is done incorrectly, camera failure is highly likely.</u>\</color>  
  
To push a fleetwide firmware update, locate the drop-down menu towards the top of the page to the right of the search bar.

<img src="/rosco/product/roscolive2.0/how_to_guide/fleet_administration/rlfleetfirmware_page_fleetfirmwarearrow.jpg" class="align-center" width="800" />

Select the desired firmware version from the list.

<img src="/rosco/product/roscolive2.0/how_to_guide/fleet_administration/rlfleetfirmware_page_fleetfirmwareselect.jpg" class="align-center" width="400" />

To enable the device to automatically reboot to apply the firmware update, select the toggle button to "Reboot immediately", otherwise select it to "Not reboot". It is recommended that when applying a firmware update to a vehicle that is off or in parking mode, to select "Not Reboot".

<img src="/rosco/product/roscolive2.0/how_to_guide/fleet_administration/rlfleetfirmware_page_fleetfirmwarereboot.jpg" class="align-center" width="300" />

Click **Upgrade**

<img src="/rosco/product/roscolive2.0/how_to_guide/fleet_administration/rlfleetfirmware_page_fleetfirmwareupgradeemphasis.jpg" class="align-center" width="400" />

A prompt will appear in the top right corner of the page confirming the fleetwide firmware upgrade request was sent.

<img src="/rosco/product/roscolive2.0/how_to_guide/fleet_administration/rlfleetfirmware_page_fleetfirmwareupgradesuccess.jpg" class="align-center" width="200" />

## Step 3: Vehicle Firmware Update

\<color #ed1c24><u>**IMPORTANT NOTE**:It is HIGHLY RECOMMENDED that you contact RoscoLive customer support before applying any firmware updates. If firmware update is done incorrectly, camera failure is highly likely.</u>\</color>  
  

### Find Vehicle to Update

Find the vehicle for the update to be applied to.

<img src="/rosco/product/roscolive2.0/how_to_guide/fleet_administration/rlfleetfirmware_vehicle.jpg" class="align-center" width="800" />

### Select Firmware Version to Upload to Vehicle

In the **Firmware Selection** column of the selected vehicle, select the firmware version to be applied from the drop-down menu.

<img src="/rosco/product/roscolive2.0/how_to_guide/fleet_administration/rlfleetfirmware_vehiclefirmware.jpg" class="align-center" width="200" />

### Select Reboot

In the **Reboot** column of the selected vehicle, click the reboot toggle to the right to enable automatic device reboot to apply firmware update, otherwise leave the toggle to the left. If left off, the device will have to be manually restarted in order to apply firmware update to the device.

<img src="/rosco/product/roscolive2.0/how_to_guide/fleet_administration/rlfleetfirmware_vehiclefirmwarereboot.jpg" class="align-center" width="100" />

### Upgrade

In the **Upgrade** column of the selected vehicle, select the **Upgrade** button to send the firmware update request to the device. After the button is selected, a prompt will appear in the top right corner of the screen confirming it was sent. The status in the **Status** column will now say "firmware update pending to dvx4_vX.X.X".

<img src="/rosco/product/roscolive2.0/how_to_guide/fleet_administration/rlfleetfirmware_vehicleupgradebutton.jpg" class="align-center" width="800" />

The cancel button will now become available. To cancel a update request **BEFORE BEING UPLOADED TO THE DEVICE**, click the **Cancel** button. A prompt will appear in the top right corner of the page confirming the update was successfully canceled. The status will also reflect the change.

<img src="/rosco/product/roscolive2.0/how_to_guide/fleet_administration/rlfleetfirmware_vehiclecancelbutton.jpg" class="align-center" width="600" />
