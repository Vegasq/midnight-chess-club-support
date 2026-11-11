# Midnight Chess Club Privacy Policy

Effective 11 November 2026. This policy describes version 0.19 and the matching hosted service. Earlier installed development builds may not offer all controls described below.

Midnight Chess Club stores your game progress on your device and sends some information to our servers when connected. Campaign and Vs AI can continue without a server connection; their gameplay records are queued locally and uploaded when a connection is available. Offline play therefore does not mean that those records will never leave your device.

For privacy questions or requests, contact **[chess@mkla.dev](mailto:chess@mkla.dev)**. Midnight Chess Club is developed by Mykola Yakovliev. Our support page is **[Midnight Chess Club Support](https://github.com/Vegasq/midnight-chess-club-support)**.

## Information stored on your device

The game keeps your save slots, chosen display names and avatars, progress, card collections, selected decks, current games, tutorial progress and preferences on your device. It also stores generated profile identifiers, a credential used to recognize each profile, queued gameplay records and local achievement progress. Achievement records and unlocked avatar choices may be shared across the save slots on the same device.

In the browser version, game records use browser storage. Clearing that storage, removing the app or deleting a save may remove information needed to resume a game or identify a profile. The game does not currently provide general cross-device account linking or a cloud-save replacement for your local campaign.

## Information sent to our servers

When the game connects, the information it sends can include:

- Your chosen display name and avatar, generated profile identifier, and information needed to authenticate the profile. The server stores a hash of the profile credential.
- A randomly generated identifier associated with a local save's gameplay records. It helps distinguish and deduplicate uploaded events; it is not an advertising identifier or a hardware serial number.
- Multiplayer room membership, selected decks, game positions, moves, card plays, opening-hand choices, results and match history.
- Campaign and Vs AI records, including event times, run and opponent identifiers, difficulty and reward settings, random seeds, moves, cards played or drawn, results, XP, card discoveries, deck choices and whether testing mode was used.

These records are associated with a profile and are not anonymous merely because a real name or email address is not required to play. We use them to operate multiplayer, maintain progression and result records, recover or deduplicate requests, understand game balance and improve reliability.

Our servers and hosting services also process network information, such as your IP address and request details, to deliver connections, limit abusive requests and maintain the service. The game does not request access to your precise location, contacts, microphone, camera or photo library.

## What other players can see

Other players can see the display name and avatar used at a multiplayer table. Open-table listings can expose the host's chosen name and avatar to people browsing tables. An opponent sees the public board, played cards, turn history, results and the hand or deck counts shown by the game; your unplayed hand remains private during normal multiplayer play.

Choose a display name that you are comfortable showing to other players. The game currently has no working player-to-player text chat.

## Support and diagnostic information

If you contact support, we receive the email address you use and the information you choose to send. The game can create a local support report containing technical details such as its version, platform, screen size, connection status, room code and recent public game actions. Creating or copying a report does not automatically send it to us. Review its contents before sharing it.

Some development or testing builds can produce additional local performance reports when explicitly enabled. Those local reports are separate from the routine gameplay statistics upload.

## Platform services and service providers

In builds configured for a platform achievement service, such as Apple Game Center, the game can read your platform identity and achievement progress and report progress to that service. Platform sign-in, account controls and the provider's own handling of data are governed by that provider's terms and privacy information. A platform account is not automatically linked to all of your local saves or to another platform's account.

We use hosting infrastructure to run the multiplayer and statistics services and email infrastructure to respond to support requests. Those providers process information needed to provide their services. Internet services may process information in countries other than the country where you live.

The current game does not show advertising, use an advertising identifier, sell personal information or combine gameplay records with activity from other companies' apps or websites for targeted advertising. Gameplay statistics are used for the game itself, including balance and reliability analysis.

## Storage and security

The game uses HTTPS for its hosted service. Local profile credentials and saved games should be treated as private: someone with access to them may be able to act as that profile. No transmission or storage method can guarantee complete security.

Server-side profile, game and statistics records are persistent, and the current implementation does not automatically expire them after a fixed period. Copies can also exist in operational backups.

## Your choices and requests

You can change local preferences, choose the information in your display name, use the offline game modes without an active connection, and delete a local save slot through its confirmation flow. Queued campaign and Vs AI records can still be uploaded if that save reconnects later. The current game has no separate switch that disables those uploads while keeping the same save online.

Settings > **Delete profile & server data** and the save-slot Delete action open a confirmation naming the selected profile. **Remove from this device** removes only that local save. **Delete profile & server data** also sends an authenticated request to erase the server profile, its campaign records, related multiplayer rooms and uploaded gameplay/statistics records. Other players keep progression they already earned.

The server-deletion choice first saves a pending request locally and stops that profile from playing or uploading more records. If offline or the service is unavailable, the request remains pending and can be retried; keep the app and its stored data until confirmation. Other save slots remain usable. After server confirmation, the local profile is removed. Minimal one-way hashes of the generated profile identifier and credential remain on the server to prevent copied credentials or stale queued uploads from recreating the deleted identity.

Neither choice resets device-wide achievements or avatar unlocks, or erases records held by an independent platform service. Removing the app or clearing browser storage does not by itself remove server records and can remove a deletion request that has not yet completed. The in-game endpoint does not erase separately retained hosting logs or historical operational backups; those copies may remain, and current storage has no automatic expiry. Contact support about those records. A backup must not be restored into active service without reapplying later erasures and revocations.

Contact **chess@mkla.dev** about access, correction or deletion of information held by us. We may need information to verify that a request concerns your profile. Requests involving platform-owned data must also follow that platform's account controls.

## Children and age suitability

The campaign contains supernatural horror and unsettling narrative themes. Follow the age suitability information shown by your app store. The game does not ask players to provide their date of birth and does not currently perform age verification. A parent or guardian can contact **chess@mkla.dev** with questions about a child's information.

## Changes and contact

We will update this policy when the game's data practices change and identify the new effective date here. Contact **[chess@mkla.dev](mailto:chess@mkla.dev)** for privacy questions or requests, or visit **[Midnight Chess Club Support](https://github.com/Vegasq/midnight-chess-club-support)**.
