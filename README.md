# Cloud-Misconfiguration-Report
## Project Scope: Cloud Data Leak Audits
## 1. Introduction to Cloud Security
Cloud computing means saving data on the internet instead of local hard drives. Cloud security focuses on protecting this data from threat actors. Security is a mutual obligation; if we make mistakes in deployment configurations, data can become public.
## 2. The Shared-Responsibility Model
Security is a teamwork between the Cloud Provider and the Customer. The provider secures physical infrastructure (servers, hardware, building safety), while the customer is responsible for access controls, strong credentials, and logical configurations.
### Landlord vs Tenant Analogy
The provider is the landlord securing the building walls, while the customer is the tenant responsible for locking their own room's door. Leaving a folder open without access controls is solely the customer's fault.
### The Threat Vector of Open Buckets
When a bucket is left public, anyone on the web can exfiltrate or delete files. Threat actors deploy automated scraping scripts to discover these misconfigured nodes, resulting in severe data breaches.
## 4. How to Prevent Open-Bucket Leaks
- Keep it Private by Default: Restrict object access upon initial creation.
- Enable Block Public Access: Enforce global hypervisor overrides to block incoming public traffic requests.
- Conduct Regular Audits: Run automated compliance tracking weekly to detect rogue exposures.
- Principle of Least Privilege: Restrict identity access management (IAM) permissions exclusively to essential personnel.
## 5. Conclusion
Cloud security demands operational discipline. The Shared-Responsibility Framework proves we cannot blame infrastructure vendors for administrative oversights. Proper privacy checks mitigate these risks entirely.
