---
title: Cleaning and Conversion
parent: Transcription Options | Map and Data Library
layout: default
created_date: 2023-01-27
staff:
    - name: Kelly Schultz
      link: https://library.utoronto.ca/staff/kelly-schultz
maintainer:
    - name: Kelly Schultz
      link: https://library.utoronto.ca/staff/kelly-schultz
nav_order: 8
---
### **Notes on Converting Audio Only Files to Videos**

For YouTube and Clipchamp, these tools work with video files only. For audio only files, you will have to turn it into a simple video to do this (so add a still image and save as a mp4 file). One way to do that would be to create one slide in PowerPoint, add the audio, and use PowerPoint to export the slideshow as a video mp4 file.  Note: Normally the audio quality is reduced with this method, which can affect the quality of the transcription.

**Windows Instructions:**

1. Open up PowerPoint and create a new blank presentation
2. Select Insert -> Audio -> Audio on My PC… and select your audio file. You should see a new audio icon appear in the middle of the slide. You can click on the play button to hear the audio
3. With that audio icon selected, you should see a Playback ribbon menu at the top appear. From the drop-down menu next to Start (in the middle), select Automatically
4. Select File-> Export -> Create a Video
5. Decide on your file quality (I would go with Full HD or better as lowering the video quality will also affect the audio quality, and you would like good audio quality for transcription)
6. Select Don’t Use Recorded Timings and Narrations and seconds spent on each slide to 0
7. Click on Create Video. You will be prompted to name the file and decide where to save it (keep the default to save it as a MPEG-4 Video). This may take some time if you have a long audio recording  
Now you have a video file (built from your audio file) that you can use for transcription.  
For Mac, the [instructions](https://support.microsoft.com/en-us/office/save-a-presentation-as-a-movie-file-or-mp4-in-powerpoint-for-mac-4e1ebcc1-f46b-47b6-922a-bac76c4a5691#tab=require-vnew) are similar.

### **Cleaning VTT files**

If you want an automated way to strip out timestamps and numbering in Zoom transcript files, you can follow these [instructions using REGEX and a text editor](https://kimberlyhirsh.com/2022/05/12/how-to-remove.html), such as [Notepad++](https://notepad-plus-plus.org/). (Generally, [REGEX](https://regexone.com/) is a powerful way to identify patterns in text and could be used in a variety of ways to clean up transcripts)

### **Advice on Workflows for using VTT files in NVivo and MAXQDA**

The article “[Auto-Creating, Correcting and Coding Transcripts from Microsoft Teams or Zoom in CAQDAS Software (ATLAS.ti, NVivo or MAXQDA)](https://caqdasblog.wordpress.com/2020/12/07/auto-creating-correcting-and-coding-transcripts-from-microsoft-teams-or-zoom-in-caqdas-software-atlas-ti-nvivo-or-maxqda/)” discusses the general process of creating your own transcripts, cleaning up VTT files, and then bringing in those files along with your audio/video files into NVivo or MAXQDA to work with them there.

**Technique:** [Qualitative Data Analysis](https://mdlutoronto.github.io/tutorials-search/?technique=Qualitative+Data+Analysis) \| **Tools:** [NVivo](https://mdlutoronto.github.io/tutorials-search/?tool=NVivo)