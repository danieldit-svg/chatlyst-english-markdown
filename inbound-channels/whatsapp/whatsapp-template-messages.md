---
description: >-
  This guide provides instructions on how to create, manage, and send WhatsApp
  Template Messages using Chatlyst.
icon: message-lines
---

# WhatsApp Template Messages

A template message is a pre-approved message format used to communicate with customers. WhatsApp enforces a 24-hour messaging rule: standard messages cannot be sent to a customer if they have not replied within the last 24 hours. However, approved templates bypass this rule and can be sent at any time.

### Manage Your Templates

The template dashboard is the central location to create, organize, and manage WhatsApp message templates.

**Prerequisite**: The template dashboard becomes available only after a WhatsApp account is successfully connected to Chatlyst. Follow more on [connect-by-linking-into-an-existing-whatsapp-business-app.md](connect-by-linking-into-an-existing-whatsapp-business-app.md "mention") or [connect-by-creating-a-whatsapp-business-account.md](connect-by-creating-a-whatsapp-business-account.md "mention").

#### Accessing the Dashboard

To locate the template dashboard, follow this:

{% stepper %}
{% step %}
From [Inbound Channel](https://app.gitbook.com/s/BW7n4ClAhZvbgvusylCd/inbound-channels), select **Configure.**

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (636).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Scroll to the bottom of the page to locate the template dashboard.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (691).png" alt="" width="563"><figcaption></figcaption></figure></div>
{% endstep %}
{% endstepper %}

#### Dashboard Features

<details>

<summary><strong>Create Template</strong></summary>

Select this option to build a new template message layout from the beginning.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (692).png" alt="" width="563"><figcaption></figcaption></figure></div>

</details>

<details>

<summary><strong>Sync Templates</strong></summary>

Select this option to refresh the Chatlyst system.&#x20;

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (693).png" alt="" width="563"><figcaption></figcaption></figure></div>

</details>

<details>

<summary><strong>Delete Templates</strong></summary>

Select the **bin icon** next to a specific template to remove it from the system.&#x20;

{% hint style="warning" %}
Deleting a template is a permanent action and cannot be reversed. Ensure the template is no longer needed before proceeding.
{% endhint %}

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (694).png" alt="" width="563"><figcaption></figcaption></figure></div>

</details>

<details>

<summary><strong>Preview Templates</strong></summary>

* Select the **down arrow icon** next to a specific template. This expands the view to display the existing template details.&#x20;

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (695).png" alt="" width="563"><figcaption></figcaption></figure></div>

* From here, adjust the Parameter Mapping if necessary, and select **Save Mapping** to apply any changes.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (700).png" alt="" width="563"><figcaption></figcaption></figure></div>

</details>

<details>

<summary><strong>Navigation</strong></summary>

The dashboard displays all templates in a list format. If the list spans multiple pages, use the page indicators located at the bottom of the screen (for example, 1 / 2) to move between pages.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (697).png" alt="" width="563"><figcaption></figcaption></figure></div>

</details>

### Understanding Template Parameters

A **parameter** (also known as a variable) is a placeholder within a template. Instead of writing a generic message like "Hello Customer," parameters allow the system to automatically insert specific details, such as "Hello John," by pulling information from the customer's profile.

There are two types of parameters used in Chatlyst:

1. **Positional parameters:** Represented by numbers enclosed in double curly brackets. These always start with the number 1.
   * _Example:_ `{{1}}`, `{{2}}`
2. **Named parameters:** Represented by descriptive words, using lowercase letters and underscores instead of spaces.
   * _Example:_ `{{customer_name}}`, `{{order_id}}`

### Mapping Parameters to Customer Data

To ensure the correct information is inserted into the message, each parameter must be mapped (connected) to a specific data field in the customer's profile. When [creating a template](whatsapp-template-messages.md#create-a-template), use the dropdown menu next to each parameter to select the correct data source.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (690).png" alt="" width="563"><figcaption></figcaption></figure></div>

| **Standard Fields**   | Standard, built-in properties that apply to most contacts (e.g., Customer Name, Customer Email, Customer Phone Number).                                      | Select the matching standard property directly from the dropdown list.                                                                                            |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Custom Attributes** | Unique, user-defined properties stored in the customer's Customer Relationship Management profile (e.g., Company Name, Membership Tier, Preferred Language). | Select the specific custom attribute from the dropdown list. For more context follow on [**Settings → Custom Attribute**](../../settings/customer-attributes.md). |

***

### Create a Template

Before you create, it is important to understand the required formatting rules. Chatlyst connects to WhatsApp, which is owned by Meta. Meta must review and approve all templates before they can be sent to customers.

#### Template Formatting Rules

To ensure a template is successfully approved by Meta, the message content must follow these specific guidelines:

1. **Parameter Placement**: A parameter is a placeholder used to automatically insert customer details, such as a name or order number, into the message. A parameter cannot be placed at the very beginning or at the very end of a message.
   * _Incorrect Example:_ `{{test}} This is a message. {{test}}`
   * _Correct Example:_ `Hello {{test}}, here is your message.`
2. **Character Limit**: The total length of the message body must not exceed 1,024 characters. This limit includes all letters, numbers, spaces, punctuation marks, and the text used for placeholders.
3. **Text-to-Parameter Ratio**: The message must contain enough standard, readable text to provide clear context for the placeholders. The ratio of standard words to parameter placeholders must meet Meta's internal standards. Avoid creating templates that consist mostly of parameters with very few regular words.

{% stepper %}
{% step %}
Select **Create Template**.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (655).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Chatlyst will prompt the window of **Create WhatsApp Template**. Enter a **Template Name**.&#x20;

{% hint style="info" %}
Use only lowercase letters, numbers, and underscores (no spaces or special characters).
{% endhint %}

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (661).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Select the **Language**.

{% hint style="warning" %}
The selected language must match the language used in the message body. If English is selected, the message must be written in English; otherwise, Meta will reject the template.
{% endhint %}

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (662).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Marketing is the only **Category** available.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (663).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Enter the **Body Message Text**.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (664).png" alt="" width="375"><figcaption></figcaption></figure></div>

1. Type the standard text.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (671).png" alt="" width="375"><figcaption></figcaption></figure></div>

2. Insert parameters using the `{{}}` format to map customer information. Parameters can be set as Free Text (Enter when sending), Standard Fields, or Custom Attributes.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (672).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Enter **Meta Review Examples** for every parameter used.

{% hint style="warning" %}
This is a strict requirement. Provide a realistic example of what the parameter will look like to help the reviewer understand the context (e.g., if the parameter is an email address, use an example like user@domain.com).
{% endhint %}

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (673).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Select **Create & Submit**.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (674).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
The newly created template will appear on the dashboard with a **Pending** status while it awaits Meta's review. Once reviewed and accepted, the status will update to **Approved**.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (699).png" alt="" width="563"><figcaption></figcaption></figure></div>
{% endstep %}
{% endstepper %}

***

### Send a Template

Templates can be sent directly from the [Chat](https://app.gitbook.com/s/BW7n4ClAhZvbgvusylCd/chat) section when communicating with a WhatsApp customer. This works whether the conversation is inside or outside the 24-hour messaging window.

{% hint style="info" %}
Templates cannot be sent if the conversation is marked as **CLOSED** in the system.
{% endhint %}

{% stepper %}
{% step %}
Open the customer conversation (WhatsApp).

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (681).png" alt="" width="563"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Locate the input field.&#x20;

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (682).png" alt="" width="563"><figcaption></figcaption></figure></div>

* If the last customer message was sent over 24 hours ago, a prompt will appear indicating the need to use a template in the input field.&#x20;

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (679).png" alt="" width="563"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Select the **Send WhatsApp Template Message**. A prompt window will appear.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (683).png" alt="" width="563"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Select the template from the list.

1. If the template **does not include Free Text parameters**.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (685).png" alt="" width="375"><figcaption></figcaption></figure></div>

2. If the selected template **includes Free Text parameters**, a system reminder will appear instructing the user to fill in these fields before sending. The specific parameter input fields will display at the bottom of the prompt window. Type the necessary information directly into these fields.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (686).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Preview the message.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (687).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Select **Send Template**.

{% hint style="info" %}
For detailed pricing, please visit [Pricing on the WhatsApp Business Platform](https://developers.facebook.com/documentation/business-messaging/whatsapp/pricing).
{% endhint %}

<figure><img src="../../.gitbook/assets/image (688).png" alt="" width="375"><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

***

### Meta Payment Settings Configuration

To use WhatsApp Template Messages seamlessly, the connected WhatsApp Business Account must have a valid credit card on file for template billing.

{% stepper %}
{% step %}
Log in to the [Meta Business Suite](https://business.facebook.com/business/loginpage/?next=https%3A%2F%2Fbusiness.facebook.com%2F%3Fnav_ref%3Dbiz_unified_f3_login_page_to_mbs\&login_options%5B0%5D=FB\&login_options%5B1%5D=IG\&login_options%5B2%5D=SSO\&config_ref=biz_login_tool_flavor_mbs) and go to **Settings**.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (657).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Under the **Account** section, select **WhatsApp accounts**.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (659).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Go to **Payment Settings**.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (660).png" alt="" width="563"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Select **Add Payment Method** and follow the guided on-screen instructions provided by the Meta. For detailed pricing, please visit [Pricing on the WhatsApp Business Platform](https://developers.facebook.com/documentation/business-messaging/whatsapp/pricing).

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (678).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}
{% endstepper %}
