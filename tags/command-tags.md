---
description: Call commands from your own actions
---

# Command Tags

Atlas provides a global tag that lets you run any existing command. Because there are roughly ~110 commands, this tag is generated on the fly when you call it. 

#### Usage

`{a!<command>;args;args}`, for example `{a!ping}` or `{a!roleinfo;{args}}.`

#### Gotchas

Command tags are basically a hack. In some circumstances, they may not work at all. They also use the context users permissions, so if you want to do `{a!ping}` in a channel when a user joins, the user has to be able to execute `a!ping` in that channel outside of actions for it to work. 

The exception to the permissions rule is `{a!ae}` which bypasses permission checks so you can send embeds in channels the context user cannot access.

