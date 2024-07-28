---
title: "[Updated] A Beginner's Tutorial on Using LUTs in AR"
date: 2024-07-27T01:06:08.982Z
updated: 2024-07-28T01:06:08.982Z
tags: 
  - screen-recording
  - ai video
  - ai audio
  - ai auto
categories: 
  - ai
  - screen
description: "This Article Describes [Updated] A Beginner's Tutorial on Using LUTs in AR"
excerpt: "This Article Describes [Updated] A Beginner's Tutorial on Using LUTs in AR"
keywords: "AR LUT Basics,Beginners Guide to LUTs,Using LUTs in AR,LUTs for AR Devices,Introduction to AR LUTs,Learning AR LUT Techniques,Essential AR LUT Tutorial"
thumbnail: https://thmb.techidaily.com/1f190d8040197877fe9d91a786d037cb715f0068f8eaaf0f310614210c430f98.jpg
---

## A Beginner's Tutorial on Using LUTs in AR

Color LUTs (Lookup Textures) are tables of RGB color values. In Spark AR, you can use color LUTs to quickly create color gradation effects throughout the scene. Go through the article and create your color LUT effect.

## Part 1\. What are Luts in Spark AR used for?

To create a color filter effect in [Spark AR](https://sparkar.facebook.com/ar-studio/), you need a color LUT in Spark AR.

To develop AR effects for mobile cameras, you can use the Mac and Windows augmented reality platform Spark AR Studio. Imagine it like Sketch or Photoshop for augmented reality. The color values of the camera texture are mapped to the x, y, and z coordinates of the location in the color LUT. This location contains a corresponding output color that is drawn over the scene to create a color gradient effect.

![create a color gradient effect](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-1.jpg)

## Part 2\. How to use LUTs in Spark AR?

**How to apply a color LUT to the whole scene in Spark AR:**

##### Step1Add a color LUT to your project

1. In the Assets panel, click Add Asset.
2. Select Import, then Color LUT, and select your file from your computer.

When you import a color LUT, compression is always set to None, and filtering is set to Low by default.

##### Step2Apply to the whole scene

1. In the Assets panel, right-click the LUT color.
2. Select Actions and then **Apply to Camera**.

A patch graph is automatically set that applies a color LUT to the entire scene.

![apply to the whole scene](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-2.jpg)

**The color LUT patch graph**

The patch graph that renders the color gradation effect looks like this:

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
<!-- affiliate ads end -->
![color lut patch graph](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-3.jpg)

**To create the effect:**

* Fix Scene Render Pass renders cameraTexture0 and all objects in the scene that are children of the device. This creates the output texture.
* ColorLUTShader looks up the RGBA values of this texture in the Tension color LUT array and converts them to a new green color. This will change the texture and create a gradient effect.
* Finally, the Screen Output patch renders the green color.

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Part 3\. Free LUTs resource for Spark AR

Here are the best free LUTs resources for Spark AR:

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 1\. [Frost Zombie (Technical Showcase)](https://we.tl/t-1uj4wJKluG)

Client filter pieces occasionally end up on the scrap heap. It was a poor Frost Zombie in this instance. Since this is one of my simpler filters, I felt it was okay to publish the build information. Four objects make up much of the scene: an EyeColor block, a custom canvas segmentation, a face mesh, and an emitter for the breath mist (my personal favorite). To show the layers used in generating the primary zombie texture, I also moved to Substance Painter. This is a demonstration of my methods rather than a step-by-step manual.

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![frost zombie](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-4.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->
### 2\. Fur

Here are the key building principles.

* Geometric layers, often known as shells, produce depth.
* Normals is used to create shells from a single mesh.
* Alpha decreases with each shell.
* Deeper shells are darker.
* Height is generated from a single grayscale channel.
* No fur is generated in the black areas of the height texture.

![fur](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-5.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
### 3\. Shockwave

Even while using large image sequences is frequently discouraged, you can still use them to make some extremely spectacular effects! I'll explain how the screen tap computation procedure relates to texture position in this walkthrough. If you want to apply this approach and texture sequence in your projects or give it a try.

<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![shockwave](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-6.jpg)

### 4\. Transition Curves

There are 11 distinct animation curves included with Spark AR in the Transition patch. Here is a helpful visual aid because it might be challenging to distinguish between a quartic and a quintic when working on a project. With the SDF circle doubled (to sharpen the edge) and inserted into the Patch Pack's alpha channel, the circles are likewise straightforward rectangles. Since RGB values are three times one, the object is white.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4708689&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Win： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
![transition curves](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-7.jpg)

### 5\. Realistic Smoke

By adding smoke to a scene, you can easily add a lot of detail and realism. Nothing revolutionary is happening here. The particle emitter creates flat planes of smoke texture that are forced upward. The force slowly shifts left and right as seen in the patch editor. The Fade particle script (created by Josh Beckwith) enlarges the particles and fades them out at the same time.

![realistic smoke](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-8.jpg)

### 6\. Rainbow Glitter

Given how beautifully Glitter Rain was received, I believed it would be fitting to broaden the potential with an HDR setting. While Glitter Rain made use of two different colors, this technique makes use of an entirely colorless substance and gets its color information via HDR.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
<!-- affiliate ads end -->
![rainbow glitter](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-9.jpg)

### Closing Thoughts

Spark AR is an amazing website for LUTs and color grading. Whether you're a new student or a seasoned pro, Spark AR Studio has all the features and capabilities you need to become a good video editor. You can download free LUTs from Spark AR and apply them to your videos. The article guides on how to use LUTs in Spark AR and how to download free LUTs. So, Spark AR is one of the best online websites for LUTs I have tried.

[Free Download](https://tools.techidaily.com/wondershare/filmora/download/)For Win 7 or later(64-bit)

[Free Download](https://tools.techidaily.com/wondershare/filmora/download/)For macOS 10.14 or later

[Free Download](https://tools.techidaily.com/wondershare/filmora/download/)For macOS 10.14 or later

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





<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-information.techidaily.com/new-5-best-360-degree-action-cameras-you-should-use/"><u>[New] 5 Best 360-Degree Action Cameras You Should Use</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-achieve-cinematic-brilliance-the-11-ultimate-tutorials-on-color-grading/"><u>[New] Achieve Cinematic Brilliance  The 11 Ultimate Tutorials on Color Grading</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-boost-productivity-on-your-mac-an-overview-of-great-tts-apps/"><u>[New] Boost Productivity on Your Mac  An Overview of Great TTS Apps</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-crafting-auditory-landscapes-in-your-videos/"><u>[New] Crafting Auditory Landscapes in Your Videos</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-crafting-content-that-captivates-instagrams-roadmap-to-success-for-2024/"><u>[New] Crafting Content that Captivates  Instagram’s Roadmap to Success for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-snapchat-mastery-the-essential-guide-to-smartphone-screen-recording-for-2024/"><u>[New] Snapchat Mastery  The Essential Guide to Smartphone Screen Recording for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-2024-approved-excellent-devices-for-frame-by-frame-filmmaking/"><u>[Updated] 2024 Approved  Excellent Devices for Frame-by-Frame Filmmaking</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-boost-your-photo-workflow-in-windows-11/"><u>[Updated] Boost Your Photo Workflow in Windows 11</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-comic-crafting-on-apple-devices/"><u>[Updated] Comic Crafting on Apple Devices</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-comprehensive-list-8-top-android-mp3-downloads/"><u>[Updated] Comprehensive List  8 Top Android MP3 Downloads</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-craft-comical-caricatures-using-giphys-kit/"><u>[Updated] Craft Comical Caricatures Using Giphy's Kit</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-proiphone-close-ups-unlocking-stunning-image-potential-for-2024/"><u>[Updated] Proiphone Close-Ups  Unlocking Stunning Image Potential for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-ultimate-list-of-leading-real-time-tv-streamers-compared/"><u>[Updated] Ultimate List of Leading Real-Time TV Streamers Compared</u></a></li>
<li><a href="https://extra-information.techidaily.com/10-best-free-image-hosting-sites/"><u>10 Best Free Image Hosting Sites</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-adapt-video-ratios-through-web-interface/"><u>2024 Approved  Adapt Video Ratios Through Web Interface</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-brief-sequences-lasting-impressions-time-lapse-with-samsung/"><u>2024 Approved  Brief Sequences, Lasting Impressions  Time-Lapse with Samsung</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-champions-5-wearable-devices-for-top-fpv-racing/"><u>2024 Approved  Champion's 5 Wearable Devices for Top FPV Racing</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-choosing-the-right-gimbal-for-flawless-youtube-footage/"><u>2024 Approved  Choosing the Right Gimbal for Flawless YouTube Footage</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-crafting-compelling-visual-narratives-with-illustrators-motion-blur/"><u>2024 Approved  Crafting Compelling Visual Narratives with Illustrator's Motion Blur</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-the-ultimate-guide-to-rapidly-discover-friends/"><u>2024 Approved  The Ultimate Guide to Rapidly Discover Friends</u></a></li>
<li><a href="https://extra-information.techidaily.com/acoustic-architects-leading-sites-to-buy-skype-tones-for-2024/"><u>Acoustic Architects  Leading Sites to Buy Skype Tones for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/avoidance-tactics-for-edg-vids-in-learning-for-2024/"><u>Avoidance Tactics for EDG Vids in Learning for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/bringing-history-forward-digitizing-old-photographs-into-video-for-2024/"><u>Bringing History Forward  Digitizing Old Photographs Into Video for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/cant-see-cursor-only-sony-a6400-glitch/"><u>Can't See, Cursor Only - Sony A6400 Glitch</u></a></li>
<li><a href="https://extra-information.techidaily.com/capturing-the-world-in-full-circle-experts-360-cams-review-2023/"><u>Capturing the World in Full Circle - Expert's 360 Cams Review, 2023</u></a></li>
<li><a href="https://extra-information.techidaily.com/chronological-tagging-adding-times-to-youtube-vids-for-2024/"><u>Chronological Tagging  Adding Times to YouTube Vids for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/comprehensive-guide-to-android-screenshotting-for-2024/"><u>Comprehensive Guide to Android Screenshotting for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/comprehensive-look-at-lg-bp350-display-specifications-for-2024/"><u>Comprehensive Look at LG BP350 Display Specifications for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/crafting-compelling-docu-scripts-a-step-by-step-guide/"><u>Crafting Compelling Docu-Scripts  A Step-by-Step Guide</u></a></li>
<li><a href="https://extra-information.techidaily.com/effortless-large-file-sharing-iphone-to-mac-streamlined-guide/"><u>Effortless Large File Sharing  IPhone to Mac Streamlined Guide</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-remove-or-bypass-knox-enrollment-service-on-poco-by-drfone-android/"><u>How To Remove or Bypass Knox Enrollment Service On Poco</u></a></li>
<li><a href="https://extra-information.techidaily.com/ignite-passion-an-essential-guide-to-10-motivational-films/"><u>Ignite Passion  An Essential Guide to 10 Motivational Films</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-5-tips-for-enhancing-photo-colors-effortlessly/"><u>In 2024, 5 Tips for Enhancing Photo Colors Effortlessly</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-a-step-beyond-excavating-the-best-vr-treadmill-experiences/"><u>In 2024, A Step Beyond  Excavating the Best VR Treadmill Experiences</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-harmonious-hush-techniques-for-quieting-tunes/"><u>In 2024, Harmonious Hush  Techniques for QUIETing Tunes</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-new-windows-11-hacks-for-efficiency-experts/"><u>In 2024, New Windows 11 Hacks for Efficiency Experts</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-screen-recorder-alternatives-in-depth-review-and-top-picks/"><u>In 2024, Screen Recorder Alternatives  In-Depth Review & Top Picks</u></a></li>
<li><a href="https://extra-information.techidaily.com/innovating-audio-visuals-podcast-covers-explained/"><u>Innovating Audio Visuals  Podcast Covers Explained</u></a></li>
<li><a href="https://extra-information.techidaily.com/innovative-approaches-to-run-a-winning-fb-giveaway/"><u>Innovative Approaches to Run a Winning FB Giveaway</u></a></li>
<li><a href="https://extra-information.techidaily.com/maximize-your-iphones-capture-potential/"><u>Maximize Your iPhone's Capture Potential</u></a></li>
<li><a href="https://extra-information.techidaily.com/perfect-audio-connection-must-have-tips-for-podcasters/"><u>Perfect Audio Connection  Must-Have Tips for Podcasters</u></a></li>
<li><a href="https://extra-information.techidaily.com/premier-mobile-dev-editor-software-guide/"><u>Premier Mobile Dev Editor Software Guide</u></a></li>
<li><a href="https://extra-information.techidaily.com/sculpting-success-in-visual-communications/"><u>Sculpting Success in Visual Communications</u></a></li>
<li><a href="https://extra-information.techidaily.com/snapping-wonders-how-to-find-optimal-iphone-viewing-points/"><u>Snapping Wonders  How to Find Optimal iPhone Viewing Points</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-manage-disks-keyways-into-windows-11s-storage-manager/"><u>Swiftly Manage Disks: Keyways Into Windows 11'S Storage Manager</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-ultimate-guide-to-metaverse-laughter-for-2024/"><u>The Ultimate Guide to Metaverse Laughter for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-ultimate-tech-handbook-working-with-srt-files-on-a-mac/"><u>The Ultimate Tech Handbook  Working with SRT Files on a Mac</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-ultimate-tv-show-prep-which-software-winsvirusmix-or-wirecast/"><u>The Ultimate TV Show Prep  Which Software Wins—VirusMix or WireCast?</u></a></li>
<li><a href="https://extra-information.techidaily.com/top-7-best-waterproof-action-camera-for-2024/"><u>Top 7 Best Waterproof Action Camera for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/transform-your-tiktok-content-with-expert-number-manipulation/"><u>Transform Your TikTok Content with Expert Number Manipulation</u></a></li>
<li><a href="https://extra-information.techidaily.com/uncovering-inexpensive-deals-for-your-gopro-camera/"><u>Uncovering Inexpensive Deals for Your GoPro Camera</u></a></li>
<li><a href="https://extra-information.techidaily.com/voicemail-recorder-on-iphone-2024/"><u>Voicemail Recorder on iPhone 2024</u></a></li>
</ul></div>
