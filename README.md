# 📱 Android Tools & System Utilities

A curated collection of useful Android tools, system utilities, DNS tools, VPN apps, and privacy-focused applications.

> ⚠️ Note: This list is for educational and personal use. Apps and tools are frequently updated, so features and availability may change over time.

---

## 🧰 System Tools

Tools for device optimization, automation, and system control.

- **[Termux](https://termux.dev)**  
  *Platforms: Android*  
  Powerful terminal emulator and Linux environment for Android. Run Linux packages, use apt package manager, script with bash/python, and access Linux tools directly on your device. Great for developers and power users.

- **[SD Maid](https://sdmaid.app)**  
  *Platforms: Android*  
  Comprehensive storage cleaner that removes leftover files, cache, app data, and system junk. Includes app cleaner, corpse finder, duplicate finder, and system cleaner. Helps free up storage space and improve performance.

- **[Shizuku](https://shizuku.rikka.app)**  
  *Platforms: Android*  
  Allows apps to use system APIs directly with adb/root privileges without requiring root access. Many apps use Shizuku to provide enhanced functionality like permission management, app ops control, and system settings modification.

- **[LSPosed](https://lsposed.org)**  
  *Platforms: Android (root required)*  
  Xposed framework implementation for Android R and above. Allows running modules that modify system behavior without modifying system partitions. Supports a wide range of modules for customization and enhancement.

- **[Magisk](https://github.com/topjohnwu/Magisk)**  
  *Platforms: Android*  
  Systemless root solution that modifies the boot partition instead of system partition. Includes Magisk Hide for root detection bypass, MagiskSU for root management, and supports modules for system modifications.

- **[KernelSU](https://kernelsu.org)**  
  *Platforms: Android*  
  Root solution for Android kernel that works at kernel level. Provides root access without modifying system partitions and supports overlayfs for system modifications.

---

## 🌐 DNS & Privacy Tools

Improve speed, privacy, and security with custom DNS solutions.

- **[1.1.1.1 (Cloudflare WARP)](https://one.one.one.one)  
  *Platforms: Android, iOS, Windows, macOS, Linux*  
  Fast, privacy-focused DNS service from Cloudflare. WARP provides VPN-like protection by encrypting DNS traffic and routing through Cloudflare's network. Includes 1.1.1.1 DNS resolver for faster, more private browsing.

- **[NextDNS](https://nextdns.io)  
  *Platforms: Android, iOS, Windows, macOS, Linux, Router*  
  Fully customizable DNS service with advanced features. Ad-blocking, parental controls, security filtering, analytics, and privacy protection. Works on all devices and can be configured via app or router settings.

- **[AdGuard](https://adguard.com)  
  *Platforms: Android, iOS, Windows, macOS, Browser extensions*  
  Comprehensive ad-blocking and privacy solution. Blocks ads, trackers, and malicious domains at DNS level across all apps and browsers. Includes AdGuard DNS, AdGuard VPN, and browser extensions for complete protection.

- **[RethinkDNS](https://rethinkdns.com)  
  *Platforms: Android, Windows, macOS, Linux, Router*  
  Open-source DNS resolver with built-in firewall capabilities. Blocks trackers, ads, and malware. Includes firewall features to control app network access. Highly customizable with multiple DNS profiles.

- **[ControlD](https://controld.com)  
  *Platforms: Android, iOS, Windows, macOS, Linux, Router*  
  Privacy-focused DNS service with customizable filtering. Ad-blocking, malware protection, parental controls, and content filtering. Supports multiple profiles and detailed analytics.

---

## 🔐 VPN Tools & Privacy

Secure your connection and protect your online identity.

- **[Proton VPN](https://protonvpn.com)  
  *Platforms: Android, iOS, Windows, macOS, Linux*  
  Privacy-first VPN with strong encryption and strict no-logs policy. Based in Switzerland with strong privacy laws. Free tier available with unlimited data. Includes Secure Core servers, DNS leak protection, and kill switch.

- **[WireGuard](https://www.wireguard.com)  
  *Platforms: Android, iOS, Windows, macOS, Linux, Router*  
  Lightweight, fast, and modern VPN protocol known for performance and simplicity. Uses state-of-the-art cryptography. Many VPN services use WireGuard as their protocol. Open-source and audited.

- **[OpenVPN](https://openvpn.net)  
  *Platforms: Android, iOS, Windows, macOS, Linux, Router*  
  Widely used open-source VPN solution for secure encrypted connections. Highly configurable and supports various encryption methods. Used by many commercial VPN services. OpenVPN Connect app available for easy setup.

- **[Mullvad VPN](https://mullvad.net)  
  *Platforms: Android, Windows, macOS, Linux*  
  Privacy-focused VPN with anonymous account system. No email required, payment via crypto/cash. Strict no-logs policy based in Sweden. WireGuard protocol. Flat pricing model, no data caps.

- **[IVPN](https://ivpn.net)  
  *Platforms: Android, iOS, Windows, macOS, Linux*  
  No-logs VPN with multi-hop connections and anti-tracking features. Based in Gibraltar with strong privacy laws. WireGuard, OpenVPN, and IKEv2 protocols. Includes anti-fingerprinting and ad-blocking features.

---

## 🔒 Firewall & Network Security

Control app network access and enhance security.

- **[NetGuard](https://netguard.me)  
  *Platforms: Android*  
  No-root firewall for blocking internet access per app. Works without root by using local VPN. Block Wi-Fi or mobile data for specific apps. Supports filtering by IP address, domain, and port. Open-source and privacy-focused.

- **[AFWall+](https://github.com/ukanth/afwall)  
  *Platforms: Android (root required)*  
  Advanced firewall for rooted Android devices. Control inbound and outbound traffic per app. Supports profiles, logging, and custom rules. Based on iptables for powerful network control.

- **[RethinkDNS + Firewall](https://rethinkdns.com)  
  *Platforms: Android, Windows, macOS, Linux*  
  Combined DNS resolver and firewall. Block trackers, ads, and malware at DNS level. Firewall features control app network access. Supports multiple profiles and detailed logging. Open-source.

- **[Blokada](https://blokada.org)  
  *Platforms: Android, iOS*  
  Ad blocker with firewall capabilities. Blocks ads across all apps without root. Includes DNS-based blocking and can block specific domains. Free and open-source version available.

---

## ⚙️ Automation & Productivity

Extra tools that improve usability and device control.

- **[Tasker](https://tasker.joaoapps.com)  
  *Platforms: Android*  
  Powerful automation tool for creating custom triggers and actions. Automate tasks based on time, location, app state, events, and more. Supports plugins for extended functionality. Can create complex workflows without programming knowledge.

- **[KDE Connect](https://kdeconnect.kde.org)  
  *Platforms: Android, Windows, macOS, Linux*  
  Sync phone and PC for file sharing, notifications, clipboard sync, and remote control. Transfer files wirelessly, reply to SMS from computer, use phone as remote input device, and find your phone. Open-source and works across platforms.

- **[Automate](https://llamalab.com/automate)  
  *Platforms: Android*  
  Automation app with flowchart-based programming. Create automated workflows using visual blocks. Supports triggers, actions, loops, conditions, and variables. Great for users who prefer visual programming over text-based scripting.

- **[MacroDroid](https://macrodroid.com)  
  *Platforms: Android*  
  Simple automation tool for Android. Create macros with triggers and actions using an easy-to-use interface. Supports location-based, time-based, and event-based automation. Good for beginners to automation.

---

## 📁 File Management

Tools for managing files and storage.

- **[Solid Explorer](https://solidexplorer.me)  
  *Platforms: Android*  
  Feature-rich file manager with cloud storage support. Supports multiple cloud services (Google Drive, Dropbox, OneDrive, etc.), FTP/SFTP, SMB, and WebDAV. Includes dual-pane view, archive support, and root access. Material Design interface.

- **[FX File Explorer](https://nextapp.com/fx)  
  *Platforms: Android*  
  File manager with root access and network browsing. Supports SMB, FTP, SFTP, WebDAV, and cloud services. Includes hex viewer, text editor, and archive extraction. Root features include system file access and app data management.

- **[Mixplorer](https://mixplorer.com)  
  *Platforms: Android*  
  File manager with archive support and cloud integration. Handles multiple archive formats (ZIP, RAR, 7z, etc.). Supports cloud services, FTP, SFTP, and SMB. Includes tabbed browsing, root access, and custom themes. Open-source.

- **[Material Files](https://zhanghai.me/materialfiles)  
  *Platforms: Android*  
  Simple, modern file manager following Material Design guidelines. Clean interface with essential features. Supports root access, cloud storage, and network locations. Open-source and lightweight.

---

## 🔧 Device Control & Customization

Tools for advanced device control and theming.

- **[QuickSwitch](https://github.com/jkuester/unlauncher)  
  *Platforms: Android TV*  
  Custom launcher for Android TV devices. Replace default launcher with a more customizable interface. Supports icon packs, custom layouts, and enhanced navigation. Great for Fire TV and Android TV boxes.

- **[Lawnchair](https://lawnchair.info)  
  *Platforms: Android*  
  Open-source launcher based on Pixel Launcher. Clean, minimal design with customization options. Supports icon packs, custom gestures, and notification dots. Lightweight and actively maintained.

- **[Nova Launcher](https://novalauncher.com)  
  *Platforms: Android*  
  Highly customizable launcher with extensive features. Custom icon packs, grid size, gestures, dock customization, and unread badges. Prime version adds more features. One of the most popular launchers.

- **[Swift Backup](https://swiftbackup.app)  
  *Platforms: Android*  
  Backup apps, data, and APKs. Schedule automatic backups, restore apps with data, and transfer backups between devices. Supports cloud storage and local backups. Works without root but enhanced with root.

- **[OAndBackupX](https://github.com/machiav3lli/oandbackupx)  
  *Platforms: Android (root required)*  
  Backup tool for rooted devices. Backup and restore apps with data, system apps, and external data. Supports batch operations, scheduling, and encryption. Fork of the original OAndBackup with modern UI.

---

## 🎮 Gaming & Performance

Tools for gaming optimization and performance monitoring.

- **[Game Turbo](https://github.com/tytydraco/GameTurbo)  
  *Platforms: Android*  
  Performance booster for gaming. Optimizes device performance for games by managing CPU/GPU frequencies, clearing background processes, and disabling battery optimizations. Supports custom profiles for different games.

- **[GFX Tool](https://gfxtool.app)  
  *Platforms: Android*  
  Graphics optimization tool for games like PUBG Mobile. Adjust resolution, FPS, graphics quality, and other graphics settings. Works by modifying game configuration files. Can improve performance on lower-end devices.

- **[Performance Monitor](https://github.com/tytydraco/PerformanceMonitor)  
  *Platforms: Android*  
  System performance monitoring tool. Displays real-time CPU, GPU, memory, and network usage. Overlay support for monitoring while gaming. Helps identify performance bottlenecks.

---

## 📊 System Monitoring

Monitor device performance and resources.

- **[CPU-Z](https://www.cpuid.com/softwares/cpu-z.html)  
  *Platforms: Android, Windows*  
  System information and hardware monitoring. Displays CPU details, GPU info, battery status, sensors, and system specs. Great for checking device specifications and monitoring hardware performance. Free and ad-free.

- **[DevCheck](https://play.google.com/store/apps/details?id=com.spirityoutube.devcheck)  
  *Platforms: Android*  
  Comprehensive device information and hardware details. Shows CPU, GPU, RAM, storage, battery, sensors, and network info. Includes dashboard with real-time monitoring. Root features for advanced system information.

- **[3C Toolbox](https://play.google.com/store/apps/details?id=ccc71.at.free)  
  *Platforms: Android*  
  System monitoring and optimization tool. CPU governor control, app manager, file manager, network monitor, and battery saver. Root features include app freezing, backup/restore, and system app management.

---

## 📌 Notes

- Apps listed here may change or update frequently
- Some features may differ depending on Android version
- Always download apps from official sources
- Root-required apps need proper setup and understanding of risks

---

<div align="center">

# 📱 Android Tools & System Utilities

**Curated collection for power users.**

</div>
