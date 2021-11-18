---
title: "Invalid SD Card Error (IN_SD)"
---
# Invalid SD Card Error (IN_SD)

Documentation Last Revision: 10/11/2018

------------------------------------------------------------------------

### Error Code

In_SD  
==== Customer Environment ====

Firmware version: **1.5.0** and higher  

### Description

Camera display “IN_SD” constantly.

### Potential Possibilities

-   SD card got swapped. - most of the case
-   PDC box got swapped. - extremely rare, but possible

### Diagnosis Process

#### Step 1

Remove the SD card from the camera.  
  
=== Step 2 === Check the labels on both the SD card and the camera and verify if the vehicle names are consistent. If it's consistent, it's the PDC box got swapped. If not, it's most likely the SD card got swapped.  
  
=== Step 3 === Look for the designated vehicle that matches the label on SD card, then remove the SD card from that camera also.  
  
=== Step 4 === Insert the SD cards into a computer and open them with DV-PRO 5 player.  
  
=== Step 5 === <u>\<color #ed1c24>**Internal Only**\</color></u> Delete the existing file "sn.txt" on both SD cards and \<color #ed1c24>**safe eject**\</color> them. **<u>Please note that fail to safe eject the SD card could create corrupted files and lead to massive data loss.</u>**  
  
\<color #ed1c24>**<u>For Customer</u>**\</color>  
[Format SD Card](/rosco/product/dual-vision_recording/dual-vision_xc4/troubleshooting/solution/format_sd_card)

#### Step 6

Put the SD cards back to its designated camera and reboot the camera.  
  
