# Using Scenes As Sources

Managing your sources across scenes is cumbersome, especially when you want to swap out something like one person across multiple scenes. Reference scenes are a _fantastic_ workaround.

Using _Nested Scenes_ is actually alot more simple than one would think on the surface. Here is an example of how a nested scene can be used as a way to manage something like your webcam, with an overlay and even alerts baked into it if you'd like.

# Setting Up Your Nested Scene

First we'll make a two new scenes. One Labeled "Main" and one labeled "Camera Nested Scene"

![Right Click in the Scenes Box to Add a Scene](https://i.imgur.com/YPI6d3a.png)

Great! Now we'll go over to "Camera Nested Scene" and add our Camera.

![Right Click in the Sources Box and Click "Video Capture Device"](https://i.imgur.com/5ydwGsz.png)

Now that we have our Camera, we need to add an Overlay.

_If you don't have an overlay, a neat trick I like to use is putting a Color Source behind the Camera, its clean, minimal, and modular to match the color of your whole channel asthetic!_

![Camera With Blue Color Source Behind It](https://i.imgur.com/NCONElX.png)

# Using Your Nested Scene

Now that we have a Scene to Nest, lets Nest it!

Our Main Scene needs everything that you plan to show for 99% of your broadcast, but for now, we'll just add a Display Capture (a great way to show everything you plan to show/play during your broadcast)

![Right Click in the Sources Box to add a Display Capture](https://i.imgur.com/Fakil29.png)

_If you'd like to see how to add things like alerts, images, videos, etc. in your scenes, stay tuned for a suplimentary doc to come out for that!_

But for now, all we're missing is our Camera, without a nested scene, we would have to add our Camera *AND* our Overlay everytime we want to use it somewhere, *BUT* with nested scenes, we can add both at the same time.

Right Click in the Sources Box and look to add "Scene"

![Scene in the Sources Menu](https://i.imgur.com/zzZcEjC.png)

!["Camera Nested Scene" in the list of available sources to add](https://i.imgur.com/DSfwR1P.png)

And after adding "Camera Nested Scene"(the Scene we just made!) You'll see the Camera and Overlay as we just set it up show in your "Main" Scene. And after some resizing, it should look something like this

![Our Complete Main Scene!](https://i.imgur.com/PX8BcMd.jpeg)

And there you have it! a Basic Intro to Nested Scenes!

Down below is an excellent tutorial and overview video by EposVox, if you'd like to see more!

<iframe width="560" height="315" src="https://www.youtube.com/embed/Sc2AiVFeDs8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; fullscreen" allowfullscreen></iframe>
