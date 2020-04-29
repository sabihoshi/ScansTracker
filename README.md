# ScansTracker

A tool for tracking your scanlation progress.

![preview](https://chito.ge/2KW1nfs.png)

## What can it do?

So far, it's still in early development, however I plan for these things to be added:

### Mangadex support

* Includes pulling up info of a manga/chapter
  * Due to how the API works, searching isn't possible
* Can find info about a scanlation's current progress
* Auto update subscribed scanlation groups and their works

### Scanlation tracker

You are able to track your progress in your group, and you can set privacy settings it won't appear on public updates.

* Can have two different densities of tracking your progress
  * Wide: Full embeds, as seen in the preview
  * Table: Will be a small table, can be customized to show names or progress only
* Able to show a card-like progress using embeds
* Can update people who subscribed to your feed in their own servers

## How do I add this?

Currently, this 'bot' is still in progress. It's more of technically a custom command in a templating language called [blargbot tags](https://blargbot.xyz/tags).

Once it's done, you can get it by inviting [blargbot](https://invite.blargbot.xyz) and then importing the tag `b!cc import tracker`. You are then able to use it as `b!tracker`.