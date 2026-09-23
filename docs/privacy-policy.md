# Frenpath Privacy Policy

**Effective date: September 20, 2026 · Last updated September 22, 2026**

Frenpath is a LumaLilt project for sharing statuses, making plans, and staying in touch. This policy explains how the Frenpath iPhone app and website handle information during the current invitation-only testing service. “We,” “us,” and “our” refer to the team operating Frenpath.

For privacy questions or requests, contact **[support-frenpath@lumalilt.com](mailto:support-frenpath@lumalilt.com)**. Do not include your password or verification codes. We may ask for information needed to verify that a request concerns your account.

## 1. Information we handle

| Information | How it is used |
| --- | --- |
| Account and authentication information | Your display name, verified email and phone number, account identifiers, verification state, and session information support sign-in, recovery, invitation matching, and access controls. Firebase Authentication handles passwords and verification; Frenpath does not store your password in its application database. |
| Selected invitation details | The email address and/or phone number you select or type, intended circle, inviter, invitation token, expiry, and redemption status let us restrict an invitation to its intended recipient. This can include information about someone who has not joined yet. |
| Statuses and relationships | Titles, descriptions, categories, start/end times, recurrence, places, addresses, links, audiences, circles, memberships, invitations, join requests, and responses provide the planning and sharing features. |
| Participation and contributions | Activity records, attendance confirmations, witnesses, game enrollment, points, streaks, trophies, event/source contributions, verification feedback, and reports support games, community discovery, moderation, and abuse prevention. |
| Preferences and account activity | Interests, category audiences, optional setup information, blocking choices, and records of authenticated activity support personalization, privacy choices, and inactivity deletion. Some preferences are stored on your device rather than the server. |
| Technical information | Our hosting and authentication providers receive information needed to deliver and protect the service, such as IP addresses, browser/device information, request information, and diagnostic or security logs. |

Your display name and profile identifier can appear to other signed-in members in people-selection and social features. Email and phone details are used for authentication and invitations, not displayed as public profile fields. An invitation sender can see the contact details they supplied and the invitation’s status.

## 2. Contacts and invitations

On iPhone, we use the system contact picker to let you choose a contact. We use only the details you select and confirm; we do not upload your full address book. You can also enter contact details manually.

You decide whether to share an invitation using Mail, Messages, a share sheet, or a copied link. Those apps handle delivery under their own policies. Frenpath does not automatically message your friend. Firebase separately sends authentication emails and SMS verification messages when requested.

Share invitations only with the intended recipient, and provide other people’s contact details responsibly. An invited person must verify a matching contact detail before accepting. Regular membership also requires both a verified email and phone number. A limited, specifically configured app-review account is exempt from phone setup.

## 3. Calendar information and reminders

Calendar access is optional and controlled through iOS permissions and Frenpath settings.

- **Finding openings:** the app reads calendar availability on your device to suggest times and schedule local reminders. It does not upload detailed calendar events merely to find free slots.
- **Calendar-to-status sync:** events covered by your enabled sync rules become server-stored statuses. The current automatic import sends the event title—or “Busy” for a busy-only rule—times, category, selected audience, and a derived source identifier used to manage updates. It does not copy the event’s full notes into the status description. Imported information is shared according to the rule and any enabled category-audience setting.
- **On-device categorization:** on supported devices, Apple Intelligence through the Foundation Models framework can use an event’s title, time, location, and details to suggest a category. This analysis runs on the device; the resulting category can be saved with the imported status. Applying category audiences is a separate setting.
- **Writing to a calendar:** when you add a status to a calendar, its title, description, times, location, and links may be copied there. Your calendar provider and that calendar’s sharing settings then govern the copy.

Sync rules, import queues, calendar links, drafts, and reminder preferences may be stored locally. Disabling a permission stops future access but does not by itself erase statuses already imported or copies already written to a calendar. App deletion, remote edits, and status deletion do not necessarily remove exported calendar copies.

Local notifications may contain plan or reminder details on your lock screen. You can control notifications and previews in iOS settings.

## 4. Location and nearby discovery

