---
description: The users username color
---

# user.color &lt;hex=false&gt; &lt;user&gt;

This tag will return the color of a user based on their highest role in role hierarchy. If hex is true, the value will be returned as a valid [hex code](https://en.wikipedia.org/wiki/Web_colors#Hex_triplet) - this is the default behavior. If hex is false, the output will be the raw role color from Discord - info at [https://discordapp.com/developers/docs/topics/permissions\#role-object-role-structure](https://discordapp.com/developers/docs/topics/permissions#role-object-role-structure)

## [Context Requirements](../tags.md#context-requirements)

`user` and `settings`

## Examples

{% tabs %}
{% tab title="Basic" %}
{% code-tabs %}
{% code-tabs-item title="Input" %}
```text
{user.color}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="Output" %}
```text
#95a5a6
```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}

{% tab title="Integer" %}
{% code-tabs %}
{% code-tabs-item title="Input" %}
```text
{user.color;true;Atlas}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="Output" %}
```text
#03a9f4
```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}

{% tab title="Specific User" %}
{% code-tabs %}
{% code-tabs-item title="Input" %}
```text
{user.color;true}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="Output" %}
```text
9807270
```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}

{% tab title="With Embeds" %}
{% code-tabs %}
{% code-tabs-item title="Input" %}
```text
{a!ae;--color="{user.color;true}";--title="Test"}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

#### ![](../../.gitbook/assets/ib7wf.png) 
{% endtab %}
{% endtabs %}



