---
title: "Updating Junction Box Software"
---
# Updating Junction Box Software

**\<color #ed1c24>Please consult the [Installing VSE](/rosco/product/mobileye/shield/installation_guide/installing_vse) page before continuing if you don’t have Visual Studio installed on your PC.\</color>**  
  
1. Connect the USB-COMi-SI to your computer. In the event that the drivers aren’t automatically found and installed, consult the Coolgear USBG-COMi-SI-M User's Manual (USBG070) located in the USBG-COMi-SI DVD Files folder: <embed src="/rosco/product/mobileye/shield/usb-comi-si_dvd_files.zip" class="align-center" />  
  
2. Open the folder of the software you intend to install. As of September 18th, 2018, the software versions are as follows:

-   <u>**<embed src="/rosco/product/mobileye/shield/jb_sw_3.17.zip" class="align-center" />**</u> – All junction boxes shipped from Mobileye as of 9/12/18 use this software version.
-   <u>**<embed src="/rosco/product/mobileye/shield/jb_sw_3.18.zip" class="align-center" />**</u> – Addresses the blinking green man issue (dusk/dawn and low visibility conditions caused by shadows).
-   <u>**<embed src="/rosco/product/mobileye/shield/jb_sw_3.22.zip" class="align-center" />**</u> – This is the latest software designed for use with EyeQ4 and night-vision cameras. This software should only be used with EyeQ4 systems.  
      

3\. To enable use of the USB-COMi-SI, you will first need to document the USB Port Number on the computer you have connected the device to. Open Devices and Printers from your Start Menu and find the USB-COMi-SI. It will appear as “USB to RS-422/485 Adapter.” Right click on the device and select “Properties” from the menu. <img src="/rosco/product/mobileye/shield/1._updating_junction_box_software.png" class="align-center" width="400" />  
4. In the Properties Menu, select the “Hardware” tab. The Port Number will be found under “Location.” In this case, it is Port 3. Take note of your Port Number. You will need it for the next step. <img src="/rosco/product/mobileye/shield/2._updating_junction_box_software.png" class="align-center" width="400" />  
5. Open the Junction Box software folder. In this case, we are opening JB SW 3.18.  
  
6. It is important in this step to have your preview pane visible in your Explorer window. Click once on “port2_downloadEyeCANcode_JB” to highlight it. In the preview pane, you will see the configuration the SREC file uses to transfer the software from computer to junction box. The first number after “AMSTClient.exe” is the Port Number you took note of earlier. <img src="/rosco/product/mobileye/shield/3._updating_junction_box_software.png" class="align-center" width="400" />  
7. Right-click the file and open with Notepad or a similar text editor. Change existing port number to the Port Number you took note of earlier… <img src="/rosco/product/mobileye/shield/4._updating_junction_box_software.png" class="align-center" width="400" />  
8. …and be careful not to make any other edits. Once the text file is updated, save and exit the text editor. <img src="/rosco/product/mobileye/shield/5._updating_junction_box_software.png" class="align-center" width="400" />  
9. Disconnect power to the Junction Box. Open the Junction Box and connect the RS-485 connector directly to the port on the JB circuit board as shown. <img src="/rosco/product/mobileye/shield/6._updating_junction_box_software.jpg" class="align-center" width="400" />  
10. Double-click the “port2” file to run the program. <img src="/rosco/product/mobileye/shield/7._updating_junction_box_software.png" class="align-center" width="400" />  
11. A command line will appear. When you see this window, connect power to the Junction Box. <img src="/rosco/product/mobileye/shield/8._updating_junction_box_software.png" class="align-center" width="400" />  
12. The software update will run in the command line. Monitor the command line to confirm the Data Blocks are successfully acknowledged. <img src="/rosco/product/mobileye/shield/9._updating_junction_box_software.png" class="align-center" width="400" />  
13. The software update will display these messages when successful. Press any key to close the command line. <img src="/rosco/product/mobileye/shield/10._updating_junction_box_software.png" class="align-center" width="400" />  
14. Disconnect power to the Junction Box. Disconnect the RS-485 connector from the Junction Box circuit board.  
  
15. Re-assemble the Junction Box and connect your CAN sniffing tool to the Junction Box. Re-connect power and observe the CAN messages. On start up, the Junction Box sends out message 0x121. This message contains the Junction Box software version, found in byte D3. If the message matches the version you flashed to the Junction Box, the update was a success. In this example we flashed 3.18 as indicated by 0x121. The update was successful. If the message does not reflect the version you are attempting to flash, repeat steps 9 through 15. <img src="/rosco/product/mobileye/shield/11._updating_junction_box_software.png" class="align-center" width="400" />  
