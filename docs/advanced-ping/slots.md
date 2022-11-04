# Slots

Slots allow you to set up your browser sources in OBS once, and be able to how swap who is in them directly from Ping. This feature is great for those who leverage nested scenes, have different guests on your broadcast, or run a show where you need to move guests around mid-broadcast.

## Setup in Ping

To get started, lets make our first Embed in the Embeds Window on the right-hand side of your call

![Embed Panel](https://i.imgur.com/qm6sFtT.png)

We'll go ahead and name this Embed like something like *"Guest"*, this will be our Embed slot that we use to rotate a new guest into our show every week.

![Embed Configuration](https://i.imgur.com/hdqPlXs.png)

Now when we have our guest join our call on Ping, we'll click on the Embed Menu icon on their video and add them to Guest.

![Embed Menu Icon](https://i.imgur.com/onfmakv.png)

:::tip

If there is already a guest in this slot, you can also click the swap button to swap them out!

:::

Great! Lets go ahead and take a look in OBS

## OBS

We are going to leverage Nested Scenes here to be able to minimize our embeds while dynamically having ourselves and guests placed differently across different scenes

:::tip

We have a full Doc on how Nesting Scenes work, check it out [here!](https://docs.ping.gg/advanced-obs/nesting-scenes)

:::

First lets make a scene and name it something like "This Week's Guest", and add a Browser Source to it.

![Adding Browser Source](https://i.imgur.com/ECkJFaa.png)

In Ping, we'll grab the Browser Source link from our embed panel by clicking the options cog on our "Guest" embed.

![guest embed](https://i.imgur.com/1tBMI0D.png)

We'll add the link to our Slot Embed to the source, and make it 1280x720 aswell.

![broswer settings](https://i.imgur.com/INoGDel.png)

From here, we'll be adding a Scene as a source instead of a Browser Source to wherever we need our guest to be!

![adding scene](https://i.imgur.com/Cnd5lrG.png)

You'll be adding "This Weeks Guest" where you need them to be, just like you would if it was a Browser Source or Video Capture Device.

![scene example](https://i.imgur.com/POIIKFN.png)

## In Conclusion

Slots is a way for you to be able to dynamically change your broadcast when using Ping without needing to manually edit browser sources. On the fly, easy snapping, and updates quickly!
