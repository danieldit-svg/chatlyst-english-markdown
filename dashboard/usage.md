---
description: >-
  This section explains what is shown in the Usage tab and how to review KC Bot
  and AI Response usage.
icon: chart-line-up
---

# Usage

### Review Credits

The Usage page shows both credit types in one panel.

<div data-with-frame="true"><img src="../.gitbook/assets/attachmentf17d7e82 e9b1 43ad 8fd3 4f2e2ffd19494a0717a8 062d 42a2 bab1 d048180ae074 (1).png" alt=""></div>

{% hint style="info" %}
Top up — Select the wallet icon to open the [top-up flow](https://app.gitbook.com/s/BW7n4ClAhZvbgvusylCd/top-up-guideline).

<img src="../.gitbook/assets/image (35).png" alt="" data-size="original">
{% endhint %}

***

### Review Overview and Trends

{% stepper %}
{% step %}
#### Choose a Date Range

Use the date range selector to specify the time period for the data displayed.

{% hint style="info" %}
Date Range — Use the top-right date range selector to view data for a specific period.

<img src="../.gitbook/assets/image (36).png" alt="" data-size="original">
{% endhint %}

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (336).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
#### Switch between Overview and Trends

Use the navigation tab in the middle of the page to switch between [Overview](usage.md#overview) and [Trends](usage.md#trends).

{% hint style="info" %}
Navigation Tab — Switch between Overview and Trend.

<img src="../.gitbook/assets/image (37).png" alt="" data-size="original">
{% endhint %}

<div data-with-frame="true"><img src="../.gitbook/assets/attachment9c40e66d ab74 4fc9 9c91 8a9c2534224aScreenshot_2026 04 27_at_2.20.12_PM (1).png" alt=""></div>
{% endstep %}

{% step %}
#### **Overview**

In Overview, key information updates based on the selected date range.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (57).png" alt=""><figcaption></figcaption></figure></div>

1. Period Summary shows key activity for the selected date range.

<div data-with-frame="true"><img src="../.gitbook/assets/attachmenta62e2adc db02 45f6 a11e bdac64711474image (1).png" alt=""></div>

2. Top Users shows the most active users during the selected period.

<div data-with-frame="true"><img src="../.gitbook/assets/attachmentb08eadba eab9 4221 a8c8 09480c7d86fdimage (1).png" alt=""></div>

3. Top Documents shows the most queried knowledge documents and a feedback breakdown.

<div data-with-frame="true"><img src="../.gitbook/assets/attachmentd8cf5657 5e90 4dd8 8fd9 3b73f6b65ba5image (1).png" alt=""></div>
{% endstep %}

{% step %}
#### **Trends**

In Trends, compare metrics such as AI Responses Used, KC Bot Used, Messages, and Cost.

The comparison depends on the selected date range.

* If the date range is **Apr 17 to Apr 18**, Chatlyst compares it to **Apr 15 to Apr 16**.

<div data-with-frame="true"><img src="../.gitbook/assets/attachmentf9cafcfa 6d6a 4a06 ac23 6f11376cdcafimage (1).png" alt=""></div>

* If the date range is **Apr 14 to Apr 20** (Last 7 days), Chatlyst compares it to **Apr 7 to Apr 13**.

<div data-with-frame="true"><img src="../.gitbook/assets/attachment4dd8fdf9 92fa 4733 ae69 73e5184fc692image (1).png" alt=""></div>
{% endstep %}
{% endstepper %}

***

### Export the Usage Log

1. Select **Export Usage Log** in the top-right corner.
2. If there is no data in the selected date range, Chatlyst does not generate a file.

<div data-with-frame="true"><img src="../.gitbook/assets/attachmentebd35569 d11e 471f 916f f2688b9475ebimage (1).png" alt=""></div>

The exported CSV includes the following columns:

* Date
* AI Response Used
* KC Bot Used
* Messages
* Cost (Currency)

An example template is shown below:

| Date       | AI Response Used | KC Bot Used | Messages | Cost (HKD) |
| ---------- | ---------------- | ----------- | -------- | ---------- |
| 2026-04-16 | 10               | 1           | 12       | 3.64       |
| 2026-04-17 | 7                | 1           | 7        | 3.21       |
| 2026-04-20 | 5                | 3           | 5        | 7.32       |

#### Troubleshooting Chinese Display Issues <a href="#csv-troubleshooting-chinese-display-issues" id="csv-troubleshooting-chinese-display-issues"></a>

If your CSV file cannot display Chinese characters, follow the steps below based on your software.

* Google Sheets — No issues expected. Simply import the file and Chinese characters will display normally.
* Pages — No issues expected. Simply open the file and Chinese characters will display normally.
* Excel  — Chinese characters may not display correctly by default. Use one of these methods:

#### Method 1: Import via File Tab

{% stepper %}
{% step %}
Open a New Blank Workbook.
{% endstep %}

{% step %}
Go to **File** and select **Import**.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (379).png" alt=""><figcaption></figcaption></figure></div>

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (381).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Select CSV file and click **Import**, then locate the CSV and select **Get Data** to proceed.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (383).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
When the Text Import Wizard appears:

1. Set **File Origin** to: 65001: Unicode (UTF-8), then select **Next**.&#x20;

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (384).png" alt="" width="375"><figcaption></figcaption></figure></div>

2. Tick **Comma** as the Delimiters, select **Finish**.&#x20;

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (385).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}
{% endstepper %}

#### **Method 2: Import via Data Tab**

{% stepper %}
{% step %}
Open a New Blank Workbook.
{% endstep %}

{% step %}
Go to **Data** then **Get Data (Power Query)**, select **From Text (Legacy)**

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (386).png" alt=""><figcaption></figcaption></figure></div>

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (387).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Locate the CSV and select **Get Data** to proceed.
{% endstep %}

{% step %}
When the Text Import Wizard appears:

1. Set **File Origin** to: 65001: Unicode (UTF-8), then select **Next**.&#x20;

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (384).png" alt="" width="375"><figcaption></figcaption></figure></div>

2. Tick **Comma** as the Delimiters, select **Finish**.&#x20;

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (385).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}
{% endstepper %}
