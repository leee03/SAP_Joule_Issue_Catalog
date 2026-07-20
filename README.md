# 🧭 SAP Joule Troubleshooting Catalog

On GitHub, you will find a consolidated catalogue of documented SAP Joule issues, organised according to the **seven architecture layers** shown below. This structure is intended to make navigation and issue identification as intuitive as possible.

> 📥 **Looking for the complete details?**  
> Download the attached Excel file [joule_issue_catalog_v2.xlsx](https://github.com/leee03/SAP_Joule_Issue_Catalog/blob/main/joule_issue_catalog_v2.xlsx) from GitHub to access the documented **root causes, resolutions, relevant SAP Notes, and support components**.

> 🤝 **Help us expand the catalogue**  
> We would be delighted to keep this resource growing. If you have additional documented issues to contribute, you are warmly invited to add them.

---

## 🖥️ Layer 1: Client / UX

Issues related to the user interface, browser behaviour, SAP Fiori launchpad, and the Joule entry point.

- **`frame-ancestors` Content Security Policy (CSP) violation**
- Joule icon not showing in SAP Fiori launchpad
- Joule icon displayed incorrectly due to the SAPUI5 version
- Unable to launch Joule using the icon due to browser cookies
- Joule icon not appearing for a specific user in SAP SuccessFactors
- Blank or greyed-out screen in SAP SuccessFactors

---

## 🔐 Layer 2: SAP Cloud Identity Services

Issues related to authentication, identity provisioning, user attributes, IAS, and IPS.

- Corporate Identity Provider refused to connect
- Joule not greeting the user by name
- Blank or white IAS login screen
- IPS transformation editing fails
- IAS source-system read job fails

---

## 🧩 Layer 3: SAP Build Work Zone

Issues related to SAP Build Work Zone plans, content management, navigation, content providers, and Joule capabilities.

- Content Manager not visible due to the limitations of the foundation plan
- Content-provider synchronisation fails with an unauthorised error
- Navigation links not working due to an incorrect proxy type
- Joule capabilities limited when using the foundation plan instead of the standard plan
- Joule cannot return transactional or navigational responses
- SAP SuccessFactors navigational use cases not working:
  - Profile button is missing
  - Deep links are not generated

---

## 🤖 Layer 4: Joule Service

Issues related to Joule activation, booster prerequisites, subscriptions, formations, and scenario execution.

- IAS tenant not found during booster prerequisite checks
- Cloud Identity system host not found
- IAS system missing from the System Landscape
- SAP Build Work Zone not available in the booster dropdown
- SAP S/4HANA Cloud Private Edition option missing from the booster
- SaaS subscription fails for `das-application`
- Formation creation fails because IAS is not enabled in SAP Build Work Zone
- Joule scenario is selected, but execution fails with:
  - An empty response
  - An error
  - A timeout

---

## 🔗 Layer 5: Connectivity

Issues related to connectivity between SAP BTP, SAP Cloud Connector, destinations, and connected systems.

- **“I'm having trouble connecting”** error
- SAP Cloud Connector cannot connect to the subaccount
- **“Digital Assistant not found”** error
- Runtime destination proxy type configured incorrectly, causing navigation-link failures

---

## 🏢 Layer 6: Backend System

Issues related to SAP S/4HANA services, business roles, semantic objects, applications, and content exposure.

- Required OData services are not activated
- Business roles are missing the required semantic objects
- Content exposure is not configured correctly
- Custom roles do not work with Joule because of:
  - Missing semantic objects
  - Missing application IDs
  - Incorrect CDM exposure

---

## ☁️ Layer 7: SAP Business Technology Platform

Issues related to SAP BTP entitlements, regional availability, system registration, and end-to-end setup.

- Joule service not available in the subaccount entitlements
- Entitlements not available despite using a supported data centre
- System Landscape menu not visible
- SAP systems not visible in the SAP BTP System Landscape
- End-to-end setup requires significant manual effort due to documentation gaps

---

## 📚 Additional Resources

For each documented issue, the downloadable Excel catalogue may include:

- 🔍 Detailed root cause
- 🛠️ Recommended resolution
- 📝 Relevant SAP Notes
- 🎫 Responsible support component
- 🧱 Corresponding architecture layer
