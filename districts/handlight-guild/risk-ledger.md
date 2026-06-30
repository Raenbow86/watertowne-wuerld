# Guild Risk Ledger

**District:** The Handlight Guild
**Origin Name:** Future Hands
**Document Type:** Risk Register
**Wuerld Translation:** A warning book for weak doors, loose keys, strange signals, and anchors that need protection

---

## Purpose of This Ledger

The Handlight Guild cannot fix every risk at once.

It does not have unlimited money.
It does not have unlimited staff.
It does not have perfect systems.

That makes the Guild real.

This Risk Ledger names the first dangers facing the Guild and helps decide what should be protected first.

In regular cybersecurity language, this is a **risk register**.

In Watertowne Wuerld language, this is the Guild’s warning book.

It is where the Guild writes down the weak doors before something crawls through them.

---

## How Risk Is Rated

Each risk is rated using three simple categories:

### Likelihood

How likely is this to happen?

* **Low** — possible, but not expected often
* **Medium** — could realistically happen
* **High** — very likely without controls

### Impact

How much damage could it cause?

* **Low** — small disruption or limited exposure
* **Medium** — serious disruption, sensitive data exposure, or operational damage
* **High** — major harm to students, systems, trust, operations, or anchors

### Priority

How soon should the Guild deal with it?

* **Low** — monitor and address later
* **Medium** — plan controls soon
* **High** — needs attention early
* **Critical** — must be addressed first

---

# Risk 1: Phishing Against Staff or Students

**Wuerld Name:** Phishing Sirens
**Affected Anchors:** Email accounts, student accounts, staff accounts, passwords, internal documents
**Likelihood:** High
**Impact:** High
**Priority:** Critical

## What Could Happen

A staff member, student, or volunteer receives a fake message that looks real.

It may ask them to reset a password, open an attachment, click a link, pay a fake invoice, or log in through a fake portal.

If someone trusts the wrong signal, an attacker could steal credentials, access Guild systems, or spread malware.

## Why It Matters

Email is one of the easiest ways into an organization.

The Guild works with students, volunteers, vendors, donors, and outside services. That means people expect messages from many different sources.

Phishing works because it sounds believable.

In Watertowne language:

A Phishing Siren does not steal the key.

She convinces you to hand it over.

## Existing Controls

* Basic user awareness
* Staff and students know to be careful with suspicious links

## Missing Controls

* Formal phishing reporting process
* MFA on all important accounts
* Regular phishing awareness training
* Email filtering rules
* Clear examples of suspicious messages
* “Report suspicious signal” instructions

## Recommended Protections

* Require MFA for staff and admin accounts
* Teach students and staff how to spot phishing
* Create a simple phishing reporting process
* Encourage people to report instead of feel embarrassed
* Use strong spam and malware filtering
* Remind users not to enter passwords from email links

---

# Risk 2: Lost or Stolen Donated Laptops

**Wuerld Name:** Missing Anchors
**Affected Anchors:** Donated laptops, student files, local accounts, training materials
**Likelihood:** Medium
**Impact:** Medium
**Priority:** High

## What Could Happen

A donated laptop assigned to a student is lost, stolen, or never returned.

If the device has saved passwords, personal files, browser history, or student work, the loss could expose sensitive information.

## Why It Matters

A donated laptop may be someone’s only doorway into the Guild’s systems.

That makes the device more than equipment.

It is an anchor.

If the Guild does not track devices, it may not know what was lost, who had it, or what data was on it.

## Existing Controls

* Devices are recognized as important assets
* Donated laptops are intended for student use

## Missing Controls

* Formal checkout process
* Device assignment records
* Encryption requirements
* Secure wiping process
* Lost device reporting process
* Standard device setup checklist

## Recommended Protections

* Create a device checkout log
* Record who each laptop is assigned to
* Wipe donated laptops before reuse
* Patch laptops before assignment
* Use full-disk encryption where possible
* Require users to report lost devices quickly
* Avoid storing sensitive files locally when possible

---

# Risk 3: Over-Permissioned Staff or Volunteer Accounts

**Wuerld Name:** Loose Keys
**Affected Anchors:** Staff accounts, volunteer accounts, shared drives, student records, internal documents
**Likelihood:** Medium
**Impact:** High
**Priority:** High

## What Could Happen

A staff member or volunteer has access to more systems or files than they need.

If their account is compromised, or if they make a mistake, sensitive records could be exposed, changed, deleted, or shared with the wrong person.

## Why It Matters

Access should match the job.

Volunteers may need to help with training, events, or repairs, but they should not automatically have access to student records or administrative systems.

