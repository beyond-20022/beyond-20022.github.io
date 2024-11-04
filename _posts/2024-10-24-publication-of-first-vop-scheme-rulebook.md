---
title: "Publication of the First Verification of Payee Scheme Rulebook"
date: 2024-10-24T12:00:00+02:00
categories:
  - blog
tags:
  - sepa
  - vop
values:
    author_profile: false
---

The European Payments Council (EPC) has officially issued the [first version of the Verification of Payee (VOP) scheme rulebook](https://www.europeanpaymentscouncil.eu/document-library/rulebooks/verification-payee-scheme-rulebook) following a public consultation. This rulebook is designed to help payment service providers (PSPs) across the Single Euro Payments Area (SEPA) meet the new regulatory requirements outlined in the EU Instant Payments Regulation (IPR), which amends the SEPA Regulation. 

**What is VOP all about?**

VOP is a security measure designed to reduce fraud and misdirected payments. It allows the payer’s PSP (Requesting PSP) to check the payee's details with the payee's PSP (Responding PSP) before a payment is made. This helps to ensure that the payment is going to the intended recipient. 

**How does VOP work in practice?**

1.  The payer provides their PSP with the payee's International Bank Account Number (IBAN) and name, or other identifiers like a VAT number or Legal Entity Identifier (LEI).
2.  The payer’s PSP (Requesting PSP) sends an instant request to the payee's PSP (Responding PSP) to verify the details.
3.  The Responding PSP instantly checks the provided details against their records. They will then send back a VOP response which could be:
    *   **Match:** The details provided are an exact match with the payee’s data held by the Responding PSP.
    *   **Close Match:** The payee's name is slightly different from the Responding PSP's records, and the Responding PSP also sends the name they have on file.
    *   **No Match:** The payee's details do not match the Responding PSP's records.
    *   **Verification check not possible:** The Responding PSP cannot perform the check for some reason.

The entire process is designed to be as quick as possible, taking no more than five seconds. This is in line with the maximum execution time stipulated in the rulebook, although participants can agree to shorter timescales.

**Scope of the VOP scheme rulebook**

The initial version of the VOP rulebook will focus on verifications for SCT and SCT Inst payments only. Future versions could encompass other payment instruments as needed. 

**What else has the EPC published?**

In addition to the rulebook, the EPC has also published:
*   Comments received during the public consultation on the proposed VOP scheme rulebook, as well as the VOP Task Force's responses.
*   The [first version of the EPC recommendations for the matching processes](https://www.europeanpaymentscouncil.eu/document-library/other/epc-recommendations-matching-processes-under-verification-payee-scheme) under the VOP scheme rulebook. 

The VOP Application Programming Interface (API) specifications and the updated API Security Framework document will be released by the end of October 2024. The EPC also plans to release further details on achieving reachability and interoperability for the VOP scheme at the EEA level. This will include information on mandatory registration and use of the EPC Directory Service (EDS), as well as the VOP adherence process. 
