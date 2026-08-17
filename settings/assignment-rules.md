---
icon: arrows-split-up-and-left
---

# Assignment Rules

Assignment rules determine how conversations are transferred from the automated bot to human agents. Configuring these rules ensures that customer inquiries are routed efficiently to the correct team members.

{% hint style="info" %}
The system will only assign a conversation to a human agent after the chatbot has completely left the active chat.
{% endhint %}

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (716).png" alt=""><figcaption></figcaption></figure></div>

#### How to Select an Assignment Rule

{% stepper %}
{% step %}
Review the available assignment options provided on the screen.

There are three options: [Sequential Priority](assignment-rules.md#sequential-priority), [Balanced Workload](assignment-rules.md#balanced-workload) and [Disabled](assignment-rules.md#disabled).&#x20;

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (717).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Select the rule that best fits the team's structure or daily workflow. Select **Save Rules** to apply.

{% hint style="info" %}
The currently selected rule will highlight in light grey and display a bold border around its card to indicate it is chosen.
{% endhint %}

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (718).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}
{% endstepper %}

***

#### Sequential Priority

Sequential Priority assigns conversations based on a fixed, ordered list of team members. The system will assign new incoming chats to the first person on the list. Once that person reaches their maximum allowed number of active chats (concurrency limit), the system will automatically route the next incoming chats to the second person on the list, and so on.

**Sequence and Concurrency Limits Management**

To customize the order and limits for your team, use the following controls:

{% stepper %}
{% step %}
**Change Priority Order**: Select the **Up Arrow** or **Down Arrow** next to a team member's name to move them higher or lower on the list. The member at the very top receives the highest priority for new chats.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (719).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
**Include or Exclude Members**: Toggle the **Auto-assign** switch to **On** or **Off**. This decides whether that specific person is eligible to receive assigned conversations.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (720).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
**Set Individual Limits**: Locate the **Limit** field next to Auto-assign switch and type in a number. This defines the maximum concurrent active chats that specific agent is allowed to handle at one time.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (721).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Select the **Save Rules** to confirm and apply the changes to the system.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (722).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}
{% endstepper %}

#### Balanced Workload

Balanced Workload is an assignment method designed to distribute customer chats equally across the entire available team.

Instead of following a strict list, the system analyzes the current workload of all active agents. When a new conversation is handed over from the bot, it is automatically assigned to the active agent who currently has the lowest number of active chats. This ensures no single team member becomes overwhelmed with tickets while others remain idle.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (723).png" alt=""><figcaption></figcaption></figure></div>

#### **Disabled**

Disabled is a setting designed to turn off all automatic routing of customer chats.

Instead of the system distributing chats automatically, all new or escalated conversations are placed into a shared queue. When a new conversation requires human assistance, it remains in an unassigned status. An agent must then review the queue and manually claim the chat to take ownership. This method provides complete control over ticket distribution, allowing team members to select specific conversations based on their expertise or current availability.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (724).png" alt=""><figcaption></figcaption></figure></div>
