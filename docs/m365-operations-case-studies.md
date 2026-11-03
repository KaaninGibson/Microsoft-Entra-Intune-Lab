# Microsoft 365 Administration and Troubleshooting Case Studies

These are **anonymized categories of work** drawn from hands-on MSP support and independent tenant administration in 2026. They are not copied customer tickets, and they do not disclose customer names, identifiers, or private configurations. They describe work performed, not quantified business outcomes.

## Exchange Online and mail delivery

**Problem classes:** Missing or delayed email, mailbox permissions, retention/archive questions, and mail security filtering.

**Administrative approach:** Use Exchange Online PowerShell message traces and recipient settings; verify mailbox/calendar delegation, shared mailbox configuration, archive and retention settings; review Microsoft Defender and AppRiver/OpenText quarantine and allow/block rules. Validate message flow after authorized changes.

**Skills demonstrated:** Exchange Online, PowerShell, mail flow, least privilege, vendor coordination.

## Identity and access

**Problem classes:** MFA challenges, account lockouts, Conditional Access and guest access issues, SSO failures.

**Administrative approach:** Correlate sign-in results and policy scope, verify group membership and licensing, review sessions and authentication methods, and use Microsoft Graph PowerShell for account/group/licensing administration. Avoid weakening tenant-wide security to resolve one user issue.

**Skills demonstrated:** Entra ID, Conditional Access diagnostics, MFA, SSO, Microsoft Graph.

## Endpoint management and security

**Problem classes:** Intune enrollment and compliance failures, Autopilot setup questions, BitLocker recovery, Windows LAPS and endpoint alerts.

**Administrative approach:** Separate enrollment, policy assignment, per-device status and effective protection. Investigate endpoint alerts and suspicious access with the security team; document findings and escalation boundaries.

**Skills demonstrated:** Intune, Windows 11, Defender/EDR collaboration, security operations.

## Independent Microsoft 365 tenant

Built and administered a small-business Microsoft 365 tenant, configured a business domain and Entra identity, and created functional shared mailboxes. Used the environment for test endpoint-management and security workflows. The tenant is a **separate personal/business project**, not an employer-managed environment.

## Evidence policy

No actual customer messages, mailbox contents, ticket numbers, user names, secrets, or tenant identifiers are published. Individual incident metrics and resolution times have not been independently verified and are intentionally omitted.
