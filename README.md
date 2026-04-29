# mdo-dailyhealthchecks


## Secure Score

https://security.microsoft.com/exposure-secure-scores

Blade: Microsoft Secure Score
> Recommended actions
> Filter > Product > Defender for Office > Apply
> Filter > Status > Planned & To address

Ask yourself:
Key take away: Do I have any new recommended actions that will reduce my posture?

> History
> Filter > Product > Defender for Office > Apply

## MDO Overview

https://security.microsoft.com/emailandcollaborationoverviewreport

### Phish / Malware Efficacy card
- Pre-delivery: Items detected before they reach the recipient's mailbox.
→ Shows how effectively threats are blocked before impact, reducing user exposure and risk.
- Post-delivery: Items removed after the item was delivered to the recipient's mailbox via zero-hour auto purge (ZAP).
→ Confirms your ability to remediate threats after delivery, minimizing dwell time.
- Uncaught: Delivered items that ZAP identified but failed to remove.
→ Highlights detection or response gaps where threats remain in user mailboxes.

### Threat detections card
The graph on the Threat detections card shows the number of messages detected by the MDO protection technologies.

### Posture recommendations
The graph on the Policy recommendations card shows the number of users directly protected by Safe Links and Safe Attachments policies as a percentage of the total number of users (the value 100% means everyone is protected).
→ Ensures all users are consistently protected by key controls, reducing exposure due to misconfigurations.

### Risky allows section

#### Messages allowed card
The Messages allowed card shows the count of messages allowed by user or organization allow entries that bypass protection.
→ Identifies emails bypassing security controls due to allow entries, exposing the organization to risk.

#### Tenant allow types card
The Tenant allow types card shows a table with the types of allow entries in the Tenant Allow/Block List that let bad mail get delivered to user mailboxes.
→ Reveals which allow mechanisms introduce risk, helping you minimize unsafe exceptions.

#### Exchange transport rules
The Exchange transport rules card shows the mail flow rules (also known as transport rules) that allowed messages that would otherwise be blocked.
→ Highlights mail flow rules that may unintentionally weaken protection and allow malicious emails through.

### Top trending attacks card
The graph on the Top trending attacks card shows the most encountered phishing attack types by volume for the review period selected.
→ Helps understand the most common phishing techniques targeting your organization so you can proactively defend against them.

