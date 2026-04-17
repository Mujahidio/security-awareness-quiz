# Security Awareness Quiz App

An interactive web-based quiz to test employee knowledge of **phishing**, **social engineering**, **vishing**, **smishing**, and other cyber threats. Built for use in organizational security awareness training programs.

Live demo: open `index.html` in any browser — no server required.

---

## Features

- 15 scenario-based questions covering real attack techniques
- Difficulty levels: Beginner / Intermediate / Advanced
- Instant feedback with detailed explanations per question
- Streak counter and live score tracking
- Final report with personalized improvement tips
- Saudi regulatory context (PDPL, SAMA CSF references)
- Zero dependencies — pure HTML, CSS, JavaScript

---

## Topics Covered

| Topic | Example Scenario |
|-------|-----------------|
| Phishing | Typosquatted domains, BEC/CEO fraud |
| Spear Phishing | Targeted attacks using personal data |
| Vishing | Fake IT support calls |
| Smishing | Suspicious SMS with shortened URLs |
| Social Engineering | Pretexting, tailgating, MFA fatigue |
| Password Security | Passphrase vs complex password strength |
| MFA & Authentication | MFA fatigue/bombing attacks |
| Incident Response | First steps after a malware click |
| Cloud Security | Leaked credentials in GitHub |
| Data Protection | PDPL compliance in data sharing |

---

## Usage

### As a standalone training tool
```bash
# Just open the file
open index.html
# or
python -m http.server 8080   # then visit http://localhost:8080
```

### Deployment
Host on any static web server, SharePoint, or internal intranet — no backend required.

---

## Customization

To add your own questions, edit the `ALL_QUESTIONS` array in `index.html`:

```javascript
{
  category: "Your Category",
  difficulty: "easy" | "medium" | "hard",
  question: "Scenario text here...",
  hint: "A helpful hint...",
  options: ["Option A", "Option B", "Option C", "Option D"],
  correct: 0,  // index of correct answer (0-3)
  explanation: "Why this answer is correct..."
}
```

---

## Author

**Mujahid Ahmed** — Cybersecurity GRC Specialist  
[LinkedIn](https://linkedin.com) | [GitHub](https://github.com)
