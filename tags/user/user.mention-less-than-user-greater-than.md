---
description: Mention a user
---

# user.mention &lt;user&gt;

This tag will mention the target user by taking their identifier and wrapping it in `<@IDENTIFIER>` which discord will replace with a proper mention once sent.

## [Context Requirements](../tags.md#context-requirements)

`user` and `guild`

## Examples

{% tabs %}
{% tab title="Basic" %}
{% code-tabs %}
{% code-tabs-item title="Input" %}
```text
{user.mention}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="Output" %}
```text
@Sylver#1058
```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}

{% tab title="Raw" %}
{% code-tabs %}
{% code-tabs-item title="Input" %}
```text
```{user.mention}
```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}
{% endtabs %}

