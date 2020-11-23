---
description: Manual setup is the best approach when you run the bot on your local machine
---

# Manual Setup

{% hint style="info" %}
Before choosing an approach you need to [register the discord app!](https://discordpy.readthedocs.io/en/latest/discord.html)
{% endhint %}

### ⬇ Install Required Software:

* [GIT](https://git-scm.com) \(GUI such [GitHub Desktop](https://desktop.github.com) can be helpful\)
* [Node.JS](https://nodejs.org)

### 🗳 Clone The Repository

To clone the repository, either use the Git GUI if you have one installed or enter the following commands:

```bash
# if you don't want to contribute, just host the bot, nothing else
git clone https://github.com/ReplacementBot/ReplacementBot.git
cd ReplacementBot
```

If you want to contribute, first [fork the original repository](https://help.github.com/en/github/getting-started-with-github/fork-a-repo) and clone the **forked** repository into your local machine. If you don't do this, you will not be able to make commits or change any files.

```bash
# if you want to contribute, make changes and work on the bot
git clone https://github.com/<username>/ReplacementBot.git
cd ReplacementBot
```

### ⚙ **Install Dependencies And Build Project**

That step will setup files on your local machine that are not copied from the repository.

```bash
npm install
npm run build
```

### ✅ That's It!

You can now run bot anytime by running this command in the project directory

```bash
npm start
```

