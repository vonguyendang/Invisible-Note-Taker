# 🎙️ Invisible Note-Taker

<div align="center">

### 🌐 Switch Language / Chuyển đổi ngôn ngữ:
[![English](https://img.shields.io/badge/🇬🇧_Currently_Viewing-English-0984e3?style=for-the-badge)](README_EN.md)
[![Switch to Vietnamese](https://img.shields.io/badge/🇻🇳_Chuyển_sang-Tiếng_Việt-d63031?style=for-the-badge)](README.md)

</div>

> A 100% secret, automated real-time meeting note-taker that transcribes audio from Zoom, Google Meet, Microsoft Teams, or YouTube directly into Google Docs via headphones—with **zero detection, zero bots, and zero monthly fees**.

---

## 📖 1. About The Project

In today's fast-paced remote work environment (Zoom, Google Meet, Microsoft Teams), meetings are frequent, dense, and packed with critical decisions and action items.

Trying to actively participate, listen, and frantically type manual notes at the same time often leads to missed context or divided attention. Meanwhile, commercial AI meeting note-takers (such as Otter.ai, Fireflies.ai, Fathom...) come with 3 severe drawbacks:
1. **Conspicuous & Awkward:** They require inviting an obvious "Bot" into the call, which can make clients, partners, or executives uncomfortable or suspicious.
2. **Blocked by Admins:** High-security enterprise or confidential calls strictly prohibit meeting recording permissions and block external participant bots.
3. **Expensive Subscriptions:** Most charge $15 to $30/month and enforce restrictive monthly transcription minute limits.

**Invisible Note-Taker** was engineered as an elegant, minimalist alternative: **It routes meeting audio directly from your headphone playback line into Google Docs via an internal virtual audio cable.** You get a faithful, word-for-word transcript in real time while remaining 100% invisible to everyone else on the call.

---

## 💰 2. 100% Free Forever Commitment

This project is strictly designed around **zero-cost, native, and open-source capabilities**:
* **No Software Purchase:** No upfront licensing, no premium software trials.
* **No Recurring Monthly Fees:** You will never be asked to upgrade plans or purchase extra transcription hours.
* **No APIs or Tokens:** Powered directly by Google Docs' built-in, unmetered Voice Typing technology and open-source/free audio splitters (BlackHole on macOS / VB-Audio Cable & Stereo Mix on Windows).

---

## 🔒 3. Security & Privacy Deep Dive

This system offers vastly superior privacy compared to cloud-based third-party AI transcription bots:

* **100% Local Audio Pipeline (No Middleman Servers):** Audio from your meeting flows strictly through your computer's virtual kernel driver into your local Chrome browser. **No unknown third-party cloud servers intercept, record, or store your voice.**
* **Protected by Your Authenticated Google Account:** Transcripts are written straight into a private Google Doc within your personal/enterprise Google Drive, safeguarded by Google's multi-factor authentication.
* **Zero Digital Footprint:**
  * No bot accounts appear in the meeting participant list.
  * Zoom and Google Meet will never display a "Recording..." status banner.
  * No intrusive automated audio announcements (*"This meeting is being recorded"*) will interrupt your colleagues.

---

## ⚠️ 4. Risk Assessment & Important Disclaimers

While this workflow is completely undetectable and local, users must understand the following technical risks and legal principles:

### 4.1. Technical Risks & Prevention Safeguards

| REAL-WORLD RISK | IMPACT | SAFEGUARD RULE |
| :--- | :--- | :--- |
| **Accidental Screen Sharing Exposure** | When sharing your screen to present, choosing "Entire Screen" will broadcast your live-typing Google Docs window to all meeting attendees. | 👉 **Golden Rule:** Always select **"A Window"** or **"A Tab"** when sharing slides. Never share your entire screen. |
| **Minimizing the Chrome Window** | Hiding the Chrome window to your taskbar/dock triggers aggressive OS power saving, putting the tab to sleep -> Voice typing stops immediately. | 👉 **Golden Rule:** Keep the Chrome window visible on screen at all times (even if resized into a tiny corner). |
| **Muting Audio at the Software Level** | Muting YouTube, your browser tab, or the meeting app reduces the virtual audio stream to 0 -> Google Docs stops receiving sound. | 👉 **Golden Rule:** Keep software volume above 50%. If it feels too loud, lower volume via the physical buttons on your headphones. |

### 4.2. Legal & Ethical Disclaimer
* **Intended Purpose:** This documentation is provided solely for educational, technological research, and personal productivity purposes (helping individuals retain meeting context and action items).
* **Corporate & NDA Compliance:** Users are solely responsible for adhering to their organization's internal Non-Disclosure Agreements (NDAs), data governance policies, and confidentiality standards.
* **Consent Laws:** Certain jurisdictions enforce strict consent regulations (e.g., Two-Party or All-Party Consent laws) regarding the recording or transcription of private conversations. Please ensure compliance with local legal requirements.

---

## 📂 5. Project Documentation

| Document | Language | Description | Switch to Vietnamese |
| :--- | :--- | :--- | :--- |
| **[README_EN.md](README_EN.md)** | 🇬🇧 English | Project overview, security, free commitment, and quick start | 👉 **[README.md](README.md)** |
| **[GUIDE_EN.md](GUIDE_EN.md)** | 🇬🇧 English | Full step-by-step handbook (Windows, Mac Intel, Mac M1-M4) | 👉 **[HUONG_DAN_CHI_TIET.md](HUONG_DAN_CHI_TIET.md)** |

---

## 🛠️ 6. How It Works (The Virtual Audio Splitter)

```
Meeting Audio (Zoom / Teams app OR Google Meet tab on Chrome)
                             │
                             ▼
               [Virtual Audio Cable / Splitter]
       ├── Branch 1 ────────► [Your Headphones (You hear audio as normal)]
       ├── Branch 2 ────────► [Laptop Speakers (Auto-switches if unplugged)]
       └── Branch 3 ────────► [Google Docs on Chrome (Auto-types live text)]
```

---

## ⚡ 7. 4-Step Quick Start

1. **Gear Preparation:**
   * Plug in your everyday headphones (wired or Bluetooth).
   * Install **Google Chrome** *(Optional: install Firefox if you prefer completely separate browsers)*.
2. **Setup the Virtual Audio Cable:**
   * **Windows:** Enable built-in *Stereo Mix* or install [VB-Audio Cable](https://vb-audio.com/Cable/).
   * **macOS:** Install [BlackHole 2ch](https://existential.audio/blackhole/) and create a *Multi-Output Device* checking all 3 devices: BlackHole + Headphones + MacBook Speakers *(Remember to check Drift Correction on M1-M4 Macs)*.
3. **Run a Test on YouTube:**
   * Play any clear YouTube video on one tab (keep volume > 50%).
   * Open a blank Google Doc on another tab, reload the page (`F5` on Windows or `Cmd + R` on Mac), enable **Voice typing**, and verify live transcription.
4. **Join Real Meetings:**
   * *Zoom / Teams:* Run the desktop app + open Google Docs in Chrome.
   * *Google Meet inside Chrome:* Set Meet's mic to your **real mic** (to speak), and Docs' mic to the **virtual cable** (to transcribe).
   * *3 Golden Rules:* Never minimize Chrome, Never share entire screen, and Never mute software volume.

👉 *For full visual steps and troubleshooting, read **[GUIDE_EN.md](GUIDE_EN.md) (English)** or **[HUONG_DAN_CHI_TIET.md](HUONG_DAN_CHI_TIET.md) (Tiếng Việt)**.*
