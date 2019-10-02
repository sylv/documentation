---
description: How do I use tags? What can tags do?
---

# Introduction to Tags

Tags are essentially placeholders with extra steps. They can range from being just that, simple placeholders, to complicated statements. While the main use for tags are in [Actions](../plugins/actions.md), they are not limited to them. Anywhere the [Tag Editor](tag-editor.md) shows up, most tags will work.   


Tag names are not case-sensitive, so `{message.authorId}` is the same as `{message.authorid}` as far as the bot is concerned.

### Context Requirements

Context requirements are essentially what the tag needs to run. For example, the `{suggestion}` tag group requires that a suggestion be in the context - for a `Message Create` action there won't be any suggestion to get the data from, so it won't work. Context varies from use to use - depending on the action trigger it could be different. There is no master list of what is available where - most tags should work almost everywhere.

