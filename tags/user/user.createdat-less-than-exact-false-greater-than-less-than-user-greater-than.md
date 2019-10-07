---
description: The time the users account was created
---

# user.createdAt &lt;exact=false&gt; &lt;user&gt;

This tag will return the time a user's account was created. "exact" determines whether to include hours:minutes or not.

## [Context Requirements](../tags.md#context-requirements)

`user` and `settings`

## Examples

{% tabs %}
{% tab title="Basic" %}
{% code-tabs %}
{% code-tabs-item title="Input" %}
```text
{user.createdAt}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="Output" %}
```text
Nov 4, 2015
```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}

{% tab title="Exact" %}
{% code-tabs %}
{% code-tabs-item title="Input" %}
```text
{user.createdAt;true}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="Output" %}
```text
Nov 4, 2015, 7:53 AM
```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}
{% endtabs %}



