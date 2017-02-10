---
title: Editing 360 Video (Advanced)
type: 360_video
layout: docs
parent_section: 360 Video
order: 4
---

To edit your 360 video clips, use the free movie editing software, DaVinci Resolve 12.5. 

Note - It is recommended that you experiment with making compelling 360 videos that do not require editing before you move onto editing. Many of the most compelling 360 videos are shot using a single take. 

# Editing Basics

* Download DaVinci Resolve 12.5 (not the studio version) from the following link: https://www.blackmagicdesign.com/products/davinciresolve
* Run the Davinci Resolve 12.5 installer and  make sure all the checkboxes are selected before pressing the “install ” button

<img src="/images/docs/360_video/image04.png">

* Run the newly installed application “Resolve”
* Watch the following tutorial for editing video clips together 
<iframe width="560" height="315" src="https://www.youtube.com/embed/PgTRPXsgv-I" frameborder="0" allowfullscreen></iframe>
* Create a new timeline in the “Edit” page. Make sure to only use video files converted by the Ricoh Theta app.
* In the “Deliver Page” select the “YouTube” template.
* Add your Timeline to the Render Queue
* Render your content


# Converting edited video to 360 
We need to manually add information to the video file exported from “Resolve” to ensure that 360 video players will register the video as a 360 file and not a normal mp4 video file. 

* Download the Spatial Metadata Injector https://github.com/google/spatial-media/releases/download/v2.0/360.Video.Metadata.Tool.win.zip
* Unzip the Spatial Metadata Injector application move it to Desktop.
* Use the Spatial Metadata Injector to add the 360 video metadata to your newly exported file.

<img src="/images/docs/360_video/image09.png">

* Check the first option, “My video is spherical (360)” when injecting metadata. 

* Press Inject metadata, and save your movie to  your 360 video folder.
* Upload the file with “_injected” appended to it to Facebook and confirm that it has successfully recognized that the video is a 360 video.
