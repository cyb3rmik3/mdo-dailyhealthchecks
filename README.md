# Defender for Office 365 – Daily Health Checks 🛡️
This guide provides a daily operational checklist for Microsoft Defender for Office 365 (MDO), helping security teams maintain strong posture, detect threats early, and continuously reduce risk.

## Secure Score 📊
- 🔗 [Go directly](https://security.microsoft.com/exposure-secure-scores) 
- 📍 Navigation
  - Microsoft Secure Score → Recommended actions
  - Filter → Product → Defender for Office
  - Filter → Status → Planned & To address
✅ Daily Check
- Review newly identified recommended actions
- Track any changes in posture or score impact

📜 History Review
- Filter → Product → Defender for Office
  - Track posture improvements over time
  - Validate progress against security goals

📚 Reference:
https://learn.microsoft.com/en-us/defender-xdr/microsoft-secure-score

📬 MDO Overview
🔗 https://security.microsoft.com/emailandcollaborationoverviewreport
This dashboard provides a high-level snapshot of email security health, threats, and protection effectiveness.

🛡️ Phish / Malware Efficacy


Pre-delivery
→ Shows how effectively threats are blocked before reaching users


Post-delivery (ZAP)
→ Confirms ability to remediate threats after delivery


Uncaught
→ Highlights gaps where threats remain in mailboxes



📈 Threat Detections

Displays total detected threats across protection technologies
→ Helps understand threat volume and trends


⚙️ Posture Recommendations

Shows % of users protected by Safe Links & Safe Attachments
→ Ensures consistent protection across all users and identifies gaps


🚫 Risky Allows
Messages Allowed

Emails bypassing filters due to allow entries
→ Identifies exposure caused by exceptions

Tenant Allow Types

Types of allow entries enabling delivery
→ Helps identify risky allowance patterns

Exchange Transport Rules

Mail flow rules that bypass protection
→ Highlights misconfigurations weakening defense


🎯 Top Trending Attacks

Most frequent phishing techniques targeting your organization
→ Enables proactive defense against common attack patterns


📚 Reference:
https://learn.microsoft.com/en-us/defender-office-365/reports-mdo-email-collaboration-dashboard

🔎 Explorer & 🌍 Threat Tracker
🔎 Explorer (Daily Operations)

Investigate active threats
Pivot across users, senders, and campaigns
Take immediate remediation actions (purge, submit, etc.)

✅ Expected Outcome:
Real-time visibility and rapid containment of threats before they spread

🌍 Threat Tracker (Proactive Defense)

Monitor emerging global attack campaigns
Assess relevance to your environment
Adjust defenses accordingly

✅ Expected Outcome:
Early warning and proactive protection against new threats

⚡ Operational Tip: Saved & Tracked Queries

Monitor recurring threat patterns automatically
Standardize investigations
Reduce manual effort and improve response time


📚 References:

https://learn.microsoft.com/en-us/defender-office-365/threat-explorer-real-time-detections-about
https://learn.microsoft.com/en-us/defender-office-365/threat-trackers


⚙️ Configuration Analyzer
🔗 https://security.microsoft.com/configurationAnalyzer
📍 Navigation
Microsoft Defender Portal
→ Email & Collaboration
→ Policies & Rules
→ Threat Policies
→ Configuration Analyzer

✅ Purpose

Central location to identify policy misconfigurations
Compare current settings against:

Standard protection baseline
Strict protection baseline




🎯 Daily Value

Detect weaker-than-recommended configurations
Identify opportunities to strengthen policies
Align with Microsoft best practices


📚 Reference:
https://learn.microsoft.com/en-us/defender-office-365/configuration-analyzer-for-security-policies

✅ Summary – Daily Operational Mindset
By performing these checks daily, you will:

🔐 Maintain a strong and evolving security posture
🚨 Detect and respond to threats faster
⚠️ Identify and eliminate hidden risks and misconfigurations
🌍 Stay ahead of emerging attack patterns
