---
icon: list
---

# Customer List

### Search Customer

Use the search bar to find customers quickly. As text is entered, the customer list updates automatically, and a customer can be selected to review details in the right panel.

<div><figure><img src="../.gitbook/assets/image (530).png" alt=""><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/image (531).png" alt=""><figcaption></figcaption></figure></div>

***

### Filters

Use structured filters to narrow the customer list.&#x20;

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (534).png" alt="" width="375"><figcaption></figcaption></figure></div>

{% stepper %}
{% step %}
**Primary Fields**

Search by customer name, email, or phone number.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (535).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
**Custom Attributes Search**

Use custom attribute to narrow the search. All system attributes and custom attributes are available as searchable fields.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (536).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Select **+ Add field filter**.&#x20;

* For attribute setup, more information on [Customer Attributes](../settings/customer-attributes.md).
* For multiple attributes search, more information on [Multiple Custom Attributes Search](customer-list.md#multiple-custom-attributes-search).

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (537).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Select an attribute from the dropdown list.&#x20;

* In this example, **age (number)** and **gender (string)** are custom attributes, and **Initial Inbound Channel (string)**, **Country (string)** and **Browser (string)** are system attributes.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (542).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Select the [operator](customer-list.md#attribute-operators) and enter the value. Select **Search** to apply the filter. (or select **Clear Local Fields** to reset the current filters and start a new search.)

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (539).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
The search results appear below the search bar based on the filters you applied.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (583).png" alt="" width="375"><figcaption></figcaption></figure></div>
{% endstep %}
{% endstepper %}

***

### Multiple Custom Attributes Search

You can add more than one custom attribute filter. Each added filter is combined, so the customer list only shows profiles that match all selected filters.

For example, if a search includes **Custom Attribute A** and **Custom Attribute B**, Chatlyst returns customers who match **A and B**.&#x20;

In the example shown, the filters are age greater than 28 and gender equal M, so the results only include customers who meet both of these conditions.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/image (541).png" alt="" width="563"><figcaption></figcaption></figure></div>

#### Attribute Operators

If the attribute type is **Number**, the following operators are available:

* Equal
* Not Equal
* Greater Than
* Greater or Equal
* Less Than
* Less or Equal
* Range (Between)

If the attribute type is **String (Text)**, the following operators are available:

* Equal
* Not Equal
