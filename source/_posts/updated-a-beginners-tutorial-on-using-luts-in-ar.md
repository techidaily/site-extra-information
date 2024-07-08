---
title: "[Updated] A Beginner's Tutorial on Using LUTs in AR"
date: 2024-05-24T10:28:25.222Z
updated: 2024-05-25T10:28:25.222Z
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
thumbnail: https://www.lifewire.com/thmb/tytwbqcYgTF7h7x0nLFuA1_IxhI=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/GettyImages-515810476-aabe0e5a88b44bb1ae49a5bfa97bec62.jpg
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

![color lut patch graph](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-3.jpg)

**To create the effect:**

* Fix Scene Render Pass renders cameraTexture0 and all objects in the scene that are children of the device. This creates the output texture.
* ColorLUTShader looks up the RGBA values of this texture in the Tension color LUT array and converts them to a new green color. This will change the texture and create a gradient effect.
* Finally, the Screen Output patch renders the green color.

## Part 3\. Free LUTs resource for Spark AR

Here are the best free LUTs resources for Spark AR:

### 1\. [Frost Zombie (Technical Showcase)](https://we.tl/t-1uj4wJKluG)

Client filter pieces occasionally end up on the scrap heap. It was a poor Frost Zombie in this instance. Since this is one of my simpler filters, I felt it was okay to publish the build information. Four objects make up much of the scene: an EyeColor block, a custom canvas segmentation, a face mesh, and an emitter for the breath mist (my personal favorite). To show the layers used in generating the primary zombie texture, I also moved to Substance Painter. This is a demonstration of my methods rather than a step-by-step manual.

![frost zombie](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-4.jpg)

### 2\. Fur

Here are the key building principles.

* Geometric layers, often known as shells, produce depth.
* Normals is used to create shells from a single mesh.
* Alpha decreases with each shell.
* Deeper shells are darker.
* Height is generated from a single grayscale channel.
* No fur is generated in the black areas of the height texture.

![fur](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-5.jpg)

### 3\. Shockwave

Even while using large image sequences is frequently discouraged, you can still use them to make some extremely spectacular effects! I'll explain how the screen tap computation procedure relates to texture position in this walkthrough. If you want to apply this approach and texture sequence in your projects or give it a try.

![shockwave](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-6.jpg)

### 4\. Transition Curves

There are 11 distinct animation curves included with Spark AR in the Transition patch. Here is a helpful visual aid because it might be challenging to distinguish between a quartic and a quintic when working on a project. With the SDF circle doubled (to sharpen the edge) and inserted into the Patch Pack's alpha channel, the circles are likewise straightforward rectangles. Since RGB values are three times one, the object is white.

![transition curves](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-7.jpg)

### 5\. Realistic Smoke

By adding smoke to a scene, you can easily add a lot of detail and realism. Nothing revolutionary is happening here. The particle emitter creates flat planes of smoke texture that are forced upward. The force slowly shifts left and right as seen in the patch editor. The Fade particle script (created by Josh Beckwith) enlarges the particles and fades them out at the same time.

![realistic smoke](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-8.jpg)

### 6\. Rainbow Glitter

