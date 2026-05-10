# MyMedicationLogger — Privacy Notice

**Effective date:** May 10, 2026
**Version:** 1.0

This Privacy Notice explains what MyMedicationLogger does with your information. It's written in plain English — not legalese — because a tool you trust with your medications shouldn't hide behind jargon.

---

## 1. The short version

- Everything you enter is stored **on your device only**. There is no cloud, no server, no account.
- Your data does not leave your device, except for two specific lookups described below.
- We do not sell, share, or analyze your data.
- If you uninstall the app, your data is gone unless you exported it first.

---

## 2. What information MyMedicationLogger handles

When you use the app, you may enter:

- Medication names (brand and generic)
- Dosage amounts and forms (tablet, capsule, etc.)
- Times of day for reminders
- The condition each medication treats
- The name of the prescribing doctor
- Inventory counts and refill thresholds
- Names, phone numbers, and addresses of doctors and pharmacies
- Records of which doses you've taken and when

This information is stored locally on the device where you use the app, in iOS's standard private app storage (the app's sandbox container, isolated from other apps).

We do not collect:
- Your identity (no name, no email, no account)
- Your location, except briefly when you tap "find nearby pharmacies"
- Health conditions beyond what you choose to type
- Diagnostic data, lab results, or any other medical record

---

## 3. What gets sent over the network

There are exactly three situations where MyMedicationLogger sends information off your device:

### 3.1 Drug-name lookups
When you type a medication name in the Add Medication wizard, MyMedicationLogger sends only that name (e.g. "Cymbalta" or "lisinopril") to the **RxNorm** API, operated by the U.S. National Library of Medicine, to find the matching brand/generic counterpart. What is sent: just the drug name string. Not your name, your identity, or any other context.

### 3.2 Doctor lookups (Pro feature)
When you use the optional NPPES doctor lookup (a Pro feature), the app sends the doctor's last name and a U.S. state code to the **NPPES** registry, operated by the U.S. Centers for Medicare & Medicaid Services. NPPES is a public registry of healthcare providers; it does not log queries against you personally.

### 3.3 External reference links
The PubMed and Mayo Clinic links shown for each medication open in your default browser when tapped. Once they open, your normal web browser is making the connection — MyMedicationLogger is not involved beyond providing the link.

That's it. There are no analytics, no telemetry, and no crash reporting that leaves your device.

---

## 4. Storage and security

- Data lives in the app's private iOS container, accessible only to MyMedicationLogger.
- Optional Face ID / passcode lock is available in Settings → Privacy & Security to require biometric or passcode authentication on app launch.
- We do not encrypt your data at rest beyond what iOS provides. iOS's full-disk encryption (active whenever your device has a passcode set) is the protection in place. If someone has unlocked physical access to your device, they could potentially read MyMedicationLogger's data.

---

## 5. Sharing and third parties

We do not share your data with anyone. The two API services above (RxNorm, NPPES) receive only drug-name or doctor-name strings and have no way to associate those with you personally.

In-App Purchases are processed by Apple via StoreKit 2. Apple's standard purchase data flows apply; refer to Apple's privacy policy.

---

## 6. Your rights

Because nothing leaves your device, classical "data subject rights" (access, deletion, portability) work by you operating the app:

- **Access:** open the app
- **Export:** Settings → Export medication list (PDF or Excel)
- **Delete one item:** swipe-to-delete or the trash icon
- **Delete everything:** Settings → "Reset all data," or uninstall the app
- **Portability:** PDF or Excel export

If you live in a jurisdiction with formal data-rights laws (GDPR, CCPA, etc.), MyMedicationLogger is unusual in that those laws were written assuming a service operator collects your data. Here, you are simultaneously the data subject and the data controller — your device is the only place the data exists.

---

## 7. Children's privacy

MyMedicationLogger is not designed for children under 13 and does not knowingly collect any data. If you are setting up the app for a child, you (the parent) are the responsible party for the data that gets entered.

---

## 8. HIPAA status

**MyMedicationLogger is not a HIPAA-compliant service, and we do not represent it as one.**

A consumer using MyMedicationLogger to track their own medications is not a Covered Entity under HIPAA, and the data entered does not become Protected Health Information in the regulatory sense. HIPAA's protections, requirements, and remedies do not apply to this configuration.

If you are a healthcare provider and you are considering using MyMedicationLogger to track patient medications on a patient's behalf, please do not do so. The current implementation does not meet the HIPAA Security Rule's technical safeguards.

---

## 9. Changes to this notice

If this notice is updated in a future version of the app, the new version will be available in the app under Settings → Privacy & Security → Privacy Policy, and the effective date at the top will change.

---

## 10. Contact

For privacy-related questions, contact: support@enchanttreedesigns.com
