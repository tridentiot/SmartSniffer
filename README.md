<h1 align=”center”>🚀 Trident IoT® SmartSniffer™</h1>

<p align=”center”>
  <em>Multi-Protocol packet intelligence — built by developers for developers.</em>
</p>


---

## 🧠 What Is SmartSniffer™?

Trident IoT® **SmartSniffer™** is a **multi-protocol diagnostic tool**.

The SmartSniffer™ is used to sniff, capture, decode, decrypt and analyze radio frequency (RF) communications within an IOT network. It acts as a protocol analyzer, allowing developers and installers to debug issues, monitor traffic, decrypt secure packets, and optimize network performance.  


---


## 🧰 Prerequisites

Before you begin, make sure you have:

- 🧾 **Required:** [Elcap Installed and Account Created](https://github.com/tridentiot/elcap)
- ⚙️ **Required:** [Smartsniffer™ Hardware](https://tridentiot.com/technology/hardware/)

---

## ⚡ Quick Start — Run via ElCap

The easiest way to run SmartSniffer™ is through **ElCap**. Set the environment variable and launch:

#### macOS / Linux
```bash
elcap tools smartsniffer
```

#### Windows (PowerShell)
```powershell
elcap tools smartsniffer
```

#### Windows (Command Prompt)
```cmd
elcap tools smartsniffer
```


-----

## 🧩 Features

| Feature                        | Status | Description                                      |
| ------------------------------ | ------ | ------------------------------------------------ |
| ![](https://img.icons8.com/?size=25&id=80168&format=png&color=000000) Zigbee Support              | ✅      | Zigbee packet analysis with attribute converters  |
| ![](https://drzwave.blog/wp-content/uploads/2020/10/z-wave-long-range.png?w=25) Z-Wave Support              | ✅      | Z-Wave packet analysis with command converters    |
| ⭐ Packet Bookmarks            | ✅      | Star packets, add notes, filter, and navigate bookmarks |
| 💾 Native `.tsf` Captures      | ✅      | Save raw+decoded snapshot data with bookmark persistence |
| 🔍 Column Filtering            | ✅      | Filter on all columns including additional fields |

## 💾 Capture Files and Bookmark Persistence

SmartSniffer now has two write paths:

1. **Save (`.tsf`)**  
   Native Trident Sniffer capture format.  
   Preserves:
   - raw packet bytes
   - decoded snapshot fields
   - bookmark flag + note
   - network keys in the capture file

2. **Export (`.dcf` / `.csv`)**  
   Compatibility output for external workflows.  
   Bookmark fields are intentionally **not** preserved in DCF/CSV export files.

### Bookmark Workflow

- Toggle bookmark from the grid star column, top-bar controls, or `B` shortcut.
- Add/edit notes in the packet details panel.
- Use `★ Only`, `◀★`, and `★▶` for fast triage navigation.
- Bookmarks are shareable when the capture is saved as `.tsf` and reopened by another user.


-----

## 💬 Community & Support

  * 📧 Email: [Support@tridentiot.com](mailto:Support@tridentiot.com)
  * 🐛 Issues: [GitHub Issues Page](https://github.com/tridentiot/smartsniffer/issues)

-----

## 🧾 License

> © 2026 **Trident IoT™** — All rights reserved.
> The Trident IoT® "SmartSniffer" is proprietary software, licensed through Trident IoT LLC.

-----
