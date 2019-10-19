---
description: The users current experience
---

# user.levelXP &lt;user&gt;

This tag will return the user's experience count. Useful with level utilities in the utils group. Apart of the [Levels ](../../plugins/levels.md)plugin.

## [Context Requirements](../tags.md#context-requirements)

`user` and `guild`

## Examples

{% tabs %}
{% tab title="Basic" %}
{% code-tabs %}
{% code-tabs-item title="Input" %}
```text
{user.levelXP}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="Output" %}
```text
54
```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}

{% tab title="More XP" %}
{% code-tabs %}
{% code-tabs-item title="Input" %}
```text
{user.levelXP}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="Output" %}
```text
1348
```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}
{% endtabs %}

