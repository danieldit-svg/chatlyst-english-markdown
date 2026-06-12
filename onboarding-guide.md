---
icon: plane-departure
---

# Onboarding Guide

### 1. Overview <a href="#id-1-overview" id="id-1-overview"></a>

This guide helps you set up Chatlyst end-to-end by:

* Creating your account and logging in
* Uploading and maintaining Business Knowledge
* Testing and improving bot responses
* Connecting inbound channels (starting with Website Embed)
* Running day-to-day chat operations

By the end, you’ll be able to keep knowledge accurate, monitor performance, and handle live conversations confidently.

***

### 2. Get Started: Account & Navigation

{% stepper %}
{% step %}
#### Create your Chatlyst account

1. Go to  [https://chatlyst.io/](https://chatlyst.io/) and select **Try for Free** to [create account](getting-started/create-account.md).
2. Sign up using email (follow the password requirements) or Google/Facebook sign-in.
3. Enter your **company details**.
   * This creates your company workspace, where you’ll manage knowledge, widgets, conversations, and credits.
{% endstep %}

{% step %}
#### Log in and learn the Home layout&#x20;

1. Go to  [https://chatlyst.io/](https://chatlyst.io/) and select [**Log in**](getting-started/log-in.md).
2. Sign in using your email/password or Google/Facebook.
3. Confirm you land on the **Home** page.
4. On [Home](getting-started/home.md), use the left sidebar to move between sections, and note that the main content updates based on the section you select. Make sure you know where to find Notifications, Usage Details, Settings, and Logout.
{% endstep %}
{% endstepper %}

***

### 3. [Business Knowledge](https://app.gitbook.com/s/BW7n4ClAhZvbgvusylCd/business-knowledge): Build a Reliable Source of Truth <a href="#id-3-business-knowledge-build-a-reliable-source-of-tr" id="id-3-business-knowledge-build-a-reliable-source-of-tr"></a>

{% stepper %}
{% step %}
#### Upload the three must-have core documents

1. **Company & Brand Identity**
   * What the bot should say about your company, brand, tone, and positioning.
2. **Ticket Handling Policy & SOP**
   * What the bot is allowed to do/say, escalation rules, and how to handle sensitive scenarios.
3. **Standard FAQ**
   * Your approved answers to common customer questions.

You can:

* Download the [templates](business-knowledge/core-knowledge.md), fill them with your current information, then upload.
* Or upload existing internal docs (if they are clear, complete, and easy for an outsider to understand). Alternatively, you can use the [Auto-fill](business-knowledge/auto-fill.md) option to populate the template **automatically** and complete the work faster when manual editing is not necessary.

These documents drive:

* **Accuracy** – what the bot says about your company
* **Behavior** – how the bot behaves, when to escalate, and what is off-limits

If documents are missing, outdated, or vague, expect more incorrect answers and repeated training tickets later.

{% hint style="info" %}
Use [**Train Document**](train-and-test-bot/train-documents.md) to update remain consistent and traceable.
{% endhint %}
{% endstep %}

{% step %}
#### Add supporting “Additional Documents”

Use [**Additional Documents**](business-knowledge/additional-documents.md) for:

* Edge cases (special workflows, niche products, region-specific rules)
* Detailed process docs that support but do not replace the Core Knowledge.&#x20;

{% hint style="info" %}
Keep titles descriptive so you can quickly select the right document when training.
{% endhint %}
{% endstep %}

{% step %}
#### Manage document health

In [**Business Knowledge**](business-knowledge/document-management.md), review each document’s status:

* **Light green** – content is current; not waiting on training items; safe to rely on.
* **Light yellow** – unresolved tickets/changes; review before expecting consistent answers.

For each document:

1. Use the expand menu on a row to open **Document Details**.
2. Confirm document type, last update, and why it is flagged.
3. When there are pending tickets, use **Train Document**.

{% hint style="info" %}
Use **KC Bot** to train Business Knowledge in a guided, consistent way and reduce the risk of training the wrong document or adding unintended wording.
{% endhint %}
{% endstep %}
{% endstepper %}

***

### 4. [Train & Test bot](https://app.gitbook.com/s/BW7n4ClAhZvbgvusylCd/train-and-test-bot): Make the Bot Safe and Accurate <a href="#id-4-train--test-make-the-bot-safe-and-accurate" id="id-4-train--test-make-the-bot-safe-and-accurate"></a>

{% stepper %}
{% step %}
#### Test your bot in Train & Test

Once Business Knowledge is uploaded:

1. Open **Train & Test bot**.
2. Start a test chat using:
   * [**Widget Preview**](train-and-test-bot/train-and-test-bot.md#preview-tab) or [**Streaming Mode**](train-and-test-bot/train-and-test-bot.md#preview-tab) (choose the mode closest to your real use-case).
3. Use [**New Chat**](train-and-test-bot/train-and-test-bot.md#new-chat) to reset the test thread whenever you need a clean slate.

Use this area to validate:

* Response accuracy and policy alignment
* Knowledge gaps or outdated information
* Tone and clarity
* Edge cases, unusual customer scenarios, risky topics

{% hint style="info" %}
Train & Test is isolated from production, so it won’t affect live customers.
{% endhint %}
{% endstep %}

{% step %}
#### Improve responses with [training feedback](train-and-test-bot/training-feedback.md)

While testing (or later, while reviewing real bot replies):

* Use **thumbs up** when an answer is correct.
* Use **thumbs down** when an answer is wrong, incomplete, off-tone, or follows the wrong process.

When submitting **negative feedback**, always:

1. State what is incorrect.
2. State what is missing.
3. Provide the correct answer (include exact wording, constraints, and required steps).
4. Select the most relevant document(s) to train.
5. Submit the ticket.

{% hint style="info" %}
This creates a traceable record, routes fixes to the right Business Knowledge, and reduces repeat mistakes over time.
{% endhint %}
{% endstep %}

{% step %}
#### [Train Documents](train-and-test-bot/train-documents.md)

To process tickets:

1. Open the **Training Panel**.
2. Filter tickets by **Status** and by **Document Type**.
3. Confirm scope:
   * Document type matches what you expected
   * Ticket count looks reasonable
   * Spot-check a few tickets to confirm consistency

Choose the right processing approach:

* [**Bulk-train**](train-and-test-bot/training-note-handling.md#bulk-train-operation)
  * When tickets are straightforward, clearly correct, and consistent.
* [**Single-train**](train-and-test-bot/training-note-handling.md#single-train-operation)
  * When tickets are nuanced, mixed-topic, or when you want to verify wording, constraints, or the target document before applying changes.

Choose the training method:

* Prefer [**Send to KC Bot Training**](train-and-test-bot/training-method.md#send-to-kc-bot-training) for guided, consistent updates and lower risk of training the wrong document or introducing unwanted wording.

If you spot a mistake after submitting a ticket:

* Use [**Edit Training Note**](train-and-test-bot/edit-training-note.md) to correct or clarify the note.
* Use **History** to audit behavior over time, spot recurring patterns, and feed back new training based on real examples.
{% endstep %}
{% endstepper %}

***

### 5. [Inbound Channels](https://app.gitbook.com/s/BW7n4ClAhZvbgvusylCd/inbound-channels): Go Live <a href="#id-5-inbound-channels-go-live-safely" id="id-5-inbound-channels-go-live-safely"></a>

{% stepper %}
{% step %}
#### Set up inbound channels (start with Website Embed)

1. Open **Inbound Channels**.
2. Review the supported channels.
3. For most rollouts, start with [**Website Embed**](inbound-channels/inbound-channels.md) to get a widget live quickly.
{% endstep %}

{% step %}
#### [Create, configure, and activate widgets](inbound-channels/website-embed/add-a-widget.md)

In **Website Embed**:

1. Select **Add Widget**.
2. Configure each section and watch the live preview:
   * [**Appearance**](inbound-channels/website-embed/add-a-widget.md#appearance) – branding, colors, widget look.
   * [**Behavior**](inbound-channels/website-embed/add-a-widget.md#behavior) – bot behavior, messaging, entry points.
   * [**Advanced**](inbound-channels/website-embed/add-a-widget.md#advanced) – any advanced options your rollout needs.
3. To edit an existing widget, select it and choose [**Configure**](inbound-channels/website-embed/configure-a-widget.md).

Use [**Preview Widget**](inbound-channels/website-embed/configure-a-widget.md#preview-widget) carefully:

* Preview messages are **live** and will appear in [**Chat**](https://app.gitbook.com/s/BW7n4ClAhZvbgvusylCd/chat) as real conversations.
* Avoid real customer information.
* Clearly label any test messages.
* Clean up test threads so they do not confuse daily operations.
{% endstep %}

{% step %}
#### Get ready for live tickets

You are ready to handle real conversations when:

* [ ] [**Business Knowledge**](https://app.gitbook.com/s/BW7n4ClAhZvbgvusylCd/business-knowledge) is uploaded and reasonably healthy (few or no yellow flags).
* [ ] Key scenarios have been tested in [**Train & Test bot**](https://app.gitbook.com/s/BW7n4ClAhZvbgvusylCd/train-and-test-bot).
* [ ] Your widget is live via [**Website Embed**](inbound-channels/website-embed/) (or another channel).

During the first weeks:

* [Monitor](https://app.gitbook.com/s/BW7n4ClAhZvbgvusylCd/dashboard) live conversations regularly.
* Let the bot handle the first response whenever possible.
* [Review conversations](chat/conversation-panel.md) periodically and submit [training feedback](chat/conversation-panel.md#provide-training-feedback) to improve accuracy and efficiency.
* [Step in](chat/conversation-panel.md#join-a-conversation) when escalation or human handling is required.
* Keep [Business Knowledge updated](business-knowledge/document-management.md#train-document) so live answers remain consistent over time.
{% endstep %}
{% endstepper %}

***

### 6. [Chat Operations](https://app.gitbook.com/s/BW7n4ClAhZvbgvusylCd/chat): Day-to-Day Work <a href="#id-6-chat-operations-day-to-day-work" id="id-6-chat-operations-day-to-day-work"></a>

{% stepper %}
{% step %}
#### Learn Chat basics: find, filter, and read conversations

Open **Chat** and get familiar with:

* [**Thread List**](chat/thread-list.md) (left): all conversations.
* [**Conversation Panel**](chat/conversation-panel.md) (right): full message history and reply area.

Practice:

1. Click through several threads and confirm the Conversation Panel updates immediately.
2. Use filters to work efficiently:
   * [**Search**](chat/thread-list.md#find-a-conversation) – find keywords/topics across many threads.
   * [**Conversation Labels**](chat/labels-and-statuses.md#conversation-labels) – narrow by category.
   * [**Status Filters**](chat/thread-list.md#status-filters) – separate items needing action now from resolved items.
   * [**Date Range**](chat/thread-list.md#date-range) – review a specific time window.

If threads “disappear,” check active filters—especially **Date Range**, which stays on until you turn it off.
{% endstep %}

{% step %}
#### Join a conversation and respond

In the [**Conversation Panel**](chat/conversation-panel.md):

1. Confirm the conversation **Status**.
2. Join the thread if applicable.
3. Before replying:
   * Scan the most recent messages.
   * Make sure your answer addresses the latest question.
   * Match the existing context and avoid repeating information unnecessarily.
4. Use [**Additional Options**](chat/additional-options-by-status.md) only when they match your intended outcome (e.g., escalation, closure).

{% hint style="info" %}
Important: **Closed conversations cannot be reopened**. Only close when the issue is fully resolved and no follow-up is expected.
{% endhint %}
{% endstep %}

{% step %}
#### Use Dashboard to monitor live work and performance

Open [**Dashboard**](dashboard/dashboard.md) and focus on three areas:

* [**Live Tickets**](dashboard/dashboard.md#live-tickets)
  * Look for Pending First Response, long-waiting threads, or spikes in new tickets.
* [**Feedback & Response**](dashboard/dashboard.md#feedback-and-response)
  * Watch thumbs up/down trends and recent feedback.
* [**Performance Metrics**](dashboard/dashboard.md#performance-metrics)
  * Compare time windows and validate whether changes (training, new documents, process tweaks) actually improved outcomes.
{% endstep %}
{% endstepper %}

***

### 7. Credits: Keep Training and Responses Running <a href="#id-7-credits-keep-training-and-responses-running" id="id-7-credits-keep-training-and-responses-running"></a>

#### Top up credits and understand credit types <a href="#id-71-top-up-credits-and-understand-credit-types" id="id-71-top-up-credits-and-understand-credit-types"></a>

Use [**Top Up**](top-up-guideline/top-up-guideline.md) when credits are low so training and live operations do not stall.

Know the two credit types:

* **Knowledge Consolidation Bot Credits (KC Bot)**
  * Used to train and update Business Knowledge (consolidate new information and apply training tickets).
* **AI Response Credits**
  * Used for bot responses and testing (Train & Test and bot-generated replies).

Keep both types healthy to avoid:

* Delays in training
* Interruptions in bot responses during tests or live conversations

If you are a **team member**:

* Notify an admin as soon as you [notice credits running low](getting-started/home.md#usage-details) so they can approve and complete the top-up before operations are impacted.

If you are an **admin**:

* [Review credit](getting-started/home.md#usage-details) usage regularly.
* Monitor [Usage](dashboard/usage.md) and [Trends](dashboard/usage.md#trends) over time.
* Top up proactively—especially before:
  * Major knowledge updates
  * Onboarding waves
  * High-traffic periods or campaigns

***

### 8. Recommended First-Day Checklist <a href="#id-8-recommended-first-day-checklist" id="id-8-recommended-first-day-checklist"></a>

Use this as a quick recap:

* [ ] Create your account and confirm you can log in.
* [ ] Upload **Company & Brand Identity** and **Ticket Handling Policy & SOP**.
* [ ] Add any high-priority **Additional Documents**.
* [ ] Run core scenarios in **Train & Test** and submit training feedback where needed.
* [ ] Set up one **Website Embed** widget and confirm it appears on your site.
* [ ] Open **Chat**, explore filters, and respond to at least one test thread.
* [ ] Check **Dashboard** once to see Live Tickets and Feedback.
* [ ] Confirm your **KC Bot** and **AI Response** credits are sufficient.
