# COSMIC WATCH
## A Detailed review of cosmic watch app
* For those who have religiously clapped for every space-shuttle lift-off and who ran to balcony to spot jupiter chasing mars, then
I am sure that cosmic watch is a real treat for them.
* **The Cosmic Watch is an interactive 3D tool.**
* It's a realtime worldclock, *time travel machine, astrolab, antikythera mechanism, 
armillary sphere, astral-chart generator.*
> A perfect introduction to basic astronomy. 
> But in my point of view it doesnot give any other information about asteroids,comet,galaxies,blackholes,nebula and so on.
> But it will be more interesting if you are a newbie.
![alt text](http://cosmic-watch.com/wp-content/uploads/2015/05/cosmic_watch_tutorial_11-960x600.jpg)

### ABOUT THE APPLICATION:
#### Permissions needed:
> * The app requests permission to access the users location and its starts everytime only from the users location.
> * The link to how do android apps access the users location is:
  > - https://developer.android.com/guide/topics/location/index.html#location
  > - http://blog.teamtreehouse.com/beginners-guide-location-android

##### ASSUMED LAYOUT USAGE:
**linear layout**
>Since there is no horizontal orientation in relative layout
 > - https://stackoverflow.com/questions/20458542/how-to-set-androidorientation-horizontal-programmatically-in-relativelayout

###### NOTED FEATURES IN THE APP:
* >There are several modes like Clock Mode,the Astrology Mode, Astronomy Mode and the Solar System mode.
* >There is also a search bar inorder to search for the locations
* >It also contains star feature which can be used to save upto three favorite locations.
* >An anchor option to switch between views
* >The bottom of the app contains a clock by which you can rewind and fast forward time, and this allows you to see the different          positions planets will be in, as well as sunset and sunrise times, and constellations.

###### HOW IT CAN BE ACHIEVED:
**Basically the cosmic watch works on an algorithm called Astronomical Algorithms of *Jean Meeus*.**
 >This algorithms have an astonishing precision which should be accurate enough for the next thousand years.
   > - Github link:https://github.com/soniakeys/meeus
* **How to built API for space apps:**
>Refer these sites to grasp knowledge about space API:
 > - https://api.nasa.gov/api.html
 > - https://www.programmableweb.com/category/solar/api
 > - http://apievangelist.com/
* **How to achieve 3D UI:**
  * The 3D UI can be achieved by using openGL ES
  * If you wanted to hand-code it, you would just create a GLSurfaceView, and draw objects into it.
  * But, you would never hand-code it in real life. To make even a simple 3D game, you would want to use a game engine like Unity3D or       jPCT-AE.
    - https://www.codeproject.com/Articles/825700/Beginners-Guide-to-Android-Animation-Graphics
    - https://developer.android.com/training/graphics/opengl/index.html
    - http://www.jpct.net/jpct-ae/





