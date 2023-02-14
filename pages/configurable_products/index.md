---
title: Configurable Products Configuration
sidebar: mydoc_sidebar
permalink: configurable_products.html
folder: configurable_products
---

## Overview

Attributes are the building blocks of the product catalog, and describe specific characteristics of a product. Product attributes can be organized into attribute sets, which are then used as templates for creating products.

Attributes determine the type of input control that is used for product options, and provide additional information for product pages. They are also used as search parameters and criteria for layered navigation, product comparison reports, and promotions.

## Creating Configurable Products
<br />
Configurable products can be created using the following steps
<br />
1.  Create new configurable attribute in Magento
1.  Add new attribute(s) to magento attribute set(s)
1.  Create mapping between Cyrane & Magento

## Create New Attribute
<br />

From the backoffice navigation to <i>Stores > Attributes > Product </i> and fill out the required information for creating a new attribute
<br />
{% include inline_image.html file="configurable_products/new-attribute-creation.png" alt="SDK button" %}
<br />
{% include important.html content="Please use 'Dropdown' as the input type. although Swatch does work....it looks stupid when combined with multiple configurable attributes" %}


## Add New Attribute to Attribute Set
<br />

Navigate to <i>Stores > Attributes > Attribute </i> Sets
<br />
Select the desired attribute set and then drag the newly created attribute into the attribute set.
<br />
{% include inline_image.html file="configurable_products/attribute-set.png" alt="SDK button" %}
<br />
{% include tip.html content="Layered navigation attributes and configurable attributes should be assigned to the 'attribute set specific' group to keep everything neat and tidy" %}
<br />
{% include links.html %}

## Create mapping between Cyrane & Magento

The attribute is most likely named differently in Cyrane and Magento therefore a mapping has to be made which links the two system together.

Navigate to <i>Stores > Configuration </i> and from the left hand menu select <i>Fitness Superstore > Attribute Mapping<i>
<br />
{% include inline_image.html file="configurable_products/cyrane-magento-mapping.png" alt="SDK button" %}
<br />

Click 'Add' to add a new mapping and select the newly created attribute from the dropdown and then paste the Cyrane Attribute name into the right hand box. Make sure you click 'save' to create the mapping.

