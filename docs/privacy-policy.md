# Frenpath Privacy Policy

**Effective date: September 24, 2026 · Last updated September 24, 2026**

Frenpath is a LumaLilt project for sharing statuses, making plans, and staying in touch. This policy explains how the Frenpath iPhone app and website handle information in the invitation-only testing service. “We,” “us,” and “our” refer to the team operating Frenpath.

For privacy questions or requests, contact **[support-frenpath@lumalilt.com](mailto:support-frenpath@lumalilt.com)**. Do not include your password or verification codes. We may ask for information needed to verify that a request concerns your account.

## 1. Information we handle

| Information | How it is used |
| --- | --- |
| Account and authentication information | Your display name, verified email and phone number, account identifiers, verification state, and session information support sign-in, recovery, invitation matching, and access controls. Firebase Authentication handles passwords and verification; Frenpath does not store your password in its application database. |
| Selected invitation details | The email address and/or phone number you select or type, intended circle, inviter, invitation token, expiry, and redemption status let us restrict an invitation to its intended recipient. This can include information about someone who has not joined yet. |
| Private cloud drafts | Content, times, categories, intended audiences, sharing settings, and source identifiers you explicitly save let you continue a draft across devices. Drafts are not visible to other members and do not appear in their feeds or generate plan notifications. |
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
- **Calendar review and posting:** matching events stay on your iPhone until you explicitly tap Save draft or Post for a chosen event. Matching can read titles and descriptions locally. The review list is never automatically uploaded as cloud drafts. Save draft sends the chosen item’s edited content, times, categories, intended audience and source identifiers to your private account so you can continue on another device. Post makes the confirmed content available to its selected audience. Calendar notes and location are not automatically copied into the post. Calendar changes do not automatically update or delete posted plans. Removing an item from the local review list does not delete the original calendar event.
- **On-device categorization:** on supported devices, Apple Intelligence through the Foundation Models framework can use an event’s title and details to suggest a category. This analysis runs on the device. You can review categories and suggested audiences before posting; no category suggestion automatically shares an event.
- **Writing to a calendar:** when you add a status to a calendar, its title, description, times, location, and links may be copied there. Your calendar provider and that calendar’s sharing settings then govern the copy.

Calendar matching setups, calendar links, unsent edits, and reminder preferences may be stored locally. The calendar review list is account-specific, limited to upcoming events, protected on disk and excluded from device backup; its saved review edits are also excluded from backup. Calendar review data is not automatically uploaded. Local candidates and their saved review edits are pruned as they expire or leave the review set. Disabling calendar permission stops calendar access but does not erase saved cloud drafts, posted statuses, or copies written to a calendar. App deletion, remote edits, and status deletion do not necessarily remove exported calendar copies.

Activity push notifications use an Apple device token, installation identifier, account association, notification preferences, and delivery records stored by Frenpath. Apple receives the notification text and routing identifiers to deliver the alert. Notifications and locally scheduled calendar or connection reminders can reveal plan or reminder details on your lock screen. You can control alert types in Frenpath and permissions and previews in iOS settings. Muting notifications does not remove Activity feed items.

Live Activities can show a current posted plan, its title and category, timing, and aggregate join, request, attendance, witness and AfterParty information on the Lock Screen or Dynamic Island. When enabled, we store an activity-specific Apple push token with your account, installation, plan identifier and delivery settings to send updates through Apple Push Notification service. Local calendar review items and private drafts are excluded. Attendee names, contact information and post descriptions are not included in Live Activity payloads. You can disable Live Activities or hide plan titles and categories in Frenpath Notifications settings. Activity registrations are removed when stopped, invalidated or cleaned up after expiry; deleting the account removes its registrations.

## 4. Location and nearby discovery

With permission, the iPhone app uses your location for nearby places, venues, and plans. Maps searches may send a search term and location or search region to Apple. Opening directions uses your chosen mapping service.

Searching for nearby plans does not itself make you discoverable. The Frenpath server uses the search area to return matches; the application does not save that search location as a location-history record. Infrastructure providers may still process request metadata and logs.

When you deliberately enable nearby discovery for a status, an approximate area is stored with that status. A place name or street address you add can be more precise and can be visible to the status’s audience. Do not include your home address or another private location unless you intend to share it. Frenpath does not provide continuous background location tracking.

## 5. Event discovery and AI

The event browser visits third-party websites, which receive ordinary web requests and may use cookies or other technologies under their own policies. Opening a search engine or an external AI service sends the information you choose to that service.

On supported iPhones, event extraction uses on-device processing, including Apple Foundation Models and, where available, text or image analysis of a page you ask it to read. Frenpath does not send your private calendar or event-page text to a remote language model for these local features.

Reading an event is different from contributing it. If you contribute a source, check an event for Local Legends, or create a status from extracted details, the submitted links, event details, area, and contribution records are sent to Frenpath. Approved community events can be published beyond your circles. Local processing does not make those later submissions private.

Extracted information can be wrong. Review dates, locations, and the original source before contributing or making plans.

## 6. Audiences, games, and sensitive information

