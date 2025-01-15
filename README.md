# activecampaign-ss-tag
Google Tag Manager server-side tag to create or update contact and event tracking

The tag is used to insert or update contacts in ActiveCampaign. To automatically add a contact to a list, the list's ID must be entered in the list field. To retrieve the list ID in ActiveCampaign, click on the list and retrieve the ID from the URL.

The tag also allows for custom field settings. To set a field, enter the custom field code as indicated in ActiveCampaign (e.g. %CUSTOM_FIELD%).

If the email passed to the tag already exists in ActiveCampaign, the contact will be updated. Otherwise, a new contact will be added.

<b>The phone number must be formatted according to the E.164 standard</b>
