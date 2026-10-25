# STEP-BY-STEP HANDBOOK: BUILD YOUR OWN SECRET MEETING NOTE-TAKER (ANYONE CAN DO THIS)

<div align="center">

### 🌐 Switch Language / Chuyển đổi ngôn ngữ:
[![English](https://img.shields.io/badge/🇬🇧_Currently_Viewing-English-0984e3?style=for-the-badge)](GUIDE_EN.md)
[![Switch to Vietnamese](https://img.shields.io/badge/🇻🇳_Chuyển_sang-Tiếng_Việt-d63031?style=for-the-badge)](HUONG_DAN_CHI_TIET.md)
[![Back to README](https://img.shields.io/badge/📖_Homepage-README_EN.md-2d3436?style=for-the-badge)](README_EN.md)

</div>

---

## 1. What does this system do and how does it work?

### 1.1. The Simplest Way to Picture It
Imagine hiring an **invisible personal secretary** sitting right next to your computer’s speakers:
* Whenever your boss or client speaks during a Zoom or Google Meet call, this secretary diligently listens and types down every single spoken word onto a blank document in real time.
* You simply wear your regular headphones, listen to the meeting as usual, and glance at the corner of your screen to read the live transcript.

### 1.2. Three Absolute Guarantees
* **100% Secret & Undetectable:** No third-party bots joining the call. No recording indicator or badge on screen. Nobody in the meeting will ever know you are transcribing.
* **100% Free:** Built entirely using free built-in and open-source tools. No subscription fees, ever.
* **Marathon Reliability:** Works uninterrupted throughout lengthy 3 to 4-hour meetings without stopping or cutting off.

---

## 2. Everything you need ready on your desk

Check off these 3 items before you begin:

- [ ] **1. Your everyday headphones:**
  * Wired headphones (3.5mm headphone jack or USB/Type-C).
  * Or wireless Bluetooth earbuds/headphones (AirPods, Sony, Samsung, Bose, etc.).

- [ ] **2. Web browser:**
  * **YOU ONLY NEED ONE BROWSER: Google Chrome** *(Highly recommended for simplicity, free download: [google.com/chrome](https://www.google.com/chrome/))*.
  * *(Optional alternative):* You can also install **Firefox** ([mozilla.org/firefox](https://www.mozilla.org/firefox/)) if you prefer keeping your meeting and your note-taking document in completely separate browsers.

- [ ] **3. "Virtual Audio Cable" software (Pick one depending on your computer):**
  * **For Windows PC:** Download **VB-Audio Cable** (Free) at: [vb-audio.com/Cable](https://vb-audio.com/Cable/) *(Click the orange button with the floppy disk icon labeled "Download").*
  * **For Mac (Apple):** Download **BlackHole 2ch** (Free) at: [existential.audio/blackhole](https://existential.audio/blackhole/) *(Enter your email to receive the direct download link for both older Intel Macs and new M1, M2, M3, M4 Apple Silicon Macs).*

> **What is a "Virtual Audio Cable"?**  
> Usually, audio from a meeting travels in one single pipe straight into your ears and disappears. This software acts as a **virtual 3-way pipe splitter**: one branch sends sound to your headphones, a second branch stays ready for your laptop speakers, and a third branch sends the exact same voice into Google Chrome for live auto-typing.

---

## 3. Detailed Setup Instructions for Your Computer

*(Find the section below that matches your computer model)*

---

### PART A: FOR WINDOWS COMPUTERS (DELL, HP, ASUS, LENOVO, THINKPAD...)

#### STEP 1: Check for the built-in "Stereo Mix" feature
Many Windows laptops already have a built-in virtual audio splitter called "Stereo Mix".

* **Action 1.1:** On your keyboard, hold down the **Windows key** (the key with 4 squares) and press the letter **R**. A small "Run" box will pop up in the lower-left corner.
* **Action 1.2:** Type `mmsys.cpl` into the box and press **Enter** on your keyboard.
* **Action 1.3:** A small window named **Sound** will appear. Click on the second tab labeled **Recording** (with a small microphone icon).
* **Action 1.4:** Look through the list for an item named **Stereo Mix** (icon looks like two vertical signal bars):
  * *If you see it and it's grayed out:* Right-click on **Stereo Mix** -> Click **Enable**. A green checkmark will appear. You are all set—skip directly to **Section 4** to test!
  * *If you DO NOT see Stereo Mix:* Don't worry! Your machine simply requires the free add-on. Proceed to **Step 2** below.

#### STEP 2: Install and configure "VB-Audio Cable" (If you don't have Stereo Mix)

* **Action 2.1 (Install):** Extract the ZIP file you downloaded in Section 2. Right-click the file named `VBCABLE_Setup_x64.exe` and click **Run as administrator** (shield icon) -> Click **Install Driver** -> Restart your computer once.
* **Action 2.2 (Set default playback):** Look at the bottom-right corner of your screen (near the clock). Left-click the **Speaker icon**. Click the small arrow next to your current speaker name -> Click on **CABLE Input (VB-Audio Virtual Cable)**.
* **Action 2.3 (Route sound back to headphones):** Press `Windows + R`, type `mmsys.cpl` and press Enter. Click the second tab labeled **Recording**.
* **Action 2.4:** Right-click on **CABLE Output** -> Click the bottom option labeled **Properties**.
* **Action 2.5:** In the new window, click the second tab labeled **Listen** (with a headphone icon). Check the box next to **Listen to this device**.
* **Action 2.6:** Right below that, under *Playback through this device*, click the drop-down menu and select **your plugged-in headphones** -> Click the **OK** button at the bottom right.  
*(Now meeting sound will flow into the virtual cable for typing and simultaneously into your ears).*

---

### PART B: FOR OLDER INTEL MACS (MACBOOK, IMAC WITH INTEL PROCESSOR)

*After downloading and installing BlackHole 2ch from Section 2:*

#### STEP 1: Open the Mac Audio Manager
* **Action 1.1:** Press the **Command (⌘)** key and the **Spacebar** together to open Spotlight Search in the center of your screen.
* **Action 1.2:** Type `Audio MIDI Setup` and hit **Return (Enter)**. The Audio Devices window will appear.

#### STEP 2: Create a Splitter "Configure Once, Use Forever"
* **Action 2.1:** Look at the bottom-left corner of the window and click the white **Plus button (+)**.
* **Action 2.2:** In the pop-up menu, click **Create Multi-Output Device**.
* **Action 2.3 (CHECK ALL 3 BOXES FOR SEAMLESS HEADPHONE & SPEAKER SWITCHING):**  
  On the right panel, check the boxes for **ALL 3 DEVICES**:
  1. **BlackHole 2ch** *(routes voice into Google Docs)*
  2. **External Headphones** *(or your connected Bluetooth headphones)*
  3. **MacBook Speakers** *(built-in laptop speakers)*  
  👉 *Checking all 3 boxes now means you can plug/unplug headphones anytime without ever having to reopen this configuration panel again!*
* **Action 2.4:** In the left sidebar, right-click on the newly created **Multi-Output Device** -> Click **Use This Device For Sound Output**.

#### STEP 3: Set Default Input
* **Action 3.1:** Click the Apple logo () in the top-left corner of your screen -> Click **System Settings** (or **System Preferences**).
* **Action 3.2:** Click on **Sound** (speaker icon) -> Click the **Input** tab -> Select **BlackHole 2ch**.

---

### PART C: FOR MODERN APPLE SILICON MACS (MACBOOK WITH M1, M2, M3, M4 CHIPS)

*Apple Silicon chips feature strict security and ultra-precise audio clocks. Follow these exact steps:*

> ⚠️ **IMPORTANT WARNING ABOUT MACOS PERMISSION POPUPS:**  
> The first time you click the microphone in Google Chrome, macOS will show a system dialog: *"Google Chrome would like to access the microphone"*.  
> 👉 **ALWAYS CLICK "ALLOW" (OR "OK").**  
> Never click "Don't Allow". If accidentally denied, macOS locks Chrome's microphone at the operating system level, and you must follow Step 2 below to unlock it.

#### STEP 1: Create a Multi-Output Device with Drift Correction
* **Action 1.1:** Press **Command + Spacebar**, type `Audio MIDI Setup`, and press **Enter**.
* **Action 1.2:** Click the **Plus button (+)** in the lower-left corner -> Select **Create Multi-Output Device**.
* **Action 1.3 (CHECK ALL 3 BOXES):** In the right list, check the boxes for:
  1. **BlackHole 2ch**
  2. **Your Headphones** (External Headphones or Bluetooth earbuds)
  3. **MacBook Speakers** (Built-in speakers).
* **Action 1.4 (MANDATORY):** Look at the column header labeled **Drift Correction**. On the horizontal line for **BlackHole 2ch**, **check the small box**.  
  *(This prevents audio jitter and keeps live transcription silky-smooth on Apple Silicon).*
* **Action 1.5:** In the left sidebar, right-click on **Multi-Output Device** -> Select **Use This Device For Sound Output**.

#### STEP 2: Grant Microphone Access to Google Chrome (Troubleshooting Safeguard)
* **Action 2.1:** Click the Apple logo () in the top-left corner -> Click **System Settings** (gray gear icon).
* **Action 2.2:** In the left sidebar, click **Privacy & Security** (blue hand icon) -> Click on **Microphone**.
* **Action 2.3:** Find **Google Chrome** in the list -> Toggle the switch to the right so it turns **Green**.

---

## 4. Test Run with YouTube (Always do this before a real meeting!)

```
[Play YouTube Video (Tab 1 in Chrome OR in Firefox)] 
                            │
                            ▼ (Audio routes through the Virtual Cable)
                            │
        [Your Headphones (You hear the audio clearly)] 
                            + 
        [Google Docs (Tab 2 in Chrome: Automatically typing words)]
```

### Step 4.1: Play Sample Audio
* Open a tab in Google Chrome (or Firefox), go to `youtube.com`, and play a clear speech or news video (e.g., a TED Talk or news channel).
* **VOLUME CHECK:** Turn the YouTube video volume slider up high (50% to 100%).
* **Verification:** Put your headphones on. **You must clearly hear the video playing in your ears.**

### Step 4.2: Open Voice Typing in Google Chrome
* In Google Chrome, open a new tab and go to `docs.google.com`. Click **Blank document**.
* In the top menu bar, click **Tools** -> Click **Voice typing** (or press keyboard shortcut `Ctrl + Shift + S` on Windows, `Command + Shift + S` on Mac).
* A small box with a **Gray Microphone icon** will appear on your page. Above the microphone, select your meeting language (e.g., `English (US)` or `Tiếng Việt`).

### Step 4.3: Direct the Virtual Microphone & RELOAD THE PAGE
* Look at Chrome's address bar at the very top (where it says `docs.google.com...`).
* On the left edge of the address bar, click the **Sliders icon** (or the small padlock icon):
  * Click **Site settings**.
  * Find the line labeled **Microphone**: Click the dropdown menu and select your virtual audio cable:
    * *On Windows:* Select **Stereo Mix** or **CABLE Output (VB-Audio Cable)**.
    * *On Mac:* Select **BlackHole 2ch**.
* **CRITICAL STEP — RELOAD THE PAGE:**  
  Return to the Google Docs tab. You MUST refresh the page for Chrome to initialize the new virtual microphone:
  * **On Windows PC:** Press the **F5** key on your keyboard.
  * **On Mac:** Press **Command + R** on your keyboard (or click the **Circular Arrow icon** next to the address bar).

### Step 4.4: Click Start
* Click directly on the **Gray Microphone icon** in Google Docs. *(If a Mac system prompt appears asking for permission, immediately click **Allow / OK**)*.
* The icon will turn **Bright Red** with a pulsing circle around it, indicating that it is listening.

### Step 4.5: Check Your Results
* **SUCCESS:**  
  You hear the YouTube video playing through your headphones, and on Google Docs, words automatically stream onto the document in real time! Your system is 100% operational.
* **TROUBLESHOOTING (Google Docs shows "Can't hear you" or stays red without typing):**
  * *Fix 1:* Verify you reloaded the page (`F5` on Windows or `Command + R` on Mac) in Step 4.3.
  * *Fix 2:* Check that the YouTube video volume is NOT muted. Keep player volume high.
  * *Fix 3:* Click the red microphone off and on again.

---

## 5. Live Meeting Setup on Zoom and Google Meet

### 5.1. CHOOSE YOUR PREFERRED METHOD:

#### 👉 OPTION A: ONE BROWSER ONLY (GOOGLE CHROME) — Recommended
* **If you meet using the ZOOM or TEAMS desktop app:**  
  * Keep it simple: Run your Zoom/Teams app normally on one half of your screen.
  * Open Google Chrome on the other half with Google Docs and click the red microphone. You do not need any second browser!
* **If you join GOOGLE MEET inside Chrome:**  
  * Open two separate Chrome windows side by side (one window for Google Meet, one window for Google Docs).
  * **CRUCIAL RULE — Independent Microphones:**
    * **In your Google Meet window (for you to speak):** Click the three dots `⋮` at the bottom of the Meet call -> *Settings* -> *Audio*. Set **Microphone** to your **Real Microphone** (your headphone mic or laptop mic) so coworkers can hear your voice.
    * **In your Google Docs window (for automated typing):** Keep the microphone set to the **Virtual Cable** (`CABLE Output` or `BlackHole 2ch`) as configured in Step 4.3.  
    *(Chrome allows separate tabs to use completely different microphones simultaneously without any conflict).*

#### 👉 OPTION B: TWO DIFFERENT BROWSERS
* Put **Firefox** on the left half of your screen (used for joining Zoom or Google Meet).
* Put **Google Chrome** on the right half (used for Google Docs transcription).

---

### 5.2. Three Golden Security Rules (Never violate these)

| RULE | WHY & WHAT TO DO INSTEAD |
| :--- | :--- |
| **1. NEVER Minimize the Chrome Window** | If you click the minimize button `_` to hide Chrome into your taskbar/dock, your computer puts the tab to sleep to save battery -> **Voice typing will immediately freeze.** <br>👉 *Always keep the Chrome window visible on your screen, even if resized into a small corner.* |
| **2. NEVER Share "Entire Screen"** | When presenting, sharing your entire desktop will expose your live Google Docs transcript to everyone. <br>👉 *Always select **"A Window"** or **"A Tab"** so participants only see your presentation slide.* |
| **3. NEVER Mute Meeting Audio on Software** | If you mute the YouTube player, browser tab, or meeting app volume, zero sound flows into the virtual cable -> **Google Docs will stop hearing words.** <br>👉 *Keep software volume at 50% or above. If audio feels too loud, adjust the physical volume buttons on your headphones.* |

---

## 6. Pro-Tip: Switch to External Speakers without Losing Live Text

### On a Mac:
* Because you already **checked all 3 boxes (BlackHole, Headphones, and MacBook Speakers)** back in Step 2.3 / 1.3, your system is now **fully automated**:
  * When you plug headphones in: Audio plays through headphones and sends a copy to Google Docs.
  * When you unplug headphones: Audio automatically plays through your MacBook speakers, and Google Docs **continues transcribing 100% uninterrupted without missing a single syllable**.
  * If using Bluetooth headphones and you want quiet speakers: Simply turn down the laptop speaker volume; the Bluetooth headphones and Google Docs will still transcribe flawlessly.

### On Windows:
* Press `Windows + R`, type `mmsys.cpl`, and hit **Enter**.
* Click the **Recording** tab, double-click **CABLE Output** (or Stereo Mix) -> Click the **Listen** tab.
* Under *Playback through this device*, change the dropdown from your headphones to **Speakers (Realtek Audio / High Definition Audio)** -> Click **OK**.
* Audio will instantly route to your laptop speakers while Google Docs keeps typing uninterrupted.
