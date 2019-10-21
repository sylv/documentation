---
description: The ID of the user that created the suggestion.
---

# suggestion.author

When a suggestion is in context, this tag will get the user ID of the user who created the suggestion.

## [Context Requirements](../tags.md#context-requirements)

`suggestion`

## Examples

{% tabs %}
{% tab title="Basic" %}
{% code-tabs %}
{% code-tabs-item title="Input" %}
```text
{suggestion.author}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="Output" %}
```text
248882595285303306
```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}

{% tab title="Mention the Approver" %}
{% code-tabs %}
{% code-tabs-item title="Input" %}
```text
{user.mention;{suggestion.author}}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="Output" %}
```text
Cykreet#5758
```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}
{% endtabs %}

