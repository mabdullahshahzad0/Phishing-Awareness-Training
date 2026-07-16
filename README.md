# 🛡️ Phishing Awareness Training

An interactive, single-page online training module built for **Task 2** of the **CodeAlpha Cyber Security Internship**. It teaches employees and everyday users how to recognize phishing emails and fake websites, understand the social engineering tactics attackers rely on, and build habits that prevent falling victim — capped off with a scored knowledge-check quiz.

🔗 **Live demo:** open `index.html` in any browser, or enable GitHub Pages (see below) for a hosted link.

---

## ✨ Features

- **What Is Phishing?** — a plain-language introduction with a key statistic callout.
- **Types of Phishing Attacks** — Email, Spear, Whaling, Smishing, Vishing, and Clone phishing explained side by side.
- **Interactive "Anatomy of a Phishing Email"** — click each highlighted line in a mock email to reveal *why* it's a red flag, with the matching checklist item auto-highlighting.
- **How to Spot a Fake Website** — a practical 6-point checklist.
- **Social Engineering Tactics** — the psychological triggers (Authority, Urgency, Fear, Curiosity, Trust) attackers exploit.
- **Real-World Attack Patterns** — common, real-world phishing scenarios organizations face today.
- **Best Practices & Tips** — actionable habits that block almost every phishing attempt.
- **Scored Knowledge Check** — a 5-question interactive quiz with instant feedback, explanations, a final score, and a retake option.
- Fully responsive, works on desktop and mobile, no build step or dependencies required.

## 🗂️ Project Structure

```
phishing-awareness-training/
├── index.html      # the entire training module (HTML + CSS + JS, single file)
└── README.md        # this file
```

## 🚀 Getting Started

No installation needed — it's a static HTML file.

**Option 1: Open locally**
```bash
git clone https://github.com/<your-username>/phishing-awareness-training.git
cd phishing-awareness-training
open index.html      # macOS
start index.html      # Windows
xdg-open index.html   # Linux
```

**Option 2: Host it for free with GitHub Pages**
1. Push this repository to GitHub (see below).
2. Go to **Settings → Pages** in your repository.
3. Under **Source**, select the `main` branch and `/ (root)` folder, then **Save**.
4. Your live training module will be available at:
   `https://<your-username>.github.io/phishing-awareness-training/`

## ⬆️ Uploading to GitHub

If this project isn't already in a repository:

```bash
cd phishing-awareness-training
git init
git add .
git commit -m "Add phishing awareness training module"
git branch -M main
git remote add origin https://github.com/<your-username>/phishing-awareness-training.git
git push -u origin main
```

## 🧰 Built With

- HTML5, CSS3 (custom properties, CSS Grid & Flexbox), vanilla JavaScript — no frameworks or build tools
- [Google Fonts](https://fonts.google.com/) — Fraunces (display) & Inter (body)
- Inline SVG icons

## 📚 About This Task

> **Task 2: Phishing Awareness Training**
> - Create a presentation or online module focused on phishing attacks.
> - Explain how to recognize phishing emails and fake websites.
> - Educate about social engineering tactics used by attackers.
> - Provide best practices and tips to avoid falling victim.
> - Include real-world examples and interactive quizzes for better engagement.

This project satisfies every requirement above as a self-contained, interactive **online module**.

## 👤 Author

**Muhammad Abdullah Shahzad**
Cyber Security Intern — CodeAlpha
📧 mabdullahshahzad0@gmail.com
🔗 [LinkedIn](https://www.linkedin.com/in/m-abdullah-shahzad-88a740321/) · [GitHub](https://github.com/mabdullahshahzad0)

## 📄 License

This project is free to use for educational and training purposes.
