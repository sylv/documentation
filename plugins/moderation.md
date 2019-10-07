---
description: 'Simple, powerful moderation for your server.'
---

# Moderation

The Moderation plugin is one of if not the biggest plugins Atlas has. You can automatically filter chat and provide powerful tools for moderators to quickly deal with users.

## Logging

Atlas can log server events such as a moderator deleting someones message or a role being deleted. There are two types that events will fall into - action logs are things like a user deleting their own message, a role being removed from a user, someone joining the server, and many more. Moderation logs are for moderator actions, such as kicking a user, deleting a members message or warning a user.

If you use logging, you should try and use the built-in moderation commands over the Discord clients ban methods \(right clicking a user and selecting "Ban"\). Using the commands guarantees we can trace who did what, and gives us some more information to log depending on what happened. If you don't use the moderation commands, Atlas will try get the information from the audit log, but that isn't always successful or accurate.

## Filters

Filters let you censor your server. You can filter for basic things like excessive spam, or even create your own filters that will trigger when a user says bad things.

* **Capitalization** triggers if a message contains EXCESSIVE CAPITALIZATION. Threshold is what % of the message has to be capitalized for the filter to trigger. There is a minimum message length for the filter to trigger, even if the threshold is set to 100%, something like `XD` will not trigger the filter.
* **Cursing** triggers if a message contains swearing. This filter is far from perfect and _will_ have false positives, so if you can avoid it you really should. If your server has issues with a specific phrase, use the "Phrases" filter. 
* **Emoji** filter excessive emojis 😂 😂 🤣😎 
* **Invites** prevent users from advertising other servers by filtering out any invite link. If someone sends an invite that is for your own server, Atlas will not block it.
* **Links** lets you block links to websites. "Hostname Exclusions" will block specific host names. If you added "youtube.com" to the hostname exclusions list and someone sent a link like [https://www.youtube.com/watch?v=dQw4w9WgXcQ](https://www.youtube.com/watch?v=dQw4w9WgXcQ), atlas would let it through.
* **Mentions** triggers when someone users an excessive amount of mentions. There is no realistic scenario where someone should be mentioning more then 5 users in a message.
* **Phrases** triggers when a message includes a phrase that is in the blocked list.
* **Spam** will trigger when someone sends an excessive amount of messages in a short amount of time. 
* **Spoilers** will trigger on messages that contain too many \|\| spoilers \|\|.

  "Exempt Roles" and "Exempt Channels" will prevent the filter running on messages from the user or in the channel that is exempt.

"Sanction Bots" means Atlas will apply the filter to other bots, but not itself.

"Sanction Moderators" means Atlas will apply the filters to users with the `Manage Messages` permission.

"Sanction Ticket Channels" means Atlas will apply filters in Ticket channels.

