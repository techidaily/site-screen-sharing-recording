---
title: "[Updated] Controlling Bitrate Overload in OBS for 2024"
date: 2024-07-19T08:38:35.874Z
updated: 2024-07-20T08:38:35.874Z
tags: 
  - screen-recording
  - ai video
  - ai audio
categories: 
  - ai
  - screen
description: "This Article Describes [Updated] Controlling Bitrate Overload in OBS for 2024"
excerpt: "This Article Describes [Updated] Controlling Bitrate Overload in OBS for 2024"
keywords: "Bitrate Management OBS,OBS Bandwidth Control,OBS Sync Rate Optimization,Limiting OBS Stream Quality,Balancing OBS Data Load,Preventing OBS Overload,Regulating OBS Transmission"
thumbnail: https://thmb.techidaily.com/b35a9a46671dd373ee6fb76f2e7c8c289a52fdab2f2b7f6dd74a2f0921700773.jpg
---

## Controlling Bitrate Overload in OBS

When you are live streaming through OBS Studio, encoding the video takes a lot of CPU resources. If you do not have a high-end computer, you are likely to face Encoding Overloaded issue while using OBS Studio. High encoding problem is rather common in OBS Studio because video recording and streaming demand high system resources which your computer is unable to meet.

In layman’s terms, encoding overloading means your hardware is just not running as fast as required to process the video you are streaming or recording. Since you cannot change your hardware configuration overnight, here are the different ways you can fix OBS high encoding when streaming.

<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
## Way 1\. Downscale Your Output Resolution

The higher the resolution of the video recording or streaming, the greater will be the CPU usage. This is because your processor has to process more number of pixels per frame. That is why you have to lower the output resolution of your video. Even when your base resolution is high, you have to cut down the output resolution. Base resolution is the resolution of the video at source which could be the game you are playing. The output resolution is the resolution of the video you are getting after recording or you are streaming in real-time. Here are the steps to follow.

Step 1: Open OBS and go to Settings.

Step 2: Select Video tab. You will have to look for Output (Scaled) Resolution option.

Step 3: You have to reduce the resolution from the current resolution. If it is at 1920 x 1080p, you have to bring it down to 1280 x 720p.

