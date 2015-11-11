# Photoshop: Tips & Tricks & Magic Tools
by [Lena Groeger](https://twitter.com/lenagroeger) & [Chris Canipe](https://twitter.com/ccanipe)

In this session, we'll learn:

1. How to automate tasks using [**Actions**](https://github.com/lenagroeger/photoshop#actions)
2. How to create [**Droplets**](https://github.com/lenagroeger/photoshop#droplets) for Actions you use regularly
3. How to make [**Animated Gifs**](https://github.com/lenagroeger/photoshop#animated-gif-simple-2-photo-animation) (including [multi-photo](https://github.com/lenagroeger/photoshop#animated-gif-multiple-photo-animation) and [video](https://github.com/lenagroeger/photoshop#animated-gif-video-animation) versions).
4. How to use [**Magical Tools**](https://github.com/lenagroeger/photoshop#more-magic-in-photoshop-perspective-crop-and-content-aware-fill) like perspective crop and content-aware fill




##Actions##
Do you find yourself repeating many of the same tasks again and again? You're working too hard. Make an action! In this example, we'll set up an action that converts a bunch of large files (of Oscar-nominated movie poster images) into a smaller size of 200px wide and 72px/in resolution.

1. [Download this folder of images](https://github.com/lenagroeger/photoshop/blob/master/zipped/OSCARS.zip?raw=true). Open an image in the Best Picture folder: **File > Open...**
<br>
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/poster1.jpg)

2. Open the Actions pallette: **Window > Actions**   ![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/poster2.jpg)

3. From the dropdown, select **New Action...** (Alternatively, click on the little icon that looks like a Post-It note to create a new action)  ![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/poster3.jpg)
4. Give it a name. Let's say "200px wide", and click "Record" ![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/poster4.jpg)

5. Select **Image > Image Size...**
<br> ![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/poster5.jpg)
6. Set the resolution to 72px and the width to 200px.
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/poster6.jpg)

7. Still recording, go to File > Save As, and save to new folder (I've called it Best Picture New). You can also do File > Save for Web.

![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/poster8.jpg)
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/poster7.jpg)

7. At the bottom of the Actions window, hit "Stop" to stop recording.
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/congress10.jpg)

8. Close the image without saving your changes.

9. To run your script, open **File > Automate > Batch...**
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/poster9.jpg)

10. First we need to pick which action to apply. Since we want to use the 200px action we just created, under "Play" make sure the Action "200px" is selected.
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/poster10.jpg)
11. Now we need to choose which folder of images we want to apply this action to, and where we want our new images to be saved. Choose your Source folder
(Best Picture) and Destination folder (Best Picture New).
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/poster11.jpg)

12. Finally, make sure the "Override Action 'Save As' Command" is checked. This will make sure each file gets saved as it's own filename (and not all filed get saved as GRANDBUDAPEST.jpg)
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/poster13.jpg)

13. Hit "OK", sit back and relax. Your photos will be ready momentarily. When the flickering Photoshop images settle, you should end up with your "Best Picture New" folder full of smaller sized images!
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/poster12.jpg)

14. *NOTE* If you end up with an image full of empty folders or are seeing a "Save Image As" popup box when you try to apply the action, you may have missed the "Save As" step. [This might help.](http://graphicdesign.stackexchange.com/questions/6842/automatically-saving-in-a-batch-action)


##Droplets##
Droplets make Actions even simpler to use by making them executuable with a simple Drag and Drop.

1. Select **File > Automate > Create Droplet...**
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/poster13b.jpg)

2. The Droplet menu is much like the Batch menu. Select a location for the Droplet icon to appear, and a folder in which you'd like your files to save (I just saved my droplet to the Desktop, and picked the same Destination folder, Best Picture New.)

![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/poster14.jpg)

3. You should end up with a little icon like this on your Desktop. (Older versions of Photoshop used to have an actual droplet icon, no idea why they replaced it with an arrow.)

![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/poster14b.jpg)

3. Now, instead of going the all the trouble of selecting Batch from the Automate menu, just drag your Best Picture folder on top of the droplet icon. That's it! You're done!
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/poster15.jpg)


