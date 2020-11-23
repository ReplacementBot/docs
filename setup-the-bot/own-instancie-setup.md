---
description: >-
  If you wish to setup ReplacementBot to contribute or to host it. This guide
  will walk you thought how to do it.
---

# Own Instance Setup

## Setup the Discord Application

To run an instance of any of Discord Bots you must first create the app on [Discord Developer Portal](https://discordapp.com/developers/applications) first. 

## Chose your approach

While setting up bot you may choose a couple of approaches. There are a couple of them but, they are straightforward to choose because of how specific they are. They are, of course, not of all the options you can choose but they are recommended.

* ✅ Recommended Approach
* ☑ Possible Approach
* ❌ Not Recommended

| What do you want  to do with the bot | Manual Setup | Heroku | PM2 | Gitpod |
| :--- | :--- | :--- | :--- | :--- |
| ✨ Use it  | ☑  | ✅  | ✅  | ❌  |
| 🔍 Check it out | ❌  | ✅  | ☑  | ❌  |
| 👨💻 Contribute to it | ✅  | ❌  | ❌  | ☑  |

### ✨ I want to use the bot

If you want to use the bot it would be best it will be up 24/7. You need to put it on the hosting service or craft your own. We provide full support for **Heroku**. It isn't best service but it's extremely easy to use, and **free tier is enough** to keep the bot running. Alternatively, If you have any device that can run all day long like [Raspberry Pi](https://www.raspberrypi.org) you can use **PM2** to handle processes programs on your device easily. 

{% page-ref page="hosting-with-heroku.md" %}

### 🔍 I want to check how the bot is working

If you want to quickly check if ReplacementBot is something that you are looking for you can use **Heroku**, it will handle all the technical stuff and will be the fastest approach.\

{% page-ref page="hosting-with-heroku.md" %}

{% page-ref page="hosting-with-pm2.md" %}

### 👨💻 I want to contribute to the bot

That's great ❤ReplacementBot is Open-Source project hosted on [GitHub](https://github.com/ReplacementBot?type=source). You will probably be interested in the **Manal Setup** on your machine or, you can the cloud development platform - **Gitpod**.

{% page-ref page="manual-setup.md" %}

{% page-ref page="cloud-development-with-gitpod.md" %}

