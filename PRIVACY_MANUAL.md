# 🕵️ Privacy Examination Manual 🕵️

This manual provides a step-by-step guide for examining Android apps manually in terms of privacy. By following these steps, you can assess apps using the [εxodus](https://reports.exodus-privacy.eu.org/en/) tracker finder, [F-Droid](https://f-droid.org/en) Anti-features, and their privacy policies.

## Step 1: Access [εxodus](https://reports.exodus-privacy.eu.org/en/) Privacy Tracker Finder

You can access the [εxodus](https://reports.exodus-privacy.eu.org/en/) Privacy Tracker Finder in two ways:

1. Download and install the [εxodus](https://reports.exodus-privacy.eu.org/en/) Privacy Tracker Finder from the Google Play Store or [F-Droid](https://f-droid.org/en). Once installed, open the app and allow any necessary permissions.
2. Alternatively, visit the [εxodus](https://reports.exodus-privacy.eu.org/en/) using a web browser to access the tracker finder without installing the app.

## Step 2: Analyze the App with [εxodus](https://reports.exodus-privacy.eu.org/en/)

1. In the [εxodus](https://reports.exodus-privacy.eu.org/en/) Privacy Tracker Finder app or on the website, search for the app you want to examine.
2. Open the app's report in [εxodus](https://reports.exodus-privacy.eu.org/en/) to view its privacy analysis.
3. Take note of the number of trackers and permissions found in the app.

## Step 3: Review [F-Droid](https://f-droid.org/en) Anti-Features

1. Visit the [F-Droid](https://f-droid.org/en) website or install the [F-Droid](https://f-droid.org/en) app on your device.
2. Search for the app you want to examine.
3. Check if the app is available on [F-Droid](https://f-droid.org/en). If it is, view the app's information page.
4. Look for any Anti-Features listed on the app's information page. These may include:
   - [Ads](https://f-droid.org/en/docs/Anti-Features/#Ads) - advertising
   - [Tracking](https://f-droid.org/en/docs/Anti-Features/#Tracking) - tracks and/or reports your activity to somewhere, even when it can be turned off
   - [Non-Free Network Services](https://f-droid.org/en/docs/Anti-Features/#NonFreeNet) - promotes or depends entirely on a non-free network service
   - [Non-Free Addons](https://f-droid.org/en/docs/Anti-Features/#NonFreeAdd) - promotes other non-libre apps or plugins
   - [Non-Free Dependencies](https://f-droid.org/en/docs/Anti-Features/#NonFreeDep) - needs a non-libre app to work (e.g. Google Maps, Market)
   - [NSFW](https://f-droid.org/en/docs/Anti-Features/#NSFW) - contains content that the user may not want to be publicized or visible everywhere
   - [Upstream Non-Free](https://f-droid.org/en/docs/Anti-Features/#UpstreamNonFree) - upstream source code is not libre, and this version has those parts replaced or rewritten
   - [Non-Free Assets](https://f-droid.org/en/docs/Anti-Features/#NonFreeAssets) - non-libre media in things that are not code (e.g. images, sound, music, 3D-models, or video)
   - [Known Vulnerability](https://f-droid.org/en/docs/Anti-Features/#KnownVuln) - known security vulnerability
   - [Disabled Algorithm](https://f-droid.org/en/docs/Anti-Features/#DisabledAlgorithm) - signed using an unsafe algorithm
   - [No Source Since](https://f-droid.org/en/docs/Anti-Features/#NoSourceSince) - source code no longer available, making new releases impossible

## Step 4: Check the App's Privacy Policy

1. Visit the app's official website, the app's information page on the Google Play Store or [F-Droid](https://f-droid.org/en), or the app's source code repository (e.g., GitHub, GitLab).
2. Look for a link to the privacy policy, typically found in the app's description, the app's settings, or the developer's website.
3. Read the privacy policy and take note of the following:
   - What data is collected by the app (e.g., personal information, usage data, etc.)
   - How the data is used and stored
   - If and how the data is shared with third parties
   - Any options for users to control their data

## Step 5: Compile Your Findings

Combine the information gathered from the previous steps to create a summary of the app's privacy aspects. This may include:

- [εxodus](https://reports.exodus-privacy.eu.org/en/) report: (number of trackers, number of permissions)
- [F-Droid](https://f-droid.org/en) Anti-Features: (list of Anti-Features found)
- Privacy Policy: (summary of the privacy policy)

By following this manual, you can examine Android apps' privacy aspects manually.

## Step 6: Example

### VLC

<img alt="VLC" height="64" src="https://github.com/videolan/vlc-android/raw/master/application/resources/assets/images/svg/icon.svg">

- [x] [εxodus report](https://reports.exodus-privacy.eu.org/en/reports/org.videolan.vlc/latest/): 0 trackers, 20 permissions
- [x] [F-Droid Anti-Features](https://f-droid.org/packages/org.videolan.vlc/): 0
- [x] [Privacy Policy](https://www.videolan.org/privacy.html): no bits collection unless you allow crash reporting.

> VLC software does not use any user account, and does not collect any user data, when working.
VideoLAN does not collect any data, nor any telemetry, when VLC is being run.
However, some limited personal information could be collected or shared in 3 precise cases:

- during the crash report process,
- during updates checking,
- for metadata retrieval.

There is also an archived version of the list of apps that is no longer maintained.