Too much access turns a small mistake into a large incident.

## Existing Controls

* Different types of users exist: students, staff, volunteers, admins

## Missing Controls

* Role-based access rules
* Regular permission reviews
* Clear onboarding and offboarding process
* Separate admin accounts
* Access approval process

## Recommended Protections

* Define basic roles: student, volunteer, staff, admin
* Give each role only the access it needs
* Review permissions every quarter
* Remove access when people leave
* Avoid shared accounts
* Use separate admin accounts for administrative work

---

# Risk 4: Forgotten Admin Accounts

**Wuerld Name:** Root Wraiths
**Affected Anchors:** Admin accounts, network equipment, shared drives, cloud systems, device management tools
**Likelihood:** Medium
**Impact:** High
**Priority:** High

## What Could Happen

An old admin account remains active after a staff member, volunteer, contractor, or vendor no longer needs access.

If that account is discovered or compromised, someone could use it to access sensitive systems.

## Why It Matters

Admin accounts are high-value keys.

They can change settings, create users, remove controls, access files, and hide activity.

A forgotten admin account is not just clutter.

It is a ghost with keys.

## Existing Controls

* Admin accounts are recognized as high-risk

## Missing Controls

* Admin account inventory
* Regular admin access reviews
* Offboarding checklist
* MFA requirement
* Logging of admin activity

## Recommended Protections

* Keep a list of all admin accounts
* Require MFA for admin access
* Disable unused admin accounts
* Review admin accounts monthly
* Avoid shared admin passwords
* Log and review administrative changes

---

# Risk 5: Weak Wi-Fi or Poor Network Segmentation

**Wuerld Name:** Fogged Doors
**Affected Anchors:** Guild Wi-Fi, guest network, internal systems, student devices, staff devices
**Likelihood:** Medium
**Impact:** High
**Priority:** High

## What Could Happen

Students, staff, guests, and unknown devices all connect to the same network.

If one device is infected or one guest is malicious, internal systems may be exposed.

Weak Wi-Fi settings or old router passwords could make the problem worse.

## Why It Matters

The Guild’s network is its signal road.

If every traveler uses the same road, every traveler can potentially reach places they should not.

Guest access should not lead directly to internal records, staff devices, or administrative systems.

## Existing Controls

* Wi-Fi is recognized as part of the Guild’s infrastructure

## Missing Controls

* Separate guest and internal networks
* Strong Wi-Fi password rotation
* Router admin password change
* Firewall rule review
* Network equipment documentation
* Firmware update process

## Recommended Protections

* Separate guest Wi-Fi from internal systems
* Change default router and access point passwords
* Use strong Wi-Fi encryption
* Rotate shared Wi-Fi passwords regularly
* Update router and firewall firmware
* Document network equipment and settings

---

# Risk 6: Sensitive Records Stored in the Wrong Place

**Wuerld Name:** Misplaced Memory
**Affected Anchors:** Student records, internal documents, shared drives, staff laptops, cloud storage
**Likelihood:** Medium
**Impact:** High
**Priority:** High

## What Could Happen

Student records, personal information, or internal documents are saved in shared folders, personal devices, unapproved cloud accounts, or lab computers.

This could expose sensitive data to students, volunteers, guests, or outside users.

## Why It Matters

Data is memory.

If the Guild stores memory carelessly, it can be changed, copied, lost, or seen by the wrong people.

Student records deserve stronger protection than general training materials.

## Existing Controls

* Student records are recognized as sensitive

## Missing Controls

* Data classification guide
* Approved storage locations
* Folder permission reviews
* Retention rules
* Staff training on handling sensitive data

## Recommended Protections

* Create data classification labels
* Define where sensitive records may be stored
* Restrict student record access to authorized staff
* Avoid storing sensitive records on shared lab machines
* Review shared folder permissions
* Back up important records securely

---

# Risk 7: Unpatched Donated or Shared Devices

**Wuerld Name:** Thin Places
**Affected Anchors:** Donated laptops, shared lab computers, staff laptops, training systems
**Likelihood:** High
**Impact:** Medium
**Priority:** High

## What Could Happen

Donated laptops or shared lab computers run outdated operating systems, old applications, or missing security updates.

Attackers could exploit known vulnerabilities, or malware could spread through shared systems.

## Why It Matters

The Guild depends on devices that may arrive used, old, or misconfigured.

A small unpatched weakness can become a doorway.

In Watertowne language:

A small tear becomes a door if nobody mends it.

## Existing Controls

* Devices are identified as important assets

## Missing Controls

