---
description: This guide shows how to set up the widget from start to finish.
icon: rectangle-plus
---

# Add a Widget

In the Website Embed channel, select **Add Widget**.

<div align="center" data-with-frame="true"><img src="../../.gitbook/assets/attachmentf8a579b4 9219 4dad 8eaa 5ffc0095458bimage (5).png" alt="" width="375"></div>

On the widget setup page, enter the widget details and configure settings using the left panel. Review the live preview on the right as changes are made, then complete the setup.&#x20;

Widget configuration includes three sections: [Appearance](add-a-widget.md#appearance), [Behavior](add-a-widget.md#behavior), and [Advanced](add-a-widget.md#advanced).

<div data-with-frame="true"><img src="../../.gitbook/assets/attachment209d98c8 05db 4e3a aaea 23952f18c950b6ef3ed1 776d 49d5 8620 7cfc33bfb7fb (2).png" alt=""></div>

{% hint style="info" %}
Navigation tab — use this tab to move between [Appearance](add-a-widget.md#appearance), [Behavior](add-a-widget.md#behavior), and [Advanced](add-a-widget.md#advanced), and quickly review or update specific sections.

![](<../../.gitbook/assets/image (45).png>)
{% endhint %}

{% stepper %}
{% step %}
### Appearance

**Control the visual design of the widget, including name, colors, and placement on the page.**

<div data-with-frame="true"><img src="../../.gitbook/assets/attachment56b1557f d988 44cf 8f23 476b6cd05879image (2).png" alt=""></div>

Users can update the following fields:

1. **Basic Information**
   * **Company Display Name** — the public-facing name shown in the widget header.
   * **Widget Name** — an internal name used to manage multiple widgets.
   * **Welcome Messag**e — the greeting shown when the widget opens.

<div data-with-frame="true"><img src="../../.gitbook/assets/attachmentb45dc036 7124 4ca1 9de1 0d0879613913Untitled_design_(12) (2).png" alt="" width="563"></div>

2. **Widget Color**

<div data-with-frame="true"><img src="../../.gitbook/assets/attachment546d14ac 69b9 42db 943c 22ce1e22650cUntitled_design_(14) (2).png" alt="" width="563"></div>

* **Primary Color** — sets the primary color used across the widget and defines the overall brand look. This color applies to the header and the widget launcher and does not change when switching themes. A color can be selected in the color picker or entered as a HEX code.

![Header](<../../.gitbook/assets/attachment41626212 5535 4902 b9ec bab2ec318c79image (2).png>) ![Launcher](<../../.gitbook/assets/attachment83ee95df e08c 4ee9 8a4b efb394a77f7cimage (2).png>)

* **Secondary Color** — sets the secondary color used for supporting UI elements and creates contrast with the primary color. This color applies only to the footer.

<div align="center" data-with-frame="true"><img src="../../.gitbook/assets/attachment3e4daf40 f1d1 4802 b3ff 41bea7736444image (2).png" alt="Footer" width="375"></div>

2.  **Widget Theme**

    * To set the widget theme for the widget experience, choose the theme option that best matches the intended look and feel for visitors.
      * **Light** — applies light styling to the widget body and input field.
      * **Dark** — applies dark styling to the widget body, input field, and footer.
      * **Auto** — automatically sets the widget theme based on system settings.

    <div><figure><img src="../../.gitbook/assets/light.png" alt=""><figcaption><p>Light Theme</p></figcaption></figure> <figure><img src="../../.gitbook/assets/dark.png" alt=""><figcaption><p>Dark Theme</p></figcaption></figure></div>
3. **Position**
   * To set where the widget appears on the website, choose the position where it will be displayed for visitors (**Bottom Right**, **Bottom Left**, **Center**, or **Embedded**). This setting determines where the widget  shows up on the screen, or whether it appears inline where the widget is embedded on the page.

![Center](<../../.gitbook/assets/attachment32b79d7e 501a 4ccc aa22 acba50a7e1f5Screenshot_2026 04 22_at_11.47.44_PM (2).png>) ![Bottom Right](<../../.gitbook/assets/attachment539e310f 1582 4337 b010 1262818e7b84Screenshot_2026 04 22_at_11.47.26_PM (2).png>)

<div align="center"><img src="../../.gitbook/assets/attachmentfe579746 7257 47bc 9eb7 d6d2b58ad8b0Screenshot_2026 04 22_at_11.47.35_PM (2).png" alt="Bottom Left" width="375"></div>
{% endstep %}

{% step %}
### Behavior

**Control how the widget interacts with visitors**

* **Human Handoff** — controls what happens when the bot needs to hand the conversation back to a live agent. If this setting is turned off, the conversation automatically closes when the bot attempts to route the chat to a human agent, instead of keeping the session open for a takeover. The default setting is turned on.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Screenshot 2026-05-29 at 5.02.59 PM.png" alt="" width="339"><figcaption></figcaption></figure></div>
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



<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (107).png" alt="" width="291"><figcaption></figcaption></figure></div>

<details>

<summary>Session Timeout</summary>

* When the session times out, the widget prompts visitors to start a new conversation so chatting can continue after the previous session expires.
* A timed-out session closes automatically in Chat and no longer appears as an active conversation.

<p align="center"><img src="../../.gitbook/assets/image (46).png" alt=""></p>

</details>
{% endstep %}

{% step %}
### Complete Configuration

After finishing configuration, select **Create**.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (109).png" alt="" width="245"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
### Widget Activation

After a widget is created, the next page opens automatically so the widget details and activation steps can be reviewed.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (110).png" alt=""><figcaption></figcaption></figure></div>

1. In the Widget Configuration tab (in the middle of the page), confirm the widget status shows **Draft** (inactive).
2. In the **Embed Code** tab (at the bottom of the page), review the inactive reminder message.
3. To activate the widget, toggle it on in the top-right corner.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (111).png" alt=""><figcaption></figcaption></figure></div>

4. Confirm the widget status changes from **Draft** to **Active** and the inactive reminder message no longer appears.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (112).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}
{% endstepper %}
