---
description: 'The target users discriminator (#1000, #number)'
---

# user.discriminator &lt;user&gt;

This tag will get the target user's discriminator, the 4-digit code after their username. 

## [Context Requirements](../tags.md#context-requirements)

`user` and `settings`

## Examples

{% tabs %}
{% tab title="Basic" %}
{% code-tabs %}
{% code-tabs-item title="Input" %}
```text
{user.discriminator}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="Output" %}
```text
1058
```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}
{% endtabs %}



