---
sidebar_position: 1
slug: /
---

# Getting Started

Ping.gg is the best way to make collab video. Live on Twitch, recorded for Youtube, produced for television, and everything in between.

If you prefer videos, Theo and Adam filmed one below to help you get started quick! Otherwise you can follow along below

<div style={{ width: "100%", display: "flex", justifyContent: "center" }}><iframe width="815  " height="480" src="https://www.youtube.com/embed/rbVQNdYHmEs" title="Ping.gg Tutorial" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>

## Streaming Software Setup

Ping is compatible with _any video software that can treat a website URL as a "source"_ (i.e. a [_browser source_](https://obsproject.com/eu/kb/browser-source)). This includes:

- [OBS Studio (Open Broadcaster Software Studio)](https://obsproject.com/)
- [Streamlabs Desktop](https://streamlabs.com/)
- [XSplit](https://www.xsplit.com/)
- [Twitch Studio](https://www.twitch.tv/broadcast/studio)

While all of these solutions work, we **highly recommend that you use [OBS](https://obsproject.com/)**.

## Browser Sources

:::tip

We highly recommend using **[nested scenes for your Ping browser sources](/advanced-obs/scene-as-source)**
:::

To get Ping into OBS, first create a [Browser Source](https://obsproject.com/eu/kb/browser-source) (+ button in "sources" -> "Browser").

Once you have the browser source customizer window open, you have to change **THREE THINGS**.

### 1. Add the Embed URL

The URL used here is an embed URL from your Ping room. These URLs are static and don't need to be changed after a call ends

![url in browser source](./img/browser-sources/browser-source-1.png)

### 2. Change the resolution to 1920x1080

Even if your guest is using a different resolution, we recommend using 1920 width and 1080 height here to guarantee the simplest scaling and resizing at a 16:9 aspect ration

![resolution in browser source](./img/browser-sources/browser-source-2.png)

### 3. Enable audio control in OBS

In order to have control of the audio from your browser source, you _**have to enable this checkbox**_

![audio controls in browser source](./img/browser-sources/browser-source-3.png)

:::warning

Everything from here down is _very_ unfinished
:::

## Ping.gg Room Setup

### Create your room

- What is a room slug
- "URL you share"

### Invite a guest

- How guests join
  - Permissions (member vs guest)

### Add them to a slot

- Slot info

## Now Go Live!

That's it! If this was helpful in getting started, please [shout us out on Twitter](https://twitter.com/pingdotgg) - also don't hesitate to [join our Discord](https://discord.gg/pinglabs) if you have any questions or want to chat with us.
