---
description: This guide explains how to disconnect LINE from Chatlyst.
icon: link-slash
---

# Disconnect LINE

{% hint style="warning" %}
You must disconnect LINE in Chatlyst and turn off the **Use webhook** setting in the LINE Developers Console.
{% endhint %}

{% stepper %}
{% step %}
## Disconnect LINE in Chatlyst

1. Go to Inbound Channel.
2. Select the widget you want to disconnect from LINE, then select **Configure**.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (415).png" alt="" width="375"><figcaption></figcaption></figure></div>

3. Select **Disconnect LINE**.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (416).png" alt=""><figcaption></figcaption></figure></div>

4. When the browser confirmation window appears, select **OK** to proceed.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (417).png" alt=""><figcaption></figcaption></figure></div>

5. Confirm the widget status changes from **Active** to **Draft**.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (418).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
## Remove Webhook from LINE

In the LINE Developers Console, turn off **Use webhook** in the **Messaging API** settings.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (494).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}
{% endstepper %}
