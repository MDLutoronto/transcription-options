---
title: Transcription Options | Map and Data Library
layout: home
created_date: 2023-01-27
description: "If you have an audio or video file that you need to get transcribed, this page describes some automated options to consider. But keep in mind, though, that none of these options (including NVivo transcription) provides a 100% perfectly accurate transcript. You will always have to go back in and correct your transcript. Note: If you want to pay a human to transcribe things accurately (so no or minimal correction is needed later), you could try Rev or Transcript Divas."
maintainer:
    - name: Kelly Schultz
      link: https://library.utoronto.ca/staff/kelly-schultz
---

# Transcription Options | Map and Data Library

If you have an audio or video file that you need to get transcribed, this page describes some automated options to consider. But keep in mind, though, that none of these options (including paid transcription services from NVivo and MAXQDA) provides a 100% perfectly accurate transcript. You will always have to correct your transcript.

Note: If you want to pay a human to transcribe things accurately (so no or minimal correction is needed later), you could try [Rev](https://www.rev.com/) or [Transcript Divas](https://transcriptdivas.co.uk/about/).

First is a comparison table of some of the automated options. Below the table are instructions for each option.

| **Option** | **Cost** | **Transcription** **Formats** | **File Type Generated** | **Languages** **Supported** | **Ethics** **Considerations** |
| --- | --- | --- | --- | --- | --- |
| [Microsoft 365 – Word Transcription](#MSWord) | $0 (but limited to 300 minutes per month) | just text; with speakers; with timestamps; with speakers and timestamps | Word document | [80+ languages/dialects](https://support.microsoft.com/en-us/office/transcribe-your-recordings-7fc2efec-245e-45f0-b053-2a97531ecf57) | UofT’s Research Ethics Board has approved this approach in the past if you stated that you were keeping all files on OneDrive using multifactor authentication (but of course that depends on your particular situation and what you wrote in your research ethics protocol). [Read more information on how the service works under the About Transcribe heading at the bottom of the page](https://support.microsoft.com/en-us/office/transcribe-your-recordings-7fc2efec-245e-45f0-b053-2a97531ecf57?ui=en-us&rs=en-us&ad=us). |
| [aTrain](#atrain) | $0 | with speakers; with speakers and timestamps | Text file | [57 languages](https://apps.microsoft.com/detail/9n15q44szns2?hl=en-US&gl=CA) | This is a program you run locally on your computer (with no need for internet access), so it is very likely that the Research Ethics Board would approve this approach. |
| [Zoom](#zoom) | $0 | with timestamps; with speakers and timestamps | VTT file; Text file | [49 languages/dialects](https://support.zoom.com/hc/en/article?id=zm_kb&sysparm_article=KB0058810#h_9668257228481712859178546) | Keep in mind that the recording and transcript are stored on Zoom’s servers in Canada (but Zoom's US servers are still used for real-time data processing). This may or may not be acceptable for research ethics. |
| [Microsoft 365 – Clipchamp Transcription](#clipchamp) | $0 | with timestamps | VTT file or Word Document | [80+ languages/dialects](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/language-support?tabs=stt) | This is similar to using the Microsoft 365 Word solution above. |
| [YouTube](#youtube) | $0 | with timestamps | VTT file | [67 languages](https://support.google.com/youtube/answer/6373554?hl=en-GB#zippy=%2Cautomatic-captions-on-long-form-videos-and-shorts) | Keep in mind that the recording and transcript are stored on YouTube's servers. This may or may not be acceptable for research ethics. |
| [NVivo Transcription](#nvivo) | $25USD/hour; cheaper bulk purchases available | with speakers and timestamps | Word document; Text file | [43 languages](https://help.mynvivo.com/nvtranscription/Content/Supported_languages.htm?plt=150.5.1.88.0&_ga=2.46124268.956831469.1674250089-581384786.1655315837) | Keep in mind that the recording and transcript are stored on Lumivero’s servers. This may or may not be acceptable for research ethics. [Read more about their data security.](https://help.mynvivo.com/nvtranscription/Content/NVT_data_security.htm) |
| [MAXQDA Transcription](#maxqda) | Different options from $23.80 USD for 2hrs up to $178.50 USD for 20hrs. You can also get 60 minutes free to get started. | with speakers and timestamps | Text file | [almost 50 languages](https://help.maxqda.com/en/support/solutions/articles/80001135589-which-languages-are-supported-for-maxqda-transcription-) | Keep in mind that the recording and transcript are stored on MAXQDA's servers. This may or may not be acceptable for research ethics. [Read more about their data security.](https://www.maxqda.com/ai-data-protection) |

 

A. [Microsoft 365 – Word Transcription](https://support.microsoft.com/en-us/office/transcribe-your-recordings-7fc2efec-245e-45f0-b053-2a97531ecf57)
---------------------------------------------------------------------------------------------------------------------------------------------------

**Summary:** Microsoft Word 365 online works with both audio and video files and is available to UofT faculty, staff, and students. You can use the transcribe feature to get a Word document transcript with just text, speaker names, timestamps, or speaker names and timestamps.

**Instructions:**

1. Go to [Word 365 online](https://www.office.com/launch/word?auth=2&home=1).
2. Enter in your UofT email address. Then it will take you to a page where you will log in using your UTORID credentials.
3. Create a new blank document.
4. Click on drop-down arrow next to the Dictate icon (i.e., the microphone icon) from Home Ribbon Menu, then select Transcribe.
5. From the right-side box, pick your language and upload your audio or video file.
6. You will see a progress bar as it transcribes - takes a bit of time, but pretty fast. Wait for it to be done.
7. When done, you should see a preview of the transcription.
8. Below the transcription, click on the drop-down arrow next to the Add to Document button.
9. Select the option you want: just text, with speakers, with timestamps, with speakers and timestamps. It will then add the transcript to the Word document that you can then edit and/or download.
10. It will then add the transcript to the Word document that you can then edit and/or download.

**Note:** **Currently, there is a limit of 300 minutes per month per user.** (In the past, Microsoft offered unlimited minutes, but that has unfortunately changed.)

B. [aTrain](https://business-analytics.uni-graz.at/de/forschung/atrain/)
------------------------------------------------------------------------

**Summary:** This is a free, open-source application you run locally on your computer. It will transcribe both your audio and video files, creating text files with speaker names and timestamps. aTrain combines [OpenAI's Whisper](https://github.com/openai/whisper) transcription models with speaker recognition and provides outputs that integrate with MAXQDA and ATLAS.ti.

**Instructions:** For Windows, you can download and install it from the [Microsoft store](https://apps.microsoft.com/detail/9n15q44szns2?hl=en-US&gl=CA). Or for Windows, MacOS, and Linux, you can use the [Download aTrain page](https://business-analytics.uni-graz.at/de/forschung/atrain/download/). Then you just select your audio or video file.Optionally provide information on what language the file is in and how many speakers there are (although speaker identification works better if you specify this). You can also decide what level of model you'd like to use to run the transcription.

aTrain comes installed with the large-v3-turbo model to start, but you can select Models from the left menu and use the download buttons to download other models (generally the larger the model, the more accurate the transcription, but at a sacrifice to speed). You can read more about the models in the [documentation](https://github.com/openai/whisper).

Once your settings are selected, click on Start. You should see a progress screen. A message will tell you when it is done. You can click on Open to open up a folder with your transcripts created in various formats. If the Open button does not work, you should be able to manually browse to this folder by going to your Documents\aTrain\transcriptions folder. The transcription.txt file just has speaker labels. The transcription_timestamps.txt just has timestamps. The transcription_maxqda.txt has both speaker labels and timestamps.

aTrain also provides a [paper](https://www.sciencedirect.com/science/article/pii/S2214635024000066) with more details on its use.

C. [Zoom](https://utoronto.zoom.us/)
-----------------------------------

**Summary**: Zoom works with both audio and video files and is available to UofT faculty, staff, and students. You can also use Zoom to capture your audio and video recordings. You generally have two options:

1. Create transcripts live
2. Create transcripts from cloud recordings (Note, though, that [undergraduate students can’t record to cloud](https://teaching.utoronto.ca/tool-guides/zoom/))

**Instructions**:

1. First decide if you are going to use Zoom to also capture your audio or video recordings of an interview, focus group, etc. If so, start your Zoom meeting
2. If instead you have an audio or video file you captured from somewhere else, use Zoom to host a meeting for one, [share your screen, including system audio](https://support.zoom.com/hc/en/article?id=zm_kb&sysparm_article=KB0063608), and be ready to play your video or audio files (as if presenting a webinar)
3. In either case, once you are ready to proceed, follow the steps below for Option 1 or 2

Option 1: [Live Captioning](https://support.zoom.com/hc/en/article?id=zm_kb&sysparm_article=KB0063899)

1. Turn on live captioning by going to the drop-down arrow next to the Show Captions option in the Zoom menu, and selecting the language for your captions
2. Then you can either Show/Hide Captions by toggling that option in the Zoom menu. Toggle the captions so that they are hidden (but are happening in the background)
3. Zoom will auto caption it live. You can download the transcript when it is done, by selecting View Full Transcript from the drop-down menu for Show Captions
4. Click on the Save transcript button at the bottom of the transcript window. This results in a text file you can download
5. If you were the only person in the meeting, it will tag all the text with your Zoom name. You would have to edit it if you wanted to label appropriate speaker names. If you were conducting your interview live, then it should automatically label appropriate speaker names

Option 2: [Cloud Recording Transcription](https://support.zoom.com/hc/en/article?id=zm_kb&sysparm_article=KB0064927)

1. Record your meeting to the cloud by click on the More options in the Zoom menu and selecting Record -> Record to the cloud
2. Conduct your meeting as normal and then leave the meeting when you are done. You will get notified when the recording is ready
3. Go to the web view of [UofT’s Zoom](https://utoronto.zoom.us/) and login with your account
4. Select Recordings & Transcripts from the left menu
5. Select the title of the meeting you just recorded. This screen will tell you if the recording is still being transcribed or if it is done. If it says unable to transcribe, make sure to select your language by hovering over audio transcript
6. When it is ready, you can select Audio transcript to download a VTT file with timestamps and speaker labels.
7. If you were the only person in the meeting, it will tag all the text with your Zoom name. You would have to edit it if you wanted to label appropriate speaker names. If you were conducting your interview live, then it should automatically label appropriate speaker names

D. [Microsoft 365 - Clipchamp Transcription](https://support.microsoft.com/en-us/office/microsoft-stream-automatically-creates-closed-captions-for-videos-8d6ac353-9ff2-4e2b-bca1-329499455308)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Summary:** Clipchamp is an option available to UofT faculty, staff, and students that works with videos files only to create VTT files (captions with text and timestamps). Generally, VTT files are not transcripts, but can help you speed up the process of creating transcripts, in some cases.

**Instructions:**

1. Go to [Clipchamp 365 online](https://www.microsoft365.com/launch/clipchamp?auth=2).
2. Enter in your UofT email address. Then it will take you to a page where you will log in using your UTORID credentials.
3. Once logged in, either select your video from the content list of videos in your OneDrive OR you can click on Upload on the left, next to the Screen recording button to upload a new file. Browse to your video file and select it to upload.
4. Once uploaded and showing up in the content list, click on it to play in Clipchamp.
5. Click on Video settings on the Right.
6. Expand the Transcript and captions section by clicking on its drop-down arrow.
7. Click on Generate and select the language to generate captions.
8. Once finished, you should see the captions listed in that section saying the language and below “Generated by Microsoft”. Close the Video settings.
9. If you click on the Transcript option that is now available on the right, you can view the video and transcript side-by-side if you want to make any edits.
10. When done, go back to Video Settings, to the Transcript and captions section. Next to the generated caption listed, click on the … icon for those captions, and select Download to download as a .docx or .vtt file.

But note that there won’t be any speakers’ names in the file; you would have to add those manually if you wanted them. Because you’ll have to add speaker names and timestamp divisions might not occur at a change in speaker, this could be a labour-intensive process to augment and clean up, depending on your file (for example, there would be a lot more cleanup required for a focus group transcript). Also, Clipchamp seems to generate more timestamp divisions than other tools.

Also, as mentioned, this only works for video files – see the Notes on [Converting Audio Only Files to Videos](https://mdl.library.utoronto.ca/technology/tutorials/transcription-options#Convert_Audio) section, if needed.

E. [YouTube](https://www.youtube.com/)
-------------------------------------

**Summary:** YouTube is a free option that works with videos only to create VTT files (captions with text and timestamps). Generally, VTT files are not transcripts, but can help you speed up the process of creating transcripts, in some cases. If the video is not private or sensitive (and so you are comfortable uploading it to YouTube and it complies with your research ethics approval, if applicable), you could use YouTube’s free auto transcription service to create a VTT file.

You don't need to share the video publicly because you can upload it as a private file to your account. After uploading the video, you can use the caption service to generate a VTT file, which you can then correct and download.

But note that there won’t be any speakers’ names in the file; you would have to add those manually if you wanted them. Because you’ll have to add speaker names and timestamp divisions might not occur at a change in speaker, this could be a labour-intensive process to augment and clean up, depending on your file (for example, there would be a lot more cleanup required for a focus group transcript).

Also, as mentioned, this only works for video files – see the Notes on [Converting Audio Only Files to Videos](https://mdl.library.utoronto.ca/technology/tutorials/transcription-options#Convert_Audio) section, if needed.

**Instructions:**

1. Follow the [upload your video instructions](https://support.google.com/youtube/answer/57407?hl=en&co=GENIE.Platform%3DDesktop) (or [the instructions if your video is longer than 15 minutes](https://support.google.com/youtube/answer/71673?hl=en&ref_topic=9257439))
2. Then follow the [instructions to use the caption service and generate a VTT file](https://support.google.com/youtube/answer/6373554?hl=en#zippy=%2Cautomatic-captions-on-videos-on-demand)
3. Then [review and correct the VTT file captions](https://support.google.com/youtube/answer/2734705?hl=en&ref_topic=7296214&sjid=2334017412508982072-NC#zippy=%2Cedit-caption-timing%2Cedit-caption-text)
4. Finally follow the [instructions to download the corrected VTT file](https://ito-engineering.screenstepslive.com/s/ito_fase/a/1639680-how-do-i-download-a-caption-file-from-youtube)

F. [NVivo Transcription](https://help.mynvivo.com/nvtranscription/Content/welcome.htm)
--------------------------------------------------------------------------------------

**Summary:** Lumivero offers a paid automated transcription service where you upload audio and video files to transcribe. You are able to edit the files in the online interface and download the transcripts as text or Word files when they are ready.

**Instructions:**

1. First sign up for and purchase the [NVivo transcription service](https://www.qsrinternational.com/nvivo-qualitative-data-analysis-software/about/nvivo/modules/transcription)
2. Then follow Lumivero’s [step-by-step instructions](https://help.mynvivo.com/nvtranscription/Content/workflow.htm) and [how-to video](https://www.youtube.com/watch?v=AES26-CdEn0) for more information

G. [MAXQDA Transcription](https://www.maxqda.com/automatic-transcription-software)
----------------------------------------------------------------------------------

**Summary:** MAXQDA offers a paid automated transcription service where you upload audio and video files to transcribe and then receive text transcripts, which you can then edit from within MAXQDA.

**Instructions:** See the bottom of [MAXQDA's transcription page](https://www.maxqda.com/automatic-transcription) for step-by-step instructions for two methods they offer for transcribing with their service.

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

### **Other Resources on Captions/Transcripts/De-Identification**

* [Centre for Teaching Support & Innovation Guide to Captioning Videos](https://teaching.utoronto.ca/resources/captioning-videos/)
* **De-Identification:** Depending upon the research, there are situations where you may be sharing your data and need to protect your human participants' identities, so that someone viewing the data couldn't figure out who the data is associated with. These resources can provide more information and tips, if you need to de-identify your transcripts:
	+ [De-Identification](https://qdr.syr.edu/guidance/human-participants/deidentification) from the [Qualitative Data Repository](https://qdr.syr.edu/)
	+ [Sharing Human Participant Data](https://managing-qualitative-data.org/modules/3/b/) from the [Managing Qualitative Social Science Data online course](https://managing-qualitative-data.org/)

Also, visit our Getting Started pages for more information, tutorials, and workshops for [NVivo](https://mdl.library.utoronto.ca/technology/tutorials/nvivo-12-information-tutorials-and-workshops) or [MAXQDA](https://mdl.library.utoronto.ca/technology/tutorials/maxqda-information-resources-tutorials-and-workshops)!
