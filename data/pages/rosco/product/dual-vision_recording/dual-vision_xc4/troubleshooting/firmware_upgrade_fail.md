---
title: "Firmware Upgrade Unable to complete"
---
# Firmware Upgrade Unable to complete

Documentation Last Revision:10/25/18

------------------------------------------------------------------------

### Customer Environment

All firmware versions.

### Description

The firmware upgrade in process fails to complete.

### Potential Possibilities

\- The firmware upgrade file is too new for the current firmware version to upgrade to it.  
- The current firmware on the camera head is corrupted or has crashed, and will not function properly.

### Diagnosis Process

#### Step 1

Attempt to upgrade the firmware of the camera. For the proper procedure, please see [Upgrade DVXC Firmware](/rosco/product/dual-vision_recording/dual-vision_xc4/troubleshooting/solution/upgrade_firmware) if you are upgrading via computer, or [How to use Fleet Firmware Update](/rosco/product/roscolive2.0/how_to_guide/fleet_administration/fleet_firmware_update) if you are upgrading via RoscoLive 2.0. If the progress of the upgrade reaches 50% but the camera shuts down and doesn't complete the upgrade, please see the possibilities listed above.

#### Step 2

In the event of the first possibility, please attempt the firmware upgrade with another firmware upgrade file that is closer to your firmware version. If this does not resolve the problem, move on to step 3.

#### Step 3

In order to re-upload the current firmware version on the camera, you will need to downgrade the current firmware version to a previous version. You can do so by [contacting us](/contact_us) and letting us know that you need a previous firmware version.

#### Step 4

After downgrading the firmware to a previous version, upgrade the unit to your current firmware version, then attempt to upgrade the firmware to the later version that you were originally attempting to upgrade to.

If both of the listed solutions fail, please contact [RoscoLive technical support](/contact_us).
