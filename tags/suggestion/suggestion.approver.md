---
description: User ID of the user who verified the suggestion
---

# suggestion.approver

This tag returns the user ID of whoever verified the suggestion. If the suggestion was not verified, this will return nothing.

## [Context Requirements](../tags.md#context-requirements)

`suggestion`

## Examples

{% tabs %}
{% tab title="Direct" %}
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
@Sylver#1058
```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}
{% endtabs %}

