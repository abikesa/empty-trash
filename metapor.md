

### 🧠 **What is `osascript`?**

`osascript` is a **command-line tool on macOS** that lets you run **AppleScript** (and JavaScript for Automation) from the terminal.

It’s the bridge between:

* your **Terminal** (UNIX/bash/zsh environment), and
* macOS’s **graphical apps** (like Finder, Safari, System Events, etc.)

---

### 🧬 Native to macOS

`osascript` is **built into macOS** — no install required. It’s how Terminal can tell GUI apps what to do.

---

### 🛠️ Basic Syntax:

```zsh
osascript -e 'AppleScript goes here'
```

Examples:

#### 🗑️ Empty the Trash:

```zsh
osascript -e 'tell application "Finder" to empty the trash'
```

#### 🌐 Open a URL in Safari:

```zsh
osascript -e 'tell application "Safari" to open location "https://www.apple.com"'
```

#### 🔊 Set volume to max:

```zsh
osascript -e 'set volume output volume 100'
```

---

### 🤖 Why it's powerful:

AppleScript taps into macOS's **scriptable GUI** — so you can automate:

* Finder actions
* App control (like Mail, Safari, Calendar)
* System dialogs and UI scripting

And `osascript` lets you do all that from **bash/zsh scripts**, crons, or aliases.

---

### 🧵 Final metaphor:

If `bash` is your scalpel for the UNIX layer, `osascript` is your **mind-control wand** for the GUI layer.

You’re not just editing files — you’re whispering to Finder like a backend sorcerer.


