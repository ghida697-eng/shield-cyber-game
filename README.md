# 🛡️ Shield: Learn to Spot Online Scams

> A mobile-friendly game that trains you to tell safe from risky online situations, one real-life scenario at a time.

**Competition type:** Technical Competition
**Hackathon:** 305 EmpowHER, October 2026 (hosted by Code Crunch Worldwide)
**Theme alignment:** Education · Cybersecurity · Beginner-friendly · Empowering women and girls with digital safety skills

---

## Links

| | |
|---|---|
| 🎮 Live demo | https://ghida697-eng.github.io/shield-cyber-game/ |
| 💻 GitHub repository | https://github.com/ghida697-eng/shield-cyber-game |
| 🎥 10-minute feature demo (MP4) | [https://youtu.be/t6UqSdMTNok?si=F7-f0kJIl4MmQbC7] |
| 🎥 5-minute backup demo (MP4) | [ADD LINK] |
| 📊 Slides (Google Slides, public) | [ADD LINK] |
| 📄 Slides (exported file) | `slides/` folder |
| 🧾 Devpost | [ADD LINK] |

## The problem

Phishing, fake job offers, impersonation and image-based blackmail reach people through everyday messages. Many people, especially women and girls, are targeted by romance, job and "private photo" scams, yet most security advice is long, technical and easy to ignore.

## Our solution

**Shield** turns cybersecurity awareness into a short game. Players read a realistic message, call, or situation and decide whether it is **Safe** or **Risky**. After every answer they see a plain-language explanation and the exact **red flags** to look for, so the lesson sticks.

## Features

- **3 difficulty levels** that grow with the player:
  | Level | What to expect |
  |---|---|
  | 🌱 Easy | Classic scams with obvious warning signs |
  | 🌿 Medium | Impersonation, fake pop-ups and everyday security habits |
  | 🔥 Hard | Lookalike domains, fake QR codes, approval spam, safe things that look scary, with a 20-second timer |
- Instant feedback with red-flag chips and a clear explanation for every scenario
- Streak counter and progress bar
- Rank and badge at the end (Just Getting Started → Apprentice Defender → Shield Bearer → Cyber Guardian)
- A 5-point safety checklist after each round
- Shuffled questions for replay value
- Best score saved on the device (localStorage, no account and no data leaves the browser)
- Shareable result text
- Responsive, mobile-first layout with automatic light and dark mode

## Technologies

- HTML5, CSS3, vanilla JavaScript (no frameworks, no external libraries, no network requests)
- Browser localStorage for the best score
- Hosted as a static page

## Run it locally

1. Download or clone this repository.
2. Open `index.html` in any modern browser.

No installation or build step is needed.

## Project structure

```
├── index.html      # The complete app (HTML, CSS, JS)
├── README.md
├── slides/         # Exported deck (pdf or pptx)
├── videos/         # Demo videos or links
└── screenshots/    # Screenshots used in this README
```

## How it works

1. Scenarios are stored as data (source, message, risky or safe, red flags, explanation).
2. Each level selects its own set of scenarios, and the order is shuffled every round.
3. Hard level starts a countdown per question; running out of time counts as a miss.
4. Score, streak and progress update after each answer; results map to a rank.

## Screenshots

*(Add screenshots: start screen with levels, a question, the feedback card, the results screen.)*

## Team

| Name | Role / Contribution |
|---|---|
| [NAME] | [e.g. Idea, scenario writing, testing, presentation] |

## Citations and AI disclosure

- This project was built with assistance from **Claude (Anthropic)**, used for brainstorming the concept, drafting code and writing scenario text. The team reviewed and tested the result.
- No external datasets, libraries, templates or open-source code are included.
- Scenarios are original, written for education and inspired by commonly reported scam types (phishing, impersonation, fake job offers, MFA fatigue, malicious QR codes, image-based blackmail).
- Safety guidance follows widely published recommendations (verify through official channels, never share one-time codes, use two-factor authentication, keep software updated).

## What's next

- More languages (Arabic first) and a larger scenario bank
- Teacher and parent mode with class scores
- Scenario packs by audience (teens, job seekers, small business owners)
- Links to local reporting and support resources

## License

MIT (or your choice)
