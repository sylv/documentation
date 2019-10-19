---
description: How much experience the next level requires
---

# user.nextLevelXP &lt;user&gt;

This tag will return how much experience the upcoming level for the user requires. You might want [{user.remainingXP}](user.remainingxp-less-than-user-greater-than.md) instead. Apart of the [Levels ](../../plugins/levels.md)plugin.

## [Context Requirements](../tags.md#context-requirements)

`user` and `guild`

## Examples

{% tabs %}
{% tab title="Basic" %}
{% code-tabs %}
{% code-tabs-item title="Input" %}
```text
{user.nextLevelXP}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="Output" %}
```text
155
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