* Standard patching process
* Device intake checklist
* Baseline security configuration
* Endpoint protection
* Regular vulnerability scans

## Recommended Protections

* Wipe and inspect donated devices before use
* Patch operating systems before assignment
* Remove unnecessary software
* Use standard device setup checklists
* Run regular vulnerability scans
* Track device update status

---

# Risk 8: Vendor Access Not Reviewed

**Wuerld Name:** Hidden Doors
**Affected Anchors:** Vendor accounts, cloud platforms, learning systems, repair partners, internet service
**Likelihood:** Medium
**Impact:** Medium
**Priority:** Medium

## What Could Happen

A vendor, repair partner, cloud platform, or outside service keeps access longer than needed or has more access than required.

If the vendor is compromised, the Guild could be affected too.

## Why It Matters

The Guild cannot do everything alone.

Outside help is normal.

But every outside connection becomes part of the Guild’s risk.

A hidden door is still a door.

## Existing Controls

* Vendors are recognized in the Asset Ledger

## Missing Controls

* Vendor list
* Vendor access review
* Right-sized access permissions
* Vendor offboarding process
* Security questions for vendors

## Recommended Protections

* Keep a vendor list
* Document what access each vendor has
* Remove vendor access when work ends
* Ask basic security questions before using services
* Limit vendors to only what they need
* Review vendor access quarterly

---

# Risk 9: Logs Are Collected but Not Reviewed

**Wuerld Name:** Unread Footprints
**Affected Anchors:** Security logs, account logs, network logs, device logs, email alerts
**Likelihood:** Medium
**Impact:** Medium
**Priority:** Medium

## What Could Happen

The Guild may have logs available, but nobody reviews them.

Suspicious logins, failed access attempts, device alerts, or unusual behavior may go unnoticed.

## Why It Matters

Logs are the footprints of the Guild.

They help the Logkeepers see what happened.

If nobody reads the logs, the system may whisper warnings that no one hears.

## Existing Controls

* Logs are recognized as important

## Missing Controls

* Log review schedule
* Alert priorities
* SIEM or central log plan
* Incident escalation process
* Responsible owner for log review

## Recommended Protections

* Decide which logs matter most
* Review important logs weekly or monthly
* Watch for failed logins and unusual access
* Create alert categories
* Document suspicious activity
* Build toward SIEM monitoring over time

---

# Risk 10: No Clear Incident Response Process

**Wuerld Name:** No Emergency Scroll
**Affected Anchors:** All Guild systems, records, devices, accounts, and people
**Likelihood:** Medium
**Impact:** High
**Priority:** High

## What Could Happen

A security incident happens, but staff do not know who to tell, what to shut down, what evidence to save, or how to communicate.

This could make the incident worse.

## Why It Matters

Even a small incident becomes more dangerous when nobody knows what to do.

The Guild needs a simple emergency plan before something breaks.

## Existing Controls

* Incident response is recognized as a needed skill

## Missing Controls

* Incident response playbook
* Reporting process
* Contact list
* Evidence preservation steps
* Communication plan
* Recovery checklist

## Recommended Protections

* Create an Incident Scroll
* Define who reports incidents
* Define who responds
* List first steps for phishing, lost device, malware, and account compromise
* Preserve logs and screenshots
* Document lessons learned after each incident

---

# Top Five Risks to Address First

The Guild should not try to fix everything at once.

The first five risks to prioritize are:

1. **Phishing Against Staff or Students**
2. **Forgotten Admin Accounts**
3. **Over-Permissioned Staff or Volunteer Accounts**
4. **Sensitive Records Stored in the Wrong Place**
5. **Weak Wi-Fi or Poor Network Segmentation**

These risks matter most because they can expose sensitive data, compromise accounts, weaken anchors, or open doors into deeper Guild systems.

---

# First Control Roadmap

## First 30 Days

* Require MFA for staff and admin accounts
* Create a phishing reporting process
* List all admin accounts
* Start a device checkout log
* Change default router and access point passwords

## First 60 Days

* Create data classification labels
* Review shared drive permissions
* Separate guest Wi-Fi from internal systems
* Create a device intake and wiping checklist
* Build a basic incident response contact list

## First 90 Days

* Review volunteer and vendor access
* Document network equipment
* Create a simple log review process
* Run vulnerability scans on Guild devices
* Draft the first Incident Scroll

---

# Closing Note

The Guild does not need perfect security.

It needs honest security.

Name the risks.
Protect the anchors.
Teach the people.
Fix the weak doors first.
Write down what happened.

That is how the Handlight Guild stays standing.
