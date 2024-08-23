---
title: Adjust Unsupported Software Package
date: 2024-08-22T19:38:42.324Z
updated: 2024-08-23T19:38:42.324Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverInstall
description: This Article Describes Adjust Unsupported Software Package
excerpt: This Article Describes Adjust Unsupported Software Package
keywords: Adjusting Unsupported Software,Unsupported Software Configuration (Long-Tail Keyword),Fix Unsupported Application Package,Updating Discontinued Programs,Remedy Outdated Software Issues (Long-Tail Keyword),Compatible Solutions for Unsupported Applications (Keyword + Long-Tail),Supporting Legacy Software Packages (Keywords & Long-Tail Keyword)
thumbnail: https://thmb.techidaily.com/d9a0fed70b3544c875727acbd189babb9991061b2738772aa77659169a12a4b8.jpg
---

## Adjust Unsupported Software Package

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0bf7fa95390.png)

 Does this look familiar? You may see this error message when launching a program or installing a driver in your Windows PC or laptop. The error usually reads:

* **This installation package is not supported by this processor type.**

 But don’t worry. Many users have resolved their problem with the solutions in this article. So check it out…

## Try these fixes

1. [**Restart PC and reinstall the application/program**](#Fix1) **[](#Method1)**
2. [**Automatically update your drivers**](#Fix2)
3. [**Update your Windows version**](#Fix3)

## Why does this problem occur when installing drivers?

 The reason why it happens when installing an application or program is that there is something wrong with the installation file when progressing, so you can try to restart your computer and try again.

As for the reason why it happens while installing drivers:

 Previously, you can successfully install the driver package when the Windows OS and processor type are as defined by the driver manufacturers.

 However, starting from 2016, Microsoft made changes to its update strategies. The change is in the format of**TargetOSVersion** decoration, an entry in **[INF file](https://docs.microsoft.com/en-us/windows-hardware/drivers/install/inf-manufacturer-section)**  . This format defines the installation information to install the driver package, such as the OS versions and the product types.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0bf47b50435.png)

 Starting with Windows 10, version 1607 (Build 14310 and later), the format adds a new part in the INF file: the**\[BuildNumber\]** part. That means that **it started to define the build number of the Windows version when installing the drivers** . Soon after, **Intel has started to adopt this new technique and also add the \[BuildNumber\] part into the installation information** .

 That is to say, If the build number of your Windows version doesn’t fit with the defined \[BuildNumber\] part of the package by the driver manufacturers, you will fail to install the driver package, despite the correct Windows version and processor type.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
<!-- affiliate ads end -->
### **How to Check the Build Number in your Windows**

**Tips:** If you want to check whether the build number in your Windows fits with the one defined by the driver manufacturer, follow these instructions:

 Check your computer’s build number and other system information via Command Prompt:

 1) Type**cmd** in the search box, and right click **Command Prompt** to**Run as administrator** . Then click**Yes** .

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a018c0f66b68.png)

 2) Type**systeminfo** and press**Enter** . Then you will see your build number as below:

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0c202e7a2f5.png)

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
<!-- affiliate ads end -->
 Then check the defined build number in the driver package (take Intel graphics driver for Windows 10 64 bit as an example):

 1) Go to the [Intel download center](https://downloadcenter.intel.com/) , and search then download your preferred device driver.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0c21f7f0851.jpg)

 2) Open the downloaded file, and click the**Graphics** folder.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0c1a2de4eb3.png)

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
 3) Find a file with **.inf extension name** and open it.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0c1a97204a5.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
<!-- affiliate ads end -->
 4) Check the **\[Manufacturer\]** part in the file, and you will see defined build number. As you can see 14393 in the \[BuildNumber\] part, this driver package supports to download on Windows 14393 and later.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0c1b58eebf9.png)

 If the build number of your Windows is not 14393 and later, you can’t install this graphics driver in your computer.

### Fix 1: Restart your PC and reinstall the application/program

 If you run into the error when you are downloading or installing a program in your computer, there may be something wrong with the installation file or parsing the file, so you can try to restart your PC, and download the installation file again to reinstall it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
### Fix 2: Automatically update your drivers

 A missing or outdated driver can also cause the error, so you can try to update the drivers in your computer to remove the error when installing the program. Though you may have problems to install drivers online, you can also try this method. There are two ways to download and install the drivers in your Windows.

