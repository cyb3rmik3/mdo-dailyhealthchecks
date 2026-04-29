# KQL Queries

Under queires > Community Queries > Microsoft 365 Defender > Email and Collaboration Queries

#### General

- Provide broad visibility across email threats, detections, and user activity
- Includes queries such as:
-- All email events with threat verdicts
 - Messages containing malicious links or attachments
 - User interaction with phishing (clicks, opens)

👉 In short:
“Baseline queries to understand overall email threat activity and user exposure.”

#### Mailflow

- Focus on how emails are processed and delivered through the system
- Includes queries such as:
 - Email delivery status (Delivered, Blocked, Quarantined)
 - Message trace-like visibility (sender → recipient flow)
 - Filtering decisions and policy actions applied

👉 In short:
“Queries to trace email delivery paths and understand how messages were handled.”

#### Overrides

- Identify where security controls were bypassed or overridden
- Includes queries such as:
 - Emails allowed due to Tenant Allow/Block List
 - Messages impacted by transport (mail flow) rules
 - Safe Links/Safe Attachments overrides or exclusions

👉 In short:
“Queries that expose security exceptions and potential protection gaps.”

#### Top Attacks

- Highlight the most prevalent and impactful threat types
- Includes queries such as:
 - Top phishing campaigns by volume
 - Most targeted users/domains
 - Common attack techniques (credential harvesting, malware delivery)

👉 In short:
“Queries that surface the most common attacks targeting your organization.”
