# Windows Autopilot — Registration and Deployment Boundary

## Documented activity

- Imported a test device hardware hash into Windows Autopilot.
- Worked with a user-driven Microsoft Entra join deployment profile; the captured device list showed **Not assigned** or **Pending** states, not confirmed successful assignment.
- Observed the imported device in the Autopilot devices list.
- Captured a profile status of **Pending** during testing.

## What is not established

A complete device wipe, out-of-box experience (OOBE), enrollment status page completion, and successful user-driven provisioning are **not verified**. This repository therefore does **not** claim a successful end-to-end Autopilot deployment.

## Future verification checklist

1. Confirm imported device record and assigned profile.
2. Verify profile assignment status transitions to assigned.
3. Reset the disposable test device and run OOBE.
4. Capture sanitized enrollment status and device registration.
5. Confirm device enrollment, compliance, and policy application after OOBE.

Never publish hardware hashes, serial numbers, user identifiers, or tenant-specific enrollment secrets.
