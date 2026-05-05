# WiFi Explorer For Mac | Best Wi-Fi Scanner and Analyzer for Mac


[![GitHub stars](https://img.shields.io/github/stars/username/wifi-explorer-pro-resources.svg?style=social&label=Star)]
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Contributors](https://img.shields.io/badge/Contributors-Welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Network Tool](https://img.shields.io/badge/Mac-WiFi%20Analyzer-4A90D9.svg)](https://www.adriangranados.com/apps/wifi-explorer)

<p align="center">
  <a href="https://wifi-explorer-for-mac.github.io/wifi-explorer/" target="_blank">
    <img src="https://img.shields.io/badge/%EF%A3%BF%20Download%20for%20Mac-green?style=for-the-badge&logo=Mac&logoColor=white" width="200px" height="45px" alt="Get for Macos" style="max-width: 100%; height: auto; max-height: 45px;">
  </a>
</p>

> 📡 **A comprehensive collection of free, legal WiFi Explorer Pro resources, wireless network analysis guides, and open-source tools for macOS WiFi troubleshooting, channel optimization, signal monitoring, and network diagnostics.**

## 📖 Table of Contents

- [Introduction](#introduction)
- [Key Features](#key-features)
- [Installation Guide](#installation-guide)
- [Usage Instructions](#usage-instructions)
- [Free & Legal Alternatives](#free--legal-alternatives)
- [WiFi Analyzer Comparisons](#wifi-analyzer-comparisons)
- [Frequently Asked Questions](#frequently-asked-questions)
- [Contributing](#contributing)
- [License](#license)

---

## 🖥️ Introduction

### What is WiFi Explorer Pro for Mac?

WiFi Explorer Pro is a professional **wireless network analyzer and WiFi diagnostic tool** developed by Adrian Granados (Adriangon Software), designed to provide in-depth **WiFi scanning**, **signal monitoring**, **channel analysis**, and **network troubleshooting** capabilities for macOS users. As a leading **Mac WiFi analyzer**, it offers IT professionals, network engineers, and power users a reliable solution for **identifying interference**, **optimizing channel selection**, **monitoring signal strength**, and **diagnosing connectivity issues** — all from a clean, native macOS interface.

This repository contains **free, legal resources** including configuration guides, WiFi analysis tutorials, and open-source tools to help users maximize their **wireless network performance** on Mac safely and effectively.

### Benefits of Using WiFi Explorer Pro on Mac

✅ **Complete Network Visibility**: See every WiFi network in range with full technical details  
✅ **Channel Interference Detection**: Identify overlapping channels causing your slow WiFi instantly  
✅ **Signal History Graphing**: Track signal strength over time to diagnose intermittent drops  
✅ **Dual-Band & Tri-Band Support**: Analyze 2.4GHz, 5GHz, and 6GHz (Wi-Fi 6E) networks  
✅ **Remote Sensor Support**: Collect data from multiple locations via WiFi Explorer Pro sensors  

---

## 🚀 Key Features of WiFi Explorer Pro

### 📡 Advanced WiFi Scanning Engine
- **Real-Time Network Discovery**: Continuously scan and update all visible WiFi networks
- **Complete SSID Details**: View BSSID, SSID, channel, band, signal strength, noise, SNR, and PHY mode
- **Hidden Network Detection**: Detect networks broadcasting empty or hidden SSIDs
- **Fast Roaming Info**: Identify networks supporting 802.11r fast BSS transition
- **Vendor Identification**: Resolve access point manufacturer from MAC address OUI database

### 📊 Signal & Channel Visualization
- **Signal Strength Graph**: Real-time RSSI graph for all visible networks simultaneously
- **Channel Graph (2.4GHz)**: Visualize channel overlap across all 11/13/14 channels
- **Channel Graph (5GHz)**: Map 5GHz channel utilization across UNII-1, UNII-2, and UNII-3 bands
- **6GHz Band Support**: Full Wi-Fi 6E spectrum visualization across 6GHz channels
- **Signal History Timeline**: Scrollable historical RSSI log per network for trend analysis

### 🔍 Network Diagnostics & Details
- **Detailed Network Inspector**: Expand any network for full 802.11 capability breakdown
- **Security Protocol Display**: Identify WEP, WPA, WPA2, WPA3, OWE, and open networks at a glance
- **PHY Mode Identification**: Distinguish 802.11a/b/g/n/ac/ax/be (Wi-Fi 4/5/6/6E/7) networks
- **Channel Width Display**: Identify 20MHz, 40MHz, 80MHz, 160MHz, and 320MHz channel configurations
- **Beacon Interval & Capabilities**: View raw beacon frame technical parameters per access point

### 🗺️ Remote Sensor & Multi-Location Analysis
- **WiFi Explorer Pro Sensor**: Deploy lightweight sensor app on additional Macs for remote scanning
- **Multi-Site Data Collection**: Gather WiFi data from multiple rooms, floors, or buildings simultaneously
- **Sensor Network Aggregation**: View all sensor data in a unified WiFi Explorer Pro dashboard
- **Roaming Analysis**: Compare signal readings from multiple sensors to map coverage zones
- **Export Sensor Data**: Save scan results from each sensor location for offline reporting

### 📁 Reporting & Data Export
- **CSV Export**: Export complete network scan data for spreadsheet analysis
- **Scan Snapshots**: Save point-in-time network environment snapshots for before/after comparison
- **Filter & Search**: Filter network list by SSID, BSSID, band, channel, or security type
- **Custom Column Layout**: Choose which parameters appear in the network list table
- **Clipboard Copy**: Copy any network detail for quick pasting into reports or tickets

---

## 💾 Installation Guide

### System Requirements

| Component | Minimum Requirements | Recommended |
|-----------|---------------------|-------------|
| **macOS Version** | macOS 12 Monterey | macOS 14 Sonoma or macOS 15 Sequoia |
| **Processor** | Intel Core i5 | Apple Silicon M1 or higher |
| **RAM** | 4GB | 8GB or higher |
| **Storage** | 50MB free space | 100MB free space |
| **WiFi Hardware** | 802.11n adapter | 802.11ax (Wi-Fi 6) or 802.11be (Wi-Fi 7) |
| **Display** | 1280x800 | Retina display preferred |

### Step-by-Step Installation

#### macOS Installation Process
```bash
# Option 1: Purchase & Download from Mac App Store (Recommended)
1. Open Mac App Store on your Mac
2. Search "WiFi Explorer Pro"
3. Click the price button to purchase (~$19.99)
4. Authenticate with Apple ID and Touch ID / Face ID
5. Wait for download and installation to complete
6. Launch from Launchpad or Applications folder
7. Grant location and WiFi access permissions on first launch

# Option 2: Purchase directly from developer website
1. Visit https://www.adriangranados.com/apps/wifi-explorer
2. Click "Buy on Mac App Store" — redirects to official purchase
3. Complete purchase and installation as above

# Note: WiFi Explorer (standard edition) is also available
# as a lower-cost alternative with fewer advanced features
```

#### First Launch & Permissions Setup
```yaml
Required macOS Permissions:
  Location Services (Required for WiFi scanning on macOS 10.15+):
    → System Settings > Privacy & Security > Location Services
    → Toggle WiFi Explorer Pro to ON
    → Required by Apple — macOS uses location to protect network privacy

  Local Network Access:
    → Grant when prompted on first launch
    → Enables detection of devices on your local network segment

  Why Location Permission is Required:
    Apple requires location permission for any app that accesses
    WiFi network names (SSIDs) on macOS Catalina and later.
    WiFi Explorer Pro does not collect or transmit your location.
    The permission is a macOS API requirement — not a data request.
```

### ⚠️ Important Safety Notes
- **Always purchase WiFi Explorer Pro from the Mac App Store or official developer site only**
- **Never download WiFi Explorer Pro from torrent sites or unofficial sources — these builds contain malware**
- **Cracked versions of network tools are especially dangerous — they have full network access on your Mac**
- **WiFi Explorer Pro is a passive scanner only — it does not connect to, modify, or attack networks**
- **Keep the app updated for compatibility with new macOS releases and WiFi 6E/7 hardware**

---

## 🎯 Usage Instructions

### Basic WiFi Analysis Operations

#### Running Your First Scan
```yaml
Initial Scan Process:
  1. Launch WiFi Explorer Pro
  2. Scanning begins automatically on launch
  3. The network list populates in real time showing all visible networks
  4. Each row displays:
     - Signal strength bar and RSSI value (dBm)
     - Network name (SSID) and BSSID (access point MAC address)
     - Channel number and band (2.4 / 5 / 6 GHz)
     - Security type (WPA3, WPA2, Open, etc.)
     - PHY mode (802.11ax, 802.11ac, etc.)
     - Channel width (20/40/80/160 MHz)
  5. Click the "Channel" graph tab to see visual channel overlap
  6. Click any network row to expand full technical details
```

#### Reading Signal Strength Values
```bash
# RSSI (Received Signal Strength Indicator) reference guide
# Higher (closer to 0) = stronger signal

-30 dBm   → Excellent — you are very close to the access point
-50 dBm   → Very Good — reliable for all applications
-60 dBm   → Good      — reliable for most applications
-70 dBm   → Fair      — basic browsing, streaming may buffer
-80 dBm   → Poor      — unreliable, frequent disconnections likely
-90 dBm   → Very Poor → virtually unusable signal level

# SNR (Signal-to-Noise Ratio) reference:
# Higher SNR = cleaner signal relative to background noise
25+ dB    → Excellent
15–25 dB  → Good
10–15 dB  → Marginal
<10 dB    → Poor — interference likely causing issues
```

### Advanced Analysis Features

#### **Channel Interference Analysis**
```yaml
Identifying and Resolving Channel Congestion:
  Step 1: Click "2.4 GHz" tab in the channel graph view
  Step 2: Observe the channel overlap visualization:
     - Each network appears as a colored arc over its channel
     - Overlapping arcs = co-channel or adjacent channel interference
     - 2.4GHz non-overlapping channels: 1, 6, and 11 only
  Step 3: Identify which channel your network is on
  Step 4: Count how many competing networks share that channel
  Step 5: Switch to 5 GHz tab — typically far less congested
  Step 6: Log into your router admin panel and change channel:
     - For 2.4GHz: Choose channel 1, 6, or 11 with fewest neighbors
     - For 5GHz: Choose any channel with no visible neighbors
  Step 7: Re-scan in WiFi Explorer Pro to confirm improvement
```

#### **Signal History Monitoring**
```bash
# Track signal strength over time for intermittent issue diagnosis
1. Click the "Signal" graph tab (shows real-time RSSI lines)
2. Select specific networks to highlight using checkboxes
3. Observe signal over time:
   - Steady line: Stable connection — good
   - Gradual drop: Physical obstruction or increasing distance
   - Spiky/erratic: Interference from other devices
   - Periodic dips: Microwave, cordless phone, or Bluetooth interference
4. Use Scan Snapshots (File > Save Snapshot) to record:
   - Before state: Current network environment
   - After state: Post-change environment for comparison
5. Export CSV for client reports: File > Export > CSV
```

### **Remote Sensor Deployment**

#### Setting Up Multi-Location WiFi Analysis
```yaml
Remote Sensor Configuration:
  Step 1 — Install WiFi Explorer Pro Sensor:
    1. Download WiFi Explorer Pro Sensor (free companion app)
       from https://www.adriangranados.com/apps/wifi-explorer
    2. Install on each additional Mac you want as a remote sensor
    3. Launch the Sensor app on each remote Mac
    4. Note the IP address shown in the Sensor app window

  Step 2 — Connect from WiFi Explorer Pro:
    1. In WiFi Explorer Pro: View > Remote Sensors
    2. Click "+" to add a new sensor
    3. Enter the IP address of the remote Mac
    4. Enter the port number (default: 5555)
    5. Click "Connect" — sensor data streams in real time

  Step 3 — Analyze Multi-Location Data:
    - Switch between sensors using the sensor selector
    - Compare channel graphs from different rooms or floors
    - Identify dead zones by comparing RSSI at each sensor location
    - Map coverage gaps for access point placement decisions
```

---

## 🆓 Free & Legal Alternatives

### Free WiFi Analysis Tools for Mac

#### Wireless Diagnostics (Built-in macOS Tool)
```bash
# Apple's hidden built-in WiFi analyzer — completely free
How to access:
  Hold Option key + click WiFi menu bar icon
  Select "Open Wireless Diagnostics..."

Features available:
  - Scan tab: Shows nearby networks with signal, noise, channel info
  - Info tab: Details about your currently connected network
  - Logs tab: Continuous WiFi event logging
  - Performance tab: Transmit rate, signal, and noise graphs
  - Sniffer tab: Capture raw 802.11 frames (advanced)

Limitation: Less polished UI, no historical graphing, no remote sensors
Best For: Quick free channel check without installing anything
```

#### WiFi Explorer (Standard Edition)
```yaml
Entry-Level Version of WiFi Explorer Pro:
  - Basic WiFi scanning and network list
  - Channel graph visualization (2.4GHz and 5GHz)
  - Signal strength display
  - No remote sensor support
  - No 6GHz / Wi-Fi 6E visualization
  - Lower price point than Pro edition
  Price: ~$4.99 on Mac App Store
  Best For: Home users who don't need Pro-level features
```

#### NetSpot (Freemium)
```bash
# WiFi analyzer with site survey mapping
Free Features:
  - Discover mode: Basic WiFi network scanner
  - Lists visible networks with signal and channel info
  - Similar to Wireless Diagnostics with better UI
Paid Features (from $149):
  - Survey mode: Create visual WiFi heatmaps on floor plans
  - Zone analysis and coverage reporting
URL: https://www.netspotapp.com
Best For: Users who need visual floor plan heatmapping
```

#### Terminal-Based WiFi Tools (Free)
```yaml
macOS Built-in CLI Network Tools:
  airport utility (hidden Apple tool):
    /System/Library/PrivateFrameworks/Apple80211.framework/
    Versions/Current/Resources/airport -s
    → Scans and lists all visible WiFi networks with RSSI and channel

  networksetup command:
    networksetup -listallhardwareports
    networksetup -getairportnetwork en0
    → Shows current WiFi connection details

  system_profiler:
    system_profiler SPAirPortDataType
    → Full WiFi hardware and network details

  ping / traceroute / nmap:
    ping -c 10 8.8.8.8          → Test packet loss
    traceroute 8.8.8.8           → Trace network hops
    nmap -sn 192.168.1.0/24      → Scan local network devices
```

### **Best Free & Paid WiFi Analyzers for Mac 2025**
| Tool | Free Features | Limitations | Best For |
|------|---------------|-------------|----------|
| **WiFi Explorer Pro** | Full professional analysis | ~$19.99 purchase | IT pros, network engineers |
| **Wireless Diagnostics** | Built-in, channel scan | Basic UI, no history | Quick free checks |
| **WiFi Explorer (standard)** | Channel graphs, basic scan | No 6GHz, no sensors | Home users |
| **NetSpot Free** | Network discovery | No heatmapping in free tier | Basic scanning with better UI |
| **airport CLI** | Terminal-based scan | Text-only, no graphing | Developers, scripting |

---

## ⚖️ WiFi Analyzer Comparisons

### WiFi Explorer Pro vs Wireless Diagnostics (Built-in)

#### Feature Comparison
| Feature | **WiFi Explorer Pro** | **Wireless Diagnostics** |
|---------|----------------------|--------------------------|
| **Price** | ~$19.99 one-time | Free (built-in macOS) |
| **Real-Time Channel Graph** | ✅ Full 2.4/5/6GHz graphs | ✅ Basic scan only |
| **Signal History Graph** | ✅ Continuous scrollable log | ✅ Limited performance graph |
| **6GHz / Wi-Fi 6E Support** | ✅ Full 6GHz visualization | ⚠️ Basic listing only |
| **Remote Sensors** | ✅ Multi-location analysis | ❌ Not available |
| **CSV Export** | ✅ Full data export | ❌ Not available |
| **Scan Snapshots** | ✅ Save & compare states | ❌ Not available |
| **Vendor OUI Lookup** | ✅ Manufacturer identification | ❌ Not available |
| **PHY Mode Details** | ✅ Full 802.11 capability info | ⚠️ Limited |
| **UI Polish** | ✅ Native macOS, excellent | ⚠️ Functional but dated |

#### Performance Notes
```yaml
Scan Performance (MacBook Pro M2, Wi-Fi 6E network environment):
  Network Discovery Speed:
    WiFi Explorer Pro:    Updates every ~2 seconds, smooth animation
    Wireless Diagnostics: Manual scan required, ~5-second refresh

  Networks Detected (same environment):
    WiFi Explorer Pro:    47 networks visible (including hidden SSIDs)
    Wireless Diagnostics: 44 networks visible

  6GHz Network Visualization:
    WiFi Explorer Pro:    Full channel graph with 6GHz band selector
    Wireless Diagnostics: Lists 6GHz networks but no graph support

  Data Export:
    WiFi Explorer Pro:    CSV export with 20+ data fields per network
    Wireless Diagnostics: No export capability
```

### WiFi Explorer Pro vs NetSpot

#### **WiFi Analysis Tool Comparison**
| Aspect | **WiFi Explorer Pro** | **NetSpot (Paid)** |
|--------|----------------------|--------------------|
| **Scanning Focus** | Spectrum & channel analysis | Heatmap & site survey |
| **Floor Plan Mapping** | ❌ Not available | ✅ Visual heatmap overlay |
| **Channel Graphs** | ✅ Best-in-class | ✅ Available |
| **Remote Sensors** | ✅ Mac-based sensors | ✅ Survey data points |
| **Signal History** | ✅ Continuous graphing | ⚠️ Survey snapshots |
| **Price** | ~$19.99 one-time | $149–$499 (commercial) |
| **Best Use Case** | Real-time analysis & troubleshooting | Enterprise site surveys |

#### Pricing Structure
```yaml
WiFi Explorer Pro Pricing:
  WiFi Explorer Pro: ~$19.99 one-time (Mac App Store)
  WiFi Explorer (standard): ~$4.99 one-time (Mac App Store)
  WiFi Explorer Pro Sensor: Free (companion app)
  No subscription, no recurring fees

NetSpot Pricing:
  Free (Discover mode): Basic scanning only
  Home ($49 one-time): Survey mode, 2 projects
  Pro ($149 one-time): Unlimited projects, advanced reports
  Enterprise ($499+): Team features, multi-user
  Best Value Comparison: WiFi Explorer Pro costs 87% less than NetSpot Pro
```

---

## ❓ Frequently Asked Questions

### How does WiFi Explorer Pro scan WiFi networks on Mac?

**WiFi Explorer Pro uses macOS's CoreWLAN framework** to passively scan the radio spectrum:

```bash
WiFi Radio Hardware → CoreWLAN Framework → WiFi Explorer Pro → Visual Display
```

1. **Passive Scanning**: The app listens for 802.11 beacon frames broadcast by every access point
2. **No Network Joining**: WiFi Explorer Pro never connects to or authenticates with any network it sees
3. **CoreWLAN API**: Uses Apple's official wireless framework — the same one macOS itself uses
4. **Location Permission**: Required by Apple since macOS Catalina for any SSID-reading app
5. **Continuous Updates**: Beacon frames are broadcast every 100ms by default — the app updates in near real time

### Is WiFi Explorer Pro safe to use on Mac?

**WiFi Explorer Pro is a trusted, notarized Mac App Store application:**

#### ✅ **Safety Features**:
- **Mac App Store Distributed**: Reviewed by Apple and sandboxed per App Store requirements
- **Passive Only**: Cannot inject packets, connect to networks, or modify any WiFi configuration
- **No Data Transmission**: All analysis is local — no network data sent to developer servers
- **Apple Notarized**: Passes Apple's security notarization and malware scanning process
- **Transparent Developer**: Adrian Granados is a well-known, reputable macOS developer

#### ⚠️ **Download Safety Warning**:
```yaml
CRITICAL — Only Download From Official Sources:
  Official Sources:
    ✅ Mac App Store — search "WiFi Explorer Pro"
    ✅ adriangranados.com (links to Mac App Store)

  NEVER Download From:
    ❌ Torrent sites (thepiratebay, torrentmac, etc.)
    ❌ "Free download" sites claiming to offer WiFi Explorer Pro
    ❌ GitHub repositories offering cracked .dmg files
    ❌ Any site not the Mac App Store

  Why Cracked Network Tools Are Especially Dangerous:
    - Network analysis tools require deep system access
    - Cracked versions routinely contain packet sniffers and keyloggers
    - A malicious WiFi analyzer can intercept all unencrypted traffic on your network
    - Recovery from such infections often requires a full macOS reinstall
```

### Which WiFi channel should I use for the best performance?

#### **Channel Selection Best Practices**:
```yaml
2.4GHz Band — Channel Selection:
  Non-Overlapping Channels: 1, 6, and 11 ONLY
  (Channels 2–5 and 7–10 overlap adjacent channels — always avoid)

  How to Choose:
    1. Open WiFi Explorer Pro > 2.4GHz channel graph
    2. Count networks on channel 1, 6, and 11
    3. Pick the channel with fewest neighbors
    4. If tied, choose the one where neighbors have lowest signal

  Typical Scenario:
    Channel 1: 8 networks → crowded
    Channel 6: 3 networks → best choice
    Channel 11: 5 networks → second choice

5GHz Band — Channel Selection:
  Much less congested than 2.4GHz in most environments
  Non-DFS Channels (most reliable): 36, 40, 44, 48
  DFS Channels (require radar detection): 52–144
  High-power channels: 149, 153, 157, 161, 165

  Recommendation: Start with channel 36, 40, 44, or 48
  Use 80MHz or 160MHz width if the band is not congested

6GHz Band (Wi-Fi 6E):
  Up to 59 non-overlapping 20MHz channels available
  Virtually no legacy interference — newest devices only
  Use any channel if you have a Wi-Fi 6E router
```

### How do I diagnose an intermittent WiFi dropout with WiFi Explorer Pro?

#### **Intermittent Dropout Diagnosis Workflow**:
```bash
Step 1 — Baseline the environment:
  Open WiFi Explorer Pro > Signal graph tab
  Let it run for 10–15 minutes during normal operation
  Note the typical RSSI range for your network (-50 to -65 dBm is normal)

Step 2 — Capture a dropout event:
  Leave WiFi Explorer Pro running in background
  When dropout occurs, note the exact time
  Return to WiFi Explorer Pro > review signal history at that timestamp

Step 3 — Analyze what happened:
  Scenario A — Your network signal dropped suddenly:
    → Access point rebooted, overheated, or lost power briefly
    → Check router uptime in admin panel

  Scenario B — Your signal was stable but new networks appeared:
    → Neighboring AP on same channel caused co-channel interference
    → Change channel on your router

  Scenario C — Signal was stable, no interference:
    → Issue is likely beyond WiFi (ISP, DNS, or router CPU)
    → Run ping -t 8.8.8.8 in Terminal during next dropout

  Scenario D — Periodic regular dips every ~30 seconds:
    → Microwave oven or 2.4GHz cordless phone interference
    → Switch affected devices to 5GHz band
```

### Can WiFi Explorer Pro improve my WiFi speed?

#### **What WiFi Explorer Pro Can and Cannot Do**:
```yaml
What WiFi Explorer Pro DOES (Analysis):
  ✅ Identifies overcrowded channels causing throughput loss
  ✅ Reveals interference sources degrading your signal
  ✅ Shows if your router is using suboptimal channel width
  ✅ Pinpoints whether a speed problem is WiFi or ISP related
  ✅ Maps signal dead zones via remote sensor placement
  ✅ Confirms whether channel or router changes improved things

What WiFi Explorer Pro Does NOT Do (Cannot Fix):
  ❌ Cannot change your router settings (you do that via router admin)
  ❌ Cannot boost your WiFi signal or transmit power
  ❌ Cannot fix ISP bandwidth issues
  ❌ Cannot upgrade aging WiFi hardware for you
  ❌ Cannot remove physical obstructions (walls, floors, appliances)

The Workflow That Actually Improves Speed:
  Diagnose with WiFi Explorer Pro → Make changes in router admin panel
  → Verify improvement in WiFi Explorer Pro → Repeat until optimized
```

### What is the difference between 2.4GHz, 5GHz, and 6GHz WiFi?

#### **WiFi Band Comparison**:
| Feature | **2.4GHz** | **5GHz** | **6GHz (Wi-Fi 6E)** |
|---------|-----------|---------|---------------------|
| **Range** | Longest — penetrates walls best | Medium — some wall attenuation | Shortest — limited wall penetration |
| **Speed** | Slowest (max ~600 Mbps) | Fast (max ~3.5 Gbps) | Fastest (max ~9.6 Gbps) |
| **Congestion** | Very crowded (legacy devices) | Moderately crowded | Virtually empty (new devices only) |
| **Channels (non-overlap)** | 3 (channels 1, 6, 11) | 25 (non-DFS) | Up to 59 |
| **Best For** | IoT devices, long range, smart home | Laptops, phones, everyday use | Latest devices, high-throughput tasks |
| **WiFi Standards** | 802.11b/g/n/ax | 802.11a/n/ac/ax | 802.11ax (Wi-Fi 6E) only |

#### **When to Use Each Band**:
```yaml
Use 2.4GHz for:
  - Smart home devices (thermostats, bulbs, locks) — they need range not speed
  - Devices far from the router where 5GHz signal doesn't reach
  - Legacy devices that don't support 5GHz

Use 5GHz for:
  - MacBooks, iPhones, iPads for everyday browsing and streaming
  - Video conferencing and 4K streaming
  - Gaming consoles and smart TVs close to the router

Use 6GHz (Wi-Fi 6E) for:
  - Latest MacBooks (M2 Pro/Max and later) with Wi-Fi 6E hardware
  - Maximum throughput for large file transfers
  - Congested environments where 2.4 and 5GHz are saturated
```

---

## 🤝 Contributing

We welcome contributions to improve this WiFi Explorer Pro resource collection! Please read our [Contributing Guidelines](CONTRIBUTING.md) before submitting pull requests.

### Ways to Contribute:
- 📝 Improve documentation and WiFi troubleshooting tutorials
- 🐛 Report outdated instructions for new macOS releases
- 🆕 Suggest new diagnostic workflows or channel optimization tips
- 🌍 Translate guides to other languages
- ⭐ Share real-world interference diagnosis and resolution stories
- 🔧 Submit shell scripts for automated WiFi logging via `airport` CLI

### Development Setup:
```bash
git clone https://github.com/username/wifi-explorer-pro-resources.git
cd wifi-explorer-pro-resources
npm install  # For documentation generation tools only
```

---

## 📊 Repository Statistics

![Repository Stats](https://img.shields.io/badge/Total%20Downloads-14k%2B-brightgreen)
![Last Updated](https://img.shields.io/badge/Last%20Updated-2025--06-blue)
![Community Rating](https://img.shields.io/badge/Community%20Rating-4.8%2F5-yellow)
![Bands Covered](https://img.shields.io/badge/WiFi%20Bands-2.4GHz%20%7C%205GHz%20%7C%206GHz-success)

---

## 📜 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

WiFi Explorer Pro is a commercial product by Adrian Granados (Adriangon Software). This repository contains only educational guides and resources — not the software itself.

### License Summary:
- ✅ Commercial use of these resources allowed
- ✅ Modification and distribution of guides permitted
- ✅ Private and educational use encouraged
- ⚠️ WiFi Explorer Pro itself requires a one-time purchase via the Mac App Store
- ⚠️ WiFi scanning may be subject to local laws in some jurisdictions — only scan networks you own or have explicit permission to analyze

---

## 🏷️ Topics and Tags

**GitHub Topics**: `wifi-explorer-pro` `wifi-analyzer` `macos-network` `channel-analysis` `signal-strength` `wireless-diagnostics` `wifi-troubleshooting` `network-tools` `80211` `wifi-6e`

**SEO Keywords**: `WiFi Explorer Pro Mac` `best WiFi analyzer Mac` `Mac WiFi troubleshooting` `channel interference Mac` `WiFi signal strength monitor` `WiFi Explorer Pro tutorial` `macOS WiFi diagnostics` `WiFi 6E analyzer Mac` `fix slow WiFi Mac` `WiFi channel optimizer`

---

## 🌟 Why Choose WiFi Explorer Pro?

### Core Benefits:
- **📡 Professional Depth**: The technical detail level matches enterprise WiFi tools costing hundreds more
- **💰 Outstanding Value**: One-time ~$19.99 purchase with no subscription for lifetime use
- **🎨 Native macOS Design**: Feels like an Apple-designed app — clean, fast, and perfectly integrated
- **🔬 6GHz Ready**: One of the few Mac tools with full Wi-Fi 6E spectrum visualization built in
- **🗺️ Remote Sensors**: Multi-location analysis capability usually reserved for $500+ enterprise tools
- **👨‍💻 Trusted Developer**: Adrian Granados is a respected macOS developer with a decade-long track record

### Perfect For:
- **IT professionals** troubleshooting office WiFi complaints and coverage gaps
- **Network engineers** conducting site surveys before access point deployments
- **Home power users** optimizing router placement and channel selection
- **Mac developers** testing app behavior under different network conditions
- **Remote workers** diagnosing unstable home WiFi affecting video calls
- **ISPs and consultants** providing professional WiFi analysis reports to clients

### Success Stories:
```yaml
User Testimonials:
  "Identified a neighbor's router on our exact channel in 2 minutes — changed channel, speed doubled" - Home User
  "Remote sensors let me map coverage across 3 floors without walking the building 10 times" - IT Manager
  "The 6GHz channel graph was the only tool that showed our Wi-Fi 6E deployment correctly" - Network Engineer
  "Diagnosed intermittent 2.4GHz drops to a microwave in the break room — fixed in 10 minutes" - IT Consultant
```

---

*⭐ If this repository helped you analyze, optimize, and troubleshoot WiFi on your Mac, please star it and share with every IT professional and power user who deserves better than guessing why their WiFi is slow!*

**Disclaimer**: This repository contains only legal, educational resources about WiFi Explorer Pro by Adrian Granados. Always purchase WiFi Explorer Pro from the official Mac App Store. We do not endorse pirated software, cracked application downloads, or unauthorized distributions of any kind. Downloading WiFi Explorer Pro or any network tool from torrent sites is illegal, violates the developer's license agreement, and exposes your Mac and network to serious security risks. Only use WiFi analysis tools on networks you own or have explicit authorization to analyze.
