---
description: >-
  This guide explains how to complete and manage the full process in the
  Training Area.
icon: dumbbell
---

# Train Documents

Training Area is the central place to process training after feedback is submitted during testing.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (503).png" alt=""><figcaption></figcaption></figure></div>

{% stepper %}
{% step %}
### Review Tickets or Add Manual Feedback

**Purpose:** Decide how to review and correct bot behaviour.

Review tickets in several ways:

* Use the [Status Filter](train-documents.md#status-filter) to narrow results.
* Select a ticket from [Ticket List](train-documents.md#ticket-list) for a focused review.
* Open the [Training Panel](train-documents.md#training-panel) to manage tickets in one place.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (504).png" alt=""><figcaption></figcaption></figure></div>

<details>

<summary>Status Filter</summary>

**Filter tickets by status**

* Select a status: **Pending, Training, Trained, Failed**.
* This opens the **Training Panel** and applies the same status filter automatically.
* Example: Selecting **Pending** updates the Training Panel to show only Pending tickets.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (142).png" alt=""><figcaption></figcaption></figure></div>

</details>

<details>

<summary>Ticket List</summary>

**Review individual tickets**

* Shows pending training tickets.
* Select a ticket to view details, then:
  * Review the **user question**.
  * Review the **bot answer**.
  * Review or edit the **training notes**.
  * Train the ticket when ready.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/Screenshot 2026-05-13 at 3.02.50 PM.png" alt="" width="375"><figcaption></figcaption></figure></div>

</details>

<details>

<summary>Training Panel</summary>

**Manage multiple tickets efficiently**

* Open and manage training tickets in one place.&#x20;
* Use status filters, review tickets, and train multiple tickets without switching views.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/Screenshot 2026-05-13 at 3.03.45 PM.png" alt="" width="563"><figcaption></figcaption></figure></div>

</details>

#### Add Manual Feedback (if needed)

**Purpose:** Create a new training ticket

1. Use when a correction is needed but no ticket exists yet.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (86).png" alt=""><figcaption></figcaption></figure></div>

2. Enter what needs to be corrected or improved, what the correct behaviour should be, and any supporting context. Select **Submit Training** to proceed.&#x20;

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (87).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
### Managing Tickets

1. Select **Open Training Panel**.

{% hint style="info" %}
The [Training Panel](train-documents.md#training-panel) is the **recommended** **place** to manage training, especially when multiple tickets need to be processed.
{% endhint %}

<div><figure><img src="../.gitbook/assets/image (88).png" alt="" width="563"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/Screenshot 2026-05-13 at 3.12.26 PM.png" alt="" width="563"><figcaption></figcaption></figure></div>

2.  **Filter tickets by Status and Document Type**

    * Use the Status filter to narrow the ticket list before training.
    * Use the Document Type filter to show only uploaded Business Knowledge documents.
    * [Training feedback](training-feedback.md) submitted here is linked to these documents for training and review.

    <div data-with-frame="true"><img src="../.gitbook/assets/attachment6029fe19 75f8 4838 bb81 0e481838dd2fimage (2).png" alt=""></div>
3. **Understand Ticket Status**

<table><thead><tr><th width="136.6953125">Status</th><th>Meaning</th></tr></thead><tbody><tr><td><mark style="color:yellow;">Pending</mark></td><td>Training tickets that still need to be addressed.</td></tr><tr><td><mark style="color:blue;">Training</mark></td><td>Tickets currently being processed.</td></tr><tr><td><mark style="color:$success;">Trained</mark></td><td>Tickets and documents that have been successfully trained.</td></tr><tr><td><mark style="color:$danger;">Failed</mark></td><td>Tickets that failed to train (rare).</td></tr></tbody></table>

4. **Pending Tickets and Related Document Types**
   * **Choose what to train now**
     * Under Status, select **Pending**.
     * Under Document Type, choose the relevant document types.
       * Example: **Company Brand Identity (1 feedback)** and **Ticket Handling Sop (5 feedbacks)**
     * When **All** is selected under Document Type, the number next to Status shows the total of all pending feedback (for example, 6 = 1 + 5).
       * If only **Company Brand Identity** is selected, the count shows 1.
       * If only **Ticket Handling Sop** is selected, the count shows 5.

<div><figure><img src="../.gitbook/assets/image (143).png" alt=""><figcaption><p>All</p></figcaption></figure> <figure><img src="../.gitbook/assets/image (144).png" alt=""><figcaption><p>Company Brand Identity</p></figcaption></figure> <figure><img src="../.gitbook/assets/image (145).png" alt=""><figcaption><p>Ticket Handling Sop</p></figcaption></figure></div>
{% endstep %}

{% step %}
### [Training Note Handling](training-note-handling.md)

**Purpose:** Decide how to process the selected tickets.

There are two types of Training Note Handling. Choose either the [bulk-train](training-note-handling.md#bulk-train-operation) or [single-train](training-note-handling.md#single-train-operation) operation based on&#x20;

1. How many tickets need to be processed.
2. How closely each ticket needs to be reviewed.&#x20;

In this example, bulk‑train is used because the tickets can be processed as a group.

{% hint style="info" %}
Follow more on [Training Note Handling](training-note-handling.md).
{% endhint %}

#### Bulk-train operation

1. Select **Train Now** in the top-right of the Training Panel.

<div data-with-frame="true"><img src="../.gitbook/assets/attachment5fda8d1b b955 4826 ab49 5365c797359eimage (2).png" alt=""></div>

2. In the training window, review the list and confirm the correct Status (for example, Pending) and Document Types are selected.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (89).png" alt="" width="375"><figcaption></figcaption></figure></div>

3. Select the tickets to train:
   * Select **Select All**, or
   * Select tickets individually using the checkbox on each row.

{% hint style="info" %}
Adjust document type selection if needed.

![](<../.gitbook/assets/image (44).png>)
{% endhint %}

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (90).png" alt="" width="375"><figcaption></figcaption></figure></div>

4. Select **Train X Selected Tickets** (for example, **Train 6 Selected Tickets**) to proceed.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (91).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
### [Training Method](train-documents.md#training-method)

**Purpose:** Choose how the documents will be trained.

There are two methods you can use to train documents. Choose either the [Send to KC Bot Training (Recommended)](training-method.md#send-to-kc-bot-training) or [Manual Training](training-method.md#manual-training). Follow more on [Training Method](training-method.md).

In this example, **Send to KC Bot Training** is used because it updates Business Knowledge in a guided and consistent way and reduces the risk of training the wrong document or adding unintended wording.

#### Confirm Processing with KC Bot

1. Review the summary, including KC Bot Credits and Document Types.
2. Select **Confirm & Process** to start processing.

<div align="center" data-with-frame="true"><img src="../.gitbook/assets/attachmentd3025a5a ec55 4053 aaac 076a9e754cdbimage (2).png" alt="" width="375"></div>

{% hint style="warning" %}
**Important Note**: KC Bot Credit is short for Knowledge Consolidation Bot Credit. These credits are used when processing training for Business Knowledge documents. How are they charged? KC Bot Credits are calculated based on the number of document types in the training batch, not the number of tickets selected. If multiple tickets link to the same document type, it still counts as one document type for credit usage. For example, 10 tickets for ONE document type consumes 1 KC Bot Credit. 30 tickets across FIVE document types consumes 5 KC Bot Credits.
{% endhint %}
{% endstep %}

{% step %}
### Complete Training

Select **Finish & Exit** to close the training window.

<div align="center" data-with-frame="true"><img src="../.gitbook/assets/attachmente704bbbb c27b 4cbd 86fd d9e98339b043image (4).png" alt="" width="375"></div>
{% endstep %}
{% endstepper %}

***

## Manual Feedback

{% stepper %}
{% step %}
Use **Add Manual Feedback** when a correction is needed but no ticket was created during testing.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (93).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
After selecting Add Manual Feedback, enter the details, select the related document, then select **Submit Training**.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (94).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
After submission, a new Pending ticket is added to the Training Panel. Review it, then train using [single training](training-note-handling.md#single-train-operation).
{% endstep %}
{% endstepper %}
