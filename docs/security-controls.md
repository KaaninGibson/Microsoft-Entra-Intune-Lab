# Endpoint Security Controls

## BitLocker

The lab included a BitLocker policy with an Intune configuration report showing one successful deployment and no reported errors/conflicts at the captured time. This **does not independently prove** the volume was encrypted.

**Follow-up validation:** review the device's encryption state and protector status using approved endpoint tools. Never publish recovery keys or key IDs.

## Windows LAPS

The lab included a Windows LAPS policy and a device management view with a last password rotation timestamp. This supports rotation management activity; the actual password, privileged credentials and device identifiers must not appear in public evidence.

## Conditional Access

A pilot Conditional Access policy required a compliant device but ran in **report-only mode**. The sign-in report-only result showed a failure for that policy. This is useful for understanding how enforcement *would* evaluate, but **no access block is claimed**.

## Microsoft Defender and updates

The historical lab notes describe Defender protection/scan validation and Intune update rings. These are documented exercises pending independent screenshot selection for this repository.

## Security troubleshooting method

1. Establish device and identity context without exposing personal data.
2. Separate policy assignment from per-device application status.
3. Check compliance state, last check-in, and specific setting failures.
4. Correlate with sign-in results for Conditional Access; note report-only versus enforced.
5. Record a sanitized before/after result and remaining limitations.