Given how beautifully Glitter Rain was received, I believed it would be fitting to broaden the potential with an HDR setting. While Glitter Rain made use of two different colors, this technique makes use of an entirely colorless substance and gets its color information via HDR.

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
<li><a href="https://extra-information.techidaily.com/accelerated-image-viewer-in-windows-environment-for-2024/"><u>Accelerated Image Viewer in Windows Environment for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-aspect-ratio-conversion-techniques-online/"><u>[Updated] Aspect Ratio Conversion Techniques Online</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-allstream-worldwide-selective-local-channel-selection/"><u>[New] AllStream Worldwide  Selective Local Channel Selection</u></a></li>
<li><a href="https://extra-information.techidaily.com/top-gratis-vector-design-and-illustration-sites-online/"><u>Top Gratis Vector Design & Illustration Sites Online</u></a></li>
<li><a href="https://extra-information.techidaily.com/transform-your-photos-with-ease-comprehensive-guide-on-background-erasure-tool-usage/"><u>Transform Your Photos with Ease  Comprehensive Guide on Background Erasure Tool Usage</u></a></li>
<li><a href="https://extra-information.techidaily.com/detailed-study-exploring-the-capabilities-of-android-lightroom/"><u>Detailed Study  Exploring the Capabilities of Android Lightroom</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-affordable-skybanking-for-heavy-data-hoarding/"><u>[New] Affordable SkyBanking for Heavy Data Hoarding</u></a></li>
<li><a href="https://extra-information.techidaily.com/nba-game-broadcasting-select-the-best-platforms/"><u>NBA Game Broadcasting  Select the Best Platforms</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-breaking-down-average-podcaster-salary/"><u>[Updated] Breaking Down Average Podcaster Salary</u></a></li>
<li><a href="https://extra-information.techidaily.com/future-of-videography-top-cameras-2024/"><u>Future of Videography  Top Cameras 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/yuneecs-breeze-a-quest-for-perfect-vision/"><u>Yuneec's Breeze - A Quest for Perfect Vision</u></a></li>
<li><a href="https://extra-information.techidaily.com/best-macos-sierra-tools-for-optimized-video-transformation-for-2024/"><u>Best macOS Sierra Tools for Optimized Video Transformation for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-building-an-instagram-empire-in-just-nine-simple-steps/"><u>[New] Building an Instagram Empire in Just Nine Simple Steps</u></a></li>
<li><a href="https://extra-information.techidaily.com/ace-applications-transforming-videos-for-tweet-for-2024/"><u>Ace Applications  Transforming Videos for Tweet for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/understanding-the-metaverse-6-compelling-realities-unveiled/"><u>Understanding the Metaverse  6 Compelling Realities Unveiled</u></a></li>
<li><a href="https://extra-information.techidaily.com/exploring-metaverse-ranking-best-8-vr-headsets/"><u>Exploring Metaverse  Ranking Best 8 VR Headsets</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-free-pass-to-premium-video-editing-tools/"><u>The Free Pass to Premium Video Editing Tools</u></a></li>
<li><a href="https://extra-information.techidaily.com/expert-audio-enhancement-toolkit/"><u>Expert Audio Enhancement Toolkit</u></a></li>
<li><a href="https://extra-information.techidaily.com/exemplar-storyboard-creators-circle/"><u>Exemplar Storyboard Creator's Circle</u></a></li>
<li><a href="https://extra-information.techidaily.com/easy-steps-for-srt-files-into-xml-ssa-ttml/"><u>Easy Steps for SRT Files Into XML, SSA, TTML</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-choreographing-ideal-canon-sequential-shots/"><u>[Updated] Choreographing Ideal Canon Sequential Shots</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-achieving-high-quality-tiktok-videos-the-zoom-method/"><u>[New] Achieving High-Quality TikTok Videos  The Zoom Method</u></a></li>
<li><a href="https://extra-information.techidaily.com/prime-8-virtual-vision-composition-program/"><u>Prime 8 Virtual Vision Composition Program</u></a></li>
<li><a href="https://extra-information.techidaily.com/media-streamlining-is-a-podcast-or-youtube-better-for-you/"><u>Media Streamlining  Is a Podcast or YouTube Better for You?</u></a></li>
<li><a href="https://extra-information.techidaily.com/12-signs-endless-stories-create-your-whatsapp-bio-narrative-for-2024/"><u>12 Signs, Endless Stories - Create Your WhatsApp Bio Narrative for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-advanced-techniques-for-dynamic-and-dramatic-ae-heads-ups/"><u>In 2024, Advanced Techniques for Dynamic and Dramatic AE Heads-Ups</u></a></li>
<li><a href="https://extra-information.techidaily.com/sdr-to-hdr-ultimate-guide-on-sdr-to-hdr-video-conversion/"><u>SDR to HDR Ultimate Guide on SDR to HDR Video Conversion</u></a></li>
<li><a href="https://extra-information.techidaily.com/1716286302649-live-streaming-software-vs-hardware-which-is-better/"><u>Live Streaming Software Vs Hardware  Which Is Better?</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-adding-visuals-on-instagram-quickly/"><u>In 2024, Adding Visuals on Instagram Quickly</u></a></li>
<li><a href="https://extra-information.techidaily.com/clearing-clutter-background-removal-for-2024/"><u>Clearing Clutter  Background Removal for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/tailoring-your-footage-a-comprehensive-guide-to-gopros-color-adjustment/"><u>Tailoring Your Footage  A Comprehensive Guide to GoPro's Color Adjustment</u></a></li>
<li><a href="https://extra-information.techidaily.com/top-7-sites-for-swapping-outringtone-files-on-snapchat/"><u>Top 7 Sites for Swapping Outringtone Files on Snapchat</u></a></li>
<li><a href="https://extra-information.techidaily.com/solving-iphone-xs-identity-crisis-fixing-face-id-failures/"><u>Solving iPhone X's Identity Crisis  Fixing Face ID Failures</u></a></li>
<li><a href="https://extra-information.techidaily.com/mastering-motion-capture-top-gear-recommendations/"><u>Mastering Motion Capture - Top Gear Recommendations</u></a></li>
<li><a href="https://extra-information.techidaily.com/battle-of-worthies-black-gopros-challenger-is-sony-x1000v/"><u>Battle of Worthies  Black GoPro's Challenger Is Sony X1000V</u></a></li>
<li><a href="https://extra-information.techidaily.com/masterful-character-animation-groups/"><u>Masterful Character Animation Groups</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-the-editors-shadows-top-tips-for-outstanding-videos/"><u>In the Editor's Shadows  Top Tips for Outstanding Videos</u></a></li>
<li><a href="https://extra-information.techidaily.com/ultimate-list-of-text-tools-and-plugins/"><u>Ultimate List of Text Tools & Plugins</u></a></li>
<li><a href="https://extra-information.techidaily.com/perfect-propeller-synergy-for-awe-inspiring-fpv-flights/"><u>Perfect Propeller Synergy for Awe-Inspiring FPV Flights</u></a></li>
<li><a href="https://extra-information.techidaily.com/grids-that-wow-discover-the-top-apps-for-pics/"><u>Grids That Wow  Discover the Top Apps for Pics</u></a></li>
<li><a href="https://extra-information.techidaily.com/optimized-process-for-melding-gopro-sequences-in-full-dome-videos/"><u>Optimized Process for Melding GoPro Sequences in Full-Dome Videos</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-beginners-choices-superior-gopro-accessories/"><u>[New] Beginner’s Choices  Superior GoPro Accessories</u></a></li>
<li><a href="https://extra-information.techidaily.com/craft-your-photos-in-minutes-learning-lunapic/"><u>Craft Your Photos in Minutes  Learning LunaPic</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-network-locked-sim-card-inserted-on-your-samsung-galaxy-m34-phone-unlock-it-now-by-drfone-android/"><u>In 2024, Network Locked SIM Card Inserted On Your Samsung Galaxy M34 Phone? Unlock It Now</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/motion-blur-magic-a-comprehensive-guide-to-final-cut-pro-techniques-for-2024/"><u>Motion Blur Magic A Comprehensive Guide to Final Cut Pro Techniques for 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-xiaomi-14-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Xiaomi 14 to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/enhancing-fb-video-clarity-to-1080p-standard/"><u>Enhancing FB Video Clarity to 1080P Standard</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-best-discord-emoji-makers/"><u>[Updated] Best Discord Emoji Makers</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-in-2024-easy-cartoon-characters-drawing-tutorials-for-you-who-are-learning-to-draw/"><u>New In 2024, Easy Cartoon Characters Drawing Tutorials for You Who Are Learning to Draw</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-spatial-symphony-with-mac-recording/"><u>2024 Approved  Spatial Symphony with Mac Recording</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-best-software-for-capturing-your-desktop-screen-pcmac-for-2024/"><u>[Updated] Best Software for Capturing Your Desktop Screen, PC/Mac for 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-top-rated-online-webm-video-minifiers-for-2024/"><u>New Top-Rated Online WebM Video Minifiers for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-intenseflame-screen-recorders/"><u>[Updated] 2024 Approved  IntenseFlame Screen Recorders</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/8-best-websites-to-download-free-sound-fx/"><u>8 Best Websites To Download Free Sound FX</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-fake-snapchat-location-on-oneplus-12r-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fake Snapchat Location on OnePlus 12R | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/apple-iphone-15-pro-max-backup-password-never-set-but-still-asking-heres-the-fix-by-drfone-ios/"><u>Apple iPhone 15 Pro Max Backup Password Never Set But Still Asking? Heres the Fix</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/full-guide-to-bypass-honor-x9a-frp-by-drfone-android/"><u>Full Guide to Bypass Honor X9a FRP</u></a></li>
<li><a href="https://change-location.techidaily.com/catchemall-celebrate-national-pokemon-day-with-virtual-location-on-xiaomi-redmi-note-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>CatchEmAll Celebrate National Pokémon Day with Virtual Location On Xiaomi Redmi Note 12 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-how-to-livestream-wisdom-without-wealth-waste/"><u>[New] 2024 Approved  How to Livestream Wisdom Without Wealth Waste</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-from-voice-to-text-top-mac-apps-for-accurate-transcription-free-and-no-download-for-2024/"><u>New From Voice to Text Top Mac Apps for Accurate Transcription Free & No Download for 2024</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/best-10-sound-boosters-for-android-and-ios-sound-booster-app/"><u>Best 10 Sound Boosters for Android and iOS-Sound Booster App</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-do-xiaomi-redmi-13c-5g-screen-sharing-drfone-by-drfone-android/"><u>How To Do Xiaomi Redmi 13C 5G Screen Sharing | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-7-phone-number-locators-to-track-xiaomi-redmi-a2plus-location-drfone-by-drfone-virtual-android/"><u>In 2024, Top 7 Phone Number Locators To Track Xiaomi Redmi A2+ Location | Dr.fone</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/top-5-ai-youtube-shorts-generators/"><u>Top 5 AI YouTube Shorts Generators</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-apple-iphone-11-pro-max-without-passcode-4-easy-methods-by-drfone-ios/"><u>How To Unlock Apple iPhone 11 Pro Max Without Passcode? 4 Easy Methods</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/soundcheck-summary-for-2024/"><u>SoundCheck Summary for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/the-best-methods-to-unlock-the-iphone-locked-to-owner-for-iphone-11-pro-max-by-drfone-ios/"><u>The Best Methods to Unlock the iPhone Locked to Owner for iPhone 11 Pro Max</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/remove-tiktok-logos-with-ease-best-online-watermark-removers-for-2024/"><u>Remove TikTok Logos with Ease Best Online Watermark Removers for 2024</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-escalate-volumes-on-screen-sounds-for-enhanced-perception/"><u>Updated Escalate Volumes on Screen Sounds for Enhanced Perception</u></a></li>
<li><a href="https://animation-videos.techidaily.com/how-to-convert-video-to-gif-fast-and-easy-for-2024/"><u>How to Convert Video to GIF Fast & Easy for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-optimizing-facebook-ads-with-a-structured-triple-layered-copywriting-approach/"><u>[New] 2024 Approved  Optimizing Facebook Ads with a Structured, Triple-Layered Copywriting Approach</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-additional-tips-about-sinnoh-stone-for-vivo-y78plus-t1-edition-drfone-by-drfone-virtual-android/"><u>In 2024, Additional Tips About Sinnoh Stone For Vivo Y78+ (T1) Edition | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-music-device-innovations-spotlighted/"><u>2024 Approved  Music Device Innovations Spotlighted</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-compreehing-and-engaging-with-your-twitter-archive/"><u>[New] 2024 Approved  Compreehing & Engaging with Your Twitter Archive</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-reset-a-honor-x50-gt-phone-that-is-locked-by-drfone-android/"><u>How to Reset a Honor X50 GT Phone that is Locked?</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-vivo-s18-pro-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>How to Track Vivo S18 Pro Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-oppo-a1-5g-without-the-home-button-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Oppo A1 5G Without the Home Button | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-on-onepluswithwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock on OnePluswith/without a PC</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-tecno-pova-5-pro-drfone-by-drfone-virtual-android/"><u>How to get the dragon scale and evolution-enabled pokemon On Tecno Pova 5 Pro? | Dr.fone</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-amplify-your-content-mastering-trending-tiktok-hashtags/"><u>[Updated] In 2024, Amplify Your Content  Mastering Trending TikTok HashTags</u></a></li>
</ul></div>

