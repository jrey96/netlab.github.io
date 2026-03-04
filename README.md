# NetLab — Interactive Networking Reference

A collection of browser-based, interactive simulators for core networking concepts. Built for network admin interview prep.

## 🚀 Live on GitHub Pages

**Your site URL will be:** `https://YOUR-USERNAME.github.io/netlab`

---

## Setup (5 minutes)

### Step 1 — Create a GitHub account
Go to [github.com](https://github.com) and sign up (free).

### Step 2 — Create a new repository
1. Click the **+** icon (top right) → **New repository**
2. Name it: `netlab`
3. Set to **Public**
4. Click **Create repository**

### Step 3 — Upload your files
1. On your new repo page, click **Add file** → **Upload files**
2. Drag in these files (maintaining the folder structure):
   - `index.html` → root level
   - `tools/arp-lab.html` → inside a `tools` folder
3. Click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Go to your repo → **Settings** tab
2. Click **Pages** in the left sidebar
3. Under **Source**, select **Deploy from a branch**
4. Set branch to **main**, folder to **/ (root)**
5. Click **Save**

### Step 5 — Visit your site
After ~60 seconds, your site is live at:
```
https://YOUR-USERNAME.github.io/netlab
```

---

## File Structure

```
netlab/
├── index.html          ← Homepage with lab cards
├── README.md           ← This file
└── tools/
    ├── arp-lab.html    ← ARP Interactive Simulator (LIVE)
    ├── vlan-lab.html   ← (add when ready)
    └── stp-lab.html    ← (add when ready)
```

## Adding a New Lab

1. Save your new lab HTML file into the `tools/` folder
2. Upload it to GitHub
3. In `index.html`, copy an existing card and update the `href`, title, and description
4. Commit — it goes live instantly, no rebuilding needed

## Labs Tracker

| Lab | Status | Topics |
|-----|--------|--------|
| ARP | ✅ Live | ARP request/reply, caching, gratuitous ARP |
| VLANs | 🔜 Soon | Access ports, trunk links, 802.1Q |
| STP | 🔜 Soon | Root bridge, port states, convergence |
| Subnetting | 🔜 Soon | CIDR, masks, host ranges |
| OSPF | 🔜 Soon | LSA flooding, SPF, convergence |
| DHCP | 🔜 Soon | DORA process |
