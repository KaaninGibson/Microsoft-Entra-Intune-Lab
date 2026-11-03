# Microsoft Entra Intune Lab — Published Screenshot Gallery

These nine images were uploaded by the lab owner. One additional directory-ID screenshot was removed from the current branch; older Git commits may still retain it. Captions describe the observed evidence without implying production readiness or completed validation that the images do not establish. **Publication does not mean a new independent full-resolution privacy audit has been completed.** If any image contains a sensitive identifier, remove it from GitHub and its history as appropriate.

## 1. Device restrictions profile

![Device restrictions profile](01_Device_Restrictions_Profile.png)

Policy configuration; successful application must be checked separately.

## 2. Device compliance settings

![Device compliance settings](02_Compliance_Settings.png)

Per-setting compliance shows errors for BitLocker, Secure Boot, and encryption of data storage; other listed controls show compliant.

## 3. BitLocker policy deployment

![BitLocker policy deployment](04_BitLocker_Succeeded.png)

A succeeded policy result; not independently proof of disk encryption.

## 4. Windows LAPS policy

![Windows LAPS policy](05_Windows_LAPS_Policy.png)

LAPS configuration; do not disclose password or recovery material.

## 5. LAPS rotation status

![LAPS rotation status](06_LAPS_Rotation.png)

Rotation timestamp shown, not password contents.

## 6. Microsoft Entra device registration settings

![Microsoft Entra device registration settings](07_Windows_Update_Ring.png)

Microsoft Entra device registration and MFA registration settings; **not** a Windows Update ring screenshot.

## 7. Conditional Access policy

![Conditional Access policy](08_Conditional_Access_Policy.png)

Report-only evaluation, not enforced access blocking.

## 8. Conditional Access report-only result

![Conditional Access report-only result](09_CA_Report_Only_Result.png)

Report-only failure, not an actual blocked sign-in.

## 9. Managed compliant device

![Managed compliant device](10_Compliant_Managed_Device.png)

Intune-managed and compliant status at capture time.

## Evidence boundaries

Screenshots of configurations, inventories, report-only evaluations, pending states, or command attempts must not be described as end-to-end successful deployments. Original unredacted archives are not intended for public release.
