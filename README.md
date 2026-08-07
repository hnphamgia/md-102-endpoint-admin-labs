# MD-102: Endpoint Administrator Lab Journal


Documentation and screenshot evidence of Microsoft 365 MD-102 practice labs.
Welcome to my hands-on lab documentation repository for the **Microsoft MD-102: Endpoint Administrator** exam certification path.

This journal records end-to-end administration, configuration, and client-side validation across Microsoft Entra ID, Microsoft Intune, and Windows 11 endpoints within a dedicated hybrid environment (**Wollongong Tech Lab**).

---

## 📐 Lab Environment Architecture

* **Primary Directory:** Microsoft Entra ID (Cloud)
* **Hybrid Sync:** On-Premises Active Directory via Microsoft Entra Connect
* **Endpoint Management:** Microsoft Intune
* **Test Endpoints:** Windows 11 Pro (`vm-windows-clie`)

---

## 📚 Core Modules & Practice Matrix

| Module | Topic | Primary Deliverables | Status |
| :--- | :--- | :--- | :---: |
| **01** | **Identity & Sync** | Hybrid sync, Password Writeback, Entra Connect | ✅ Complete |
| **02** | **Device Enrollment** | MDM scope, Entra ID Join, Intune enrollment | ✅ Complete |
| **03** | **Configuration Profiles** | Settings Catalog, Kiosk Mode profiles | ✅ Complete |
| **04** | **App Management** | Win32 packaging (`.intunewin`), Company Portal | 🔄 In Progress |
| **05** | **Compliance & CA** | Device Compliance rules, Conditional Access | ✅ Complete |
| **06** | **Endpoint Security** | BitLocker key escrow, Security baselines | ⏳ Scheduled |
| **07** | **Autopilot Deployment** | Hardware hash import, Zero-touch OOBE | ⏳ Scheduled |

---

## 📂 Repository Structure

```text
md102-lab-journal/
├── README.md
├── 01-identity-and-sync/
├── 02-device-enrollment/
├── 03-configuration-profiles/
├── 04-application-management/
├── 05-compliance-and-ca/
│   ├── lab-05-device-compliance.md
│   └── screenshots/
├── 06-endpoint-security/
└── 07-autopilot-deployment/
