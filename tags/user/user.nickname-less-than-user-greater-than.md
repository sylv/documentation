---
description: The users nickname
---

# user.nickname &lt;user&gt;

Returns the users nickname. If the user does not have a nickname, this tag will use their username instead.

## [Context Requirements](../tags.md#context-requirements)

`user` and `settings`

## Examples

{% tabs %}
{% tab title="Basic" %}
{% code-tabs %}
{% code-tabs-item title="Input" %}
```text
{user.nickname}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="Output" %}
```text
ihaveanickname
```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}

{% tab title="Users without a Nickname" %}
{% code-tabs %}
{% code-tabs-item title="Input" %}
```text
{user.nickname}
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

