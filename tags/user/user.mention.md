---
description: Give a server member a role.
---

# user.addrole \[role\] &lt;user&gt;

This tag is used to give a member a role. For Atlas to be able to dish out roles, it has to be above the target role and must have permissions to assign roles.

### [Context Requirements](../tags.md#context-requirements)

`user`, `guild` and `settings`

### Examples

{% tabs %}
{% tab title="Basic" %}
{% code-tabs %}
{% code-tabs-item title="Input" %}
```text
{user.addrole;Humans}
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

{% tab title="Specific User" %}
{% code-tabs %}
{% code-tabs-item title="Input" %}
```text
{user.addrole;Humans;Sylver#1058}
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





