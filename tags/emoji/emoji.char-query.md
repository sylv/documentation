---
description: The discord-compatible emoji character
---

# emoji.char \[query\]



This tag will get the ID of the input emoji. If the &lt;query&gt; resolves to a non-guild emoji, it defaults to {emoji.char}. 

## [Context Requirements](../tags.md#context-requirements)

None

## Examples

{% tabs %}
{% tab title="With Unicode Emoji" %}
{% code-tabs %}
{% code-tabs-item title="Input" %}
```text
{emoji.char;smile}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="Output" %}
```text
😄
```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}

{% tab title="With Guild Emoji" %}
{% code-tabs %}
{% code-tabs-item title="Input" %}
```text
{emoji.char;fortniteepicf}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="Output" %}
```text
<:fortniteepicf:538223757291028480>
```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}
{% endtabs %}

