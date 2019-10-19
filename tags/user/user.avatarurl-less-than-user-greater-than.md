---
description: The target users avatar url
---

# user.avatarURL &lt;user&gt;

This tag will get the target user's avatar URL from Discord. If the user does not have an avatar, it will default to Discord's default avatars. [Output format](https://discordapp.com/developers/docs/reference#image-formatting-cdn-endpoints%20)

## [Context Requirements](../tags.md#context-requirements)

`user` and `guild`

## Examples

{% tabs %}
{% tab title="Basic" %}
{% code-tabs %}
{% code-tabs-item title="Input" %}
```text
{user.avatarURL}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="Output" %}
```text
https://cdn.discordapp.com/avatars/111372124383428608/a_db60101ca8c6b08e7e1d1ffb23fe0326.gif?size=128
```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}

{% tab title="Specific User" %}
{% code-tabs %}
{% code-tabs-item title="Input" %}
```text
{user.avatarURL;Sylver}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="Output" %}
```text
https://cdn.discordapp.com/avatars/111372124383428608/8ab12121b57c7a462389a8d1009e7904.png?size=256
```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}
{% endtabs %}

