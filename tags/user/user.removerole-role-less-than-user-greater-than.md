---
description: Remove a role from the user
---

# user.removerole \[role\] &lt;user&gt;

This tag lets you remove roles from the target user. The role can be anything - preferably a role ID, but names are also acceptable.

## [Context Requirements](../tags.md#context-requirements)

`user`, `guild` and `settings`

## Examples

{% tabs %}
{% tab title="Basic" %}
{% code-tabs %}
{% code-tabs-item title="Input" %}
```text
{user.removerole;Humans}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="Output" %}
```text

```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}
{% endtabs %}

