# DramaOps privacy policy

Policy version: 2026-11-04-v2. This policy covers the connected features of DramaOps Commander and DramaOps Studio for Windows, including the November 2026 preview repairs. Older releases may have different controls. The apps use YouTube API Services.

Contact the publisher at [dramaopszero@gmail.com](mailto:dramaopszero@gmail.com) about privacy, removal requests, or support. Do not send passwords, authorization tokens, or stream keys.

## Accounts, information and purpose

Google and Twitch handle sign-in and permission consent. DramaOps receives authorization tokens and provider account/channel identity, rather than your Google or Twitch password. Twitch and YouTube are optional, separate connections; using one does not require the other.

Depending on the features and permissions you select, the apps access channel IDs and names; broadcast and stream IDs; titles, descriptions, tags, categories, audience and visibility settings; thumbnails; ingest addresses and stream keys; platform statistics; and live-chat messages, author IDs, display names and timestamps. This information supports account verification, stream preparation, metadata editing, chat, overlays and reports you configure. A selected provider receives the metadata, thumbnail or message you submit through its connected controls or an action/trigger you explicitly enable. Enabled automatic actions can send messages without another click. Loading a saved game setup is separate from pressing Update to apply it.

Studio initially uses YouTube read-only access for identity and stream discovery. Its editing and chat flows ask for additional permissions when needed. Commander requests permissions used by its read, chat and metadata features. Google's scope descriptions can cover more operations than the app exposes; granting a scope does not mean every operation in that scope is implemented. New YouTube sign-in and permission-expansion flows include access to this policy, the DramaOps terms and the YouTube terms.

YouTube API readings are identified separately from DramaOps calculations. The repaired previews exclude YouTube readings from derived audience-growth predictions and combined Twitch audience summaries. Native output-health measurements come from DramaOps, not YouTube.

## Storage and sharing

Saved account credentials and ingest keys use Windows protection for the current Windows user. Studio associates accounts with output profiles. This does not encrypt every application file. Setups, scene configuration, artwork, copied thumbnails, reports, logs, diagnostics, exports and backups can be ordinary files on your computer. Recordings and exports are stored at the locations you choose. Uninstalling may preserve app data.

Authenticated local pairing lets Commander read Studio status and stream information, apply reviewed metadata changes and select configured scenes. Studio can read supported Commander chat, events and Twitch readings. Pairing does not copy one app's Google or Twitch OAuth credentials into the other app. Each app has its own account store and authorization.

Studio's publisher Google sign-in uses a DramaOps token-exchange service hosted by Cloudflare. The service processes authorization-code and refresh exchanges with Google and returns an encrypted response to the requesting desktop. This service is separate from static product pages and local app pairing.

When you configure your own Google Desktop app registration in Studio, authorization-code and refresh exchanges go directly to Google using that profile's registration. The optional client ID and Desktop client secret are protected for your Windows user and are separate from account tokens. Commander also supports an advanced user-provided Google registration. These options do not require a separate DramaOps user account.

Optional chat artwork is downloaded directly from fixed provider or public CDN services into bounded memory caches. Community emote catalogs from 7TV, BetterTTV and FrankerFaceZ are disabled until you opt in. Enabling a catalog discloses your public Twitch channel ID and ordinary network information to that service; provider authorization tokens are not sent to emote services. Unavailable or unsupported images fall back to text.

Optional advanced chat integrations use the credentials and destination identifiers you configure. Kick authorization and sending use Kick's official endpoints. Facebook Page chat uses Meta's official API and verifies the configured managed Page and broadcast. Receiving chat through a provider webhook requires a separately configured and authorized public endpoint; a local sign-in or enabled send adapter does not itself provide that endpoint. Unsupported providers and missing prerequisites are identified in the app. DramaOps does not ask you to supply browser-session cookies for these integrations.

Moderation controls require the relevant provider permission and a reviewed message, viewer and channel. A delete, timeout or ban is sent only after its explicit confirmation. An unconfirmed provider result is reported as unknown and is not automatically replayed. Other enabled chat automations retain the behavior described above.

Scripts, plugins, browser sources, media URLs and enabled integrations can contact their configured services and process the data you expose to them. Browser content may use cookies or similar storage under its host's policies. Scenes and overlays may display configured information publicly when you stream or share them. Review destinations and displayed content before use. Content you send to YouTube or Twitch is also processed under that provider's policies. Cloudflare processes network information needed to deliver and protect hosted services; see its [privacy policy](https://www.cloudflare.com/privacypolicy/). If you email support, your address and message are used to handle that request.

## Retention and removal

Credentials remain until replaced, removed or otherwise cleared. Studio's optional Google Desktop app registration remains after local account logout, grant revocation or profile removal unless you explicitly clear it. The removed-profile app-settings manager lists eligible registration files for review and clears only the selected file after checking the current library and file version; it does not revoke Google access or erase account tokens, other profiles, original media or backups. Clearing registration credentials can prevent later refreshes for that removed profile. Connected features refresh or revalidate authorization during use. The repaired Commander preview expires its tagged Google-derived caches and automatically collected replay references after 29 days, unless an eligible reference is freshly verified. Studio removes cached YouTube readings from its stream reports after 29 days while running or when next opened, preserving other-provider reports and native output health. These rules do not erase your original media or every file in a backup or export.

Local logout and Google revocation are distinct. Logout removes the selected app/profile's saved connection as described in its dialog; it does not itself revoke Google's grant. The explicit YouTube revoke-and-remove control explains the broader effect before acting. A Google grant can cover other profiles or clients in the same Google project. The default Commander and Studio publisher registrations use separate Google projects; custom registrations may differ.

The revoke-and-remove operation attempts Google revocation and removes the app-managed account records, account-bound destinations and supported caches identified by the app. A network failure, locked file or incomplete cleanup is reported as incomplete and can be retried. Studio retains a Windows-protected pending-removal record when necessary to retry an unconfirmed revocation, and blocks reuse of affected connections while removal is pending. Do not interpret a successful remote revocation alone as proof that every local copy was removed.

Commander's explicit revoke-and-delete control also clears all saved automation variables and run history and disarms triggers because older copies cannot be separated by provider. Action definitions, stream setups and original media remain.

User-authored setups, original media, manual stream destinations and copies held in exports, backups, other apps or hosted services can remain. A removal result identifies supported cleanup and warns about remaining copies; it does not delete content held by YouTube itself. Contact the publisher for help locating app-managed information and completing a broader deletion request. Backups and copies outside the running app need separate handling.

You may also revoke access in [Google Account permissions](https://security.google.com/settings/security/permissions). After revoking there, use the app's removal controls or contact the publisher to request local-data cleanup. To delete content stored on YouTube, use YouTube's own controls.

Read the [Google Privacy Policy](https://policies.google.com/privacy), [YouTube Terms of Service](https://www.youtube.com/t/terms) and [DramaOps terms](https://github.com/dramaopszero/dramaops-commander-releases/blob/main/TERMS.md). Public Google verification is a separate review; publication of this policy does not mean Google has approved DramaOps.