With permission, the iPhone app uses your location for nearby places, venues, and plans. Maps searches may send a search term and location or search region to Apple. Opening directions uses your chosen mapping service.

Searching for nearby plans does not itself make you discoverable. The Frenpath server uses the search area to return matches; the current application does not save that search location as a location-history record. Infrastructure providers may still process request metadata and logs.

When you deliberately enable nearby discovery for a status, an approximate area is stored with that status. A place name or street address you add can be more precise and can be visible to the status’s audience. Do not include your home address or another private location unless you intend to share it. Frenpath does not provide continuous background location tracking.

## 5. Event discovery and AI

The event browser visits third-party websites, which receive ordinary web requests and may use cookies or other technologies under their own policies. Opening a search engine or an external AI service sends the information you choose to that service.

On supported iPhones, event extraction uses on-device processing, including Apple Foundation Models and, where available, text or image analysis of a page you ask it to read. Frenpath does not send your private calendar or event-page text to a remote language model for these local features.

Reading an event is different from contributing it. If you contribute a source, check an event for Local Legends, or create a status from extracted details, the submitted links, event details, area, and contribution records are sent to Frenpath. Approved community events can be published beyond your circles. Local processing does not make those later submissions private.

Extracted information can be wrong. Review dates, locations, and the original source before contributing or making plans.

## 6. Audiences, games, and sensitive information

A status can be private to you, shared with selected circles or people, or public to Frenpath members. Nearby discovery is an additional choice. “Public” does not promise publication to the entire internet; it does mean a broader audience within the service. People who receive content can still copy or share it outside the app.

Circle memberships, participation, game activities, leaderboards, and friend-visible trophies can reveal connections and attendance to the relevant audience. Private trophies use the private visibility option. Blocking restricts access within the app but cannot recall information someone already saw or copied.

Optional JW Mode stores planning preferences such as selected goals, service targets, companions, and notes. These can reveal religious beliefs or associations. Other statuses or categories can reveal health, caregiving, or similarly sensitive matters. Such information is not required for basic use; consider what you enter and whom you share it with. Setup preferences are not automatically a public profile, but plans you create from them follow their selected audiences.

The optional generation-based theme prompt does not save or transmit your generation answer; it uses the answer to choose a theme locally. The resulting theme preference may remain on that device.

## 7. Providers and other disclosures

We use service providers to operate the app, including:

