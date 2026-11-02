# Security Policy

LicenseForge is security-sensitive software: it signs and verifies licenses that control access to our users' products. We take reports seriously and appreciate responsible disclosure.

## Reporting a vulnerability
**Please do not open public issues for security problems.**

Report privately through one of:
1. **GitHub private vulnerability reporting**: the "Report a vulnerability" button on the affected repository's Security tab (preferred).
2. Email **security@licenseforge.io**.

Please include affected component and version, a description, reproduction steps or proof of concept, and the impact you expect.

## What to expect
- Acknowledgement within **3 business days**.
- An initial assessment within **10 business days**.
- We coordinate a fix and disclosure date with you. Our default embargo is **90 days** or until a fix is released, whichever comes first.
- Fixes are announced through GitHub Security Advisories with a CVE where applicable. We credit reporters unless you prefer otherwise.

## Supported versions
Until 1.0, only the **latest minor release** receives security fixes. A longer support policy will be published with 1.0.

## Scope
In scope: the LicenseForge server, CLI, agent, SDKs, Helm chart and official add-ons, and the license file format.

Out of scope: bypassing license checks by modifying a client application on a machine you control. LicenseForge signs licenses so they can't be forged; it does not claim to prevent tampering with client code. See the threat model in the documentation.
