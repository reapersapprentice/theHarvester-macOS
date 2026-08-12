<h1 align="center">theHarvester <sub>· for macOS</sub></h1>

<p align="center"><b>Map a domain's public footprint — emails, names & subdomains — on your Mac.</b></p>

<p align="center">
  <img src="https://img.shields.io/badge/platform-macOS-000000?logo=apple&logoColor=white" alt="macOS">
  <img src="https://img.shields.io/badge/Intel%20%26%20Apple%20Silicon-supported-success" alt="Apple Silicon & Intel">
  <img src="https://img.shields.io/badge/license-GPL--2.0-blue" alt="license">
  <img src="https://img.shields.io/badge/beginner-friendly-ff69b4" alt="beginner friendly">
</p>

---

## ✨ What is this?

A classic reconnaissance tool: point it at a domain and it gathers the e-mail addresses, subdomains, hosts and names that are publicly discoverable across dozens of open sources.

This repository is a **macOS-ready conversion** — packaged so it runs on an Apple
Mac (Intel **or** Apple Silicon) without needing a Linux computer or a virtual
machine. This is an independent macOS conversion by **C.Studva**. The underlying program is open-source software distributed under the GNU General Public License; that license is kept in this repository (see `LICENSE`/`COPYING` and `NOTICE`).

## 🚀 Quick start

Open the **Terminal** app (press **Cmd ⌘ + Space**, type *Terminal*, hit Return),
then:

### 1. Get the files onto your Mac

```bash
git clone https://github.com/reapersapprentice/theHarvester-macOS.git
cd theHarvester-macOS
```

### 2. Install what it needs (one time)

```bash
pip3 install .
```

### 3. Run it

```bash
python3 -m theHarvester -d example.com -b duckduckgo
```

(swap `example.com` for a domain you're authorized to assess)

That's it — you're running **theHarvester** on your Mac. 🎉

## 🧰 What it can do

- Collects emails, subdomains, hosts and employee names
- Pulls from dozens of public search sources
- Great first step for an authorized security assessment

## 💻 What you need

- A Mac (macOS 12 or newer) — Intel or Apple Silicon
- Python 3 (already on macOS)

## 🆘 New to the Terminal? Read this (30 seconds)

- The **Terminal** is just a window where you type commands. Nothing here can hurt your Mac.
- Run the commands **one line at a time**, pressing **Return** after each.
- To paste, use **Cmd ⌘ + V**.
- ⚠️ **Copy only the command itself** — never the three back-ticks around it, and
  never a line that starts with `#` (those are notes). Pasting those is the #1
  beginner mistake and causes a `parse error`.
- If a command seems stuck, it's usually just working — give it a minute.

## ⚠️ Disclaimer

**For authorized and educational use only.** Only use this against systems,
accounts or data you **own** or have **written permission** to test. You are
responsible for how you use it. See [DISCLAIMER.md](DISCLAIMER.md) for the full
terms. In short: **C.Studva, the author of this macOS conversion, is not liable**
for any damage, loss or misuse.

## 📄 License

This is an independent macOS conversion by **C.Studva**. The underlying program is open-source software distributed under the GNU General Public License; that license is kept in this repository (see `LICENSE`/`COPYING` and `NOTICE`).

## 🍎 More macOS conversions by C.Studva

Same idea — popular Linux tools, packaged to run **natively on your Mac**:

- [**Hash-Buster**](https://github.com/reapersapprentice/Hash-Buster-macOS) — identify & crack hashes in seconds
- [**Eagle Eye**](https://github.com/reapersapprentice/EagleEye-macOS) — find someone's social profiles from a photo
- [**Sublist3r**](https://github.com/reapersapprentice/Sublist3r-macOS) — fast subdomain enumeration
- [**httptunnel**](https://github.com/reapersapprentice/httptunnel-macOS) — tunnel a data stream over HTTP

---

<p align="center"><sub>macOS conversion crafted by <b>C.Studva</b>.</sub></p>