**Option 1 – Manually** : You can manually download and install the drivers in your Windows. You may need to find the correct drivers on the website, check if the build number defined by the driver installation package match with the build number in your Windows (you can click [here](#Step1) to know how to check the build number), and then download it in your Windows. That may require time and computer skills.

**Option 2 – Automatically (Recommended)** : If you don’t have time or skills to find and install the drivers manually, you can do it automatically with [**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) .

 With Driver Easy, you don’t need to know the exactly build number of your computer, and you don’t need to risk installing the wrong driver. Furthermore, it supports the new scan technique in Windows 10\. This will help you find more accurate scan results.

 You can update your drivers automatically with either the**FREE** or the**Pro version** of Driver Easy. But with the Pro version it takes just 2 clicks (and you get**full support and a 30-day money back guarantee**):

 1) [**Download**](https://tools.techidaily.com/drivereasy/download/)   and install Driver Easy.

 2) Run Driver Easy and click **Scan Now** . Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0c05705e2b9.jpg)

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 3) Click the **Update**  button next to a flagged driver to automatically install the correct driver (you can do this with the FREE version).

Or click **Update All** to automatically download the correct version of _all_  the drivers that are missing or outdated on your system (this requires the [**Pro version**](https://tools.techidaily.com/drivereasy/download/) – you’ll be prompted to upgrade when you click Update All).

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0bf3e95e05a.jpg)

 4) Restart your Windows and you will have the latest and correct drivers in your Windows.

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Fix 3: Update your Windows version

 You can update your Windows 10 to the latest version to solve this problem. In doing that, your build number is always the latest. While installing the driver, you don’t need to worry whether your build number is correct or not. Follow these instructions to update:

 1) Click the**Settings** button in the**Start menu** .

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0beef3646db.png)

 2) Click **Update & security** .

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0bef3bdbe04.jpg)

 3) Click**Check for updates** to scan for the latest update, then your Windows will automatically download the updates.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0bf009896fc.png)

 4) Click**Restart Now** to restart your PC/laptop and finish the update.

 5) Try to install the driver again to see if it works.

 Hope these methods can help you fix the error. If you problem still persists, feel free to let us know and we will see what more we can do to further help.

