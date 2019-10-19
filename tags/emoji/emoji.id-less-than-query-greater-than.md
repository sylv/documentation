---
description: The ID of the emoji
---

# emoji.id \[query\]

This tag will get the ID of the input emoji. If the &lt;query&gt; resolves to a non-guild emoji, it defaults to {emoji.char}.

## [Context Requirements](../tags.md#context-requirements)

None

## Examples

{% tabs %}
{% tab title="With Guild Emoji" %}
{% code-tabs %}
{% code-tabs-item title="Input" %}
```text
{emoji.id;aguildemoji}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="Output" %}
```text
538223757291028480
```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}

{% tab title="With Unicode Emoji" %}
{% code-tabs %}
{% code-tabs-item title="Input" %}
```text
{emoji.id;smile}
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
{% endtabs %}

