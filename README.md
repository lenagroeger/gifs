# Data Gifs!!
by [Lena Groeger](https://twitter.com/lenagroeger)


This tutorial will teach you how to:

1. Make a [multiple-photo or series gif](https://github.com/lenagroeger/gifs#animated-gif-multiple-photo-animation) in Photoshop.
2. Make a [video or screensharing gif](https://github.com/lenagroeger/gifs#animated-gif-video-animation) using Photoshop & Quicktime.
3. Make a gif [from the command line](https://github.com/lenagroeger/gifs#animated-gif-command-line)

##Animated Gif: Multiple Photo Animation ##

1. Let's say you want to do more than animate between 2 photos, you want to show a progression of many photos, like [this example from the Wall Street Journal.](http://graphics.wsj.com/ukraine-rebel-maps/)
2. Let's try it! [Download this folder](https://github.com/lenagroeger/photoshop/blob/master/zipped/Ukraine.zip?raw=true) and open one of the images from the Ukraine folder in Photoshop.
3. Drag and drop your other images onto the stage. This will bring them into your file as separate layers.<br>
  ![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/GifLayers.png)<br>

4. Select **Window > Timeline** from the toolbar to open up a new panel in Photoshop.
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


##Animated Gif: Command Line ##

1. We can also use [ImageMagick](https://www.imagemagick.org/script/index.php) to create gifs from a folder of images right on the command line.
![](https://github.com/lenagroeger/photoshop/blob/master/screengrabs/imagemagick.gif)

2. First [install ImageMagick](https://www.imagemagick.org/script/download.php). I use `brew install ImageMagick`, but take your pick.

3. Then you can start using their [command line tools](https://www.imagemagick.org/script/command-line-processing.php).



