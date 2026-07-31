---
description: >-
  The customer panel shows key details about a contact in one place, including
  channel information, profile attributes, internal notes, and past
  conversations.
icon: sidebar
---

# Customer Panel

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (571).png" alt=""><figcaption></figcaption></figure></div>

**Primary Contact Details**: Basic customer information such as phone number or email, if available.

**Active Channel IDs**: The messaging channel linked to this customer.

**Custom Profile Fields**: extra attributes used to search, group, or organize customers. They include both manually defined custom attributes and system-generated attributes, such as inbound channel and last conversation ID.

**Customer Notes**: Internal notes for the team. These notes are not visible to customers.

**Recent Conversations**: Recent conversations show a list of the customer’s past and current conversations for quick reference. When a user selects a conversation from the list, Chatlyst opens the [Chat](../chat/chat.md) section and displays the full conversation so the user can review the complete history.

***

### Edit Customer Profile

{% stepper %}
{% step %}
Select **Edit Profile** on the right corner of the Customer Panel.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (553).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Chatlyst opens the **Edit Customer Profile** window.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (555).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
In this window, update the customer **Title**, **Full Name**, **Primary Email** and **Phone** number as needed.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (556).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Enter or update any custom attributes for the customer.&#x20;

* For attribute setup, see [Customer Attributes](../settings/customer-attributes.md).
* If **Auto‑Update Customer Attributes (AI)** is enabled, Chatlyst automatically parses customer interaction logs to extract and update attribute values at regular intervals. For more details, see [Auto‑Update Customer Attributes (AI)](../settings/customer-attributes.md#auto-update-customer-attributes).

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (557).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Select **Save** to apply the changes, or **Cancel** to discard.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (558).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}
{% endstepper %}

***

### Profile Actions

#### Link ID

Use Link ID to connect a new messaging channel token or identifier to the customer profile.

{% stepper %}
{% step %}
Select **Actions** → **Link ID**.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (559).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Chatlyst opens the **Link Channel Identity** window.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (560).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Select the **Channel Type** and enter the **Channel ID Value**.

<div><figure><img src="../.gitbook/assets/image (561).png" alt=""><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/image (563).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Select **Establish Link** to link the channel identity, or select **Cancel** to discard the action.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (564).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}
{% endstepper %}

#### Merge Profile

Use Merge Profile to combine the current customer profile with another customer profile.

{% stepper %}
{% step %}
Select **Actions** → **Merge Profile**.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (565).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Chatlyst opens the **Merge Customer Profile** window.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (566).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Search for the target customer profile by name, email, or phone number. As text is entered, matching profiles appear automatically.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (567).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Select the target profile to merge into.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (568).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Select **Confirm Merge & Delete Current Profile**.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (570).png" alt="" width="375"><figcaption></figcaption></figure></div>

{% hint style="warning" %}
**Important Note**: When the merge is confirmed, the current profile is deleted and its data is merged into the selected target profile. For example, if Profile A is the current profile and Profile B is the target profile, Profile A is deleted after the merge.
{% endhint %}
{% endstep %}
{% endstepper %}

***

### Customer Notes

#### Add Note

{% stepper %}
{% step %}
To add an internal note, select **Add Note**.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (572).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Enter a free-text note for the customer profile.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (573).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Select **Save** (or select **Cancel** to discard the action).

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (574).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
The saved note appears under **Customer Notes**. Users can also see **who created the note** and the **timestamp** for when it was added.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (575).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}
{% endstepper %}

#### Edit or Archive Note

{% stepper %}
{% step %}
To edit or archive an internal note, first select the note.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (576).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
* To edit the note, modify the existing text and select **Save**.&#x20;
* To archive the note, select **Archive** (or select **Cancel** to discard the action).

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (577).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}
{% endstepper %}
