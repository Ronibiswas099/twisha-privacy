# Twisha Privacy Policy

**Effective date: November 16, 2026**

Twisha is a Discord music bot developed by Soul and powered by Zyven Development. This policy explains what information Twisha processes when you use the bot, why it is used, and how to ask questions or request deletion.

## Information Twisha processes

Depending on the features used and the server configuration, Twisha may process:

- **Discord identifiers and server settings:** Discord user, server, channel, and role IDs; configured command prefixes; music and moderation settings; and premium or vote status.
- **Commands and command arguments:** Message content is read to recognize Twisha's prefix, direct mention, and owner-authorized no-prefix commands. The command handler also sends command-use logs to the bot owner's configured webhook. These logs can include the server, channel, user, and up to 1,500 characters of the command message.
- **Music data:** Track information needed to play audio, user-created playlists and favourites, and listening history when history is enabled. History entries contain track data and play timestamps. Twisha provides controls to disable or clear listening history.
- **Voice connection data:** Voice channel and voice-state information needed to join, play audio, and maintain music sessions.
- **Moderation event data:** When Discord reports a member leaving, Twisha checks the server audit log for a recent kick. If confirmed, it can send the server, removed member, moderator, and any available reason to the bot owner's configured webhook. This is used for server administration.
- **Feature and administration records:** Depending on use, this can include playlist ownership, staff-role settings, premium entitlements, vote records, badges, and no-prefix access or trial records.

Twisha does not request or use the Presence intent. It does not use member presence or activity status for its features.

## How information is used

Twisha uses this information to run commands, provide music and playlist features, remember server and user preferences, manage access to bot features, process configured integrations, and support bot administration and abuse prevention.

## Services that may receive information

Twisha communicates with Discord to operate as a bot and receive events permitted by its configured intents. Music playback requests are sent to the Lavalink audio service configured by the bot operator. The operator stores bot data using its configured PostgreSQL and Redis services.

If enabled or used, integrations such as Spotify, Top.gg, premium providers, and the bot owner's configured Discord webhooks may receive the information needed for that feature. For example, command-use and confirmed member-kick details may be sent to the operator's webhook. These services process information under their own policies and terms.

## Retention and deletion requests

Twisha keeps stored settings and feature data while they are needed to provide the bot's features and operate the service. Listening history is bounded and can be disabled or cleared with the bot's history controls. Retention periods for operational logs and provider-side records can depend on the bot operator's configuration and the relevant provider.

To ask a question or request deletion of information associated with your Discord account or server, contact the Twisha operators through the [Twisha support server](https://discord.gg/gm6pAGpNGu). Include the relevant server or user ID and the data you want reviewed. The operators may need to retain limited records where necessary for security, abuse prevention, or legal obligations.

## Security

The operators use technical and organizational measures intended to protect stored information. No online service or transmission can be guaranteed completely secure.

## Changes to this policy

This policy may be updated as Twisha's features or data practices change. The latest version will be published at this URL, with a revised effective date when appropriate.

## Contact

For privacy questions or deletion requests, contact the Twisha operators in the [support server](https://discord.gg/gm6pAGpNGu).

---

This policy describes Twisha's current implementation and integrations as understood by its operators. Third-party services are governed by their own privacy policies.