A status can be private to you, shared with selected circles or people, or public to Frenpath members. Nearby discovery is an additional choice. “Public” does not promise publication to the entire internet; it does mean a broader audience within the service. People who receive content can still copy or share it outside the app.

Save draft stores content privately from other members; its intended audience and public/discovery settings take effect when you post. “Private” does not mean end-to-end encrypted or inaccessible to the providers and authorized administrators described below. A copied plan link remains subject to sign-in and audience checks; sharing a link alone does not grant access to a restricted plan.

Category defaults and calendar setup choices can preselect circles. Multiple categories can add their saved circles together, alongside people or circles you select directly. Review the displayed audience before saving a posted edit or tapping Post. Enabling Limit guests also enables Open to company; it does not by itself make a status public or enable nearby discovery. Open to company allows join requests, and confirmation depends on approval and capacity.

Returning your posted status to Drafts removes that shared occurrence and saves its editable content as a private cloud draft. This does not recall notifications, screenshots, messages, calendar exports or other copies someone holds. Reposting creates a new post and does not restore its previous invitations or join responses. Recurring schedules store the content, timing and sharing choices needed to generate their occurrences. Removing one occurrence or returning it to Drafts does not stop the schedule; stopping the series is a separate action.

Circle memberships, participation, game activities, leaderboards, and friend-visible trophies can reveal connections and attendance to the relevant audience. Private trophies use the private visibility option. Blocking restricts access within the app but cannot recall information someone already saw or copied.

Optional JW Mode stores planning preferences such as selected goals, service targets, companions, and notes. These can reveal religious beliefs or associations. Other statuses or categories can reveal health, caregiving, or similarly sensitive matters. Such information is not required for basic use; consider what you enter and whom you share it with. Setup preferences are not automatically a public profile, but plans you create from them follow their selected audiences.

The optional generation-based theme prompt does not save or transmit your generation answer; it uses the answer to choose a theme locally. The resulting theme preference may remain on that device.

## 7. Providers and other disclosures

We use service providers to operate the app, including:

