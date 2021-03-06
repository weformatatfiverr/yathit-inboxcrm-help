---
title: Creating and updating record
section: Working with SugarCRM
index: 3
---

{% include side-image.html file="create-Contacts.gif" %}
_New Record Panel_ is the second tabbed panel on [Sidebar Panel,Using Sidebar] identified by plus icon, {{ "plus" | svg_icon }}. 

A _new record form_ for Leads will appear on the panel. The _record form_ has a _header_ and _content_. Top header has an SugarCRM _record type icon_ on the left and a hamburger menu button on the right. Record type icon has two characters symbol of the record type, in this case, "Le" with record type color for Leads.

Default new record form will create a new lead record. You can change to other New menu item from the _hamburger menu_. Notice that record type icon in the header change accordingly.

The content panel consists input for record fields compartmentalized by their groups. If a field does not have group, it is placed under the default group. The label of a field can be seen by tooltip over the field input. Not all fields are displayed in the content panel. Field can be show or hide by changing setting in the "Fields..." menu from the hamburger menu. Some field are read only and cannot be change, but still be displayed.

Edit the fields as necessary and click _submit button_, {{ "check-circle" | svg_icon }}, on the header. The submit button appears only if content value(s) is dirty (change from initial value). Clicking submit button will send a new record create request to SugarCRM backend server. If success, header and content will be update with field values received from the server. Notice that header now should record label (Contact's full name) as web link to SugarCRM record view. You may use the web link to see record in SugarCRM web app.

# Leads

[Sugar’s Leads module](http://support.sugarcrm.com/02_Documentation/01_Sugar_Editions/04_Sugar_Professional/Sugar_Professional_7.2/Application_Guide/10_Leads/) consists of individual prospects who may be interested in a product or service your organization provides. Once the lead is qualified as a sales opportunity, leads can be converted into contacts, opportunities, and accounts. There are various ways you can create leads in Sugar such as via the Leads module, duplication, importing leads, etc. Once the lead record is created, you can view and edit information pertaining to the lead via the Leads record view. This documentation will go over the basics of the Leads module as well as the various options available in performing the actions related to the module.

## Creating a new Lead

A new Lead record can be created from [Sidebar](../sidebar/index.html) or [Context Widget](../context/index.html).

### Using Sidebar to create a new Lead

To create a new record using Sidebar, click "Create a new record" tab, {{ "plus" | svg_icon }}. 
{% include side-image.html file="create-Leads.gif" %}

A _new record form_ will appear on the panel (see in the figure). The _record form_ has a _header_ and _content_. Top header has an SugarCRM _record type icon_ on the left and a hamburger menu button on the right. Record type icon has two characters symbol of the record type, in this case, "Le" with record type color for Lead.

The content panel consists input for record fields compartmentalized by their groups. If a field does not have group, it is placed under the default group. The label of a field can be seen by tooltip over the field input. Not all fields are displayed in the content panel. Field can be show or hide by changing setting in the "Fields..." menu from the hamburger menu. Some field are read only and cannot be change, but still be displayed.

Edit the fields as necessary and click _submit button_, {{ "check-circle" | svg_icon }}, on the header. The submit button appears only if content value(s) is dirty (change from initial value). Clicking submit button will send a new record create request to SugarCRM backend server. If success, header and content will be update with field values received from the server. Notice that header now should record label (Lead's full name) as web link to SugarCRM record view. You may use the web link to see record in SugarCRM web app.

### Using Context widget to create a new Lead


{% include side-image.html file="create-Leads-context.gif" %}

Creating a new Lead record inside Gmail [Context Widget](../context/index.html) is a little different, more convenient and smarter. 

When a new email thread is open, Gmail show _info column_ on the right side of the main panel. The top of Gmail info column is about _the most relevant contact_ panel. If there are more contacts involved in the email, additional contact link are provided under the most relevant contact. (Sometimes it may happen that the most relevant contact is not available for some email like system generated message). Yathit InboxCRM context widget panel is injected just below the most relevant contact panel. Email address and its full name are taken to the context widget panel and retrieve from SugarCRM records. If any SugarCRM record is found matching the email address, the record is shown. Otherwise, it is hidden and only _search input_ is shown.

To create a new Lead record, you can either type email address or full name to the search input and then click search button, {{ "search" | svg_icon }}, or press enter. You may also use auto suggested list in the search input. The new Lead record form will appear below the search input box with email or full name field filled. If social add-on is available, additional contact field values will be fill up from publicly available information from multiple social networks.

Edit the fields as necessary and click _submit button_, {{ "check-circle" | svg_icon }}, on the header.

## Updating a Lead


{% include side-image.html file="edit-Leads.gif" %}

Updating a record is similar to creating a record. You can either use [Sidebar](../sidebar/index.html) or [Context Widget](../context/index.html).

First search the record you want to edit. Click search button tab, {{ "magnifying-glass" | svg_icon }}, on the Sidebar. 


Click edit menu item from the hamburger menu, {{ "menu" | svg_icon }}, on the right of record header to edit the record.

Edit the fields in the _record content panel_ as necessary and click _submit button_, {{ "check-circle" | svg_icon }}, on the header. The submit button appears only if content value(s) is dirty (change from initial value). A message should appear to notify the record is updated. The record content panel is updated with field values received from the server.

## Deleting a Lead

To delete a record, search the record you want to delete. Click search button tab, {{ "magnifying-glass" | svg_icon }}, on the Sidebar. 

{% include side-image.html file="delete-Leads.gif" %}

Click delete menu item from the hamburger menu, {{ "menu" | svg_icon }}, on the right of record header to delete the record.

A message should appear to notify the record is deleted.

## Searching Lead records

Lead records can be search on search tab, {{ "magnifying-glass" | svg_icon }}, on the Sidebar. You can search record fields by emails, name, id, description.

# Contacts


[Sugar’s Contacts module](http://support.sugarcrm.com/02_Documentation/01_Sugar_Editions/04_Sugar_Professional/Sugar_Professional_7.2/Application_Guide/11_Contacts/)  consists of individual people with whom your organization has a relationship. Contact records are typically related to an account record, and multiple contacts may be associated to a single account. There are various ways you can create contacts in Sugar such as via the Contacts module, importing contacts, converting leads to contacts, etc. Once the contact record is created, you can view and edit information pertaining to the contact via the Contacts record view. Each contact record may then relate to other Sugar records such as meetings, cases, opportunities, and many others, making the contact record a hub for viewing and continuing your interaction with the individual. This documentation will cover how to use the Contacts module as well as the various actions and options available from within the module..

## Creating a new Contact

A new Contact record can be created from [Sidebar](../sidebar/index.html) or [Context Widget](../context/index.html).

### Using Sidebar to create a new Contact

{% include side-image.html file="create-Contacts.gif" %}
To create a new record using Sidebar, click "Create a new record" tab, {{ "plus" | svg_icon }}.

A _new record form_ for Leads will appear on the panel. The _record form_ has a _header_ and _content_. Top header has an SugarCRM _record type icon_ on the left and a hamburger menu button on the right. Record type icon has two characters symbol of the record type, in this case, "Le" with record type color for Leads. Change to Contacts record type by selecting New > Contacts menu item from the _hamburger menu_. Notice that record type icon change to Contacts.

The content panel consists input for record fields compartmentalized by their groups. If a field does not have group, it is placed under the default group. The label of a field can be seen by tooltip over the field input. Not all fields are displayed in the content panel. Field can be show or hide by changing setting in the "Fields..." menu from the hamburger menu. Some field are read only and cannot be change, but still be displayed.

Edit the fields as necessary and click _submit button_, {{ "check-circle" | svg_icon }}, on the header. The submit button appears only if content value(s) is dirty (change from initial value). Clicking submit button will send a new record create request to SugarCRM backend server. If success, header and content will be update with field values received from the server. Notice that header now should record label (Contact's full name) as web link to SugarCRM record view. You may use the web link to see record in SugarCRM web app.

## Updating a Contact

{% include side-image.html file="edit-Contacts.gif" %}
Use [Sidebar](../sidebar/index.html) to update a Contacts record.


First search the record you want to edit. Click search button tab, {{ "magnifying-glass" | svg_icon }}, on the Sidebar. 

Click edit menu item from the hamburger menu, {{ "menu" | svg_icon }}, on the right of record header to edit the record.

Edit the fields in the _record content panel_ as necessary and click _submit button_, {{ "check-circle" | svg_icon }}, on the header. The submit button appears only if content value(s) is dirty (change from initial value). A message should appear to notify the record is updated. The record content panel is updated with field values received from the server.

## Deleting a Contact


{% include side-image.html file="delete-Contacts.gif" %}
To delete a record, search the record you want to delete. Click search button tab, {{ "magnifying-glass" | svg_icon }}, on the Sidebar. 

Click delete menu item from the hamburger menu, {{ "menu" | svg_icon }}, on the right of record header to delete the record.

A message should appear to notify the record is deleted.

## Searching Contact records

Contact records can be search on search tab, {{ "magnifying-glass" | svg_icon }}, on the Sidebar. You can search record fields by emails, name, id, description.

## Export SugarCRM Contact record to Gmail Contact entry

{% include side-image.html file="export-sugarcrm-record-to-gmail-contact.gif" %}
 You can export SugarCRM Contact record with Gmail Contact entry. Once exported these two record are synchronize with each other. Changes from one record will update to other record.

Visit to the Contact record on the Record Panel of the sidebar, that you want to export. To export Export SugarCRM Contact record to Gmail Contact entry, click menu item, 'To Gmail' on from the hamburger menu, {{ "menu" | svg_icon }}.

# Accounts


[Sugar’s Accounts module](http://support.sugarcrm.com/02_Documentation/01_Sugar_Editions/04_Sugar_Professional/Sugar_Professional_7.2/Application_Guide/12_Accounts/) consists of companies with whom your organization has a relationship and is generally seen as the hub for managing and analyzing your business’ interactions with each customer. There are various ways you can create accounts in Sugar such as via the Accounts module, duplication, importing accounts, etc. Once the account record is created, you can view and edit information pertaining to the account via the Accounts record view. Each account record may then relate to other Sugar records such as contacts, meetings, cases, opportunities, and many others as the customer’s relationship matures. This documentation will cover how to use the Accounts module as well as the various actions and options available from within the module.

## Creating a new Account

A new Account record can be created from [Sidebar](../sidebar/index.html) or [Context Widget](../context/index.html).

### Using Sidebar to create a new Account

To create a new record using Sidebar, click "Create a new record" tab, {{ "plus" | svg_icon }}.

A _new record form_ for Leads will appear on the panel. The _record form_ has a _header_ and _content_. Top header has an SugarCRM _record type icon_ on the left and a hamburger menu button on the right. Record type icon has two characters symbol of the record type, in this case, "Le" with record type color for Leads. Change to Accounts record type by selecting New > Accounts menu item from the _hamburger menu_. Notice that record type icon change to Accounts.

The content panel consists input for record fields compartmentalized by their groups. If a field does not have group, it is placed under the default group. The label of a field can be seen by tooltip over the field input. Not all fields are displayed in the content panel. Field can be show or hide by changing setting in the "Fields..." menu from the hamburger menu. Some field are read only and cannot be change, but still be displayed.

Edit the fields as necessary and click _submit button_, {{ "check-circle" | svg_icon }}, on the header. The submit button appears only if content value(s) is dirty (change from initial value). Clicking submit button will send a new record create request to SugarCRM backend server. If success, header and content will be update with field values received from the server. Notice that header now should record label (Account's full name) as web link to SugarCRM record view. You may use the web link to see record in SugarCRM web app.

## Updating a Account

Use [Sidebar](../sidebar/index.html) to update a Accounts record.

First search the record you want to edit. Click search button tab, {{ "magnifying-glass" | svg_icon }}, on the Sidebar.

Click edit menu item from the hamburger menu, {{ "menu" | svg_icon }}, on the right of record header to edit the record.

Edit the fields in the _record content panel_ as necessary and click _submit button_, {{ "check-circle" | svg_icon }}, on the header. The submit button appears only if content value(s) is dirty (change from initial value). A message should appear to notify the record is updated. The record content panel is updated with field values received from the server.

## Deleting a Account

To delete a record, search the record you want to delete. Click search button tab, {{ "magnifying-glass" | svg_icon }}, on the Sidebar.

Click delete menu item from the hamburger menu, {{ "menu" | svg_icon }}, on the right of record header to delete the record.

A message should appear to notify the record is deleted.

## Searching Account records

Account records can be search on search tab, {{ "magnifying-glass" | svg_icon }}, on the Sidebar. You can search record fields by emails, name, id, description.



