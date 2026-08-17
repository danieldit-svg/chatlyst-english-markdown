---
description: This guide shows how to set up the widget from start to finish.
icon: rectangle-plus
---

# Add a Widget

In the Website Embed channel, select **Add Widget**.

<div align="center" data-with-frame="true"><img src="../../.gitbook/assets/attachmentf8a579b4 9219 4dad 8eaa 5ffc0095458bimage (5).png" alt="" width="375"></div>

On the widget setup page, enter the widget details and configure settings using the left panel. Review the live preview on the right as changes are made, then complete the setup.&#x20;

Widget configuration includes three sections: [Appearance](add-a-widget.md#appearance), [Behavior](add-a-widget.md#behavior), and [Advanced](add-a-widget.md#advanced).

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (755).png" alt=""><figcaption></figcaption></figure></div>

{% hint style="info" %}
Navigation tab — use this tab to move between [Appearance](add-a-widget.md#appearance), [Behavior](add-a-widget.md#behavior), and [Advanced](add-a-widget.md#advanced), and quickly review or update specific sections.

![](<../../.gitbook/assets/image (53).png>)
{% endhint %}

{% stepper %}
{% step %}
### Appearance

**Control the visual design of the widget, including name, colors, placement on the page and widget icon setting.**

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (756).png" alt=""><figcaption></figcaption></figure></div>

Users can update the following fields:

1. **Basic Information**
   * **Company Display Name** — the public-facing name shown in the widget header.
   * **Widget Name** — an internal name used to manage multiple widgets.
   * **Welcome Messag**e — the greeting shown when the widget opens.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (758).png" alt="" width="563"><figcaption></figcaption></figure></div>

2. **Widget Color**

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (759).png" alt="" width="563"><figcaption></figcaption></figure></div>

* **Primary Color** — sets the primary color used across the widget and defines the overall brand look. This color applies to the header and the widget launcher and does not change when switching themes. A color can be selected in the color picker or entered as a HEX code.

<div><figure><img src="../../.gitbook/assets/image (760).png" alt="" width="563"><figcaption><p>Header</p></figcaption></figure> <figure><img src="../../.gitbook/assets/image (763).png" alt="" width="563"><figcaption><p>Launcher</p></figcaption></figure></div>

* **Secondary Color** — sets the secondary color used for supporting UI elements and creates contrast with the primary color. This color applies only to the footer.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (762).png" alt="" width="375"><figcaption><p>Footer</p></figcaption></figure></div>

2.  **Widget Theme**

    * To set the widget theme for the widget experience, choose the theme option that best matches the intended look and feel for visitors.
      * **Light** — applies light styling to the widget body and input field.
      * **Dark** — applies dark styling to the widget body, input field, and footer.
      * **Auto** — automatically sets the widget theme based on system settings.

    <div><figure><img src="../../.gitbook/assets/image (764).png" alt=""><figcaption><p>Light Theme</p></figcaption></figure> <figure><img src="../../.gitbook/assets/image (765).png" alt=""><figcaption><p>Dark Theme</p></figcaption></figure></div>
3. **Position**
   * To set where the widget appears on the website, choose the position where it will be displayed for visitors (**Bottom Right**, **Bottom Left**, **Center**, or **Embedded**). This setting determines where the widget  shows up on the screen, or whether it appears inline where the widget is embedded on the page.

<div><figure><img src="../../.gitbook/assets/image (766).png" alt=""><figcaption><p>Center</p></figcaption></figure> <figure><img src="../../.gitbook/assets/image (767).png" alt=""><figcaption><p>Bottom Left</p></figcaption></figure> <figure><img src="../../.gitbook/assets/image (768).png" alt=""><figcaption><p>Bottom Right</p></figcaption></figure></div>

4. **Widget Icon Type**&#x20;

* To determine the visual image displayed on the chat widget to website visitors. To set the appearance of the widget, choose the option that best matches the desired look and feel for the website.
  * **Fallback to Initial of Display Name** — This option applies the configured Company Display Name.&#x20;
  * **Use Company Icon** — This option automatically applies the company logo previously uploaded in the Settings. For instructions on how to upload the main company icon, please refer to the [Company](../../settings/company.md) guide.
  *   **Upload Custom Icon** — This option applies a unique image specifically for this individual widget, overriding the default company icon.

      * How to upload: Select this option to reveal the upload menu. Choose an image file from the local computer to upload it.

      <div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (769).png" alt="" width="358"><figcaption></figcaption></figure></div>

{% hint style="info" %}
The company icon supports PNG, JPG, and SVG file formats. A square aspect ratio is recommended for the best display results.
{% endhint %}

<div><figure><img src="../../.gitbook/assets/image (773).png" alt=""><figcaption><p>Fallback to Initial of Display Name</p></figcaption></figure> <figure><img src="../../.gitbook/assets/image (771).png" alt=""><figcaption><p>Use Company Icon</p></figcaption></figure> <figure><img src="../../.gitbook/assets/image (772).png" alt=""><figcaption><p>Upload Custom Icon</p></figcaption></figure></div>
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

<div><figure><img src="../../.gitbook/assets/image (277).png" alt="" width="321"><figcaption><p>Human Handoff — <strong>ON</strong></p></figcaption></figure> <figure><img src="../../.gitbook/assets/image (278).png" alt="" width="325"><figcaption><p>Human Handoff — <strong>OFF</strong></p></figcaption></figure></div>
{% endstep %}

{% step %}
### Advanced

**Adjust technical and session settings**

* **Max Assistant Messages Per Session** — sets the maximum number of assistant messages allowed in a single chat session. When the limit is reached, the chat switches to a human user, and the status updates to **Pending 1st Response**.

{% hint style="info" %}
The default is 30 messages per session, with a minimum of 10.
{% endhint %}

* [**Session Timeout**](add-a-widget.md#session-times-out) **(minutes)** — sets how long a session stays active after the most recent message. The session stays active as long as messages continue. If no new message arrives within the set time (measured from the last message), the session expires and closes. If a human takes over during the session, the session remains active.

{% hint style="info" %}
The default value is 1,440 minutes (24 hours). This is the recommended settings.&#x20;
{% endhint %}

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (345).png" alt="" width="324"><figcaption></figcaption></figure></div>

<details>

<summary>Session Timeout</summary>

* When the session times out, the widget prompts visitors to start a new conversation so chatting can continue after the previous session expires.
* A timed-out session closes automatically in Chat and no longer appears as an active conversation.

<p align="center"><img src="../../.gitbook/assets/image (54).png" alt=""></p>

</details>
{% endstep %}

{% step %}
### Complete Configuration

After finishing configuration, select **Create**.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (774).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
### Widget Activation

After a widget is created, the next page opens automatically so the widget details and activation steps can be reviewed.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (775).png" alt=""><figcaption></figcaption></figure></div>

1. In the Widget Configuration tab (in the middle of the page), confirm the widget status shows **Draft** (inactive).
2. In the **Embed Code** tab (at the bottom of the page), review the inactive reminder message.
3. To activate the widget, toggle it on in the top-right corner.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (778).png" alt=""><figcaption></figcaption></figure></div>

4. Confirm the widget status changes from **Draft** to **Active** and the inactive reminder message no longer appears.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (779).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}
{% endstepper %}
