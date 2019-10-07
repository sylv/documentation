---
description: 'Reaction roles, join roles, self-assignable roles and a lot more.'
---

# Roles

The Roles plugin is a vague plugin that contains role-related features.

## Join Roles

When a member joins, Atlas will give them this role.

## "I Am" or "Self-Assignable" Roles

Adding a role to this list will let users give themselves the role through Atlas by doing the `a!iam <role name>` command.

## Reaction Roles

Let users give themselves roles by reacting to a message with a custom reaction.

{% hint style="info" %}
If you provide a channel and message ID, Atlas will automatically add the reactions to the target message.
{% endhint %}

{% hint style="danger" %}
Atlas may not add the reactions to the target message. This is expected, and doesn't indicate that the configuration is wrong.
{% endhint %}

