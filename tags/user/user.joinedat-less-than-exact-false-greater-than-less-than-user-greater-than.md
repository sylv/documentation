---
description: When the user joined the server
---

# user.joinedAt &lt;exact=false&gt; &lt;user&gt;

This tag will return the time the user joined the server. Functionally the same as [{user.createdAt}](user.createdat-less-than-exact-false-greater-than-less-than-user-greater-than.md).

## [Context Requirements](../tags.md#context-requirements)

`user` and `settings`

## Examples

{% tabs %}
{% tab title="Basic" %}
{% code-tabs %}
{% code-tabs-item title="Input" %}
```text
{user.joinedAt}
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
{user.joinedAt;true}
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