* [Drivers](https://tools.techidaily.com/drivereasy/download/)
* [Windows 10](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://facebook-video-footage.techidaily.com/new-best-of-the-best-cutting-edge-hiring-videos-1-10-for-2024/"><u>[New] Best of the Best  Cutting-Edge Hiring Videos #1-10 for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-claim-cost-free-visuals-from-highest-rated-4-youtube-sources-for-2024/"><u>[New] Claim Cost-Free Visuals From Highest-Rated 4 YouTube Sources for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-crafting-cinematic-content-with-video-enhance-v22/"><u>[New] Crafting Cinematic Content with Video Enhance V2.2</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-essential-history-series-youtube-recommendations-for-learners-for-2024/"><u>[New] Essential History Series  YouTube Recommendations for Learners for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/new-essential-tools-for-youtube-live-broadcasting-reveal-the-7-key-apps/"><u>[New] Essential Tools for YouTube LIVE Broadcasting  Reveal the 7 Key Apps</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-mobile-streamers-guide-post-photos-and-videos-not-twits-for-2024/"><u>[New] Mobile Streamers' Guide  Post Photos & Videos, Not Twits for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/he-rotation-ritual-youtube-video-techniques-for-visual-impact/"><u>[New] The Rotation Ritual  Youtube Video Techniques for Visual Impact</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-7-best-video-player-for-mac/"><u>[Updated] 7 Best Video Player for Mac</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-reawakening-dormant-connections-with-your-obs-cam/"><u>[Updated] In 2024, Reawakening Dormant Connections with Your OBS Cam</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-notable-creators-superior-insta-highlight-craftsmen-for-2024/"><u>[Updated] Notable Creators  Superior Insta Highlight Craftsmen for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-xiaomis-precision-flight-insights-via-4k-lens-for-2024/"><u>[Updated] Xiaomi's Precision Flight Insights via 4K Lens for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-breaking-down-chromes-multi-tasking-the-pip-experience/"><u>2024 Approved  Breaking Down Chrome's Multi-Tasking  The PIP Experience</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-globes-biggest-video-content-mogul/"><u>2024 Approved  Globe’s Biggest Video Content Mogul</u></a></li>
<li><a href="https://buynow-info.techidaily.com/assessing-google-stadia-identifying-potential-enhancements/"><u>Assessing Google Stadia: Identifying Potential Enhancements</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/creating-the-perfect-viewing-space-how-to-construct-a-diy-projector-screen/"><u>Creating the Perfect Viewing Space: How to Construct a DIY Projector Screen</u></a></li>
<li><a href="https://extra-information.techidaily.com/editors-edge-the-power-of-video-tools-on-m1-technology/"><u>Editors' Edge  The Power of Video Tools on M1 Technology</u></a></li>
<li><a href="https://win-dash.techidaily.com/fixing-startech-hardware-drivers-on-various-windows-versions-tips-for-windows-1187-users/"><u>Fixing StarTech Hardware Drivers on Various Windows Versions: Tips for Windows 11/8/7 Users</u></a></li>
<li><a href="https://driver-install.techidaily.com/how-to-resolve-lack-of-sound-over-hdmi-from-a-computer-connected-to-monitor-and-tv/"><u>How To Resolve Lack of Sound Over HDMI From a Computer Connected to Monitor and TV</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-unbrick-a-dead-honor-x7b-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Unbrick a Dead Honor X7b | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-decoding-youtubes-economic-strategy-the-rise-of-short-videos/"><u>In 2024, Decoding YouTube’s Economic Strategy  The Rise of Short Videos</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-lock-apps-on-nokia-105-classic-to-protect-your-individual-information-by-drfone-android/"><u>In 2024, How to Lock Apps on Nokia 105 Classic to Protect Your Individual Information</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-retrospective-on-the-goofy-movie-a-comprehensive-review/"><u>In 2024, Retrospective on 'The Goofy Movie'  A Comprehensive Review</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-slomo-videography-the-complete-app-analysis/"><u>In 2024, SloMo Videography  The Complete App Analysis</u></a></li>
<li><a href="https://win-dash.techidaily.com/logitech-t630-supported-software-and-updates-download-for-windows-7-8-10/"><u>Logitech T630 Supported Software & Updates - Download for Windows 7, 8, 10</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/planning-to-use-a-pokemon-go-joystick-on-honor-x50iplus-drfone-by-drfone-virtual-android/"><u>Planning to Use a Pokemon Go Joystick on Honor X50i+? | Dr.fone</u></a></li>
<li><a href="https://driver-install.techidaily.com/refresh-intel-support-in-win-11781-hardware-setup/"><u>Refresh Intel Support in Win 11/7/8.1 Hardware Setup</u></a></li>
<li><a href="https://driver-install.techidaily.com/reinstalling-atheros-wireless-card-drivers-step-by-step/"><u>Reinstalling Atheros Wireless Card Drivers Step-by-Step</u></a></li>
<li><a href="https://driver-install.techidaily.com/release-announcement-amds-new-graphics-drivers/"><u>Release Announcement: AMD's New Graphics Drivers</u></a></li>
<li><a href="https://driver-install.techidaily.com/restore-functionality-with-reinstalled-atheros-drivers/"><u>Restore Functionality with Reinstalled Atheros Drivers</u></a></li>
<li><a href="https://driver-install.techidaily.com/routine-for-updating-and-keeping-your-amd-drivers-current/"><u>Routine for Updating & Keeping Your AMD Drivers Current</u></a></li>
<li><a href="https://driver-install.techidaily.com/secure-logitech-webcam-updater-for-windows-10/"><u>Secure Logitech Webcam Updater for Windows 10</u></a></li>
<li><a href="https://driver-install.techidaily.com/simple-step-superior-scsi-functionality/"><u>Simple Step, Superior SCSI Functionality</u></a></li>
<li><a href="https://driver-install.techidaily.com/simple-updates-to-graphics-drivers-in-win7/"><u>Simple Updates to Graphics Drivers in Win7</u></a></li>
<li><a href="https://driver-install.techidaily.com/simple-smooth-solutions-to-driver-glitches/"><u>Simple, Smooth Solutions to Driver Glitches</u></a></li>
<li><a href="https://driver-install.techidaily.com/simplified-gtx-750-ti-driver-access/"><u>Simplified GTX 750 Ti Driver Access</u></a></li>
<li><a href="https://driver-install.techidaily.com/smooth-operations-with-hp-projector-8710-driver-pack-windows-compatibility/"><u>Smooth Operations with HP Projector 8710 Driver Pack (Windows Compatibility)</u></a></li>
<li><a href="https://win-answers.techidaily.com/speedy-tweaks-to-resolve-stutter-in-elden-ring/"><u>Speedy Tweaks to Resolve Stutter in Elden Ring</u></a></li>
<li><a href="https://driver-install.techidaily.com/step-by-step-guide-to-fast-nvidia-drivers-update/"><u>Step-by-Step Guide to Fast Nvidia Drivers Update</u></a></li>
<li><a href="https://driver-install.techidaily.com/streamline-audio-support-in-windows-11/"><u>Streamline Audio Support in Windows 11</u></a></li>
<li><a href="https://driver-install.techidaily.com/streamline-hp-printer-functionality-using-win11-drivers/"><u>Streamline HP Printer Functionality Using Win11 Drivers</u></a></li>
<li><a href="https://driver-install.techidaily.com/streamlining-audio-support-in-ws1111-version-upgrade/"><u>Streamlining Audio Support in WS11/11 Version Upgrade</u></a></li>
<li><a href="https://driver-install.techidaily.com/successful-installation-of-win10-audio-drivers/"><u>Successful Installation of Win10 Audio Drivers</u></a></li>
<li><a href="https://driver-install.techidaily.com/supercharge-your-gameplay-rtx-3090-for-windows/"><u>Supercharge Your Gameplay - RTX 3090 for Windows</u></a></li>
<li><a href="https://driver-install.techidaily.com/the-key-to-modernizing-msi-boards-in-legacy-operating-systems/"><u>The Key to Modernizing MSI Boards in Legacy Operating Systems</u></a></li>
<li><a href="https://driver-install.techidaily.com/transform-your-screen-hp-drivers-in-windows-10/"><u>Transform Your Screen: HP Drivers in Windows 10</u></a></li>
<li><a href="https://driver-install.techidaily.com/transitioning-joy-cons-from-xbox-to-windows-pcs/"><u>Transitioning Joy-Cons From Xbox to Windows PCs</u></a></li>
<li><a href="https://driver-install.techidaily.com/troubleshoot-deskjet-printer-in-windows-os/"><u>Troubleshoot Deskjet Printer in Windows OS</u></a></li>
<li><a href="https://driver-install.techidaily.com/turbo-speed-tp-link-wi-fi-drivers-downloads-for-windows/"><u>Turbo Speed: TP Link Wi-Fi Drivers Downloads for Windows</u></a></li>
<li><a href="https://driver-install.techidaily.com/turbocharged-windows-10-rapid-acer-drivers-upgrade-guide/"><u>Turbocharged Windows 10: Rapid Acer Drivers Upgrade Guide</u></a></li>
<li><a href="https://driver-install.techidaily.com/ultra-performance-winrtx-3090-ti-driver/"><u>Ultra Performance: WinRTX 3090 Ti Driver</u></a></li>
<li><a href="https://driver-install.techidaily.com/uninstalling-and-refresh-wacom-drivers-on-multiple-windows-editions/"><u>Uninstalling & Refresh Wacom Drivers on Multiple Windows Editions</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/unleash-your-creativity-video-editing-on-mac-os-x-yosemite-for-beginners-for-2024/"><u>Unleash Your Creativity Video Editing on Mac OS X Yosemite for Beginners for 2024</u></a></li>
<li><a href="https://driver-install.techidaily.com/unlock-new-capabilities-in-huion-h420-via-windows-updates/"><u>Unlock New Capabilities in Huion H420 via Windows Updates</u></a></li>
<li><a href="https://driver-install.techidaily.com/update-with-a-click-lenovo-g580-drivers/"><u>Update with a Click: Lenovo G580 Drivers</u></a></li>
<li><a href="https://driver-install.techidaily.com/update-your-computers-amd-radeon-driver/"><u>Update Your Computer's AMD Radeon Driver</u></a></li>
<li><a href="https://driver-install.techidaily.com/updating-sound-drivers-on-windows-11/"><u>Updating Sound Drivers on Windows 11</u></a></li>
<li><a href="https://driver-install.techidaily.com/upgrade-windows-10-for-enhanced-audio-capabilities/"><u>Upgrade Windows 10 for Enhanced Audio Capabilities</u></a></li>
<li><a href="https://change-location.techidaily.com/ways-to-trade-pokemon-go-from-far-away-on-vivo-v30-pro-drfone-by-drfone-virtual-android/"><u>Ways to trade pokemon go from far away On Vivo V30 Pro? | Dr.fone</u></a></li>
<li><a href="https://driver-install.techidaily.com/win11s-aural-ascension-convex-audio-driver-update-required/"><u>Win11's Aural Ascension - Convex Audio Driver Update Required</u></a></li>
<li><a href="https://driver-install.techidaily.com/windows-10-update-nvidia-gtx-970-drivers/"><u>Windows 10 Update: Nvidia GTX 970 Drivers</u></a></li>
<li><a href="https://driver-install.techidaily.com/windows-hub-reconciliation-fixed/"><u>Windows Hub Reconciliation - Fixed!</u></a></li>
<li><a href="https://driver-install.techidaily.com/xbox-one-controller-drivers-for-windows-11/"><u>Xbox One Controller Drivers for Windows 11</u></a></li>
</ul></div>
