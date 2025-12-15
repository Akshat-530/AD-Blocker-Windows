# 🛡️ DNS Configuration Tool - Akshat_530

A lightweight and user-friendly **batch script** to quickly **apply, reset, or inspect DNS settings** across all connected network adapters on a Windows machine. Switch between popular DNS services like **AdGuard, Cloudflare, and Google**—with full IPv4 and IPv6 support—and restore to default DHCP with one click.

---

## 📦 Features

- ✅ One-click DNS configuration for all active adapters
- 🚀 Switch between DNS services:
  - **AdGuard DNS** (Ad & tracker blocking)
  - **Cloudflare DNS** (Fast & privacy-focused)
  - **Google DNS** (Reliable and widely used)
- 🔄 Restore default DHCP DNS
- 👀 View current DNS settings
- 🌐 Direct links:
  - [GitHub Scripts Page](https://github.com/Akshat-530)
  - [Ko-fi Support](https://ko-fi.com/akshat_530)
- 🧰 Auto-elevates to Administrator if required
- 🖥️ Compatible with Windows 10 and 11

---

## 📝 How It Works

The script uses native Windows commands (`netsh`) to manage DNS:

1. Detects all **connected network adapters**.  
2. Applies or resets **IPv4 and IPv6 DNS** settings.  
3. Provides an **interactive menu** for DNS selection.  
4. Supports multiple DNS profiles:

| DNS Provider | Profile | IPv4 | IPv6 |
|--------------|--------|------|------|
| Google       | Standard | 8.8.8.8, 8.8.4.4 | 2001:4860:4860::8888, 2001:4860:4860::8844 |
| Google       | Secure / DoT | 8.8.8.8, 8.8.4.4 | 2001:4860:4860::8888, 2001:4860:4860::8844 |
| Google       | Family | 8.8.8.8, 8.8.4.4 | 2001:4860:4860::8888, 2001:4860:4860::8844 |
| Cloudflare   | Standard | 1.1.1.1, 1.0.0.1 | 2606:4700:4700::1111, 2606:4700:4700::1001 |
| Cloudflare   | Family | 1.1.1.3, 1.0.0.3 | 2606:4700:4700::1113, 2606:4700:4700::1003 |
| Cloudflare   | Security | 1.1.1.2, 1.0.0.2 | 2606:4700:4700::1112, 2606:4700:4700::1002 |
| AdGuard      | Ad Blocking | 94.140.14.14, 94.140.15.15 | 2a10:50c0::ad1:ff, 2a10:50c0::ad2:ff |
| AdGuard      | Family Protection | 94.140.14.15, 94.140.15.16 | 2a10:50c0::bad1:ff, 2a10:50c0::bad2:ff |
| AdGuard      | Non-Filtering | 94.140.14.140, 94.140.14.140 | N/A |
| Other        | Quad9 | 9.9.9.9, 149.112.112.112 | 2620:fe::fe, 2620:fe::9 |
| Other        | OpenDNS | 208.67.222.222, 208.67.220.220 | N/A |
| Other        | OpenDNS FamilyShield | 208.67.222.123, 208.67.220.123 | N/A |

---

## 🚀 Usage

1. **Download** the latest release and **unzip** it.  
2. **Double-click** the `AdBlocker v1.2.bat` file.  
3. Follow the **interactive menu** to select your preferred DNS:

- Selecting a DNS profile applies it **to all active adapters**.  
- Option to **restore defaults** reverts DNS settings back to DHCP.  
- Option to **view current DNS** shows IPv4 and IPv6 settings per adapter.  

---

## 💡 Tips

- **Secure DNS / DoT** requires supporting adapters and system settings.  
- Use **Family or AdGuard profiles** to filter content or block ads.  
- Ensure the script runs with **Administrator privileges** to make DNS changes effective.  

---

## 🔗 Links

- [GitHub Scripts Page](https://github.com/Akshat-530)  
- [Ko-fi Support](https://ko-fi.com/akshat_530)  

---

## ⚡ License

MIT License © Akshat_530
