---
description: Whether the target user is a bot or not
---

# user.bot &lt;user&gt;

This tag will return true if the user is a bot and false under any other circumstance.

## [Context Requirements](../tags.md#context-requirements)

`user` and `guild`

## Examples

{% tabs %}
{% tab title="Basic" %}
{% code-tabs %}
{% code-tabs-item title="Input" %}
```text
{user.bot;Atlas}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="Output" %}
```text
true
```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}

{% tab title="" %}
{% code-tabs %}
{% code-tabs-item title="Input" %}
```text
{user.bot}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="Output" %}
```text
false
```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}
{% endtabs %}

