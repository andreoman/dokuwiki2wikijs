---
title: "Camera Events Page"
---
# Camera Events Page

ref: RoscoLive v2.4.1

------------------------------------------------------------------------

This page is a step-by-step overview of the **Camera Events** page on the RoscoLive add-on for MyGeotab.

## Reviewing Geotab Events

### Step 1: Navigate to Camera Events Page

Locate and select the **Camera Events** menu option within MyGeotab. <img src="/user/product/geotab_partner/geotab_how_to/rlgeo_cameraevents_option.jpg" class="align-center" width="200" />

### Step 2: Search for Vehicle and Date Period

Events from all of the cameras within the fleet will appear on this page ordered the latest event first. To search for a specific vehicle, select the vehicle's name in the search box and select a date range.

<img src="/user/product/geotab_partner/geotab_how_to/rlgeo_cameraevents_searchbar.jpg" class="align-center" width="1100" />

To narrow the results further, a filter can be applied by selecting the desired filters from the **Filters** drop-down menu. <img src="/user/product/geotab_partner/geotab_how_to/rlgeo_cameraevents_filters.jpg" class="align-center" width="200" />

Selected filters appear light blue, while deselected ones appear dark blue. By default, all filters are deselected. When a filter option is selected, only results matching the search criteria and filter setting will appear in the list.

### Step 3: Reviewing the Event

Once the desired camera event is located, there are three options for reviewing the event.  
***NOTE**: Depending on the rule settings, some options may not be available for the selected event.*  
  
<img src="/user/product/geotab_partner/geotab_how_to/rlgeo_cameraevents_videoreviewbuttons.jpg" class="align-center" width="200" />

The options for reviewing the event are from, left to right:

1.  **View Snapshots**
2.  **View Clip**
3.  **Download Clip**  
      

#### View Snapshots

When this option is selected, the **View Snapshot** window will appear. This window will display the snapshots taken from the time the event occured.

<img src="/user/product/geotab_partner/geotab_how_to/rlgeo_cameraevents_viewsnapshotwindow.jpg" class="align-center" width="600" />  
  

The numbers seen on the bottom of the window can be selected to view the snapshot from each channel available.

<img src="/user/product/geotab_partner/geotab_how_to/rlgeo_cameraevents_viewsnapshotwindow_cropped.jpg" class="align-center" width="600" />

#### View Clip

When this option is selected, the **Quad-View Clip Player** will appear. <img src="/user/product/geotab_partner/geotab_how_to/rlgeo_cameraevents_viewclipplayer.jpg" class="align-center" width="1200" />

This player will display all channels available in a quad-view format. If a channel has audio enabled, the audio can be isolated by clicking on the camera view in the player for that channel. A few other features to note:

1.  **Meta Data** - The meta data for the event is displayed on the right side of the player. It contains information about the name of the vehicle, the date and time the event occured, firmware version, speed, direction, RPM, and G-sensor acceleration. It is important to note that the Geotab GO device provides the speed, RPM, and g-sensor acceleration metadata only at the exact time an event occurs. If a custom video is requested, the metadata from the GO device will not be present due to no actual exception occurring.
2.  **Google Maps Overlay** - This map displays the vehicle's location and direction of travel when the exception occurred.
3.  **Video Download** - When selected, these buttons download the exception video clip in the format specified on the button. The **NVR Video** button downloads the video in .nvr file format that can be played back in DV-Pro5. **MP4 Video** button downloads the video in .mp4 file format.

#### Download Clip

When this option is selected, the event video file will be downloaded in .nvr format to your computer. This file format must be played back using the DV-Pro5 player. <img src="/user/product/geotab_partner/geotab_how_to/rlgeo_cameraevents_downloadclipbrowser.jpg" class="align-center" width="1200" /> *Note: The browser used in this picture is Google Chrome. The download notification may differ between different browsers.*

### Step 4: Making Custom Video Requests

To view a non-exception related video clip, a **Custom Video Request** must be made.

#### Select Custom Video Request

Locate the **Custom Video Request** button at the top of the page and select it to drop down the custom video request window. <img src="/user/product/geotab_partner/geotab_how_to/rlgeo_cameraevents_customvideorequest.jpg" class="align-center" width="1000" />

#### Requesting the Custom Video

Select the desired vehicle, date and time, and desired length of the video clip. Text can be added in the *Note* field for any pertinent information regarding the video clip. After entering the relevant information, select **Request Video**. <img src="/user/product/geotab_partner/geotab_how_to/rlgeo_cameraevents_customvideorequestsubmit.jpg" class="align-center" width="600" />  

After the request has been submitted, a confirmation will appear at the top right corner of the page that the custom video request was successful. The custom video request will now appear on the **Camera Events Page**. Note that the event type is *custom*. <img src="/user/product/geotab_partner/geotab_how_to/rlgeo_cameraevents_customvideorequestpending.jpg" class="align-center" width="1000" />

Whenever the vehicle is within network connectivity, the server will request the custom video from the camera and then the video will be uploaded to the Camera Events page for viewing. If the vehicle is not within network range or otherwise not connecting to the server, the video request will be queued until the vehicle comes back online and then the request will be sent.

#### Requesting multiple custom video requests

If more than one video request is desired, click **Add Video**[^1]. This will add an additional field to request another custom video. The **Add Video** button can be selected multiple times to add more request fields to the list. To remove a request from the list, select the dash button located to the right of each request[^2]. After all requests are entered, select **Request Video**[^3] to send off the requests.

<img src="/user/product/geotab_partner/geotab_how_to/rlgeo_cameraevents_customvideorequestmultiple.jpg" class="align-center" width="600" />

[^1]: 1

[^2]: 2

[^3]: 3
