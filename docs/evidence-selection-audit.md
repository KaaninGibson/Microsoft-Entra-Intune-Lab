# Entra and Intune: evidence selection audit

This document records the **curated, private** screenshot candidates selected from the original lab archives. The screenshots in this list are **not uploaded or approved for public display** merely because they appear here. Original archives and unredacted images must remain private.

| Candidate | Supported observation / limit |
|---|---|
| Device restrictions profile | Configuration exists; assignment and success require separate result. |
| Compliance settings | Multiple compliant states and one encryption error. |
| Assigned apps list | Application listing; not installation success unless status shown. |
| BitLocker policy | One succeeded; not proof of volume encryption. |
| Windows LAPS policy | Policy settings, not password retrieval proof. |
| LAPS rotation | Last password rotation timestamp visible; no password disclosed. |
| Windows Update ring | Update-ring configuration, not proof of installed updates. |
| Conditional Access policy | Report-only; not enforced. |
| CA report-only result | Report-only failure; no enforced block. |
| Managed device | Corporate, compliant, Intune-managed status at screenshot time. |

## Publication standard

Only upload full-resolution derivatives after checking for user names, email addresses, tenant/subscription/device/object IDs, public IP addresses, hardware serials, recovery keys, secrets, and hidden metadata. A configuration screen is not proof of deployment, a script filename is not proof of execution, and an error is not proof of success.

## Excluded evidence

Duplicated inventory views, empty Drive Maps editor, unassigned or pending Autopilot profile states when presented as successes, and the zero-byte PowerShell script screenshot are not recommended as primary portfolio evidence. They can be documented as troubleshooting only when useful.

## Status

Candidate selection is documented; final full-resolution privacy clearance and image upload have **not** been completed. No claim of successful publication is made here.
