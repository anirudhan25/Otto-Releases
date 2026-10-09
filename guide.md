# Installing Otto (Beta Guide)

Thank you for beta testing **Otto**!

Because Otto is currently in early beta and distributed outside official app stores, your operating system (macOS or Windows) will display a security warning during initial setup.

**These steps are only required once for your initial installation.** All future app updates will download and install automatically in the background without security prompts.

---

##  macOS Installation Guide

### Step 1: Download & Move to Applications

1. Download the installer file corresponding to your Mac from the **Assets** list:
   - **Apple Silicon (M1/M2/M3/M4):** the file ending in `_aarch64.dmg`
   - **Intel Macs:** the file ending in `_x64.dmg`
2. Open the downloaded `.dmg` file.
3. Drag **Otto.app** into your **Applications** folder.

---

### Step 2: Authorize Otto (Choose Method A or B)

#### Method A: Right-Click Shortcut (Fastest)

1. Open your **Applications** folder.
2. **Right-click** (or hold `Control` and click) on **Otto.app**.
3. Click **Open** from the menu.
4. When the macOS warning prompt appears, click **Open**.

---

#### Method B: Privacy & Security Settings

If you double-clicked Otto and saw a warning dialog:

1. Click **Done** or **Cancel** on the pop-up (_do not move the app to the Bin_).
2. Click the **Apple Logo ()** in the top-left corner and select **System Settings**.
3. Select **Privacy & Security** from the left sidebar.
4. Scroll down to the **Security** section.
5. Next to the notice stating _"Otto was blocked from use..."_, click **Open Anyway**.
6. Enter your Mac password or use Touch ID to confirm.

---

## Windows Installation Guide

### Step 1: Run the Installer

1. Download the file ending in `_x64-setup.exe` from the **Assets** list.
2. Double-click the file to begin installation.

### Step 2: Bypass SmartScreen

1. When the blue **Windows protected your PC** window appears, click the **More info** link located under the main warning text.
2. Click the **Run anyway** button that appears at the bottom of the window.
3. Follow the on-screen prompts to complete installation.

---

## Getting started (2 minutes)

### 1. Sign in

Click your name at the bottom-left → **Sign in**. Otto works signed out, but an account is what lets you:

- use **Otto**, the built-in research assistant (it runs through our servers, so it needs to know who's asking);
- **share a project** with collaborators and get invitations;
- connect **Google Docs**, **Zotero**, **Mendeley**, **Teams** and **Zoom**.

### 2. Add free search keys (highly recommended)

Search works without any keys, but the free limits are low: OpenAlex, our main catalogue, allows only about 100 searches a day without one. In **Settings → Search sources**, click **Get a key** next to **OpenAlex** (and Semantic Scholar if you like), then paste it in. Keys are free, take a minute, and stay on your computer.

### 3. Set your university link (for paywalled papers)

In **Settings → Access**, paste your library's link prefix, then click **Connect university** and sign in on your library's own page. Otto never sees your password.

- **Southampton:** `http://soton.idm.oclc.org/login?url=`
- **UCL:** `https://libproxy.ucl.ac.uk/login?url=`
- Anywhere else: search your library's site for "EZproxy" or "off-campus access".

### 4. Meet Otto (and please go easy on it...)

Otto is the assistant in the bottom-right corner. Click it, or press **⌘J** (Ctrl+J on Windows), and tell it what you want: _"Triage this project's inbox"_, _"Highlight the key findings in this paper"_, _"Plan these tasks over the next month"_. It works inside the app for you and asks before anything hard to undo.

**This is a test build, and we pay for every Otto request.** Please keep usage light 🙂:

- In **Settings → Assistant**, prefer **GPT-5.4 mini** or **GPT-5.4**. Those are the **free** ones for you to use as much as you need.
- The other models (the larger GPT and Claude models) are **paid for by us**, so use them only when you really need to compare.
- Each account has a monthly allowance; Otto will tell you if you reach it.
- Let us know via Feedback if Otto does or says anything unexpected or incorrect

### 5. Tell us what breaks

See the small **bug icon** at the top-right of every screen? Click it any time something looks wrong, slow or confusing, or just to send an idea. It reaches us directly, and it's the most useful thing you can do as a tester.

---

## Your data

- Your library, PDFs, highlights and notes live **on your computer**. We don't receive them and can't see them.
- PDFs are never uploaded by us. (Backing them up to _your own_ Google Drive is an optional switch in Settings → Connectors, off by default.)
- If you **share a project**, the things in it that collaborators need (paper details, pages, tasks, highlights and comments, but never PDFs) are synced through our cloud so they can see them. Projects you don't share stay local except for your private notes or comments.
- When you ask Otto something, the text it needs for that request is sent to the AI provider to get an answer, or if you choose to use a local model then it is just for you.
- A bug report sends what you typed plus basic technical details (which screen, app version). It does not include your papers or notes.