##Droplets 2##
Now let's apply our droplet-making skills to solve a real-life problem that you may encounter if you cover politics. I want every single member of congress's photo, but not in color – in black and white. There are 879 photos, so manually opening up each photo in Photoshop is out of the question. What to do?

1. First, we need all the images. [Download them here](https://github.com/lenagroeger/photoshop/blob/master/zipped/Congress%20Photos.zip?raw=true), then open up the "Congress Photos" folder (note, this only includes the first 20 photos, if you really want all 879 [get them here](https://github.com/unitedstates/images/tree/gh-pages/congress)).
   ![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/congress1.jpg)

2. Now, open one up in Photoshop.

   ![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/congress2.jpg)

3. Create a new action, I'm calling mine B&W. Click Record.
  ![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/congress4.jpg)

4. Go to Image > Mode > Grayscale, and click OK. You should now have a black and white photo!
   ![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/congress6.jpg)

6. Just for fun, let's add one more step to make the photo sepia colored. Go to Image > Mode > Duotone, and select "Duotone" from the Dropdown.
    ![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/congress7.jpg)

7. Click on the white box and select a new color (I am choosing Orange)
   ![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/congress8.jpg)

8. You might need to give this new color a name, but when you hit OK it should have given your photo a nice sepia effect!
   ![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/congress9.jpg)

9. Now let's save it. File > Save for Web, and save it to a new folder (I called it Congress Photos New)

10. Stop recording this action by hitting the "Stop" button

   ![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/congress10.jpg)

11. Now let's go straight to making a droplet. **File > Automate > Create Droplet...**

12. I'll save this droplet as "B&W" to the Desktop, and select "Congress Photos New" as my destination folder.
   ![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/congress11.jpg)

13. Now I'll drag my Congress Photos folder onto the droplet, and wait for my computer to do all the work! You should end up with a bunch of newly sepia-fied images. Hurray!



##Animated Gif: Simple 2-Photo Animation ##
Do you have an interactive graphic you'd like to promote on the front page? Animated Gifs are a great way to draw attention to interactive work.

1. We're going to use these two delightful before-after photos, which you can download here: [Image 1](https://raw.githubusercontent.com/lenagroeger/photoshop/master/zipped/taxidermy1.jpeg) and [Image 2](https://raw.githubusercontent.com/lenagroeger/photoshop/master/zipped/taxidermy2.jpeg)
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/taxidermyB&A.jpg)
<br>[Full back story](http://www.nydailynews.com/life-style/real-estate/brokers-digital-trickery-sell-drab-apartments-article-1.1885998), and [a related something you should read on the trip home from IRE](http://www.susanorlean.com/articles/lifelike.html).

2. Open up Photoshop, and go to Window > Timeline.
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/photogif1.jpg)

3. You should now see a bottom bar with a tab called Timeline.
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/photogif2.jpg)

4. Open up both photos in Photoshop and copy and paste them into the same file (Or just drag and drop them in). You should end up with each photo on its own layer.
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/photogif3.jpg)

5. Click on "Create Frame Animation."
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/photogif4.jpg)



6. You should see a little box with a photo, we'll refer to that as a single "frame."<br>
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/photogif3b.jpg)

7. Go ahead and set the duration for .5 seconds.<br>
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/photogif6.jpg)

8. And then set the looping to FOREVER (I mean, go big or go home).<br>
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/photogif7.jpg)

9. Now we need to make a second frame with the other photo. You can do this two ways. We'll do the manual way first. Click on the new page button.<br>
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/photogif3c.jpg)


10. You should see a new frame appear.<br>
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/photogif7b.jpg)

11. Now we have a new frame, but they both look the same! So with the second frame selected, go over to your layers and click on the eye icon to toggle one layer off and reveal the second photo.<br>
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/photogif7c.jpg)<br>

12. The animation frames reflect the current state of your layers, so we've just set the second frame to show the second photo. If you look closely you should see that the frame indeed looks different (it's full of taxidermy).<br>
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/photogif7d.jpg)

13. If you have more than 2 or 3 layers and need to make them all frames, a shortcut is to go to the Timeline dropdown and select "Make Frames from Layers"
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/photogif7e.jpg)

14. Go to File > Save for Web.
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/photogif8.jpg)

