# Chatbot Integrations

Ping Ask features support for using the StreamElements Chat Bot, Nightbot and Fossabot!

## **StreamElements**

To incorporate Ping Ask with the StreamElements Chat Bot, we'll hop on over to our StreamElements [Dashboard](https://streamelements.com/dashboard), then navigate to the Chatbot Dropdown and click "Chat Commands".

![Screenshot of Dropdown](https://i.imgur.com/CDOsUE4.png)

Then we'll go to the Custom Commands Tab and click "Add New Command".

![Custom Commands Tab](https://i.imgur.com/kYj6MOS.png)

You can name this command whatever you want, we'll name this one "Ask".

In the response section you'll copy and paste this into the box.

> ${urlfetch https://ask.ping.gg/api/external/chatbots?channel=${channel}&q=${queryescape ${1:}}&user=${user}}

![Screenshot of the New Command Box with everything filled](https://i.imgur.com/fESkotn.png)

Any messages sent to this command on your channel will be added to your question queue.

:::tip

Make sure the bot is joined to your channel by checking the Bot Settings box on the front page of your Dashboard. If it says "Part Channel" then there is nothing you need to do.

:::

## **Nightbot**

To incorporate Ping Ask with Nightbot, we'll head on over to our [Dashboard](https://nightbot.tv/dashboard). Then click the "Commands" tab on the left and "Custom" in the drop down

![Screenshot of the commands dropdown](https://i.imgur.com/sUsoSmt.png)

Now we'll click "Add Command" in the top right corner

![sreenshot of the add command button](https://i.imgur.com/MR5cMeI.png)

You can name this command whatever you want, we'll name this one "Ask".

In the "Message" section you'll copy and paste this into the box.

> $(urlfetch https://ask.ping.gg/api/external/chatbots?q=$(querystring)&channel=$(channel)&user=$(user))

![nightbot box filled](https://i.imgur.com/tClIWSS.png)

Any messages sent to this command on your channel will be added to your question queue.

:::tip

Make sure that the bot is joined to your channel by clicking the "Join Channel" button in the top right corner of the main page of your dashboard. If it says "Part Channel" then you do not need to do anyhing.

:::

## **Fossabot**

to incorporate Ping Ask with Fossabot, we'll head over to the [Website](https://fossabot.com/) and log into our dashboard. Then navigte to "Commands" under Main.

![Screenshot of Command under main](https://i.imgur.com/32VbtgD.png)

Now we'll click "Create" in the top right corner.

![screenshot of create](https://i.imgur.com/nJo4G6A.png)

You can name this command whatever you want, we'll name this one "Ask".

In the response section you'll copy and paste this into the box.

> $(customapi https://ask.ping.gg/api/external/fossabot)

![Screenshot of the New Command Box with everything filled](https://i.imgur.com/UlGaWFr.png)

Any messages sent to this command on your channel will be added to your question queue.

:::tip

Make sure that Fossabot is joined to your channel by checking the "Bot Controls" box on the right side of the main page of the dashboard and clicking "Join Channel". If it says "Part Channel" then there is nothing more for you to do

:::
