# Defender for Office 365 – Daily Health Checklist 🛡️

## Secure Score
Review new recommended actions for Defender for Office.
```
EmailEvents | summarize count() by ThreatTypes
```

## MDO Overview
Check threat efficacy, detections, posture, risky allows, and trending attacks.
```
EmailEvents | summarize count() by DeliveryAction, ThreatTypes
```

## Uncaught Phish/Malware
Identify emails not remediated by ZAP.
```
EmailEvents | where DeliveryLocation == 'Inbox' and ThreatTypes != 'None'
```

## Risky Allows
Review messages bypassing protection via allow rules.
```
EmailEvents | where EmailAction == 'Allowed' and DetectionMethods has 'Allow'
```

## Explorer
Investigate active threats and take remediation actions.
```
EmailEvents | where Timestamp > ago(1d) and ThreatTypes != 'None'
```

## Threat Tracker
Review emerging campaigns and adjust defenses.
```
EmailEvents | summarize count() by SenderFromDomain
```

## Saved Queries
Reuse queries for consistent monitoring.

## Configuration Analyzer
Review policy gaps vs Standard/Strict baseline.
