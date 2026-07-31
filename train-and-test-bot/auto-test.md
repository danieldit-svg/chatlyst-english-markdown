---
description: >-
  Auto Test lets you run realistic, automated chat simulations so you can see
  how your bot behaves before going live.
icon: microchip-ai
---

# Auto Test

Auto Test runs a fully automated dialogue between your bot and a simulated user, based on a persona, scenario, and language that you configure. It is designed to:

* Check how your bot responds in common and edge-case situations.
* Confirm tone of voice and policy compliance.
* Identify gaps in Business Knowledge or training before production.

### Before You Start

Make sure:

* The bot has enough [Business Knowledge](../business-knowledge/business-knowledge.md) and training so the test reflects real behavior.
* You have sufficient [AI response credits](https://app.gitbook.com/s/BW7n4ClAhZvbgvusylCd/top-up-guideline) for the planned number of messages.

{% hint style="info" %}
Start with shorter simulations (fewer messages) to quickly spot obvious issues, then increase Max Messages once the bot is stable.
{% endhint %}

### Run an Auto Test

{% stepper %}
{% step %}
Choose the **widget** you want to test.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (626).png" alt="" width="563"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Select **Auto Test**.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (627).png" alt="" width="563"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Chatlyst will open the Auto Test Bot Simulation window, where you can configure the simulated user.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (612).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Set up the test **Persona**.

* Define who the simulated user is.&#x20;

<details>

<summary>Chatlyst offers preset personas to choose from, so you can match your real audience and evaluate tone and answers properly. Persona including:</summary>

* **Impatient & Direct** (Busy, values efficiency and speed)
* **Chatty & Unfocused** (Talks a lot, details-heavy, slow to get to point)
* **Skeptical & Suspicious** (Inherent distrust of Al, corporate lines)
* **Short & Casual** (Fast-paced, mobile user, brief replies)
* **Simple Vocabulary** (Polite, basic words and simple sentences)

</details>

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (613).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Define the **Scenario**.

* Select a scenario example that matches the situation you want to test.&#x20;

{% hint style="info" %}
The scenario acts like a script prompt, guiding the simulated user’s behavior in the conversation. Scenarios cover common customer enquiries across different industries, such as E‑Commerce, SaaS, services, and general questions.
{% endhint %}

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (614).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Choose the **Language**.

* Select the language the simulated user will use, such as English, Traditional Chinese, or another supported language.&#x20;

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (615).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Set **Max Messages.**

1. Select the maximum number of messages for the simulation.&#x20;
2. Select **Next** to proceed.

{% hint style="info" %}
**Per-Response Charges**: AI Response Credits are deducted for each individual response generated.

Use Max Messages to control:

* How long the conversation runs.
* How detailed or deep the scenario exploration should be.
{% endhint %}

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (617).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Before the test begins, a **Confirm Credits Usage** window will appear to help monitor the account balance. Review the following details on this screen:

**Estimated AI response credits to be consumed**: The projected number of credits the system expects to use during the test.

**Current wallet balance**: The total number of credits currently available in the account.

After reviewing these details, Select **Start Simulation** to begin the test.

{% hint style="info" %}
The estimated credits represent a projection of what might be required. To view the exact number of credits consumed after the test, navigate to [Billing](../settings/billing.md).
{% endhint %}

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (618).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
How the Simulation Runs

Once initiated, Chatlyst automatically generates the entire conversation between the simulated user and the chatbot. This interaction is guided precisely by the persona, scenario, and language settings configured in the previous steps.&#x20;

* No manual typing, sending, or replying is required. The system handles the entire exchange.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (628).png" alt="" width="563"><figcaption></figcaption></figure></div>
{% endstep %}
{% endstepper %}

***

### Simulation Results Review

After a simulation (a test run of the bot) completes, use the Review screen to evaluate the conversation and train the bot for better accuracy.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (630).png" alt="" width="563"><figcaption></figcaption></figure></div>

The conversation view to read the full message-by-message dialogue. As you read through the interaction, complete the following steps to evaluate and improve the bot:

{% stepper %}
{% step %}
#### Evaluate performance

Review how accurately the bot answers initial questions, manages follow-up context, and handles edge cases (unusual scenarios) or company policies.
{% endstep %}

{% step %}
#### Rate every response

Select **Thumbs Up** or **Thumbs Down** for each answer to continuously train the system on what is helpful.

* If a bot response is incorrect or unhelpful, select the **Thumbs Down** to log a poor rating. For further instructions, refer to the [Training Feedback](training-feedback.md).

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (631).png" alt="" width="563"><figcaption></figcaption></figure></div>
{% endstep %}
{% endstepper %}

***

### Running Again and Managing History

#### Re-run with the new setup

* Select **Auto Test** or **Run Simulation Again** and set up a brand-new persona, scenario, or language.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (632).png" alt="" width="563"><figcaption></figcaption></figure></div>

#### History

All Auto Test runs are saved in [**History**](auto-test.md#history), so you can:

* Review past simulations at any time.
* Compare older and newer runs to see how training is improving the bot.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (625).png" alt=""><figcaption></figcaption></figure></div>
