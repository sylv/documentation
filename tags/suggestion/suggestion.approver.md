---
description: The ID of the user that approved the suggestion.
---

# suggestion.approver

When a suggestion is in context, this tag will get the user ID of the user who approved the suggestion, if any.

## [Context Requirements](../tags.md#context-requirements)

`suggestion`

## Examples

{% tabs %}
{% tab title="Basic" %}
{% code-tabs %}
{% code-tabs-item title="Input" %}
```text
{suggestion.approver}
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

{% tab title="Mention the Approver" %}
{% code-tabs %}
{% code-tabs-item title="Input" %}
```text
{user.mention;{suggestion.approver}}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="Output" %}
```text
Sylver#1058
```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}
{% endtabs %}

