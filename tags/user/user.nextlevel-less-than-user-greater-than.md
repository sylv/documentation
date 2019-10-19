---
description: The level the user will have after a level-up
---

# user.nextLevel &lt;user&gt;

This tag will return the user's upcoming level. Apart of the [Levels ](../../plugins/levels.md)plugin.

## [Context Requirements](../tags.md#context-requirements)

`user` and `guild`

## Examples

{% tabs %}
{% tab title="Basic" %}
{% code-tabs %}
{% code-tabs-item title="Input" %}
```text
{user.nextLevel}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="Output" %}
```text
2
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% hint style="warning" %}
This assumes the user is currently level one.
{% endhint %}
{% endtab %}
{% endtabs %}



