---
description: How much experience until the user levels up
---

# user.remainingXP &lt;user&gt;

This tag will return how much experience the upcoming level for the user requires. You might want [{user.remainingXP}](user.remainingxp-less-than-user-greater-than.md) instead. Apart of the [Levels ](../../plugins/levels.md)plugin.

## [Context Requirements](../tags.md#context-requirements)

`user` and `guild`

## Examples

{% tabs %}
{% tab title="Basic" %}
{% code-tabs %}
{% code-tabs-item title="Input" %}
```text
{user.remainingXP}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="Output" %}
```text
2016
```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}
{% endtabs %}



