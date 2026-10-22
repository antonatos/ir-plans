# Northstar Logistics — Phishing Response v0.1

**Workshop case:** NSL-IR-026  
**Document type:** Internal incident response playbook (training seed)  
**Status:** Existing procedure; last owner/review not specified  
**Trigger:** A user reports a suspicious email or the mail gateway flags a potentially malicious link.

## Objective
Quickly identify and remove suspected phishing email to prevent further user interaction.

## Procedure

1. **Receive report.** Open a security ticket and record the reporting user's name and the suspicious message subject.
2. **Check reputation.** Investigate the sender, link domain, and any URL indicators using available reputation services.
3. **Search for other copies.** Find matching messages in mailboxes and remove messages considered malicious.
4. **Check user interaction.** Ask the user whether they clicked the link and whether they entered credentials.
5. **Reset password if suspicious.** If the user reports entering credentials or if the email is clearly malicious, ask IT to reset the password.
6. **Inform SOC lead.** Send a short incident summary to the team lead.
7. **Close.** Close the ticket when matching messages are removed and the user has changed their password, if required.

## Existing notes
- Relevant tools: email gateway, threat-intelligence lookup, helpdesk ticketing system.
- Applicable systems/assets: "corporate email".
- Detailed roles, approval criteria, evidence retention, and service recovery: not recorded.

---

**TRAINING NOTICE:** This is a deliberately incomplete playbook. It is not a safe production response procedure. Its omissions are intentional learning material; participants are asked to identify and address them. Do not execute destructive, tenant-level, or disruptive actions from this seed.

**Suggested public comparison:** Microsoft phishing investigation playbook:
https://learn.microsoft.com/en-us/security/operations/incident-response-playbook-phishing
