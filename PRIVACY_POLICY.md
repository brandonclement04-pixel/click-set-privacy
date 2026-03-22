# Privacy Policy for Click Set

**Last updated: March 22, 2026**

Brandon Clement ("we", "our", or "us") built Click Set as a commercial application. This Privacy Policy explains how we collect, use, and protect your information when you use Click Set ("the App").

## Information We Collect

### Information You Provide

- **Planning Center Account Data**: If you choose to connect your Planning Center Online account, we temporarily process your Planning Center OAuth access token and refresh token to import your service plans, songs, and arrangements. Your Planning Center credentials (username and password) are never collected or stored by the App — authentication is handled entirely through Planning Center's secure OAuth 2.0 flow.

- **Song and Arrangement Data**: Songs, click sets, tempos, time signatures, sections, and arrangements you create or import are stored locally on your device using Apple's SwiftData framework.

### Information Collected Automatically

- **Subscription Status**: The App uses Apple's StoreKit 2 framework to manage subscriptions. Your purchase history and subscription status are managed entirely by Apple. We do not collect, store, or have access to your payment information, Apple ID, or transaction details.

### Information We Do Not Collect

- We do **not** collect personal identification information (name, email, phone number, address)
- We do **not** collect analytics, usage data, or telemetry
- We do **not** use any third-party analytics or advertising SDKs
- We do **not** collect device identifiers, IP addresses, or location data
- We do **not** collect crash reports automatically
- We do **not** track you across apps or websites

## How We Use Your Information

- **Planning Center tokens** are used solely to authenticate API requests to import your service plans. Tokens are stored securely in your device's Keychain and are never transmitted to any server other than Planning Center's API (`api.planningcenteronline.com`).
- **Song and arrangement data** is stored locally on your device and is never uploaded to our servers. Exported `.clickset` files are created locally and shared only through methods you choose (AirDrop, Files, etc.).

## Data Storage and Security

- Planning Center OAuth tokens are stored in the device Keychain, protected by Apple's hardware-backed encryption.
- All song and arrangement data is stored locally on your device using SwiftData.
- Network communication with Planning Center uses HTTPS encryption.
- We do not operate any servers that store your data.

## Third-Party Services

The App integrates with the following third-party services:

- **Apple StoreKit**: For managing in-app subscriptions. Subject to [Apple's Privacy Policy](https://www.apple.com/privacy/).
- **Planning Center Online** (optional): For importing service plans. Subject to [Planning Center's Privacy Policy](https://planning.center/privacy). This integration is entirely optional and requires your explicit authorization.

## Data Retention and Deletion

- All app data is stored locally on your device. Uninstalling the App removes all locally stored data.
- You can disconnect your Planning Center account at any time from Settings, which immediately deletes all stored tokens from the Keychain.
- You can delete individual songs, sets, or all data from within the App at any time.

## Children's Privacy

Click Set does not knowingly collect personal information from children under 13. The App does not require account creation and does not collect personal data.

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time. Changes will be posted on this page with an updated revision date. Your continued use of the App after changes are posted constitutes acceptance of the revised policy.

## Your Rights

Since we do not collect or store personal data on our servers, there is no personal data for us to provide, modify, or delete. All your data remains on your device under your control.

## Contact Us

If you have questions about this Privacy Policy, please contact us at:

**Email**: brandonclement06@icloud.com
