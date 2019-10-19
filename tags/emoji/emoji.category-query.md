---
description: The emoji's category from the emoji picker
---

# emoji.category \[query\]

This tag will get the ID of the input emoji. If the &lt;query&gt; resolves to a non-guild emoji, it defaults to {emoji.char}.

## [Context Requirements](../tags.md#context-requirements)

None

## Examples

{% tabs %}
{% tab title="With Unicode Emoji" %}
{% code-tabs %}
{% code-tabs-item title="Input" %}
```text
{emoji.name;smile}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="Output" %}
```text
People
```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}

{% tab title="With Guild Emoji" %}
{% code-tabs %}
{% code-tabs-item title="Input" %}
```text
{emoji.category;<:fortniteepicf:538223757291028480>}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="Output" %}
```text
guild
```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}
{% endtabs %}

