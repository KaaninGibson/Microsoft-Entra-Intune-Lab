# Entra and Intune: evidence selection audit

This document records the curated evidence selection. Selected screenshot derivatives have now been uploaded to the repository; see the [published gallery](published-evidence-gallery.md). The original archives and unredacted images must remain private. Publication is not a guarantee that every small identifier has been cleared.

| Candidate | Supported observation / limit |
|---|---|
| Device restrictions profile | Configuration exists; assignment and success require separate result. |
| Compliance settings | Multiple compliant states and one encryption error. |
| Directory groups screenshot | Removed from current branch: displayed object IDs and did not show application assignments. |
| BitLocker policy | One succeeded; not proof of volume encryption. |
| Windows LAPS policy | Policy settings, not password retrieval proof. |
| LAPS rotation | Last password rotation timestamp visible; no password disclosed. |
| Microsoft Entra device settings | Device registration settings; not a Windows Update ring. |
| Conditional Access policy | Report-only; not enforced. |
| CA report-only result | Report-only failure; no enforced block. |
| Managed device | Corporate, compliant, Intune-managed status at screenshot time. |

## Publication standard

Only upload full-resolution derivatives after checking for user names, email addresses, tenant/subscription/device/object IDs, public IP addresses, hardware serials, recovery keys, secrets, and hidden metadata. A configuration screen is not proof of deployment, a script filename is not proof of execution, and an error is not proof of success.

## Excluded evidence

Duplicated inventory views, empty Drive Maps editor, unassigned or pending Autopilot profile states when presented as successes, and the zero-byte PowerShell script screenshot are not recommended as primary portfolio evidence. They can be documented as troubleshooting only when useful.

## Status

The image upload is complete for the selected set (9 currently published; one removed due to visible directory IDs). The captions and selection notes have been reconciled with the uploaded filenames. Final independent full-resolution privacy certification is **not** claimed; a removed image may persist in Git history.
