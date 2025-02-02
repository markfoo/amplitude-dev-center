---
title: Amplitude Developer Docs Changelog
description: See what's new and changed in the Ampltude Developer Center!
status: new
hide:
  - toc
---
<!-- Turn off linting rules that don't apply here -->
<!-- vale Amplitude.Headings = NO --> 
<!-- vale Amplitude.We = NO -->
<!-- vale Amplitude.Passive = NO -->
<!-- vale Amplitude.Adverbs = NO -->
<!-- markdownlint-disable MD036 -->
<!-- / End linting rules -->

See what's new and changed in the Amplitude Developer Center. Updates are typically posted the last business day of the week.

!!!note "Changelog notes"

    - This changelog covers only documentation changes, and doesn't cover product changes. See [Product Updates](https://community.amplitude.com/product-updates?utm_source=devdocs&utm_medium=helpcontent&utm_campaign=devdocswebsite) for those changes.
    - This changelog is incomplete and in January 2023. For a complete history of the Amplitude Developer Docs, see the [GitHub repo](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center).

## Week of February 12, 2023

**New**

- Added [Quickstart guide for Google Tag Manager](../data/sources/google-tag-manager/), and new documentation for the [Amplitude Analytics Legacy](../data/sources/google-tag-manager-client-legacy/) template, [Browser SDK template](../data/sources/google-tag-manager-client/), and the [Amplitude Analytics](../data/sources/google-tag-manager-server/) template. [#583](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/583)

**Updated**

- Updated navigation paths in integration docs to reflect the new Data UI experience. [#584](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/584)
- Added info on batching and configuration to the [iOS SDK](../data/sdks/ios-swift/) doc. [#592](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/592)
- Added section for inclusion lists to the [Variant Jumping](../experiment/guides/troubleshooting/variant-jumping) doc. [#581](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/581)
- Changed "Legacy" to "Maintenance" in previous-generation SDKs. We did this to prevent confusion. [#589](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/589)
- Added clarifications to the [Client-side vs Server-side](../data/sources/client-side-vs-server-side) guide. [#586](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/586)
- Fixed a formatting issue in the [Accounts Instrumentation](../guides/accounts-instrumentation-guide/) guide. [#585](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/585)

<!-- markdown-link-check-disable -->
<!-- turn off link checking for old entries cause otherwise it takes forever. The cron job runs daily and will catch busted links elsewhere-->

## Week of February 5, 2023

**New**

- Added [overview page](../experiment/guides/getting-started/) for Experiment Getting Started guide. [#559](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/559)
- Added [Plotline Cohort Syncing](../data/destinations/plotline-cohort) doc. [#575](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/575)
- Added [HTTP V2 Quickstart guide](../analytics/apis/http-v2-api-quickstart), and added code examples in more languages to the [HTTP V2](../analytics/apis/http-v2-api) doc. [#578](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/578)

**Updated**

- Added new-format request examples to [HTTP V2 API](../analytics/apis/http-v2-api) doc. [#571](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/571).
- Added new-format request examples to [Behavioral Cohorts API](../analytics/apis/behavioral-cohorts-api) doc. [#573](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/573)
- Updated [Event Streaming Overview](../data/destination-event-streaming-overview) doc to clarify how events are counted. [#562](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/562).
- Added configuration information to [Legacy Android SDK](../data/sdks/android/) doc. [#577](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/577)
- Made tweaks to quickstart guides. [#570](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/570)
- Added deduplication section to [S3 Import](../data/sources/amazon-s3) doc. [#579](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/579)

## Week of January 29, 2023

**New**

- Added new [Warehouse Destination Overview](../data/destination-warehouse-overview) doc to improve breadcrumb navigation. [#554](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/554)
- Added new [Kameleoon Event Streaming](../data/destinations/kameleoon-event-streaming) doc. [#557](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/557)
- Added new [Marketo Static List Cohort Syncing](../data/destinations/marketo-static-list-cohort) doc. [#566](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/566)

**Updated** 

- Updated tooltips in the keys table in [Amplitude Keys Guide](../guides/amplitude-keys-guide) docs. [#552](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/552)
- Updated some field descriptions in the [Productboard cohort](../data/destinations/productboard-cohort) doc. [#545](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/545)
- Fixed incorrect endpoint URI in the [Dashboard API](../analytics/apis/dashboard-rest-api) doc. [#555](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/555)
- Added links to overview pages from the Source and Destination home pages. [#561](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/561)
- Site change: streamlined how the table of contents appears on page. [#556](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/556)
- Fixed broken links in [SDK Quickstart](../data/sdks/sdk-quickstart) guide. [#565](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/565/files)
- Made clarity and context improvements the [Android SDK Quickstart](../data/sdks/sdk-quickstart#android) guide. [#558](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/558)
- Added missing code example to the [legacy iOS](../data/sdks/ios) doc. [#560](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/560)

## Week of January 22, 2023

**New**

- Added new [migration guide](../data/sdks/ios-swift/migration/) for moving from the legacy iOS SDK to the new Amplitude-Swift SDK. [#493](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/493). 
- Added new [Time-to-Live](../data/ttl-configuration) doc. [#539](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/539)
- Added new [Extole Event Streaming](../data/destinations/extole-event-streaming) doc. [#544](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/544)
- Added new [Import Sprig Events](../data/sources/sprig) doc. [#549](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/549)
- Navigation changes: Updated navigation for the SDK section of the site and added new links to content to improve browseability. [#529](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/529)

**Updated**

- Updated the status returned for requests outside of data retention period in [Event Streaming Metrics Summary API](../analytics/apis/event-streaming-metrics-summary-api) doc. [#528](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/528)
- Updated required timestamp format in [Snowflake Import](../data/sources/snowflake) doc. [#526](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/526)
- Updated [Ampli CLI](../data/ampli/cli) docs. [#520](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/520)
- Fixed broken code formatting and clarified callouts in [User Privacy API](../analytics/apis/user-privacy-api) doc. [#531](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/531)
- Made formatting and link improvements in [Batch Event Upload API](../analytics/apis/batch-event-upload-api) doc. [#532](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/532)
- Fixed an issue that made buttons on the homepage open in new tabs without warning. [#534](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/534)
- Fixed an incorrect URL in the [Go SDK](../data/sources/sdks/go) doc. [#536](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/536)
- Added recommendations to initialization instructions in the [Android-Kotlin SDK](../data/sdks/android-kotlin) doc. [#537](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/537)
- Added new styling elements to headings in the [SDK Quickstart](../data/sdks/sdk-quickstart) doc to make the page easier to follow. [#542](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/542)
- Added supported versions and shutdown information to [Python SDK](../data/sdks/python) doc. [#541](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/541)
- Fixed incorrect link in the [React Native](../data/sdks/typescript-react-native) doc. [#547](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/547/)
- Fixed `setGroup` calls in several Ampli docs. [#548](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/548).
- Added table with server URLs for all SDKs for sending data to Amplitude via [domain proxy](../analytics/domain-proxy).   

## Week of January 16, 2023

**New** 

- Added new [Event Streaming Metrics Summary API](../analytics/apis/event-streaming-metrics-summary-api) doc. [#519](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/519).
- Added Event Streaming Metrics Summary API examples to the [Postman Collection](https://www.postman.com/amplitude-dev-docs/workspace/amplitude-developers/overview). 

- Added new [Cloud Storage Destination Overview](../data/destination-cloud-storage-overview) doc. [#510](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/510)
- Added new [Cloud Storage Source Overview](../data/source-cloud-storage-overview) doc. [#511](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/511)
- Added new [Other Sources Overview](../data/source-other-overview) doc. [#512](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/512)
- Added new [Cohort Syncing Destinations Overview](../data/destination-cohort-overview) doc. [#516](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/516)
- Added new [API Reference Overview](../analytics/api-reference-overview) doc. [#517](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/517)
- Added new [Guides](../guides) landing page to make it easier to find getting started material. [#523](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/523)

**Updated**

- *Site change*: Added breadcrumb navigation. [#507](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/507)
- *Site change*: Massive overhaul to the docs home page and other high-level pages to make browsing easier for new readers. [#523](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/523)
- *Repo change*: Simplified README and moved all repo meta docs to Wiki format to make them easier to browse and read. [#508](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/508)
- Updated Ampli docs to call out `environment` as Required, standardized language across the docs, cleaned up table whitespace, and fixed Swift code snippet. [#515](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/515/files)
- Updated multiple event streaming destination docs. [#453](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/453)
- Added quickstart sections to Ampli docs. [#489](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/489) 
- Added new-format API examples to [Export API](../analytics/apis/export-api) doc. [#496](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/496)
- Overhauled [APIs page](../analytics/apis) to include more useful information. [#517](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/517)
- Changed the URL of [Event Streaming Overview](../data/destination-event-streaming-overview) for clarity and consistency. There is a redirect in place, but we recommend updating your bookmarks. [#513](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/513)
- Updated wording in the Integration Portal docs to reflect a small UI change. [#514](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/514)
- Updated description in [Maze Cohort Syncing](../data/destinations/maze-cohort) docs. [#518](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/518)
- Added IP addresses to allowlist in [Snowflake Export](../data/destinations/snowflake), and fixed broken IP allowlist formatting in [Snowflake Import](../data/sources/snowflake). [#522](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/522)

## Week of January 8, 2023

**New** 

- Added Doc Changelog (this page). [#499](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/499)
- Added new [Client-side vs Server-side sources overview](../data/sources/client-side-vs-server-side/), and organized the Analytics SDKs by client-side and server-side. [#486](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/486)
- Added new [Amplitude API Keys and Tokens Guide](../guides/amplitude-keys-guide) doc. [#504](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/504)
- Added new [Exposures without Assignments](../experiment/guides/troubleshooting/exposures-without-assignments/) doc. [#484](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/484)
- *Site change*: Introduced an update that forces external links to open in a new tab.

**Updated** 

- Added new-format API examples to [Attribution API](../analytics/apis/attribution-api) doc. [#488](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/488)
- Added new-format API examples to [CCPA DSAR API](../analytics/apis/ccpa-dsar-api) doc. [#495](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/495)
- Added new-format API examples to [User Profile API](../analytics/apis/user-profile-api) doc. [#498](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/498)
- Changed the “Table of contents” heading on the right nav to “On this page”. Bundled with [#498](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/498)
- Updated [Marketo doc](../data/destinations/marketo-cohort) for new Upsert functionality. [#490](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/490)
- Added missing Optional identifiers to the Identify API doc. [#491](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/491)
- Cross-linked [Lookup Table API](../analytics/apis/lookup-tables-api) and [Lookup Table source](../data/sources/lookup-table) docs, with minor formatting and language improvements in both articles. [#492](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/492)
- Added a link to help doc on managing privacy notifications to our [User Privacy API](../analytics/apis/user-privacy-api) doc. [#494](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/494)
- Made some clarifying changes to [SendGrid Cohort](../data/destinations/sendgrid-cohort) doc. [#500](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/500)
- Removed "New" badges from articles older than 2 months, and removed the global feedback banner. [#503](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/503)
- Added `flush` documentation to Ampli docs. [#502](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/502)

## Week of January 1, 2023

**New**

- Added new doc for the [Aliasing API](../analytics/apis/aliasing-api). [#472](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/472)
- Started adding <span class="required">Required</span> and <span class="optional">Optional</span> tags in our parameter tables. You can see this in action in the API docs. [#481](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/481)
- Added Aliasing API requests to our [Postman Collection](https://www.postman.com/amplitude-dev-docs/workspace/amplitude-developers/overview). 

**Updated**

- Experiment Python SDK became generally available, updated doc to remove beta labels. [#479](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/479)
- Corrected timestamp calculation info in Snowflake doc. [#480](https://github.com/Amplitude-Developer-Docs/amplitude-dev-center/pull/480)