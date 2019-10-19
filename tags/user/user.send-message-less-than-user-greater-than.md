---
description: Direct-message the user
---

# user.send \[message\] &lt;user&gt;

This tag lets you direct-message users a custom message. If the user does not allow direct-messages or they aren't apart of the guild, this tag will throw an error.

Abusing this tag will result in your server being blacklisted. Abuse would be using it to advertise to server members. In general, use common sense and you'll be fine.

## [Context Requirements](../tags.md#context-requirements)

`user` and `channel`

## Examples

{% tabs %}
{% tab title="Basic" %}
{% code-tabs %}
{% code-tabs-item title="Input" %}
```text
{user.send;Hello :)}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="Output" %}
```text

```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% hint style="success" %}
This tag outputs nothing on success.
{% endhint %}
{% endtab %}

{% tab title="Error Handling" %}
{% code-tabs %}
{% code-tabs-item title="Input" %}
```text
{catch;{user.send;This is a test};Uh oh! Something went wrong direct-messaging you.}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="Output" %}
```text
Uh oh! Something went wrong direct-messaging you.
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% hint style="danger" %}
For this example, we assume the target user has direct-messaging disabled.
{% endhint %}
{% endtab %}
{% endtabs %}

