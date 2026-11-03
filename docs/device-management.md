# Windows Endpoint Enrollment and Management

## Scope

This project records a Windows 11 test endpoint joined to Microsoft Entra ID and enrolled in Intune. The endpoint was reported as corporate and compliant at the time of the lab.

## Implementation and validation

1. Prepared a Windows 11 virtual endpoint with UEFI, Secure Boot and virtual TPM.
2. Used a test identity to join the endpoint to Entra ID and enroll in Intune.
3. Inspected the Intune device record, enrollment status, ownership, and compliance result.
4. Reviewed configuration deployment status and device-level results rather than assuming assignment meant success.
5. Tested Windows management capabilities including Company Portal deployment, update policy and a SYSTEM-context script.

## Distinguishing the evidence

- **Enrolled:** device appears in Intune and is managed.
- **Compliant:** device record reports compliant at a specific point in time; this is not permanent proof.
- **Configured:** a policy exists or is assigned.
- **Succeeded:** Intune reports a successful configuration result for the target.
- **Protected:** requires independent endpoint verification for controls such as actual volume encryption.

See [security controls](security-controls.md) and the [evidence matrix](evidence-matrix.md). Do not publish user emails, device IDs, or tenant IDs.
