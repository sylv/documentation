---
description: Gets the identifier of a random user.
---

# user.random

This tag will get the identifier of a random user in the server. You can use it as the last argument to all [{user}](./) tags. No one is excluded, so this tag may pick bots as well as regular users.

  
Relying on this for something like a giveaway is not ideal due to Atlas not always being able to see everyone in the server at the same time. True random isn't guaranteed as it's practically impossible.

## [Context Requirements](../tags.md#context-requirements)

`user` and `guild`

## Examples

{% tabs %}
{% tab title="Basic" %}
{% code-tabs %}
{% code-tabs-item title="Input" %}
```text
{user.random}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="Output" %}
```text
111372124383428608
```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}

{% tab title="With Other {user} Tags" %}
{% code-tabs %}
{% code-tabs-item title="Input" %}
```text
I pick you, {user.tag;{user.random}}!
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="Output" %}
```text
I pick you, Sylver#1058!
```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}
{% endtabs %}



