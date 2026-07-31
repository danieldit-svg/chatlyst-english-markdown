---
description: This guide explains how to set up a widget from start to finish.
icon: rectangle-plus
---

# Add a Widget

In the WhatsApp channel, select **Add Widget (Connect Whatsapp Number)**.

<div data-with-frame="true"><img src="../../.gitbook/assets/attachmentbab7e808 52a4 403b bbec a7133236f72dimage.png" alt="" width="375"></div>

Widget configuration includes three sections: [**Appearance**](add-a-widget.md#appearance), [**Behavior**](add-a-widget.md#behavior), and [**Advanced**](add-a-widget.md#advanced).

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (601).png" alt=""><figcaption></figcaption></figure></div>

{% hint style="info" %}
Use the navigation tabs to move between **Appearance**, **Behavior**, and **Advanced**, and to quickly review or update specific sections.

![](<../../.gitbook/assets/image (354).png>)
{% endhint %}

{% stepper %}
{% step %}
### Appearance

Users can update the following fields:

* **Company Display Name** — the public-facing name shown in the widget header.
* **Widget Name** — an internal name used to manage multiple widgets.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (602).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
### Behavior

**Control how the widget interacts with visitors**

* **Human Handoff** — controls what happens when the bot needs to pass the conversation back to a live agent. The default setting is **ON**.
  * When **ON**, the conversation stays open for a human takeover.
  * When **OFF**, the conversation closes automatically when the bot tries to hand it off.
* **Handoff Message** and **Handoff Unavailable Message**
  * If no custom message is set:&#x20;
    * When Human Handoff setting is **ON**, **Handoff Message**:\
      _“Thanks for your question. I am passing this conversation to a human agent now. Someone from our team will reply shortly.”_
    * When Human Handoff setting is **OFF**, **Handoff Unavailable Message**:\
      _“Thanks for reaching out. I am not able to help with this request in chat right now, so this conversation will be closed for now. Please contact our team directly if you still need assistance.”_
* Language Support
  * There is currently no translation support for this feature. If multiple languages are needed, set the message for each language separately.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (279).png" alt=""><figcaption><p>Human Handoff — <strong>ON</strong></p></figcaption></figure></div>

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (280).png" alt=""><figcaption><p>Human Handoff — <strong>OFF</strong></p></figcaption></figure></div>
{% endstep %}

{% step %}
### Advanced

**Adjust technical and session settings.**

* **Max Assistant Messages Per Session** — sets the maximum number of assistant messages allowed in a single chat session. When the limit is reached, the chat switches to a human user, and the status updates to Pending 1st Response.

{% hint style="info" %}
The default is 30 messages per session, with a minimum of 10.
{% endhint %}

* **Session Timeout** (minutes) — sets how long a session stays active after the most recent message. The session stays active as long as messages continue. If no new message arrives within the set time (measured from the last message), the session expires and closes. If a human takes over during the session, the session remains active.

{% hint style="info" %}
The default value is 1,440 minutes (24 hours). This is the recommended settings. For WhatsApp channel, this value cannot exceed 1440 minutes.
{% endhint %}

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (603).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
### Complete the configuration

After finishing configuration, select **Create**.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (604).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
### Activate the widget

After you create a widget, the next page opens automatically so you can review the widget details.

<div data-with-frame="true"><img src="../../.gitbook/assets/attachment8504622f 4f3f 4d17 8b87 a28c0b0da01fimage.png" alt=""></div>
{% endstep %}

{% step %}
### **Connect with WhatsApp**

1. Select **Connect with WhatsApp.**

<div data-with-frame="true"><img src="../../.gitbook/assets/attachment77632f7a b93b 4f09 8879 f72a30e51465image.png" alt=""></div>

2. In the Meta window, log in to your Facebook account (if required). When prompted, connect with Effex, then select **Continue**.

{% hint style="warning" %}
Meta may take a few minutes to load this window. Please be patient.
{% endhint %}

<div data-with-frame="true"><img src="../../.gitbook/assets/attachmentd8f5a984 4974 445b 9abf ef0bde628014image (1).png" alt="" width="375"></div>

3. Select a **Business Portfolio.**

<div data-with-frame="true"><img src="../../.gitbook/assets/attachmentb19144b8 0e4c 4577 9808 a9ae9477a6ceimage (1).png" alt="" width="375"></div>

4. Select a WhatsApp Business account option to proceed.
   * Choose one option:
     * If you already have a registered WhatsApp Business account, select [**Connect a WhatsApp Business app**](connect-by-linking-into-an-existing-whatsapp-business-app.md);
     * If you do not have a registered WhatsApp Business account, select [**Create a WhatsApp Business account**](connect-by-creating-a-whatsapp-business-account.md).&#x20;

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (261).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}
{% endstepper %}
