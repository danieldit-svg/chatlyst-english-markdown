---
icon: line
---

# Set Up LINE Messaging API Credentials

### Before you start <a href="#before-you-start" id="before-you-start"></a>

A registered LINE account is required before setup begins.

During setup, use two LINE pages:

* [<mark style="background-color:cyan;">**LINE Developers Console**</mark>](https://developers.line.biz) for the Channel Secret and long-lived Channel Access Token.
* [<mark style="background-color:orange;">**LINE Official Account Manager**</mark>](https://manager.line.biz) for enabling Messaging API and webhook settings.

{% stepper %}
{% step %}
### Create the Provider and Channel

Go to the [<mark style="background-color:cyan;">LINE Developers Console</mark>](https://developers.line.biz/) and select **Log in to Console.**

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (469).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Login with your LINE account.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (470).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
LINE supports sign-in by email address or QR code. In this example, will use QR code as login method.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (471).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Scan the QR code with your phone to proceed.

* On your computer:

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (473).png" alt=""><figcaption></figcaption></figure></div>

* On your phone:

1. Select LINE on your phone

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (474).png" alt="" width="375"><figcaption></figcaption></figure></div>

2. Select Scan button on the top-right corner, then scan the QR code on your computer.&#x20;

<div><figure><img src="../../.gitbook/assets/image (475).png" alt=""><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (476).png" alt=""><figcaption></figcaption></figure></div>

3. After scanning, select **Log in** to proceed.&#x20;

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (477).png" alt="" width="375"><figcaption></figcaption></figure></div>

4. Enter the verification code from LINE.

* On your computer:

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (478).png" alt=""><figcaption></figcaption></figure></div>

* On your phone:

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (479).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
After sign-in, **Create Business ID**.&#x20;

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (481).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Input **Developer name**, **Your email** and tick the box of **LINE Developers Agreement**, then select **Create my account**.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (483).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Select **Create a new provider**.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (484).png" alt=""><figcaption></figcaption></figure></div>

* Enter **Provider name** and select **Create** to proceed.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (486).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}
{% endstepper %}

***

{% stepper %}
{% step %}
### Enable Messaging API

Select **Create a Messaging API** **channel** and then select **Create a LINE Official Account**.

{% hint style="info" %}
You will be redirected to the <mark style="background-color:orange;">LINE Official Account Manager</mark>. Please keep the <mark style="background-color:cyan;">LINE Developers</mark> page open in your current browser.
{% endhint %}

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (488).png" alt=""><figcaption></figcaption></figure></div>

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (430).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
In the <mark style="background-color:orange;">LINE Official Account Manager</mark> site, select **Verify by text message** to continue.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (492).png" alt="" width="563"><figcaption></figcaption></figure></div>

* Enter your phone number registered to your LINE account, then select **Send text message**. A verification code will be sent by SMS; enter the code and continue.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (493).png" alt="" width="563"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Enter the details for your LINE Official Account and select **Continue**. Then complete the LINE setup and select **Go to LINE Official Account Manager** to move to the next step.

<div><figure><img src="../../.gitbook/assets/image (434).png" alt=""><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (436).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
In <mark style="background-color:orange;">LINE Official Account Manager</mark>, select **Settings** in the top right corner.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (437).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
1. Select **Messaging API** from the left menu in **Settings**.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (438).png" alt=""><figcaption></figcaption></figure></div>

2. Select **Enable Messaging API** and turn it on for the official account.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (440).png" alt=""><figcaption></figcaption></figure></div>

3. Choose the provider you created, then confirm the setup.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (441).png" alt="" width="375"><figcaption></figcaption></figure></div>

4. (Optional) Enter Privacy Policy and Terms of Use, select **OK**.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (442).png" alt="" width="375"><figcaption></figcaption></figure></div>

5. Select **OK** to confirm and finish enabling the Messaging API.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (443).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}
{% endstepper %}

***

{% stepper %}
{% step %}
### Copy LINE credentials

Go back to the <mark style="background-color:cyan;">LINE Developers Console</mark> and open the Messaging API channel.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (446).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
In **Basic settings**, find **Channel secret** and copy it.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (447).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Paste that value into the **LINE Channel Secret** field in Chatlyst.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (404).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Next, go to **Messaging API** tab and find **Channel access token (long-lived)**.&#x20;

* Select **Issue**, then copy the token that is generated.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (448).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Paste that value into the **LINE Channel Access Token** field in Chatlyst, then select **Save**.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (403).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}
{% endstepper %}

***

{% stepper %}
{% step %}
### Configure webhook

In the <mark style="background-color:cyan;">LINE Developers Console</mark>, open the **Messaging API** tab for the channel.

* In **Webhook settings**, select **Edit**.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (408).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Enter this webhook URL: `https://chat-api.effex.co/line/` and select Update.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (405).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
**Verify** the webhook URL. A success message will appear if the verification is successful.

{% hint style="warning" %}
If the URL is unable to verify, please contact [Chatlyst Support](../../getting-started/home.md#chatlyst-support) for assistance.
{% endhint %}

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (406).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Turn on **Use webhook**.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (407).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}
{% endstepper %}

***

{% stepper %}
{% step %}
### Update response settings

Open the <mark style="background-color:orange;">LINE Official Account Manager</mark>, go to **Settings** → **Response settings**.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (453).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
1. Turn off **Auto-response messages**

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (400).png" alt=""><figcaption></figcaption></figure></div>

2. Then turn on **Webhook** and **Chat**.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (401).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
The LINE channel is set up and ready to use.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (414).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}
{% endstepper %}
