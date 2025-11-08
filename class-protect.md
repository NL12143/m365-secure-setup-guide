
## 📄 Document Classification Table

| Icon | Classification | Description |
|------|----------------|-------------|
| 🔓   | **PUBLIC**      | Information intended for unrestricted distribution. May be freely shared without limitations. |
| 🏢   | **INTERNAL**    | Information meant for internal use only. Not intended for public release but not highly sensitive. |
| 🔐   | **CONFIDENTIAL**| Sensitive information requiring restricted access. Sharing is limited to authorized personnel only. |
| 👥   | **PERSONNEL**   | Subclass of CONFIDENTIAL. Includes HR-related data such as employee records, contracts, evaluations, and medical information. |
| 🛡️   | **SECRET**      | Highly sensitive information with strict access controls. Unauthorized disclosure could cause serious harm. |

Please ensure all documents are labeled appropriately and handled in accordance with their classification level.


# 📄 Document Classification & Access Matrix

This matrix defines how document sensitivity (**CLASS**) influences access permissions and control mechanisms.

Most documents are protected by permissions (e.g., SharePoint groups, roles, or labels), represented by:
- 🚫 = access not permitted
- ➡️ = access permitted via directional control

Some documents require stricter protection through encryption or advanced enforcement:
- 🔐 = access permitted via encryption or strict control

| CLASS           | Public | Internal | Group | Per-User |
|----------------|:------:|:--------:|:-----:|:--------:|
| **PUBLIC**      | ✅     | ✅       | ✅    | ✅       |
| **INTERNAL**    | 🚫     | ➡️       | ➡️    | ➡️       |
| **CONFIDENTIAL**| 🚫     | 🚫       | ➡️    | ➡️       |
| **PERSONNEL**   | 🚫     | 🚫       | 🔐    | 🔐       |
| **SECRET**      | 🚫     | 🚫       | 🚫    | 🔐       |


## 🔐 Document Classification & Access Matrix

| CLASS           | Public | Internal | Group | Per-User |
|----------------|:------:|:--------:|:-----:|:--------:|
| **PUBLIC**      | ✅     | ✅       | ✅    | ✅       |
| **INTERNAL**    | 🚫     | ➡️       | ➡️    | ➡️       |
| **CONFIDENTIAL**| 🚫     | 🚫       | ➡️    | ➡️       |
| **PERSONNEL**   | 🚫     | 🚫       | 🔐    | 🔐       |
| **SECRET**      | 🚫     | 🚫       | 🚫    | 🔐       |

---

## 📘 Legend

| Icon   | Access control voa Permissions or Encryption       |
|--------|----------------------------------------------------|
| ✅     | Access permitted via standard permissions         |
| ❌     | Access not permitted via permissions              |
| 🚫     | Access not permitted, enforced via encryption     |
| 🔐     | Access permitted via encryption or strict control |
| 🛂	   | Passport control—symbolic of authorized entry      | 


## 🧠 Notes
- **CLASS** defines the sensitivity of the document.
- **ACCESS** defines who may view the document.
- **CONTROL**  defines how access is technically enforced.