Step 4: Click on Apply and Ok buttons. Restart your computer and start streaming or recording again.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
![obs reduce the output resolution](https://images.wondershare.com/filmora/article-images/obs-reduce-the-output-resolution.jpg)

## Way 2\. Lower Your Frame Rate

The frame rate of a video determines the number of frames captured per second. The higher the frame rate, the greater will be the pressure on GPU to render more number of frames per second. Unless you have a powerful configuration, you will come across OBS high encoding when streaming if the frame rate is high such as 60FPS. Here are the steps to lower the frame rate of your video on OBS.

Step 1: Launch OBS and go to Settings.

Step 2: Go to Video tab and look for Common FPS Values option.

Step 3: If it is set to 60, you have to bring it down to 30\. Basically, you have to reduce the current value.

Step 4: Click on Apply and Ok button to save the new setting. Restart your computer and resume your OBS operation.

![obs click on apply and ok button](https://images.wondershare.com/filmora/article-images/obs-click-on-apply-and-ok-button.jpg)

## Way 3\. Change Encoder Preset

By default, OBS uses x264 as encoder and the encoder preset is set to “veryfast”. This is generally the best and most balanced setting. However, if you are getting OBS high encoding warning, you have to change the encoder preset to reduce the CPU usage. Generally, the higher the preset, the lower is CPU usage. Therefore, you have to set the preset from “veryfast” to “ultrafast” and here are the steps.

Step 1: Launch OBS and go to Settings.

Step 2: Go to Output tab and make sure that the encoder is Software(x264).

Step 3: Turn on Enable Advanced Encoder Settings option.

Step 4: Change the Encoder Preset from Veryfast to Ultrafast.

Step 5: Click on Apply and Ok button. Restart your computer and perform your action on OBS.

![obs change encoder preset](https://images.wondershare.com/filmora/article-images/obs-change-encoder-preset.jpg)

## Way 4\. Try Hardware Encoding

You can try out different hardware encoders available such as Quicksync, AMF, or NVENC. The availability of different hardware encoders depends on your computer hardware configuration. These hardware encoders are better than the default x264 encoder as they use less CPU resources. Since the issue is primarily with encoder, you should try changing the encoder and see if the problem is fixed.

Step 1: On OBS, you will have to go to Settings.

Step 2: Select Output tab and set Output Mode to Advanced.

Step 3: Go to Streaming tab, and check all the encoders available.

Step 4: Change the encoder from default x264 to any other hardware encoder available.

Step 5: Click on Apply and Ok to save the settings. Restart your computer and perform your operation on OBS.

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![obs restart your computer and perform your operation](https://images.wondershare.com/filmora/article-images/obs-restart-your-computer-and-perform-your-operation.jpg)

## Way 5\. Change Some Advanced Settings

If you are still facing OBS high encoding problem, you need to change some advanced settings in order to fix this encoder overloaded issue. You can change the keyframe interval so that your processor gets enough time for rendering. Similarly, you can change Rate Control from Constant to Variable so that the video does not demand high bandwidth.

Step 1: Open OBS and go to Settings.

Step 2: Go to Output tab and set Output Mode as Advanced.

Step 3: From Streaming tab, change Keyframe Interval and set it to 2 from zero.

Step 4: Change Rate Control from CBR to VBR.

Step 5: Change Profile from None to Main.

Step 6: Click on Apply and Ok button to save the changes. Restart your computer and check if the problem is resolved.

![obs open and go to settings](https://images.wondershare.com/filmora/article-images/obs-open-and-go-to-settings.jpg)

## Way 6\. Use OBS Alternative

If none of the above-mentioned ways can solve the constant encoding overloaded warning you are receiving while using OBS Studio for recording or streaming, you have to opt for an alternative. Wondershare Filmora is the best alternative to OBS for recording screen and webcam. Filmora does not affect the CPU performance as significantly as OBS Studio does. That is why the encoding overloaded issue is unlikely to occur in Filmora.

Filmora is one of the most popular video recorders that come with inbuilt video editor. You can record your screen, gameplay as well as webcam along with audio from different sources. Thereafter, you can edit the video as per your requirements starting from adding effects and animations to adjusting color and trimming out unnecessary parts. Here are the steps to record screen with Filmora.

[Try It Free](https://tools.techidaily.com/wondershare/filmora/download/)

For Win 7 or later (64-bit)

[Try It Free](https://tools.techidaily.com/wondershare/filmora/download/)

For macOS 10.12 or later

Step 1: Install Wondershare Filmora on your computer based on your OS. Launch Filmora and click on PC Screen to record your screen.

![pc-screen](https://images.wondershare.com/filmora/article-images/pc-screen.jpg)

Step 2: Select the recording screen size and the audio sources. If you want to capture webcam as well, turn on Record The Camera Stream option.

![set-audio](https://images.wondershare.com/filmora/article-images/set-audio.jpg)

Step 3: Click on Record button to start recording. Press F9 to stop recording whenever you want.

Step 4: You can edit the recorded video. Thereafter, click on Export button to save it on your hard drive in any desired file format.

![export the project](https://images.wondershare.com/filmora/article-images/export-the-project.jpg)

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Conclusion

OBS high encoding warning or encoding overloaded warning is not uncommon. In fact, you are likely to come across this problem if you do not have a high-end computer. In that case, you have to lower resolution, lower frame rate, change encoder preset, try different encoders as well as tweak advanced settings to fix the problem. If the problem is not solved after trying out all the means available, you can switch to Wondershare Filmora as a better alternative for recording and video editing.

[Try It Free](https://tools.techidaily.com/wondershare/filmora/download/)

For macOS 10.12 or later

Step 1: Install Wondershare Filmora on your computer based on your OS. Launch Filmora and click on PC Screen to record your screen.

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![pc-screen](https://images.wondershare.com/filmora/article-images/pc-screen.jpg)

Step 2: Select the recording screen size and the audio sources. If you want to capture webcam as well, turn on Record The Camera Stream option.

![set-audio](https://images.wondershare.com/filmora/article-images/set-audio.jpg)

Step 3: Click on Record button to start recording. Press F9 to stop recording whenever you want.

Step 4: You can edit the recorded video. Thereafter, click on Export button to save it on your hard drive in any desired file format.

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![export the project](https://images.wondershare.com/filmora/article-images/export-the-project.jpg)

## Conclusion

OBS high encoding warning or encoding overloaded warning is not uncommon. In fact, you are likely to come across this problem if you do not have a high-end computer. In that case, you have to lower resolution, lower frame rate, change encoder preset, try different encoders as well as tweak advanced settings to fix the problem. If the problem is not solved after trying out all the means available, you can switch to Wondershare Filmora as a better alternative for recording and video editing.

[Try It Free](https://tools.techidaily.com/wondershare/filmora/download/)

For macOS 10.12 or later

Step 1: Install Wondershare Filmora on your computer based on your OS. Launch Filmora and click on PC Screen to record your screen.

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![pc-screen](https://images.wondershare.com/filmora/article-images/pc-screen.jpg)

Step 2: Select the recording screen size and the audio sources. If you want to capture webcam as well, turn on Record The Camera Stream option.

![set-audio](https://images.wondershare.com/filmora/article-images/set-audio.jpg)

Step 3: Click on Record button to start recording. Press F9 to stop recording whenever you want.

Step 4: You can edit the recorded video. Thereafter, click on Export button to save it on your hard drive in any desired file format.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
<!-- affiliate ads end -->
![export the project](https://images.wondershare.com/filmora/article-images/export-the-project.jpg)

<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Conclusion

OBS high encoding warning or encoding overloaded warning is not uncommon. In fact, you are likely to come across this problem if you do not have a high-end computer. In that case, you have to lower resolution, lower frame rate, change encoder preset, try different encoders as well as tweak advanced settings to fix the problem. If the problem is not solved after trying out all the means available, you can switch to Wondershare Filmora as a better alternative for recording and video editing.

[Try It Free](https://tools.techidaily.com/wondershare/filmora/download/)

For macOS 10.12 or later

Step 1: Install Wondershare Filmora on your computer based on your OS. Launch Filmora and click on PC Screen to record your screen.

![pc-screen](https://images.wondershare.com/filmora/article-images/pc-screen.jpg)

Step 2: Select the recording screen size and the audio sources. If you want to capture webcam as well, turn on Record The Camera Stream option.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![set-audio](https://images.wondershare.com/filmora/article-images/set-audio.jpg)

Step 3: Click on Record button to start recording. Press F9 to stop recording whenever you want.

Step 4: You can edit the recorded video. Thereafter, click on Export button to save it on your hard drive in any desired file format.

![export the project](https://images.wondershare.com/filmora/article-images/export-the-project.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Conclusion

OBS high encoding warning or encoding overloaded warning is not uncommon. In fact, you are likely to come across this problem if you do not have a high-end computer. In that case, you have to lower resolution, lower frame rate, change encoder preset, try different encoders as well as tweak advanced settings to fix the problem. If the problem is not solved after trying out all the means available, you can switch to Wondershare Filmora as a better alternative for recording and video editing.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>







