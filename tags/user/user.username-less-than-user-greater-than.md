---
description: The users username.
---

# user.username &lt;user&gt;

This tag will get the target users username. In most cases, using [{user.nickname}](user.nickname-less-than-user-greater-than.md) for addressing the user and [{user.id}](user.id-less-than-user-greater-than.md) for identifying them is preferable.

 Using this tag to identify users in a {perset} is not advised and may result in losing user data if they change their username, or data being overwritten if two users share the same username. Use [{user.id}](user.id-less-than-user-greater-than.md).

## [Context Requirements](../tags.md#context-requirements)

`user` and `guild`

## Examples

{% tabs %}
{% tab title="Basic" %}
{% code-tabs %}
{% code-tabs-item title="Input" %}
```text
{user.username}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="Output" %}
```text
Sylver
```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}
{% endtabs %}