- **Google Firebase Authentication** for account verification, sign-in, recovery, and abuse protection. Google receives and stores phone numbers used for authentication for spam and abuse prevention across Google services, including Firebase. See [Firebase’s phone-authentication disclosure](https://firebase.google.com/docs/auth/web/phone-auth) and [Google’s Privacy Policy](https://policies.google.com/privacy).
- **OpenAI Sites and its hosting infrastructure, including Cloudflare**, to host the website, API, and application database. Frenpath uses Firebase sign-in and does not require a ChatGPT account. Hosting through Sites does not mean local AI features send their inputs to ChatGPT.
- **Apple services**, where you use iOS, TestFlight, Maps, calendar integrations, or device features. TestFlight may provide developer-facing testing, crash, or feedback information under Apple’s settings and policies. See [Apple’s Privacy Policy](https://www.apple.com/legal/privacy/).

Authorized administrators may access information needed to provide support, moderate contributions, investigate abuse, and operate the service. We may disclose information when required by law or necessary to protect users, enforce service rules, or respond to security incidents. We do not promise that shared statuses are end-to-end encrypted.

When you report content, Frenpath sends moderators a copy of the reported content, your chosen reason and explanation, and your account identifier. Your identity is not shared with the person reported. Moderators can hide or restore content and keep decision notes. Limited report evidence and moderation records may be retained after content or account deletion to handle appeals, investigate abuse, and prevent repeated violations.

Frenpath does not sell personal information or integrate a third-party advertising network. Sponsored/ad placeholders can appear, and feedback about them is stored to operate and review that content.

## 8. Cookies and device storage

The website uses necessary authentication cookies and Firebase browser storage to provide sign-in, session restoration, and security. Frenpath’s session cookie lasts up to one hour; Firebase sign-in storage persists until sign-out or clearing it. Phone verification may load Google’s security challenge when you request a code. Settings you explicitly choose, including themes, category-audience behavior, and locally created connection reminders, use device storage to provide those features. Temporary form recovery may use session storage for the life of the tab.

Optional browser storage remembers unfinished plan drafts between visits, including any entered location and audience. It is off until you choose Accept all. Necessary only rejects all optional storage and removes saved browser drafts without signing you out, deleting your account, or changing published plans. Text currently open in an editor remains there until you close or leave it. These browser-only recovery copies expire 30 days after their last edit and are removed when the website next checks storage. Explicit Save draft stores a separate private cloud draft regardless of optional browser storage. Cloud drafts remain until you delete them, post them, or your account data is deleted. Posting removes the draft content and retains a small retry record to avoid duplicate posts.

Your choice, notice version, and decision time are stored on this browser for 180 days. You can change or withdraw the choice at any time using Privacy choices in the website footer or Settings. Withdrawal disables optional draft storage and removes saved drafts from this browser. Frenpath does not add advertising or analytics trackers. Accept all applies only to the optional storage described here.

These browser choices do not give blanket consent to processing personal information, change content audiences, or waive privacy rights. Necessary storage cannot be turned off through this optional-storage control; blocking it in your browser may prevent sign-in or other requested features. External websites have their own storage policies. The native iPhone app uses device storage for its requested features and does not use this browser draft-consent setting.

[Review or change your privacy choices](https://frenpath.com/privacy-choices).

Clearing browser/app data can remove local settings or sign you out. Signing out does not delete your server account. Device backups and calendar-provider copies may retain local information according to their own settings.

## 9. Retention and deletion

You can request account deletion in Frenpath Settings. Deletion removes app membership and associated personal app records, including owned statuses and circles, subject to the exceptions below. Deleting a circle can affect other members’ access to it.

Accounts also have an inactivity-deletion setting of **1, 3, or 6 months**, with **6 months as the default** and no Off option. The inactivity setting measures authenticated app activity, not only the last time you typed a password. Cleanup runs as the service is used, so deletion may occur after rather than precisely at the deadline.

Important limits:

- Firebase identity deletion is queued separately and retried. It is not guaranteed to complete at the same moment as deletion from the app database.
- Limited account identifiers and deletion/retry records can remain to enforce deletion and prevent inappropriate restoration.
- Approved community-event facts may remain as system-owned community content after the contributor’s account is deleted.
- Deletion cannot recall recipients’ copies, screenshots, shared messages, third-party website records, or exported calendar events.
- Provider logs and backups may have separate retention periods. There is no single guaranteed deletion deadline for every provider copy.

If you cannot sign in, contact us using the address above to request help or deletion. For invitation or access questions, you can also contact the person who invited you. Never share your password or verification codes with them. Do not send identity documents unless specifically requested through an appropriate private channel.

## 10. Your choices and requests

You can review audiences, edit or remove your content, manage circles and blocks, change reminder and discovery settings, revoke device permissions, and choose your inactivity period in the app. Some controls are device-specific.

Depending on where you live, applicable law may give you rights to access, correct, obtain a copy of, delete, restrict, or object to certain processing, withdraw consent, or complain to a privacy regulator. Contact us to exercise applicable rights or ask about information concerning an invited non-member. We may need to verify your identity and explain any legal or technical limits. Revoking a permission or withdrawing consent does not undo processing already carried out.

## 11. Security, international processing, and children

We use authenticated access, audience checks, secure transport, and restricted server credentials. No service or transmission can be guaranteed completely secure. Protect your account, device, and invitation links, and tell us if you suspect unauthorized access.

Our providers may process information in countries other than yours. Their arrangements and applicable law govern those transfers; this policy does not promise that all data stays in one country.

Frenpath is for people aged 16 and older. Enrollment is available for residents of the United States and Canada. We ask for a country of residence and an age band, not a birthday or identity document. We retain the declaration, eligibility state, source, policy version and update time to enforce account access across devices. The iPhone app can also receive an age range and applicable restrictions from Apple. These signals can be declarations; they do not establish legal identity or universally verified age. Recorded younger ages or restrictions are not cleared by choosing an older age on another device. Contact support for corrections, age-transition review, underage concerns or privacy requests. We do not provide a parent-managed child-account system, and parental permission does not waive our minimum age.

When available, Firebase App Check uses Apple App Attest to help confirm that an enrollment request comes from a genuine app instance. This does not verify your age or legal identity. We retain the resulting assurance label with eligibility information. Short-lived enrollment challenges and one-use token hashes prevent replay; expired entries are removed when the next challenge is created. We do not store the raw attestation token in the application database.

Protected accounts, including eligible 16–17-year-olds and accounts without established adult eligibility, use private sharing. Public and nearby sharing and automatic category-audience expansion are unavailable. New posts limit circle access to members included when shared, subject to current membership and blocks; newly added members do not automatically gain access to earlier posts. Automatic recurring expansion is paused for protected accounts without deleting saved setups. Account owners can still review their own saved information.

An invited person aged 16 or older in an unsupported country can join an email waitlist without creating an account or requesting an SMS. With explicit consent, we retain their provided email, country, age band, invitation reference, consent version and time, review state and contact dates so the Frenpath team can contact them about availability in that country. Waitlist email addresses are not independently verified and are not used for marketing. Only site administrators can view the contact list. Existing country-interest requests are not automatically enrolled for email. One entry is saved per invitation. People can leave through their original invitation even after it expires, or ask support to remove their details. Entries expire 180 days after the latest consent and are removed on the next waitlist/request check or associated account-data deletion. Joining does not create membership, reserve a position or guarantee availability; normal invitation and eligibility checks still apply when enrollment opens.

Admins assign separate Post Moderator, Image Moderator and trusted-uploader permissions to eligible adult accounts. Moderation access is limited by role and checked when content is reviewed or acted on. Image uploads are disabled. Role changes and country-request decisions have private audit records. Service restrictions do not remove the ability to contact support, request correction or request deletion.

## 12. About this notice

The date above identifies this notice. It describes Frenpath’s data handling and works alongside the [Terms of Use](https://frenpath.com/terms). Privacy choices and use of the service do not waive rights under applicable law.
