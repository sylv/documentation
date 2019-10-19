---
description: The ID of the user that created the suggestion
---

# suggestion.author

This tag will return the ID of the user that created the suggestion.

## [Context Requirements](../tags.md#context-requirements)

`suggestion`

## Examples

{% tabs %}
{% tab title="Direct" %}
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
111372124383428608
```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}

{% tab title="Mention the Author" %}
{% code-tabs %}
{% code-tabs-item title="Input" %}
```text
{user.author;{suggestion.approver}}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="Output" %}
```text
@Sylver#1058
```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}
{% endtabs %}

