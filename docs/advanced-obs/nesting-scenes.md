# Nesting Scenes

Nesting scenes is a great hack that not a whole lot of people know about in OBS. This allows you to change one source across many different scenes with one action.

We'll go through an example of how Nested Scenes can help in a simple collaborative Scene Collection, and use Ping.gg as our source that we'll be swapping out.

## Setup

First we'll make some Scenes
 - Interview
 - Interview w/ Screen
 - Buffer (Optional, but a great way to keep your scenes organized)
 - This Weeks Guest

 ![Our Scenes](https://i.imgur.com/AAEap3t.png)

In "This Weeks Guest", all we are going to add is a Browser Source from Ping!

:::tip

Check out our Doc on Slots to see how you can leverage those and nested scenes together!

:::

Right click in the sources box and add a Browser Source, we'll be making it 1280x720 and dropping an embed link that we grabbed from our call on Ping.gg

![Adding Browser Source](https://i.imgur.com/ECkJFaa.png)

![broswer settings](https://i.imgur.com/INoGDel.png)

Now that we have this setup in our scene, we'll be able to nest this scene into others.

Adding scenes with dynamically changing sources, like our guest that rotates out every week, will prevent us from having to update multiple different scenes every time we need to bring someone new into the fold.

To add our Scene as a source, all you'll need to do is right click the sources window and add "Scene". We'll be picking "This Weeks Guest"

![adding scene](https://i.imgur.com/Cnd5lrG.png)

And now that they are added, we are able to move them around and format them any way that we want in any scene that we want!

Here is an example of a scene that have both participants split 50/50 on screen

![scene example](https://i.imgur.com/POIIKFN.png)

And here is one with both participants on screen, but also with a Desktop Capture!

![desktop example](https://i.imgur.com/Y2vjclq.png)

## In Conclusion

Nested Scenes was a hidden gem in OBS that only within the last 1-2 years started getting leveraged by broadcasters. It is a fantastic way to manage and alter multiple scenes at once!