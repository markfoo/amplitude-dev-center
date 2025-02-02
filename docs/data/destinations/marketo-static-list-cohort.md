---
title: Send Cohorts to Marketo Static List
description: Send behavioral cohorts from Amplitude to a Marketo static lists and better engage your users based on their patterns of interaction with your product and their lifecycle timing.
---

!!!alpha

    This integration is currently in Alpha and is in active development. If you have any feedback to improve or have suggestions, please email <integrations@amplitude.com>. 

The Marketo static list destination lets you export cohorts into Marketo as a static list, sending them to a destination folder or program of your choice. Use this to leverage Marketo’s tools for in-app messaging, push notifications, and email campaigns to better engage your users. 

!!!info 

    This page is about the Marketo Static List destination. Unlike the [Marketo Cohort](../destinations/marketo-cohort/) destination, this integration automatically exports cohorts as a static list in Marketo.

## Considerations

- Email values are case-sensitive. If you use email addresses to map users between Amplitude and Marketo, the email address must be consistent between both systems.
- Marketo automatically generates Amplitude users that don't already exist in Marketo are generated automatically.

## Setup

### Marketo setup

!!!note

    You need a Marketo Admin for these setup steps.

You need your Marketo Client ID, Client Secret, and REST API Endpoint. For more detailed instructions, visit [Marketo's documentation](https://developers.marketo.com/blog/quick-start-guide-for-marketo-rest-api/).

1. Create a role with "Read-Write Person" and "Read-write Assets" permissions under "Access API"
2. Create an API-only user and associate it with the API role created previously.
3. Go to **Admin > Integration > Launchpoint** to create a new service. Set 'Service' to 'Custom' and select the API Only User you created in the last step.
4. On the service, click **View Details** and copy the `Client ID` and `Client Secret`.
5. Go to **Admin > Integration > Web Services** and copy the REST API Endpoint. **Important**: Remove the `\rest` at the end of the endpoint. If you don't remove it, the integration doesn't work correctly.

!!!example "Example Keys"

          - `Client ID:` 97890c99-9999-46e4-bccc-351071cd5c3b
          - `Client Secret:` xzy3XYZxyZqIroHtliA7mDKTx7NUXyZZ
          - `REST API Endpoint:` `https://133-CDN-660.mktorest.com`

### Amplitude setup

1. In Amplitude Data, click **Catalog** and select the **Destinations** tab.
2. In the Cohort section, click **Marketo Static List**.
3. Enter the name for the connection.
4. Paste the Client ID, Client Secret, and REST API endpoint you copied from Marketo.
5. Assign the Amplitude field mapping for email. This must be a unique identifier.
6. Save when finished.

## Send a cohort

To sync your first cohort, follow these steps:

1. In Amplitude, open the cohort you want to sync, then click **Sync**.
2. Select **Marketo Static List**, then click **Next**.
3. Choose the account you want to sync to.
4. Choose the folder/program type and provide the folder/program ID.
    a. The program ID can be found in the URL, and is the 4-5 digits between the G and A in the URL of the selected program. 
5. Choose the sync cadence.
6. When finished, save your work.

It may take a few minutes depending on the size of your cohort to see the correct number of cohort users on Marketo's side.

## Use cases

1. Create a marketing campaign targeted at a cohort of users created on Amplitude
2. Automate emails from Marketo based on activities tracked in a cohort
3. Reduce the number of fields in Marketo by syncing cohorts to lists instead of fields
