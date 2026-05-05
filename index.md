# Privacy Policy

**Backlog & Prioritization App**
*Last updated: May 4, 2026*

## Overview

The Backlog & Prioritization App ("the App") is an internal productivity tool built for AB InBev's BEES development teams. It serves as a mobile companion for the Backlog & Prioritization Hub, enabling team members to manage and rank backlog items on the go.

This policy describes how the App collects, uses, and protects your information.

## Data We Collect

### Authentication Data
- **Jira session credentials**: Used to authenticate you via your existing Jira account through OAuth. Session tokens are stored securely and expire after 30 days.

### Push Notification Data
- **Firebase Cloud Messaging (FCM) token**: A device-specific identifier used to deliver push notifications. This token does not contain personal information.
- **Device platform**: Whether you are using iOS or Android, stored alongside your FCM token.
- **Device identifier**: A randomly generated UUID unique to your app installation, used to manage your notification preferences.

### Usage Data
- **Rank changes and session activity**: Actions you perform within the App (e.g., ranking items, syncing changes) are recorded for audit and operational purposes.

## How We Use Your Data

- **Authentication**: To verify your identity and authorize access to backlog data.
- **Push Notifications**: To alert you when new items require ranking or when items are returned from frozen/fridged states.
- **Operational Integrity**: To maintain audit trails of rank changes and ensure data consistency with the web-based Hub.

## Third-Party Services

| Service | Provider | Purpose |
|---------|----------|---------|
| Firebase Cloud Messaging | Google | Push notification delivery |
| Jira Cloud | Atlassian | Authentication and backlog data |

We do not share your data with any other third parties. We do not use any analytics, advertising, or tracking SDKs.

## Data Storage & Security

- All data is stored in a secured PostgreSQL database hosted on AB InBev's infrastructure.
- Session tokens are encrypted and transmitted over HTTPS.
- FCM tokens are deactivated upon logout and marked inactive when they become stale.

## Data Retention

- **Session tokens**: Expire after 30 days of creation. Invalidated immediately upon logout.
- **FCM tokens**: Deactivated on logout. Stale tokens are automatically cleaned up when delivery fails.
- **Rank change logs**: Retained indefinitely for audit purposes.

## Your Rights

- **Logout**: Logging out of the App immediately invalidates your session and deactivates push notifications for your device.
- **Data Access**: Contact the development team to request a copy of data associated with your account.
- **Data Deletion**: Contact the development team to request deletion of your data.

## Children's Privacy

This App is not intended for use by individuals under the age of 18. We do not knowingly collect data from children.

## Changes to This Policy

We may update this Privacy Policy from time to time. Changes will be communicated through the App or via internal channels.

## Contact

For questions about this Privacy Policy or your data, contact the BEES Development team.
