---
description: The name of the emoji.
---

# emoji.name \[query\]

This tag will get the ID of the input emoji. If the &lt;query&gt; resolves to a non-guild emoji, it defaults to {emoji.char}. 

## [Context Requirements](../tags.md#context-requirements)

None

## Examples

{% tabs %}
{% tab title="With Guild Emoji" %}
{% code-tabs %}
{% code-tabs-item title="Input" %}
```text
{emoji.name;<:wtf:614467591959871535>}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="Output" %}
```text
wtf
```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}

{% tab title="With Unicode Emoji" %}
{% code-tabs %}
{% code-tabs-item title="Input" %}
```text
{emoji.char;😄}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="Output" %}
```text
smile
```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}
{% endtabs %}

