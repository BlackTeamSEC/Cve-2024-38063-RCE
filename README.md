# CVE-2024-38063

## Description
This repository contains details and potential exploit code for CVE-2024-38063, a critical Windows TCP/IP Remote Code Execution (RCE) vulnerability. The vulnerability allows an unauthenticated attacker to execute arbitrary code on the target system through specially crafted TCP/IP packets.

This vulnerability affects the Windows TCP/IP stack and could allow remote attackers to take full control of affected systems without any user interaction or authentication.

## Metrics

### CVSS 3.x Severity and Vector Strings:
- **CNA**: Microsoft Corporation
- **Base Score**: 9.8 (CRITICAL)
- **Vector**: CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H

The CVSS score represents the severity of the vulnerability:
- **Attack Vector (AV)**: Network (N) - The vulnerability is exploitable remotely.
- **Attack Complexity (AC)**: Low (L) - The attack is straightforward with no special conditions required.
- **Privileges Required (PR)**: None (N) - The attacker does not require any privileges to exploit the vulnerability.
- **User Interaction (UI)**: None (N) - No user interaction is needed for exploitation.
- **Scope (S)**: Unchanged (U) - The exploit does not affect resources beyond the vulnerable component.
- **Confidentiality (C)**: High (H) - Full access to confidential information can be gained.
- **Integrity (I)**: High (H) - Complete control over system integrity.
- **Availability (A)**: High (H) - Complete disruption of the system's availability.

### NIST CVSS Score vs. CNA Score:
The NIST CVSS score for this vulnerability may differ from the CNA score provided by Microsoft, so always refer to both sources for a complete understanding of the severity.

## Exploit Code

This repository includes the exploit code for CVE-2024-38063. This code is intended for educational and research purposes only. Unauthorized use of this code in a live environment is illegal and unethical.

## Reference

For more detailed information and to access the code, visit the [GitHub Repository](https://github.com/ynwarcs/CVE-2024-38063?tab=readme-ov-file).