15. Save it as a gif!
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/photogif9.jpg)

16. Now, open up that gif in a browser. You should see a spectacular transformation of dead animals.
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/taxidermyFinal.gif)

17. Now, contemplate all the much more useful combinations of photos you can now make into gifs.



##Animated Gif: Multiple Photo Animation ##

1. Let's say you want to do more than animate between 2 photos, you want to show a progression of many photos, like [this example from the Wall Street Journal.](http://graphics.wsj.com/ukraine-rebel-maps/)
2. Let's try it! [Download this folder](https://github.com/lenagroeger/photoshop/blob/master/zipped/Ukraine.zip?raw=true) and open one of the images from the Ukraine folder in Photoshop.
3. Drag and drop your other images onto the stage. This will bring them into your file as separate layers.<br>
  ![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/GifLayers.png)<br>

4. Like we did before, select **Window > Timeline** from the toolbar to open up a new panel in Photoshop.
5. From the Timeline panel, click on "Create Frame Animation".
7. From the dropdown in the upper right of the Timeline window, select "Make Frames from Layers"
 ![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/FramesFromLayers.png)

8. Make sure your frames are in the correct sequence, then set the duration for which you'd like each to display.<br>
  ![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/SetFrameDurations.png)

9. Select **File > Save for Web**
10. Select Gif as your save format. At the bottom of the window, you'll also be able to set the number of times you'd like the animation to loop. For a homepage promo, it might not be appropriate to loop infinitely, but we'll pick "Forever" for now.
  ![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/ukraine.gif)

11. Save and you're done. Woot!



##Animated Gif: Video Animation ##


1. Sometimes you want to convert a short segment of a video to a gif, whether that's a YouTube clip or a screen recording. You can do this easily with QuickTime + Photoshop. Let's try it out on  [this Guardian interactive on measles](http://www.theguardian.com/society/ng-interactive/2015/feb/05/-sp-watch-how-measles-outbreak-spreads-when-kids-get-vaccinated).</a>

2. Open up QuickTime, and select "New Screen Recording."
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/screengif1.jpg)

3. A little popup box will appear, click on the Red Record button to start recording.
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/screengif2.jpg)

4. But that doesn't actually start the recording, you have to select a viewport for your recording. Go ahead and do that. Then click "Start Recording."
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/screengif3.jpg)

5. After some seconds, hit the very difficult to find "Stop" button at the top of your screen.<br>
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/screengif4.jpg)

6. Now save that movie recording to your Desktop.<br>
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/screengif3b.jpg)

7. Open up Photoshop, select Import > Video Frames to Layers.
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/screengif5.jpg)

8. You'll get a little slider where you can select precisely the seconds of video you want for your gif (smaller is better for loading times).
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/screengif6.jpg)

9. You should end up with this:<br>
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/screengif7.jpg)

10. See all those layers? Those are all the frames of your little gif!<br>
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/screengif8.jpg)

11. Ok, let's save this thing. Go to File > Save for Web<br>
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/screengif9.jpg)

12. Make sure you have "Gif" as the format type, and that Looping Options are set to Forever. Save it!<br>
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/screengif10.jpg)

13. Now, open up that gif in a browser. Happy giffing!<br>
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/measles2.gif)



##More Magic in Photoshop: Perspective Crop and Content Aware Fill ##


1. [Download this photo](https://raw.githubusercontent.com/lenagroeger/photoshop/master/zipped/warpeace.jpg), and then open it up in Photoshop.
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/warpeace.jpg)

2. Using the crop perspective tool this time, draw a selection on the four corners of the book cover.
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/perspectivetool.jpg)
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/perspectivecropping.jpg)
Crazy, right??
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/covercorrect.jpg)

3. Now, rotate the canvas 90&#8451; clockwise. Go to Image > Image Rotation > 90&#8451; CW
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/90cw.jpg)
4. Good, now it's right side up. Now, say we want to get rid of the "and" in War and Peace (scandalous, I know). Select the "and" with the selection tool so it looks like this.
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/selectand.jpg)
5. Go to Edit > Fill, and do a Content-Aware fill.
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/noand.jpg)
6. MIND BLOWN
7. Contemplate all the other uses of the perspective crop tool and content-aware fill tool.


