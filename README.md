# DNS Configuration Tool - Ad Blocker for Windows 11

This batch script provides a simple, menu-driven interface to configure or reset DNS settings on Windows 11. It's designed to help users apply **AdGuard DNS** for ad-blocking across system-wide connections, or revert back to automatic DNS using DHCP.

---

## 🔧 Features

- Automatically elevates to administrator privileges
- Supports both **Wi-Fi** and **Ethernet** connections
- Configures both **IPv4** and **IPv6** DNS addresses
- Provides a menu with:
  - `1` - Apply AdGuard DNS (for ad blocking)
  - `2` - Restore default DNS (automatic/DHCP)
- Lightweight, portable `.bat` file — no installation required

---

## 📦 DNS Servers Used

**AdGuard DNS (non-family-safe):**

- IPv4:
  - Primary: `94.140.14.14`
  - Secondary: `94.140.15.15`
- IPv6:
  - Primary: `2a10:50c0::ad1:ff`
  - Secondary: `2a10:50c0::ad2:ff`

---

## 🚀 How to Use

1. **Download** The zip from Releases.
2. **Run** the script:
   - Double-click `AdBlocker.bat`
   - It will request **administrator access** automatically if needed.
3. **Choose an option**:
   - Press `1` to apply AdGuard DNS.
   - Press `2` to reset DNS to automatic.

---

## ⚠️ Adapter Name Notes

This script assumes the default network adapter names:
- `Wi-Fi`
- `Ethernet`

If your system uses different names (e.g., `Ethernet 2`, `Local Area Connection`), edit these two lines in the script:
```bat
set "wifi=Wi-Fi"
set "ethernet=Ethernet"
