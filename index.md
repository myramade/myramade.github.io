
# MyraMade VR MakerLab

## Table of Content
- [About](#about)
- [VR Terminology](#vr-terminology)
- [Assets](#assets)
- [Labs](#labs)
- [Resources](#resources)
- [Contact](#contact)


## About
**Description**: This **MakerLab** consists of four individual labs that increase in complexity. **Lab 1** gets you building simple VR experience in under 5 minutes, from there we move on to **Lab 2** building a **WebVR** experience, then you move onto **Lab 3** building a **Navtive VR** experinece. Each lab makes use of a different VR creator tool, however, there is *NO* coding experience required, finally in **Lab 4** building a WebVR ona platform that offers some great analytics and again, no coding required. 

**Audience**: Learning Experience Designers, Instructional Designers, Instructional Design Developers, Learning Scientist

**Required Skills**: To complete these labs you must be have some basic computer skills and be able to download, upload, copy, and paste files from/to a web browser. For Labs 2 & 3, you should be able to have some basic storyboarding skills, however, be warned - storyoarding for VR is NOT like storyboarding for video or elearning. 

**Goal**: The goal of this lab is to build the required knowledge to design a virtual reality (VR) experience for learning

![sanberg-vr](https://user-images.githubusercontent.com/28787937/41195931-5014b11c-6beb-11e8-98a0-87b7cd38b664.gif)

## VR Terminology
There are a few terms you need to add to your vocabulary when it comes to VR. Visit the [VR Glossary](http://www.vrglossary.org/)for more indepth terminology

Terminology | Definition
------------|-----------------
Agency | this is the act of interacting with objects in a virtual space such as moving an item or causing change
Gaze Activated Content | this is one way of selecting items in a VR space, the user uses two crosshairs in the VR space to select items by looking at the item and ensuring the crosshairs are on the item and then holding their gaze on the item for a few seconds
Field of View | an important design aspect of VR, Field of View (FOV) is the user's visual span while rotaing their heads from one position to another
Homeworld | this is the first scene in your VR scnenario, it's your VR landing page. 
Head mounted display | this is the headset that is doned by the VR user it can be stand-alone such as a Google Cardboard that uses a smartphone and the new Occulus Go where the VR experience lives in the device itself or tethered such as an Occulus Rift or HTC Vive which must be connected to a computer to work deliver the VR experience
WebVR | a VR experience that is delivered via the web (internet). It's tool and device agnostic.  
CAVE | is an acronym for *cave automatic virtual environment* it's an enviroment made up ofr three to six walls that form a cube that uses projectors to display a virtual world on the walls and is controlled by the movement of the users within the CAVE
Presence | this is an important concept in VR. presence is achieved when the users is completely immersed in the virual world ignoring and many times unaware of what's going on int he physical world
Cinematic VR | a VR experience that uses 360 video and images instead of 3D graphics
Data Glove | this is an interactive device that connects to a computer, the users uses it to manipulate items in the VR world
Haptic | you've experienced haptics on your smartphone when you first purchased it and dialed numbers of sent a text message, its the sensation of touch and pressure on keys, this technology is also used in the VR space to support Agency.
Stitching | This is a the process used to combine all parts of the footage from a 360 camera to create one complete image or vidieo file in post-production. 
Eqirectangular | This is a mouthful to pronounce. When you shoot your video or record your 360 video, the source files will appear flat (think of map images we've all seen). In most cases you will need to run your captured video or image through a special media metadata injector (Youtube has some free for [mac](https://github.com/google/spatial-media/releases/tag/v2.0) or [Windows](https://github.com/google/spatial-media/releases/tag/v2.0)).  Some cameras will convert your file for you without the need to use 3rd-party software. 
Monoscopic 360 video | If you have a 360 camera, this is most likely the standard type of video your camera will shoot. Monoscopic 360 video/images have no depth information - creating a Flat World (guess those flat world conspiracy theorist were right) Because you are recording video with one 360 camera from a single point of view, making your videos much easier and cost-effective to shoot and edit. When you record a 360 image or video, using a 360 camera there is some **stitching** that happens post-production in order to create one image. The stitching either happens automatically in within your camera's software or you may have to manually stitch your image using software like Video [Stitch Studio](https://www.orah.co/software/videostitch-studio/)or [EasyPano](https://www.easypano.com/) or [Kolor Pano](http://www.kolor.com/360-videos/). Need an analogy? Think of all the audio you've recorded and edited in some tool like Audacity. When you have mono audio you end up with one track that is easy to edit)
Stereoscopic 360 Video | Also known as stereoscopic 3D in VR. Most high-end 360 cameras (the types with multiple cameras integrated) will allow you to shoot stereoscopic 360 videos. In this case, the videos are recorded side-by-side with separate recordings mapped to each eye which offsets the imagery recorded giving the user a feeling of 3D (think 3D movies you've watched in the movie theater). Unlike monoscopic, stereoscopic has depth information and spacial awareness of the 360 environment. This is where **Field of View** considerations come in. (Need an analogy? Back to our audio analogy! When you have stereo audio you end up with two tracks that can be edited individually or together, but when rendered you get one audio file)
Stereoscopic layout | This is important when building a 360 VR experience using some industry software. Stereoscopi layout refers to the image positioning of your 360 video. Since recordings are mapped for each eye, this means that we end up with two separate recordings that are either stached on on top of the other (Top/Bottom) or side-by-side (Left/Right). Some software will ask you about the layout of your stereoscopic recording - some support only one format: Top/Bottom or Left/Right and others will support both and you must indicate the layout in order to ensure the camera settings in the software. 


## Assets
In order to create our VR experiences, you will need to assets that you can use to create your experience. I have created a number of assets that you can use to create your experience.  You can find additional assets at one of the following websites:
1. [Myra's 360 Asset Folders](https://github.com/mirarol/mirarol.github.io/tree/master/vr/assets)
2. [Google Images](https://www.google.com/search?q=equirectangular&tbm=isch&tbs=isz:l&cad=h)
3. [Flickr](https://www.flickr.com/groups/equirectangular/)
4. [Photopin](http://photopin.com/free-photos/equirectangular)

You can also checkout a video of my first VR creation [3D VR Team Game Activity] (Demofest_Submission_MyraRoldan_GPStrategies.mp4)

## Labs

[Lab 1: VR Viewer](https://github.com/mirarol/mirarol.github.io/blob/master/vr/lab1.md)

[Lab 2: WebVR](https://github.com/mirarol/mirarol.github.io/blob/master/vr/lab2.md)

[LAB 3: App-based VR](https://github.com/mirarol/mirarol.github.io/blob/master/vr/lab3.md)

[LAB 4: WebVR App-based](https://github.com/myramade/myramade.github.io/blob/master/vr/lab4.md)

## Resources
These labs are part of a workshop that I faciliate. In this repo, I will not go over how to capture 360 images and video. However, there are several resource you can find by a simple Google search. However, here are some reference materials and equipment I recommend:

**Storyboarding for IDs**

* [Myra's FOV Storyboard](https://www.dropbox.com/s/hdntgapiifgbl2f/FOV-Guide-1.pdf?dl=0)

**Reference eBook & Websites**

* [The 360 Video Handbook](https://www.dropbox.com/s/hupwexizck8n95b/The360%C3%82%C2%B0VideoHandbook.pdf?dl=0)

* [Freedom360](https://freedom360.us/tutorials/)

**Equipment**

* Ricoh Theta 360 Camera - there are two great versions the lower cost [SC](https://www.amazon.com/Ricoh-Theta-SC-camera-Sand/dp/B01MA0XP2K/ref=sr_1_1_sspa?ie=UTF8&qid=1528579282&sr=8-1-spons&keywords=ricoh+theta+sc&psc=1) and its higher end cousin, the [V](https://www.amazon.com/Ricoh-Theta-360-Spherical-Camera/dp/B074W5BKYS/ref=sr_1_2_sspa?ie=UTF8&qid=1528579282&sr=8-2-spons&keywords=ricoh+theta+sc&psc=1)
* [Tripod - SMATree selfie stick with tripod](https://www.amazon.com/Smatree-Q3-Telescoping-Session-Cameras/dp/B00XN1P9QI/ref=sr_1_1?ie=UTF8&qid=1528579527&sr=8-1&keywords=smatree+q3+telescoping+selfie+stick+with+tripod+stand+for+gopro+hero)
* [Ricoh Theta phone app](https://theta360.com/en/about/application/)

## Contact
Want to bring me to your org for a VR Maker Lab? Connect with me on [LinkedIn](https://www.linkedin.com/in/myraroldan/) & send me a message. 
![17f8b46e-c02f-4d39-9193-d3c1fcedaaa2](https://user-images.githubusercontent.com/28787937/41196329-11a3ce5c-6bf2-11e8-9b53-f7c7e0846266.GIF)
