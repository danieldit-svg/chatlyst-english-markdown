---
description: >-
  Customer attributes are predefined keys used to store tenant-specific customer
  data. Customers can only be assigned values for attributes that have already
  been created.
icon: creative-commons-by
---

# Customer Attributes

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (585).png" alt=""><figcaption></figcaption></figure></div>

### Create Custom Attributes

{% stepper %}
{% step %}
Select **+ Add Attribute**.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (586).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Chatlyst opens the **Predefine Customer Attribute** window.



<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (571).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Enter the **Display Name** of the attribute. The **Attribute Key** is generated automatically as you type.&#x20;

* Attribute Keys support only lower‑case alphanumeric characters, underscores, and hyphens. The key is always saved in lower‑case.

{% hint style="info" %}
It is recommended to use the automatically generated **Attribute Key**. Do not enter the key manually, as the system-generated key is more consistent and less error‑prone.&#x20;
{% endhint %}

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (572).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Select a **Data Type**: **String (Text)** or **Number**.

{% hint style="info" %}
**Data type behavior**

* **String (Text)**: Use this type for text-based values.
* **Number**: Use this type for numeric values.
* The selected data type controls how the attribute can be filtered later. For more information, see [Filters](../customers/customer-list.md#filters).
{% endhint %}

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (573).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Enter **Description** for the attribute.&#x20;

{% hint style="info" %}
Chatlyst uses this description to auto-fetch relevant information from customer conversations and consolidate it into the attribute value. If there are limits or conditions for how this attribute should be interpreted, add them in square brackets **\[a, b and c]** at the end of the description to keep the fetched data accurate. For more information, see [Auto-Update Customer Attributes](customer-attributes.md#auto-update-customer-attributes).

![](<../.gitbook/assets/image (516).png>)
{% endhint %}

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (574).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Select **Create Attribute** to save it, or **Cancel** to discard it.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (592).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}
{% endstepper %}

***

### Attributes Management

#### Edit Custom Attributes <a href="#edit-custom-attributes" id="edit-custom-attributes"></a>

{% stepper %}
{% step %}
Select the attribute from the list, then select the **pencil icon** next to the attribute you want to edit.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (576).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Chatlyst opens the **Edit Customer Attribute** window. Update the **Display Name** and **Description** as needed.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (577).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Select **Save** **Changes** to apply the update, or **Cancel** to discard it.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (591).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}
{% endstepper %}

### Remove Custom Attributes <a href="#remove-custom-attributes" id="remove-custom-attributes"></a>

{% stepper %}
{% step %}
Select the attribute from the list, then select the **bin icon** next to the attribute you want to remove.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (579).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Chatlyst shows a confirmation message asking you to confirm deletion. Select **OK** to remove the attribute, or **Cancel** to keep it.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (515).png" alt=""><figcaption></figcaption></figure></div>

{% hint style="info" %}
**Deleted custom attributes:** If a custom attribute is deleted, it remains on any customers who already had that attribute applied. If you need to remove it from existing customers, contact [Chatlyst Support](../getting-started/home.md#chatlyst-support) for assistance.
{% endhint %}
{% endstep %}
{% endstepper %}

### Auto-Update Customer Attributes (AI)

Chatlyst can automatically parse customer interaction logs to extract and update attribute values at regular intervals. When a custom attribute’s **description is detailed and specific**, Chatlyst uses it as a reference to auto‑fetch relevant information from customer conversations and consolidate it into the attribute value.

This helps reduce manual data entry and human error when updating customer profiles. Because most conversations mention the customer’s name and basic contact details, auto‑update also helps avoid anonymous records in the Chat section and improves overall management of customer profiles.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (588).png" alt=""><figcaption></figcaption></figure></div>

#### Update Frequency Settings

Users can set the auto‑fill update frequency for custom attributes to run every 3, 6, or 9 hours, depending on preference.

If **Auto‑Update Customer Attributes** is enabled, it consumes an additional AI Response credit per message. For example, a standard bot reply consumes 1 AI Response credit; with Auto‑Update Customer Attributes enabled, the same interaction consumes 2 credits (one for the bot response and one for the attribute update).

{% hint style="info" %}
There is **no extra charge** tied directly to the chosen update interval. Setting the update to run every 3 hours does **not** mean credits are charged automatically every 3 hours.
{% endhint %}

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (589).png" alt=""><figcaption></figcaption></figure></div>

{% hint style="warning" %}
**Important Note**: If the business requires more frequent updates or a specific time frame that is not covered by the default options, contact [Chatlyst Support](../getting-started/home.md#chatlyst-support) for assistance..
{% endhint %}

#### How it works (example) <a href="#how-it-works-example" id="how-it-works-example"></a>

{% stepper %}
{% step %}
A custom attribute is predefined: **preferred language** and Update Frequency is set to **Every 3 Hours**.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (590).png" alt="" width="563"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
During a conversation, Chatlyst asks for basic information, including **name**, **phone number**, **email**, and **preferred language**.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (1).png" alt="" width="563"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
In the current customer profile, these fields are initially empty.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (2).png" alt="" width="563"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
After the next scheduled auto‑update runs, Chatlyst scans the conversation, detects the information, and updates the profile automatically:

* **Name** is set to **Alan**.
* **Email** is set to **alan@demo.com**.
* **Phone number** is set to **98765432**.
* **Custom Profile Fields** automatically add **preferred language** and fill it with the provided value **English**.
* **Customer Notes** are also updated with a summary of the conversation to support better follow‑up.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (3).png" alt="" width="563"><figcaption></figcaption></figure></div>
{% endstep %}
{% endstepper %}

