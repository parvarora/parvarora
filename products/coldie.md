<div align="center">

<img src="../assets/coldie-logo.png" alt="ColdIE logo" width="110" height="110" style="border-radius:24px" />

# ColdIE

### Personalized bulk emails — save time. ❤️

**Send 50 personalized cold emails in one click, get the small details right, and track every reply — so reaching out feels less cold and more _you_.**

🔗 **Live:** [coldie.web.app](https://coldie.web.app) &nbsp;·&nbsp; [← Back to profile](../README.md)

</div>

---

## 🌷 What is ColdIE?

Cold-emailing recruiters is exhausting: hunt down contacts, clean the data, guess the right greeting, personalize each message, send them one by one, then chase replies.

**ColdIE turns all of that into one warm, encouraging workflow.** Paste a messy list of contacts, let AI structure and personalize everything, send the whole batch in a single click, and watch the replies roll in — built for people who are putting themselves out there and deserve a tool that feels like it's rooting for them.

---

## ✨ What it does

- **🤖 AI contact extraction** — paste any messy text (emails, directories, notes) and it pulls out clean names, emails, and companies.
- **🫡 Smart honorifics** — automatically guesses the right greeting (`sir` / `mam` / `sir/mam`) so nothing feels generic.
- **✍️ Templates with placeholders** — write once with `{Name}`, `{Company}`, or your own fields, plus fallbacks like `{Company : your team}`.
- **📨 Bulk personalized send** — one click sends an individually-tailored email to everyone, paced safely.
- **👀 Live, editable preview** — see exactly what each person will receive, tweak any single one, reset anytime.
- **📊 Reply tracking** — see who replied, with counts, snippets, and your overall reply rate.
- **🗂️ Send history** — a scrollable record of everything you've ever sent (date + resume used), kept forever.
- **📎 Attachments & video pitch** — attach your resume and drop in a Loom/YouTube/Drive portfolio link.
- **☁️ Cloud sync** — your campaigns and contacts follow you across sessions.

---

## 📖 How to use ColdIE

### 1. Sign in
Open [coldie.web.app](https://coldie.web.app) and **sign in with Google**. This lets ColdIE send emails *as you* and read your inbox to detect replies. We never see your password — it's standard Google sign-in.

### 2. Write your email
In the **Template** editor, set your **subject** and **body**. Use placeholders wherever something should change per person:

| Placeholder | Becomes |
|-------------|---------|
| `{Name}` | the recipient's name |
| `{Company}` | their company |
| `{salutation}` | sir / mam / sir/mam |
| `{anything_you_want}` | a custom field you define |
| `{Company : your team}` | uses a **fallback** ("your team") when the value is missing |

The **"fields to extract"** box below the template stays in sync with the placeholders you use — so the AI knows exactly what to pull from your contact text.

> 💡 Sound genuine, not robotic. This email represents *you* — placeholders make it personal, but the voice should be yours.

### 3. Add your resume & portfolio (optional)
Attach your **resume** (PDF/doc) and/or paste a **video pitch link** (YouTube, Loom, Drive). These ride along with every email in the batch.

### 4. Add your recipients
Paste any unstructured contact text into the **AI Recipient Intelligence** box — email lists, a directory dump, rough notes — and hit **"Generate mails to preview & confirm."** Gemini extracts each person's name, email, company, the right honorific, and any custom fields you asked for. You can also **add rows manually**.

### 5. Review & personalize
Everyone shows up in the **spreadsheet**. Fix any name/email/company inline. The **Live Preview** shows exactly what each recipient will get — and you can hand-edit a single email if you want (then **reset to template** anytime).

### 6. Send the batch
Hit **"Execute ColdIE Campaign."** ColdIE sends a personalized email to everyone who hasn't been sent yet, paced safely to keep your account healthy. Watch the live progress bar — and **abort** anytime.

### 7. Track replies
Reply status updates automatically after sending, or hit **"Scan All Replies"** / the refresh icon on a row. The dashboard shows **Replies Received** and your **reply rate**.

### 8. Keep things tidy
- **Sent emails stay forever** in the scrollable history (with date + resume used).
- **Clear Drafts** removes unsent rows so you can start a fresh batch — your sent and failed rows are kept.
- A **50 emails/day** limit keeps your sending in safe territory.

---

## 💡 Tips for better replies

- **Personalize for real** — fill in the data behind your placeholders; identical mass emails are the #1 reason messages land in spam.
- **Keep it short and human** — recruiters skim. Lead with why *them*, not just why *you*.
- **Attach proof** — a resume + a 60-second video pitch stands out.
- **Don't blast from a brand-new account** — warm it up; send steadily, not all at once.

---

## 🔒 Your data, your inbox

- Sign-in is handled by Google — **we never see your password.**
- Your contacts and campaigns live in **your own isolated cloud space**.
- ColdIE only ever sends the emails **you approve**, and never stores your email bodies.

---

## 🛠️ Built with

React 19 · TypeScript · Vite · Tailwind CSS 4 · Node/Express · Google Gemini 3.5 Flash · Firebase Auth & Firestore · Gmail API

---

<div align="center">

Made with <span>❤️</span> by **Parv Arora**

_Your next role starts with the right email. Go get it._ 🚀

</div>
