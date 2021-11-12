# PCI DSS

## What is PCI-DSS?
PCI-DSS (Payment Card Industry Data Security Standard) is a set of actionable rules defined by the Payment Card Industry Security Standards Council to encourage the broad adoption of consistent data security measures around the world with an aim to reduce credit card fraud.

These rules apply to anyone who stores, processes, or transmits cardholder data.

## Why do shops need to be PCI DSS compliant?
PCI DSS was designed and includes detailed requirements for exactly this reason—to minimize the chance of compromise and the effects if a compromise does occur. 

## How to be PCI-DSS compliant?
To be PCI compliant, the shop have to have an SSL Certificate, a PCI-compliant web host OR a payment gateway that uses a Third-Party Payment Page that is PCI compliant, and a filled-out SAQ. 

Typically, PCI compliance reports are enforced by the payment processor – they may require that you fill out questionnaires (Self Assessment Questionnaire – or SAQ) or be scanned by an ASV (approved scanning vendor) of their choosing.

List of ASV:
https://www.pcisecuritystandards.org/assessors_and_solutions/approved_scanning_vendors

In our case, the shop is using a Third-Party Payment Page, Stripe. All Stripe users must validate their PCI compliance annually. Most users can do this with a Self-Assessment Questionnaire (SAQ) provided by the PCI Security Standards Council.  

Therefore, getting SAQ ready would make the shop PCI compliant. 