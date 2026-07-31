---
description: This guide shows how to manage the LINE channel.
icon: line
---

# LINE

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (403).png" alt="" width="375"><figcaption></figcaption></figure></div>

## Important Notes:

#### **Prerequisite for Connection**

To connect a LINE channel, you must have LINE account. For more details, please refer to [LINE](https://www.line.me/en/).

#### **Centralize Conversations**

Due to LINE API constraints and limitations, messages are not synchronized with the LINE Official Account website. Chatlyst is therefore the primary workspace for managing conversations.

#### **24-Hour Session Window**

In the LINE channel, if no customer message is received within 24 hours, the Chatlyst chat session will automatically close.

* You may continue replying via LINE Official Account Manager, and your messages will still appear in Chatlyst under the same conversation.
* When the customer sends a new message after the session has closed, Chatlyst will create a new chat session. At that point, you may either allow the bot to respond or manually join the conversation in Chatlyst.

#### **Message History**

Chatlyst does not sync historical messages from the LINE. Only messages within active Chatlyst sessions will be visible in the platform.

#### **Multimedia Messages**

Chatlyst supports images, videos, files and location sharing, but does not support contact sharing.

<details>

<summary><strong>Location Sharing</strong></summary>

<div align="left"><figure><img src="../../.gitbook/assets/image (506).png" alt="" width="563"><figcaption></figcaption></figure></div>

</details>

***

## Manage Widgets

### **Widget On/Off**

Use the switch in the top-right corner to turn a channel on or off.

When a channel is turned off, it is disabled immediately, and the chatbot stops appearing on that channel.

Any widgets connected to the channel automatically change from **Active** to **Draft**. This removes them from the live experience until the channel is enabled again.

<div><figure><img src="../../.gitbook/assets/image (433).png" alt=""><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (434).png" alt=""><figcaption></figcaption></figure></div>

### **Recent Metrics**

The tab shows the number of conversations and messages from the past 30 days. Use these metrics to confirm the channel is receiving traffic and validate performance before making configuration updates.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (435).png" alt="" width="375"><figcaption></figcaption></figure></div>

### **Add and Configure Widget**

To add a widget, select **Add Widget (Connet LINE Account)** to launch the widget setup flow. For additional context, follow [Add a Widget](add-a-widget.md).

1. The guided setup walks through:
   * Entering the widget’s key details.
   * Reviewing the default settings.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (436).png" alt="" width="375"><figcaption></figcaption></figure></div>

2. To configure a widget, select the widget from the list, then select **Configure** to open the widget setup and review its configuration. For additional context, follow [Configure a Widget](../whatsapp/configure-a-widget.md).

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (437).png" alt="" width="375"><figcaption></figcaption></figure></div>

{% hint style="warning" %}
**Important Note**: All widgets share the same Business Knowledge base. This means updates to your Business Knowledge apply to every widget, so users do not need to maintain separate knowledge for each one.
{% endhint %}
