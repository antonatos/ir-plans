# Northstar Logistics — Inject 01 / Initial alert

**Scenario clock:** 08:42 | **Workshop reveal:** minute 10

### Facts available to the response team
- Logistics supervisor **Maya K.** reported an email claiming to be from a delivery allocation portal.
- Displayed sender: `dispatch-updates@northstar-notice.example`
- Link in email: `https://login.northstar-verify.example/auth`
- The user reports clicking the link at 08:39 and entering their work username and password.
- An unfamiliar high-risk cloud sign-in is flagged at 08:47 for the same account.
- Source IP in the fictitious alert: `203.0.113.24` (RFC 5737 TEST-NET; reserved for documentation).
- No confirmed endpoint malware execution and no confirmed data theft at this stage.

### Questions
1. What is proven, what is only suspected, and what do you need to validate?
2. Which playbook step handles the identity sign-in event? Who owns it?
3. Which assets may be impacted beyond the email gateway?
4. Is a password reset sufficient to declare recovery?

**Safe lab boundaries:** all domains are reserved `.example` domains; no phishing page exists; do not attempt live access to the simulated URLs.
