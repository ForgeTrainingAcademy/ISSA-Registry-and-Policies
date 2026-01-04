# ISSA-Registry-and-Policies
ISSA Registry and Policies
ISSA Certification Registry – JSON Data
This repository contains the official JSON data source used for the public verification of certifications aligned with ISSA (International Security Standards Authority) standards.
The data published in this repository is used exclusively to support certification and badge verification through the ISSA public registry and related verification tools.
Purpose of This Repository
The JSON file hosted in this repository provides a read-only data source for:
verification of ISSA-aligned certifications
confirmation of certification status
support for employers, recruitment organisations and authorised stakeholders
This repository does not function as a training record, student database or licensing system.
Data Structure
The JSON file contains an array of certification records.
Each record represents one issued ISSA certification.
Fields
Field	Description
fullName	Full name of the certificate holder
certification	Certification title (e.g. Close Protection Officer – CPO)
issueDate	Date of certification issuance (YYYY-MM-DD)
expiryDate	Certification expiry date (YYYY-MM-DD)
certificationNumber	Unique ISSA certification number (e.g. ISSA-CPO-300-0001)
approvedTrainingCentre	ISSA Approved Training Centre that delivered the programme
Certification Number Format
ISSA certification numbers follow a standardised and centrally managed format:
ISSA-CPO-300-000X
Where:
ISSA identifies the issuing authority
CPO identifies the qualification
300 identifies the standard / sector
000X is a unique, sequential identifier
Certification numbers identify the certification, not the individual.
Certification Status
Certification status (Active, Expired, Withdrawn) is determined dynamically by comparing the current date with the certification expiry date, or through ISSA governance decisions where applicable.
Displayed status reflects certification alignment at the time of verification.
Data Governance & Updates
All data is managed and updated exclusively by ISSA or authorised representatives.
Records may be added, updated or withdrawn in accordance with ISSA Certification and Governance Policies.
Historical certification numbers are never reused.
Disclaimer
ISSA certification confirms alignment with the relevant ISSA standard at the time of certification.
Certification and ISSA badges:
do not constitute a licence to operate
do not replace legal, regulatory or licensing requirements imposed by national authorities
ISSA does not provide training and does not authorise operational deployment.
The information published in this repository is provided for verification purposes only.
Contact
For certification verification enquiries, governance matters or corrections, please refer to official ISSA communication channels.
