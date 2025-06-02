# Action1 Agent Deployment – Resident EDU Network

This repository contains Action1 agent installers for macOS and Windows devices used across the Resident Education (Res EDU) network.

The installers are organized by facility (Organizational Unit) and are designed for:
- ✅ macOS deployment via Mosyle MDM
- ✅ Windows deployment via Action1 agent scripts or manual onboarding

---

## 📦 Contents

This repo includes:

- `.pkg` files for macOS (MDM-compatible)
- `.msi` files for Windows (silent install support)
- Releases organized by facility tag

---

## 🏷️ Releases by Facility

Click to download the macOS and Windows installers for each facility:

| Facility | macOS (.pkg) | Windows (.msi) |
|----------|--------------|----------------|
| **BCF**  | [Download](https://github.com/KShaw-mdoc/Action1-Deployment/releases/download/BCF/action1_bcf.pkg) | [Download](https://github.com/KShaw-mdoc/Action1-Deployment/releases/download/BCF/action1_bcf.msi) |
| **DCF**  | [Download](https://github.com/KShaw-mdoc/Action1-Deployment/releases/download/DCF/action1_dcf.pkg) | [Download](https://github.com/KShaw-mdoc/Action1-Deployment/releases/download/DCF/action1_dcf.msi) |
| **LCYDC**| [Download](https://github.com/KShaw-mdoc/Action1-Deployment/releases/download/LCYDC/action1_lcydc.pkg) | [Download](https://github.com/KShaw-mdoc/Action1-Deployment/releases/download/LCYDC/action1_lcydc.msi) |
| **MCC**  | [Download](https://github.com/KShaw-mdoc/Action1-Deployment/releases/download/MCC/action1_mcc.pkg) | [Download](https://github.com/KShaw-mdoc/Action1-Deployment/releases/download/MCC/action1_mcc.msi) |
| **MSP**  | [Download](https://github.com/KShaw-mdoc/Action1-Deployment/releases/download/MSP/action1_msp.pkg) | [Download](https://github.com/KShaw-mdoc/Action1-Deployment/releases/download/MSP/action1_msp.msi) |
| **SMWRC**| [Download](https://github.com/KShaw-mdoc/Action1-Deployment/releases/download/SMWRC/action1_smwrc.pkg) | [Download](https://github.com/KShaw-mdoc/Action1-Deployment/releases/download/SMWRC/action1_smwrc.msi) |
| **WC**   | [Download](https://github.com/KShaw-mdoc/Action1-Deployment/releases/download/WC/action1_wc.pkg) | [Download](https://github.com/KShaw-mdoc/Action1-Deployment/releases/download/WC/action1_wc.msi) |

> 🔗 [**Browse all releases**](https://github.com/KShaw-mdoc/Action1-Deployment/releases)

---

## 🔗 Direct URLs (for scripting or MDM systems)

| Facility  | macOS (.pkg)                                                                                 | Windows (.msi)                                                                               |
|-----------|----------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------|
| **BCF**   | `https://github.com/KShaw-mdoc/Action1-Deployment/releases/download/BCF/action1_bcf.pkg`     | `https://github.com/KShaw-mdoc/Action1-Deployment/releases/download/BCF/action1_bcf.msi`     |
| **DCF**   | `https://github.com/KShaw-mdoc/Action1-Deployment/releases/download/DCF/action1_dcf.pkg`     | `https://github.com/KShaw-mdoc/Action1-Deployment/releases/download/DCF/action1_dcf.msi`     |
| **LCYDC** | `https://github.com/KShaw-mdoc/Action1-Deployment/releases/download/LCYDC/action1_lcydc.pkg` | `https://github.com/KShaw-mdoc/Action1-Deployment/releases/download/LCYDC/action1_lcydc.msi` |
| **MCC**   | `https://github.com/KShaw-mdoc/Action1-Deployment/releases/download/MCC/action1_mcc.pkg`     | `https://github.com/KShaw-mdoc/Action1-Deployment/releases/download/MCC/action1_mcc.msi`     |
| **MSP**   | `https://github.com/KShaw-mdoc/Action1-Deployment/releases/download/MSP/action1_msp.pkg`     | `https://github.com/KShaw-mdoc/Action1-Deployment/releases/download/MSP/action1_msp.msi`     |
| **SMWRC** | `https://github.com/KShaw-mdoc/Action1-Deployment/releases/download/SMWRC/action1_smwrc.pkg` | `https://github.com/KShaw-mdoc/Action1-Deployment/releases/download/SMWRC/action1_smwrc.msi` |
| **WC**    | `https://github.com/KShaw-mdoc/Action1-Deployment/releases/download/WC/action1_wc.pkg`       | `https://github.com/KShaw-mdoc/Action1-Deployment/releases/download/WC/action1_wc.msi`       |

---

## 🚀 Deployment Instructions

### 📱 macOS via Mosyle MDM

1. In Mosyle, go to **Install PKG > Add New Package**
2. Select:
   - ✅ “Already Have the PKG”
   - ✅ “Automatically Set App Info”
3. Paste the download link from the table above (macOS `.pkg`)
4. Assign to the appropriate Smart Group by facility

### 💻 Windows via Action1 Console or Script

1. Download the `.msi` file for the correct facility
2. Install manually or use RMM/script:

```powershell
msiexec /i action1_<tag>.msi /qn
```
---

📞 Contact
For deployment support or facility-specific installer management, contact:
📧 Kenneth.Shaw@maine.gov




