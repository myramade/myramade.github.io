# Lab 3 - App-based VR 
Level of Difficulty: Normal

## About
In this lab, we will design a navtive VR experiencing using 360 images and video with gaze-activated content. Native VR is equipment dependent, in the case of this prototype, it will be a mobile app that will be built using a web interface and publish as to an app. We will be using [Warp Studio's VR Creator](https://warp.studio/). 

## Design 
In Warp Studio you will create a *Scenario* and within your *Scenario* you will create a number of *Scenes*. Our design will have four (4) scenes, use your [VR_FOV_Template](VR_FOV_Template](https://www.dropbox.com/s/ekhp9eue6gendp2/VR_FOV_Template.pdf?dl=0)) to storyboard the VR experience you will create:
* Homeworld 
* Scene 2
* Scene 3
* Scene 4

## Assets
For this lab you will need to three to five VR Assets, we will use a combination of 360 images and video. Download the assets you will use from one of the following locations:
1. [Myra's 360 Asset Folders](https://github.com/myramade/myramade.github.io/tree/master/vr/assets)
2. [Google Images](https://www.google.com/search?q=equirectangular&tbm=isch&tbs=isz:l&cad=h)
3. [Flickr](https://www.flickr.com/groups/equirectangular/)
4. [Photopin](http://photopin.com/free-photos/equirectangular)

You will need to either download the 360 images/videos(write the image/video name in your VR storyboard) Now you're read move onto the *Build* phase

# Build
1. Go to https://warp.studio/ and sign up for a *Free* account. You will need to verify your account before you can use it by clicking on the link in the verification email you receive from Warp. 

*Note: The Warp Studio interface is similar to the [Twine](http://twinery.org) user interface.* 

2. Begin by adding all the images and videos you will use in your scenario, select **Media** at the top of the screen. Select **Add Media** and then in the *Add media* page, drag and drop you media assets or use the *browse* option to search the files you wish to upload. 

3. Now we will create our *Scenario*, select **Scenarios** at the top of the screen, then click **Add scenario**. On the *Add scenario* page, enter your scenario title, a description for your scenario, and select a launchpage image and then click *Save*. 

![warp-scenario](https://user-images.githubusercontent.com/28787937/41213938-3f5d5d3e-6cfd-11e8-8a59-8f576c6c5376.png)

4. Next, we'll add *Scenes*. Scene cards are created on the default *flow* screen. At first look the user interface doesn't appear intuitive, but adding a scene is super easy just double-click anywhere on the workspace. An *Add scene* menu displays. Select the *Scene* type you would like to create. For this project, we will select *Information* for our first scene. 

You have a choice of 5 scene types:
  * [Information](http://help.warp.studio/creating-scenarios/different-scene-types/add-an-information-scene) - An Information scene is a scene with only one interactive element, which is a question in combination with a button. Both question and button are required. Use this scene when you want to inform your trainee about something. 
    
  * [Multiple Choice](http://help.warp.studio/creating-scenarios/different-scene-types/add-a-multiple-choice-scene) - A multiple choice scene consists of a question and at least two answers. Use this scene to ask your trainee a question. Each answer can link to a specific scene. Both question and answers represent one element which can be positioned in the scene.
    
  * [Direction](http://help.warp.studio/creating-scenarios/different-scene-types/add-a-direction-scene) - A Direction scene consists of an optional question and one or more arrows. Use this scene to guide your trainees to a certain location. Each arrow can link to a specific scene. The question and arrows are elements which can be positioned separately. Arrows can only be positioned along the bottom of the video.
    
  * [Auto transition](http://help.warp.studio/creating-scenarios/different-scene-types/add-an-auto-transition-scene) - An Auto transition scene is the most simple scene of all. In this scene type there are no interactive elements. Only after a clip of 360˚ video is fully played the trainee will be guided to a new scene.
    
  * Hotspot - A hotspot is used to navigate through the VR exprience by simply gazing at an item. 


Note: You can zoom you workspace view in and out. The more scenes you add the more you'll find yourself dragging scenes around. This is where storyboarding and naming conventions coming handy. 

5. Enter the details for your scene including title, description, a question and an answer. The answer works like button and is displayed to the user. This is not an actual question and answer. Once you enter the details, click *Save*.

![warp-scene1](https://user-images.githubusercontent.com/28787937/41213957-60bba54e-6cfd-11e8-9d9e-5ddb312829cf.png)

6. To create and link a new scene to your first scene, click on the *A* and drag your mouse across the workspace, a connector will appear, when you release your mouse the *Add scene* menu displays. Follow Steps 4 & 5 to add additional scenes based on the storyboard you created. Explore using the different scene types. 

![linking](https://downloads.intercomcdn.com/i/o/34261921/eb82fc8673d1b767a3911d5a/flow-linking-new.gif)

Note: You can also create a new scene by double-clicking on the workspace. To link unlinked scenes click on the *A* that appears on the scene you want link and then click and drag you mouse to the connected scene and release your mouse. A connector all display linking the two scenes. 

![linkingtwoscenes](https://downloads.intercomcdn.com/i/o/34261224/b83777e719e6a2bf84cc7212/flow-linking.gif)

7. You will need to decid how to end the exprience. Each scenario must have at least one ending, but can have multiple. Although all endings are the same, it doesn't matter for the scenario itself how much endings you add to your flow diagram. You could add more than one to get a better organised flow diagram. Endings are added in the same way you create a new scene. 

8. Now, let's add media assets to our *Scenes*. Media is added on the *Scene* page, select the *Scenes* link. On the *Scenes* page scroll down to the bottom of the page. You can only add 360 video to your scenes, click the **Select 360 media** button and then select the video that you want to use for the scene.  

Since you've already uploaded the video, it should render on screen pretty fast. It will appear as a flat image. You can now click and drag the menu icons that were created based on the type of scene you selected. You can also adjust when the menu icons appear and the starting point of your video loop. 

<img width="1168" alt="warp-select-media" src="https://user-images.githubusercontent.com/28787937/41270540-b4c10b48-6dc0-11e8-894f-2532197bc985.png">


*Note: you can not add more than one video to a scene and you cannot resize the menu icons. *

9. Repeat step 8 for the rest of your scenes. 

*Note: You can use Warp Studio to design first and decide what videos need to be captured after the fact.  On the *Scenes* page, scroll down and select *Filming*. On the *Filming* page you can descript the location of the scene that should be captured. You can then export by clicking on the additional menu (...) and select *Export Scenario*, this will create a pdf with all your scenarios i you select to export them all. 

## Test
Review the scenes in your scenario and make sure they follow the flow of your planned design You can test your design flow before publishing.  Click *Test* on the top right of the page and run through the scenario.  Your 360 videos will not display when testing here. You will only be able to view the branching. 
<img width="890" alt="warp-test" src="https://user-images.githubusercontent.com/28787937/41270626-1eaedfd0-6dc1-11e8-9690-7754afe4da7b.png">

## Publish
Before you publish your scenario, you will need to add the names of trainees that you want to have access to the VR exprience. Click **Trainees** at the top of the screen, then click **Add user**. Enter the required user information. *Note: users will need to donlwoad the Warp VR app to their devices to access the VR experience*

<img width="883" alt="warp-addusers" src="https://user-images.githubusercontent.com/28787937/41270567-d23640f8-6dc0-11e8-973a-9a7c23d41a9a.png">

Once all your trainees are added. Go back to **Scenes** and select **Publish**. Run through the required checks to publish you Scenario, including adding the trainees who will have access to the VR experience. Your VR scenario will be pushed to the Warp App to the trainees you selected.  

Warp provides you with usage reports that displays the user's interaction with the VR scenario. Below is a sample report: 
![activity](https://user-images.githubusercontent.com/28787937/41270488-6e3d61f8-6dc0-11e8-9ff3-26741af9d069.png)

## Sample
**Coming Soon!**

## Home

[Back to main page](https://github.com/myramade/myramade.github.io/blob/master/index.md)