- **Google Firebase Authentication** for account verification, sign-in, recovery, and abuse protection. Google receives and stores phone numbers used for authentication for spam and abuse prevention across Google services, including Firebase. See [Firebase’s phone-authentication disclosure](https://firebase.google.com/docs/auth/web/phone-auth) and [Google’s Privacy Policy](https://policies.google.com/privacy).
- **OpenAI Sites and its hosting infrastructure, including Cloudflare**, to host the website, API, and application database. A ChatGPT account is not required for current Frenpath sign-in. Hosting through Sites does not mean local AI features send their inputs to ChatGPT.
- **Apple services**, where you use iOS, TestFlight, Maps, calendar integrations, or device features. TestFlight may provide developer-facing testing, crash, or feedback information under Apple’s settings and policies. See [Apple’s Privacy Policy](https://www.apple.com/legal/privacy/).

Authorized administrators may access information needed to provide support, moderate contributions, investigate abuse, and operate the service. We may disclose information when required by law or necessary to protect users, enforce service rules, or respond to security incidents. We do not promise that shared statuses are end-to-end encrypted.

When you report content, Frenpath sends moderators a copy of the reported content, your chosen reason and explanation, and your account identifier. Your identity is not shared with the person reported. Moderators can hide or restore content and keep decision notes. Limited report evidence and moderation records may be retained after content or account deletion to handle appeals, investigate abuse, and prevent repeated violations.

The current app does not integrate a third-party advertising network or sell personal information. Sponsored/ad placeholders may appear, and related feedback may be stored. Those placeholders are not a claim that a live ad network is receiving your data. We will update this policy before introducing materially different advertising or data uses.

## 8. Cookies and device storage

The website uses necessary authentication cookies and Firebase browser storage to provide sign-in, session restoration, and security. Frenpath’s session cookie lasts up to one hour; Firebase sign-in storage persists until sign-out or clearing it. Phone verification may load Google’s security challenge when you request a code. Settings you explicitly choose, including themes, category-audience behavior, and locally created connection reminders, use device storage to provide those features. Temporary form recovery may use session storage for the life of the tab.

Optional browser storage remembers unfinished plan drafts between visits, including any entered location and audience. It is off until you choose Accept all. Necessary only rejects all optional storage and removes saved browser drafts without signing you out, deleting your account, or changing published plans. Text currently open in an editor remains there until you close or leave it. Drafts expire 30 days after their last edit and are removed when the website next checks storage.

Your choice, notice version, and decision time are stored on this browser for 180 days. You can change or withdraw the choice at any time using Privacy choices in the website footer or Settings. Withdrawal stops future draft storage and removes saved drafts from this browser. We do not add advertising or analytics trackers. A new optional purpose would require a new choice; Accept all does not authorize undisclosed future uses.

These browser choices do not give blanket consent to processing personal information, change content audiences, or waive privacy rights. Necessary storage cannot be turned off through this optional-storage control; blocking it in your browser may prevent sign-in or other requested features. External websites have their own storage policies. The native iPhone app uses device storage for its requested features and does not use this browser draft-consent setting.

[Review or change your privacy choices](https://frenpath.com/privacy-choices).

Clearing browser/app data can remove local settings or sign you out. Signing out does not delete your server account. Device backups and calendar-provider copies may retain local information according to their own settings.

## 9. Retention and deletion

You can request account deletion in Frenpath Settings. Deletion removes app membership and associated personal app records, including owned statuses and circles, subject to the exceptions below. Deleting a circle can affect other members’ access to it.

Accounts also have an inactivity-deletion setting of **1, 3, or 6 months**, with **6 months as the default** and no Off option. The current implementation measures authenticated app activity, not only the last time you typed a password. Cleanup runs as the service is used, so deletion may occur after rather than precisely at the deadline.

Important limits:

- Firebase identity deletion is queued separately and retried. It is not guaranteed to complete at the same moment as deletion from the app database.
- Limited account identifiers and deletion/retry records can remain to enforce deletion and prevent inappropriate restoration.
- Approved community-event facts may remain as system-owned community content after the contributor’s account is deleted.
- Deletion cannot recall recipients’ copies, screenshots, shared messages, third-party website records, or exported calendar events.
- Provider logs and backups may have separate retention periods. We do not currently promise a fixed deletion deadline for every provider copy.

If you cannot sign in, contact us using the address above to request help or deletion. For invitation or access questions, you can also contact the person who invited you. Never share your password or verification codes with them. Do not send identity documents unless specifically requested through an appropriate private channel.

## 10. Your choices and requests

You can review audiences, edit or remove your content, manage circles and blocks, change reminder and discovery settings, revoke device permissions, and choose your inactivity period in the app. Some controls are device-specific.

Depending on where you live, applicable law may give you rights to access, correct, obtain a copy of, delete, restrict, or object to certain processing, withdraw consent, or complain to a privacy regulator. Contact us to exercise applicable rights or ask about information concerning an invited non-member. We may need to verify your identity and explain any legal or technical limits. Revoking a permission or withdrawing consent does not undo processing already carried out.

## 11. Security, international processing, and children

We use authenticated access, audience checks, secure transport, and restricted server credentials. No service or transmission can be guaranteed completely secure. Protect your account, device, and invitation links, and tell us if you suspect unauthorized access.

Our providers may process information in countries other than yours. Their arrangements and applicable law govern those transfers; this policy does not promise that all data stays in one country.

Frenpath is not designed specifically for children. We do not offer a parent-managed child-account system. If you believe a child has provided information in circumstances requiring parental consent, contact us so we can investigate and address it.

## 12. Policy updates

We will revise this document as the service changes and update the effective date. Where required, we will provide notice or obtain consent before material changes take effect. This policy describes current practices, not unbuilt features or a guarantee that experimental features will remain available.
