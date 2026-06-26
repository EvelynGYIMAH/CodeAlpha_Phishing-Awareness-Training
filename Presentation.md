# Phishing Awareness Training: Shielding the Human Element
**Company:** CodeAlpha Cybersecurity Initiative  
**Target Audience:** Corporate Employees & Engineers  

---

## Slide 1: Introduction to Phishing
### What is Phishing?
Phishing is a form of **social engineering** where attackers impersonate trusted entities (banks, colleagues, IT support) to trick individuals into revealing sensitive information.

* **Target Assets:** Credentials, financial data, internal code repositories, API keys.
* **The Vulnerability:** Unlike software vulnerabilities, phishing exploits human psychology—trust, fear, urgency, or curiosity.

---

## Slide 2: Common Phishing Variants
Attackers customize their delivery vectors depending on the objective:

* **Mass Phishing:** Broad, un-targeted emails blast out to thousands hoping a small percentage click standard bait links.
* **Spear Phishing:** Highly targeted attacks customized with personal information (name, role, project details) gathered from OSINT (Open Source Intelligence) or LinkedIn.
* **Whaling:** Special spear phishing aimed exclusively at high-profile executives (CEOs, CFOs) to authorize large financial wire transfers.

---

## Slide 3: Anatomy of a Malicious Email


How do you spot a fake? Watch for these structural anomalies in inbound traffic:

1. **The Sender Domain:** Looks like `support@github-security.com` instead of a legitimate domain like `support@github.com`.
2. **Artificial Sense of Urgency:** "Your account will be suspended in 2 hours. Click immediately!"
3. **Generic Greetings:** "Dear Customer" or "Dear Valued Employee" instead of personalized names.
4. **Disguised Hyperlinks:** Hovering your mouse over the button reveals a completely different URL than what the text displays.

---

## Slide 4: Real-World Scenarios
### Scenario A: The Fake IT Security Alert
* **The Bait:** An email claiming your password expired or a suspicious login was blocked.
* **The Trap:** A link pointing to a cloned sign-in interface designed to log your corporate keystrokes.

### Scenario B: Urgent HR or Accounting Requests
* **The Bait:** A message from "HR" demanding you update your direct deposit info or review a shared document.
* **The Trap:** Downloading a malicious PDF or macro-enabled Excel sheet that installs a backdoor.

---

## Slide 5: Defensive Best Practices
To protect organizational infrastructure, follow these technical baselines:

* **Verify via Out-of-Band Channels:** If your manager messages you asking for a sudden transfer or access token, verify it via phone call or an internal chat message first.
* **Never Open Untrusted Attachments:** Treat unexpected `.zip`, `.exe`, `.xlsm`, or `.pdf` files with high suspicion.
* **Deploy MFA (Multi-Factor Authentication):** Even if an attacker steals your plaintext password via a phishing form, strong MFA tokens (FIDO2 keys or authenticator apps) prevent unauthorized logins.
* **Report Suspicious Traffic:** Use your email provider's reporting button to forward suspicious messages directly to the Security Operations Center (SOC).
