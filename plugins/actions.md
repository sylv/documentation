---
description: 'The one, the only...'
---

# Actions

Actions are a core part of Atlas. They allow users to make their own commands, send messages on an interval, and a lot more. An "action" is like a script that Atlas can run on a trigger. An action can use [Tags](../tags/tags.md) to modify it's behavior. People have done some pretty incredible things using actions. 

You can see examples for actions at the the community actions repository on GitHub, available at [https://github.com/atlasbot/community-actions](https://github.com/atlasbot/community-actions). There are some actions that are so big they could be worthy of their own plugin. Some actions have even been added to the core bot, like the `tag` command which was originally made by node\#2153.

Actions don't have to be simple. Most of the time, they're used for simple commands like a command that links to a website, or a command that gives a user a role.

Unlike most plugins, "Actions" doesn't have the standard options most others have. You can't disable it and you can't set restrictions.   
  
If you abuse actions or slow the bot down, your server and the action author will be permanently banned from using Atlas with no way to get the ban removed.

### Triggers

* **Command** Triggers when someone does `a!triggercontent`
* **Keyword** Triggers when someone sends a message that containers the trigger content.
* **Interval** Triggers every`interval content`
* **Message Reaction Add** Triggers when the `trigger content` reaction 😀 is added to a message. Supports guild emojis.
* **Message Reaction Remove** Triggers when the `trigger content` reaction is removed from a message. Supports guild emojis.
* **Message Create** Triggers when a message is sent. If set to `Any Message`, it will trigger on _any message_ in the server. If set to a channel, it will trigger when a message is sent to the channel. This trigger has heavy limits to prevent abuse, see the info box on the dashboard for more.
* **Member Join** Triggers when someone joins the server.
* **Member Leave** Triggers when someone leaves the server.
* **Message Role Add** Triggers when a role is added to a user in the server.
* **Message Role Remove** Triggers when a role is removed from a user in the server.

### 

### Scripts

Scripts are what the tag engine will run. Each script is executed consecutively, so "Script Two" will run right after "Script One". `{get}` and `{set}` tags will not persist between scripts. `{perset}` tags will, but ideally you should avoid using them unless they are absolutely necessary.

