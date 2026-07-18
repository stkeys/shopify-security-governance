RACI Matrix & Gap Analysis
# 3. RACI Matrix: Third-Party App Security Reviews
*Color Guide: Red = Accountable (A) | Green = Responsible (R) | Yellow = Consulted (C) | Grey = Informed (I)*

| Governance Activity | App Developer | Vendor Security Team | CISO | Legal & Compliance | GRC Team |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **Submit App Security Profiles** | **R** | **I** | **I** | **I** | **I** |
| **Perform Automated API Scans** | **I** | **R** | **I** | **I** | **R** |
| **Final App Store Listing Approval**| **I** | **C** | **A** | **C** | **I** |
| **Enforce PCI-DSS v4.0 Matrix** | **R** | **R** | **A** | **C** | **R** |


---


# 4. Governance Gap Analysis (App Store Ecosystem)

| # | Governance Area | Current State (Where We Are) | Gap / Finding | Target State (Where We Need to Be) | Priority |
| :-: | :--- | :--- | :--- | :--- | :-: |
| **1** | **API Scoping & Privilege** | Apps can request wide database access without explicit architectural justification. | Severe data over-privilege; vulnerability to automated database scraping. | Strict Least-Privilege API model; mandatory justification for high-risk scopes. | **H** |
| **2** | **Continuous App Auditing** | Apps are vetted heavily at intake, but post-approval code updates are unmonitored. | Visibility vacuum for post-intake malicious code injections or supply-chain changes. | Real-time automated behavioral scanning of live marketplace applications. | **H** |
