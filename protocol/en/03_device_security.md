# 📖 PART III: DEVICE SECURITY

## 7. Smartphone: Your Weakest Link

Your phone knows more about you than any other device. Your location history. Your contacts. Your messages. Your photos. Your banking apps. Your email. Your calendar.

It goes everywhere with you. It's easy to lose. Easy to steal. Easy to leave unlocked on a table.

This makes it your weakest link.

### **[CRITICAL]** Screen Lock: PIN vs Pattern vs Biometrics

An unlocked phone is an open door. Anyone who picks it up has full access to everything.

**Options for locking your screen:**

**PIN (Personal Identification Number)**
4-8 digit code you enter to unlock.

Pros: Simple, reliable, works in all conditions
Cons: Can be shoulder-surfed, shorter PINs are weak

Use at least 6 digits. Avoid obvious patterns like 123456 or your birth year.

**Pattern**
Draw a shape on a grid of dots.

Pros: Faster than typing
Cons: Leaves visible smudge marks on screen, easy to observe and copy, fewer possible combinations than long PIN

Not recommended as primary lock method.

**Biometrics (Fingerprint, Face Recognition)**
Use your fingerprint or face to unlock.

Pros: Fast, convenient, can't be forgotten
Cons: Someone can force you to unlock (hold phone to your face, press your finger while you sleep). Can't be changed if compromised. Sometimes fails in certain conditions (wet hands, different lighting, masks).

Good for daily convenience. Understand the limitations.

**Password**
Full alphanumeric password.

Pros: Strongest option
Cons: Slow to type on phone, annoying for frequent unlocking

Use for extremely sensitive situations. Overkill for most daily use.

**Recommendation:**
Biometrics for convenience + strong PIN as backup. Disable biometrics in high-risk situations (protests, border crossings, arrests).

**Settings to check:**

- Lock timeout: 30 seconds to 1 minute maximum
- Require authentication after restart (no biometrics until PIN entered)
- Hide sensitive notifications on lock screen

### **[CRITICAL]** Device Encryption

Encryption scrambles all data on your phone. Without your PIN/password, the data is unreadable.

Modern phones encrypt by default when you set a lock screen. But verify.

**How to check if encryption is enabled:**

Most devices show this in Settings → Security → Encryption or Settings → Privacy → Encryption.

If your phone supports encryption and it's not enabled: enable it now. The process takes 30-60 minutes and requires your phone to be charging.

Encryption only works if you have a strong lock screen. Weak PIN = weak encryption.

### **[CRITICAL]** Remote Wipe

If your phone is lost or stolen, you can erase everything remotely.

**Requirements:**

- Remote wipe feature enabled in settings
- Phone connected to internet
- You remember your account credentials

**How remote wipe works:**

You log into your account from another device (computer, friend's phone). You locate your phone on a map. You can:

- Make it ring (if you lost it nearby)
- Lock it with a message ("Call this number to return")
- Erase all data

Once erased, data is gone forever. Make sure you have backups.

**When to use remote wipe:**

- Phone stolen and you're certain you won't recover it
- Phone lost in public place and contains sensitive data
- Phone confiscated and you need to protect data

**When NOT to use remote wipe:**

- You just misplaced it at home
- There's a chance you'll find it soon
- You don't have recent backup

Enable this feature now. You can't enable it remotely after you've lost the phone.

### App Hygiene: What You Install and What Permissions It Has

Every app you install is a potential security risk.

**Before installing any app:**

Ask yourself:

- Do I actually need this?
- Is it from a trustworthy source?
- What permissions will it request?
- Are there alternatives with better privacy?

**Download only from official app stores.**  Sideloading apps from random websites is how phones get infected.

Even official app stores contain malicious apps. Check:

- Developer name (is it legitimate?)
- Number of downloads (millions vs hundreds)
- Reviews (look for complaints about permissions, ads, suspicious behavior)
- Age of app (brand new apps are riskier)

**App Permissions**

Apps request access to:

- Camera
- Microphone
- Location
- Contacts
- Photos
- Storage
- Notifications

Many apps request more than they need.

A flashlight app doesn't need your location. A game doesn't need your contacts. A calculator doesn't need your camera.

**Review and restrict permissions:**

Go to Settings → Apps → Permissions (or similar).

For each app, check what it can access. Revoke anything unnecessary.

For location: Choose "Only while using app" instead of "Always." Most apps don't need background location tracking.

**Uninstall apps you don't use.**  Every app is a potential vulnerability and privacy leak. Less is more.

### Public WiFi: Threats and Protection

Public networks at cafes, airports, hotels, libraries are convenient but dangerous.

**Risks:**

- Anyone on the same network can intercept your traffic
- Fake networks with similar names ("Free Airport WiFi" vs "Free_Airport_WiFi")
- Network owner can see all unencrypted traffic
- Malicious actors can inject malware or redirect you to fake websites

**Protection:**

**Use encrypted connections only.**  Look for HTTPS (padlock icon) in browser. Never enter passwords or sensitive data on non-HTTPS sites.

**Avoid sensitive activities on public WiFi.** No online banking. No password changes. No accessing medical records. Wait until you're on trusted network or use cellular data.

**Use a VPN** if you must do sensitive work on public WiFi. VPN encrypts all traffic between your device and VPN server, protecting you from local network snooping.

**Disable auto-connect to WiFi networks.** Your phone shouldn't automatically join any available network. You choose when to connect.

**Forget networks after use.** Don't save public networks. Reconnect manually next time.

**Turn off file sharing and AirDrop** when on public networks.

### Common Mistakes

**Using simple 4-digit PIN like 1234 or birth year**
Takes seconds to guess. Use 6+ digits, non-obvious.

**Never restarting phone**
Restart weekly. Clears memory, closes background processes, can stop certain malware.

**Ignoring system updates**
Updates patch security holes. Delaying updates leaves you vulnerable.

**Installing every app friends recommend without checking**
Apps can be malicious or poorly secured. Research first.

**Leaving Bluetooth and WiFi on all the time**
When not needed, turn them off. Reduces tracking and attack surface.

**Not having screen lock because "it's annoying"**
You will lose your phone eventually. Theft, accident, forgetfulness. Unlocked phone = total compromise.

### Quick Wins

- **2 minutes:** Set a 6-digit PIN if you don't have one.
- **5 minutes:** Enable remote wipe feature.
- **10 minutes:** Review app permissions, revoke unnecessary access.
- **15 minutes:** Uninstall apps you haven't used in 6 months.

## 8. Computer: Data Fortress

Your computer stores your work, your memories, your finances, your communications. Protecting it is non-negotiable.

### **[CRITICAL]** Disk Encryption

Full disk encryption protects all data on your hard drive. If someone steals your laptop or pulls out your hard drive, they cannot read your files without your password.

**Modern operating systems include encryption:**

Encryption is only active if enabled and if you use a strong password to log in. Weak password = weak encryption.

**How to enable:**

The process varies by operating system, but generally found in Settings → Security → Encryption.

Enabling encryption can take hours depending on disk size. Start it before bed, let it run overnight.

**Important:** Write down your recovery key. If you forget your password and lose the recovery key, your data is permanently inaccessible.

Store recovery key in safe place (physical safe, safety deposit box, with trusted family member).

### **[CRITICAL]** User Accounts: Administrator vs Standard vs Guest

Operating systems have different account types with different permission levels.

**Administrator**
Full control over system. Can install software, change settings, access all files.

**Standard User**
Can use installed programs, change own settings, access own files. Cannot install software or change system settings without admin password.

**Guest**
Temporary account with minimal permissions. No password required. No access to other users' files.

**Best practice:**

Create two accounts:

1. Administrator account for system maintenance (strong password, rarely used)
2. Standard account for daily use

Use standard account for browsing, email, normal work. Only switch to admin account when you need to install software or change system settings.

Why: If malware infects your account or you accidentally run malicious software, it has limited ability to damage the system from a standard account. Admin accounts have full system access.

**Guest account** for when others need to borrow your computer. They can browse and work temporarily without accessing your files. Session erased when they log out.

### **[RECOMMENDED]** Updates: Why You Can't Ignore Them

Software updates fix security vulnerabilities.

Attackers constantly search for weaknesses in operating systems and programs. When they find one, they exploit it. Developers release updates to patch these holes.

Old, unpatched software is low-hanging fruit for attackers.

**What to update:**

- Operating system (weekly or as released)
- Browsers (set to auto-update)
- Security software
- Any program that connects to internet

**Enable automatic updates** for operating system and browser. Manual updates for other software (check monthly).

**"But updates break things"**
Sometimes, yes. Rarely. Much rarer than being compromised through unpatched vulnerability.

Delay major updates for a few days if you want others to test first. But don't delay months.

### Antivirus: When It's Needed and When It's Not

**Built-in protection is usually sufficient for most users.**

Modern operating systems include decent anti-malware protection that runs automatically in the background.

**You need additional antivirus if:**

- You frequently download files from untrusted sources
- You visit high-risk websites
- You're a high-value target (journalist, activist, executive)
- You're required by work policy

**You probably don't need additional antivirus if:**

- You practice good security hygiene (don't click suspicious links, download from official sources only, keep system updated)
- You use standard operating system on standard hardware

**If you choose third-party antivirus:**

- Research before installing (some antivirus software is itself invasive or poorly designed)
- Stick to established, reputable options
- Don't install multiple antivirus programs (they conflict)

**What antivirus cannot do:**

- Protect you from phishing if you willingly enter your password on a fake site
- Protect you from social engineering
- Compensate for weak passwords or disabled updates

Antivirus is one layer. Not a replacement for good habits.

### **[RECOMMENDED]** Shared and Family Devices

Not everyone has their own personal device. Family computers, shared tablets, library/cafe computers are common realities.

**Securing shared devices:**

**Use separate user accounts:**

- Create individual user accounts for each person
- Each account has its own password
- Files and settings stay separate
- No one sees others' browsing history or documents

**On Windows/Mac/Linux:** Settings → Users → Add User

**On Android tablets:** Settings → Users/Multiple Users → Add User

**Guest mode for temporary use:**

- Most operating systems offer Guest Mode
- Temporary session with no saved data
- Everything deleted when guest logs out
- Use this for visitors, or when using someone else's device

**What NOT to do on shared devices:**

**Never save passwords in browser:**

- Anyone using that account can access your accounts
- Always log out when finished
- Use private/incognito mode if available

**Don't save sensitive files:**

- Others might access them accidentally or intentionally
- Use cloud storage with strong password instead
- Or use encrypted USB drive you keep with you

**Assume nothing is private:**

- Other users might see your files
- IT admins (at work/school/library) can see everything
- Browsing history might be monitored

**Public/cafe computers - extreme caution:**

- Assume keyloggers might be installed
- Never access banking or sensitive accounts
- Use incognito/private mode
- Log out of everything
- Clear browser data when done
- Consider the computer compromised

**For parents sharing devices with children:**

- Create child account with parental controls
- Limit what apps they can install
- Set screen time limits at OS level
- Keep your account password-protected

**If you must share one account:**

- Establish rules about privacy (don't read others' messages)
- Use separate browser profiles (Chrome/Firefox support this)
- Clear browsing data regularly
- Encrypt sensitive files individually

**Remember:** Full privacy is impossible on shared devices. Adjust your behavior accordingly.

### Secure Shutdown and Sleep

**Shutdown** completely turns off computer. All RAM cleared. Disk encryption active (data protected).

**Sleep/Standby** keeps computer in low-power state. RAM contents preserved. Faster to resume.

**Hibernate** saves RAM contents to disk and powers off. Slower to resume than sleep, faster than full boot.

**Security implications:**

Encrypted disk protects data when computer is completely off. When computer is sleeping or hibernating, encryption keys may remain in memory. Physical access could potentially extract them.

**Best practice:**

- Shut down completely if you'll be away for extended time or traveling
- Require password on wake from sleep
- Don't leave laptop unattended in sleep mode in untrusted environments (cafes, hotels, offices with many people)

**Automatic lock after inactivity:** Set screen to lock after 5 minutes of inactivity. Require password to unlock.

### Common Mistakes

**Using the same password for computer login and online accounts**
If your computer password is compromised (someone watches you type, malware, etc.), all your accounts are compromised if you reuse it.

**Never backing up before major updates**
Updates rarely cause problems, but when they do, you want a backup. We'll cover backups in Part IV.

**Disabling security features because they're annoying**
User Account Control prompts, firewall warnings, update notifications exist for a reason. Don't disable them to avoid annoyance.

**Sharing admin account with family members or coworkers**
Everyone should have their own account. Standard accounts for most people. Admin privileges only when necessary.

**Leaving computer logged in when stepping away**
Lock your screen. Every time. Even at home. It's a habit that protects you everywhere.

### Quick Wins

- **5 minutes:** Enable full disk encryption if not already enabled.
- **10 minutes:** Create a standard user account for daily use.
- **5 minutes:** Enable automatic updates for OS and browser.
- **2 minutes:** Set screen to lock after 5 minutes of inactivity.

## 9. Home Network: The Invisible Guardian

Your home network connects all your devices to the internet. If it's compromised, everything connected to it is at risk.

Most people never think about their router after initial setup. This is a mistake.

### **[CRITICAL]** Securing Your Router: Changing Password and Network Name

Your router has two passwords:

**1. WiFi password** (what devices use to connect to your network)
**2. Admin password** (what you use to access router settings)

Both must be strong and unique.

**WiFi Password**

Default WiFi passwords are often weak or printed on a sticker on the router. Change it.

Requirements:

- At least 16 characters
- Mix of letters, numbers, symbols
- Not a dictionary word or personal information

You'll type this less often than other passwords (devices remember it). Make it strong.

**Admin Password**

This is the password you use to log into router settings (usually through a web browser at an address like 192.168.1.1).

Default admin passwords are often "admin" or "password" or printed in the manual. Attackers know these.

Change it immediately.

If someone accesses your router admin panel, they can:

- See all devices on your network
- Redirect your traffic to malicious sites
- Change DNS settings
- Install malicious firmware
- Steal data

**Network Name (SSID)**

Default network names often reveal router brand and model (e.g., "NETGEAR-5G-A7B3"). This tells attackers exactly what router you have and what vulnerabilities to target.

Change network name to something generic that doesn't identify you or your router.

Avoid:

- Your name or address
- Router brand/model
- Anything offensive (neighbors will see it)

Fine:

- Random words
- Generic names
- Non-identifying terms

### **[CRITICAL]** WPA3 vs WPA2: Encryption Standards

WiFi encryption protects data transmitted over your network.

**Encryption standards:**

**WPA3** – Newest, strongest. Use if your router and all devices support it.

**WPA2** – Older but still secure. Minimum acceptable standard. Use if WPA3 not available.

**WEP** – Ancient, completely broken. Never use.

**Open/No encryption** – All traffic visible to anyone in range. Never use for home network.

**How to check and change:**

Log into router admin panel. Look for Wireless Security or WiFi Settings. Select WPA3 if available. If not, select WPA2.

Some routers offer "WPA2/WPA3 mixed mode" to support both old and new devices. This is acceptable.

If your router only supports WEP or is very old, replace it. Old routers have unpatched vulnerabilities.

### **[RECOMMENDED]** Guest Network: Why Not Let Everyone Into the Main One

A guest network is a separate WiFi network that shares your internet connection but isolates guest devices from your main network.

**Why this matters:**

When a friend, contractor, or visitor connects to your main network, their device can potentially:

- See other devices on your network
- Access shared folders and printers
- Spread malware to your devices
- Snoop on network traffic

Guest network prevents this. Guest devices can access internet but cannot see or interact with your main network devices.

**Enable guest network in router settings.**  Give it a different password from your main network.

Use guest network for:

- Visitors
- IoT devices (we'll cover this in next chapter)
- Devices you don't fully trust

### DNS: What It Is and How to Choose a Safer One

DNS (Domain Name System) translates website names into computer addresses.

When you type a website address, your device asks a DNS server "what's the address for this site?" DNS server responds, and your device connects.

**Your DNS provider can see every website you visit.**

By default, you use your internet provider's DNS. They can:

- Log all websites you visit
- Sell your browsing history
- Inject ads
- Redirect mistyped addresses to their own search pages
- Be compelled by government to block or monitor sites

**You can change to a different DNS provider.**

Options include privacy-focused DNS services that:

- Don't log your queries
- Support encrypted DNS
- Block malware and phishing sites
- Are faster than ISP DNS

**How to change DNS:**

Change it at router level (affects all devices on network) or per-device.

Router: Admin panel → WAN/Internet settings → DNS servers → Enter custom DNS addresses

Per-device: Network settings → DNS → Manual → Enter custom DNS addresses

Benefits:

- Better privacy (DNS provider doesn't log or sell your data)
- Better security (malware/phishing blocking)
- Sometimes faster
- Bypass ISP restrictions

### How to Check Who's Connected to Your WiFi

Unknown devices on your network could be:

- Neighbors stealing WiFi
- Attacker within range
- Forgotten devices you no longer use

**Check connected devices:**

Log into router admin panel. Look for "Connected Devices," "Device List," or "DHCP Clients."

You'll see:

- Device name (often generic like "iPhone" or "android-abc123")
- MAC address (unique hardware identifier)
- IP address
- Connection time

**Identify each device.**  Compare list to devices you own. Unknown device = problem.

**If you find unknown devices:**

1. Change WiFi password immediately
2. Change router admin password
3. Disconnect unknown devices (router interface usually has disconnect/block option)
4. Verify WPA2/WPA3 encryption is enabled
5. Check router firmware is updated

**Prevent unauthorized access:**

- Strong WiFi password
- WPA2/WPA3 encryption
- Disable WPS (WiFi Protected Setup) – convenient but insecure
- Regularly check connected devices

### Common Mistakes

**Never changing default router passwords**
Default passwords are public knowledge. Change them.

**Using same password for WiFi and router admin**
If WiFi password leaks, attacker shouldn't also get admin access. Keep them different.

**Disabling firewall on router**
Router firewall is your first line of defense. Leave it enabled.

**Enabling remote administration without strong security**
Some routers allow you to access settings from internet. Unless you absolutely need this and secure it properly, disable it.

**Never updating router firmware**
Routers receive security updates too. Check manufacturer website or router admin panel for firmware updates quarterly.

### Quick Wins

- **5 minutes:** Change router admin password from default.
- **10 minutes:** Change WiFi password to strong unique password.
- **5 minutes:** Verify WPA2 or WPA3 encryption is enabled.
- **10 minutes:** Enable guest network.
- **5 minutes:** Check list of connected devices, identify unknowns.

## 10. IoT Devices: Smart Home, Dumb User?

Internet of Things (IoT) devices are everywhere. Smart TVs. Voice assistants. Smart speakers. Security cameras. Video doorbells. Smart locks. Thermostats. Light bulbs. Fitness trackers. Baby monitors. Kitchen appliances.

They promise convenience. They deliver surveillance.

### The Problem with Smart Devices

Most IoT devices:

- Collect far more data than necessary
- Have poor security
- Rarely receive updates
- Send data to manufacturer servers constantly
- Have opaque privacy policies
- Can be hacked to spy on you or join botnets

**You bring these devices into your home, and they watch, listen, and report.**

### Smart TVs and Streaming Devices

Modern TVs track:

- What you watch
- When you watch
- How long you watch
- Apps you use
- Sometimes even what's displayed on screen via automatic content recognition

This data is sold to advertisers.

**Mitigation:**

**Don't connect TV to internet** if you don't need smart features. Use external streaming device instead, which you have more control over.

**Disable automatic content recognition** in TV settings (often buried under Privacy or Viewing Data).

**Disable personalized ads** in TV settings.

**Cover or disable built-in cameras and microphones** if present and not used.

**Create a separate network for TV** (guest network) so it can't see other devices.

### Voice Assistants

Smart speakers and voice assistants are always listening for wake word. This means they're processing audio constantly.

Manufacturers claim they only record after wake word. Data breaches and reports have shown:

- Accidental activations happen constantly
- Recordings are sometimes reviewed by human employees
- Data is stored longer than claimed
- Recordings have been subpoenaed in criminal cases

**If you use voice assistants:**

**Mute microphone** when not in use (most have physical mute button).

**Disable recording storage** in privacy settings or regularly delete voice history.

**Don't place in private rooms** (bedroom, bathroom, home office where sensitive conversations happen).

**Review what's been recorded** periodically. Delete recordings.

**Use only for non-sensitive tasks** (timers, weather, music). Not for shopping, banking, anything private.

**Consider if you actually need it.**  Convenience vs privacy tradeoff.

### Security Cameras and Doorbells

Cameras in and around your home can enhance security. They can also:

- Be hacked to spy on you
- Leak video to internet
- Be accessed by employees of camera company
- Be subpoenaed by law enforcement
- Have weak passwords allowing unauthorized access

**If you use security cameras:**

**Change default passwords immediately.**  Camera default passwords are publicly listed.

**Disable remote access** unless absolutely necessary. Local-only viewing is more secure.

**Check if video is stored locally or in cloud.**  Cloud storage means company has access. Local storage (SD card, NAS) is more private but less convenient.

**Point cameras outward, not inward.**  Monitor entrances, not living spaces.

**Disable audio** if you only need video.

**Check for firmware updates** regularly. Cameras are common targets for hackers.

**Use cameras from reputable manufacturers** with track record of security updates, not random cheap brands.

### Smart Locks and Doorbells

Physical security devices connected to internet create risk.

**Concerns:**

- Remote unlock by unauthorized party if hacked
- Lock history logged and accessible to manufacturer
- Relies on internet/power—what happens during outage?
- Potential for lockout if software fails

**If you use smart locks:**

**Keep traditional key backup.**  Don't depend entirely on electronic lock.

**Use locks from established companies** with security track record.

**Enable all available security features** (two-factor for app, encryption, tamper alerts).

**Regularly review access logs** for unauthorized attempts.

**Update firmware** when available.

**Consider if convenience is worth risk.** Traditional locks are less convenient but have no electronic attack surface.

### How to Limit Tracking and Data Leaks

**General principles for all IoT devices:**

**Don't buy devices you don't need.** Every device is a potential vulnerability and privacy leak.

**Research before buying.** Look for:

- Privacy policy (do they sell data?)
- Security track record (history of breaches?)
- Update policy (do they release security patches?)
- Reviews mentioning privacy/security concerns

**Change all default passwords immediately.**

**Disable features you don't use** (remote access, cloud storage, voice control, location tracking).

**Isolate IoT devices on separate network** (guest network or dedicated IoT network). Prevents compromised device from accessing your computers and phones.

**Check privacy settings** on device and associated app. Disable data sharing, personalized ads, cloud analysis.

**Regularly update firmware.**  Set reminders to check quarterly if auto-update not available.

**Don't link to sensitive accounts.**  Don't connect IoT devices to email or accounts that control banking, health, etc.

**Unplug or disable when not needed.** Camera you only use when traveling? Unplug it when home.

### Separate Network for IoT [ADVANCED]

For almost everyone, a **guest network is enough**. It gives you the main benefit (isolation) with minimal complexity.

**Recommended default: Guest network (simple):**
Enable guest network on your router and connect all IoT devices to it. They can access the internet but can't see your main devices.

**Optional (for network enthusiasts): VLANs:**
If your router already supports VLANs and you know how to configure them, you can build a dedicated “IoT” network with stricter firewall rules. If that sentence felt like homework, skip VLANs—guest network is fine.

**Why separate:**

- Compromised IoT device can't access your computers/phones
- You can apply stricter firewall rules to IoT network
- Easier to monitor and control IoT traffic
- If IoT device is hacked and joins botnet, your personal devices unaffected

### Common Mistakes

**Buying cheap devices from unknown brands**
Often have horrible security, no updates, leak data to random servers.

**Never changing default passwords**
Thousands of IoT devices get hacked daily because users never changed "admin/admin."

**Giving devices more permissions than needed**
Light bulb app doesn't need your location. Thermostat doesn't need access to contacts.

**Trusting privacy policies**
"We respect your privacy" means nothing if the policy says "we share data with partners and third parties."

**Not updating or not knowing how to update**
Many IoT devices have no automatic updates. You must manually check. Most people never do.

### Quick Wins

- **5 minutes:** Inventory all IoT devices in your home.
- **15 minutes:** Change default passwords on all IoT devices.
- **10 minutes:** Disable unused features (remote access, cloud storage, voice).
- **20 minutes:** Move all IoT devices to guest network.
- **10 minutes:** Review and delete voice assistant recordings.

## 11. Old Hardware: How to Say Goodbye Safely

You upgrade your phone. You replace your laptop. You throw away an old tablet.

What happens to the data?

Most people assume deleting files or factory reset erases everything. It doesn't.

Data remains on the drive, recoverable with simple tools. Your photos. Your documents. Your browsing history. Your saved passwords. Your emails.

Selling, donating, or throwing away devices without proper data destruction is handing your digital life to strangers.

### **[CRITICAL]** Complete Disk Wipe Before Selling or Disposing

**Deleting files doesn't delete them.** It marks the space as available but data remains until overwritten.

**Factory reset can be sufficient on modern encrypted phones**, but don’t assume it always is. What matters is whether the device was encrypted and whether the reset actually destroys the encryption keys.

**Goal:** make old data unrecoverable before you sell, donate, or dispose of a device.

**For computers:**

Use a disk wipe / secure erase method for the entire drive. One pass is sufficient for most purposes (multiple passes are overkill for modern drives).

Methods vary by operating system. Tools exist specifically for this purpose.

**For phones and tablets:**

**Modern encrypted devices (typical):** A factory reset is usually sufficient because it destroys encryption keys, making old data unreadable.

**Older or unencrypted devices:** Don’t rely on factory reset alone. Use a secure erase option if available, or encrypt first and then reset.

**For external drives and USB sticks:**

Same as computers—use secure erase tool to overwrite entire drive.

**For SSDs (Solid State Drives):**

SSDs have built-in "Secure Erase" command that cryptographically erases data. Use this instead of overwriting tools. Check manufacturer instructions.

### Tools for Permanent Data Deletion

**File shredders** (for individual files):
Overwrite specific files multiple times before deletion. Use when you want to delete specific sensitive files but keep using device.

Examples: Eraser (Windows), File Shredder (Windows), Permanent Eraser (Mac), shred command (Linux)

**Disk wipe utilities** (for entire drives):
Overwrite entire drive. Use before selling/disposing device.

Examples:

- **DBAN (Darik's Boot and Nuke)** - Free, bootable, wipes entire hard drives
- **Eraser** - Windows, can wipe entire drives or free space
- **Disk Utility** - Mac built-in; use it to erase drives (features vary by macOS version)
- **dd or shred** - Linux command-line tools
- See [Appendix A: Tools](a_tools_essential_list.md) for current recommendations

**Built-in options:**
Many operating systems include secure erase options in disk utility or settings.

**For very high security:**
Physical destruction. Drill holes through drive platters (for hard drives) or crush chips (for SSDs/phones). Only necessary for extremely sensitive data.

### What to Do With a Broken Screen Phone

Broken screen doesn't mean data is safe. Phone still works; you just can't see the display.

**If phone still turns on:**

Connect to computer. If you've previously authorized that computer, you can access files and back up data.

Use remote wipe feature to erase device before disposing.

**If you can't access phone:**

Some repair shops can connect to external display to allow access for backup/wipe.

If phone was encrypted and you can't access it, data is relatively safe. But if possible, physically destroy the storage chip before disposal.

**Don't just throw broken phone in trash.** Data may still be accessible.

### Recycling: Where to Dispose of Electronics Safely

Electronics contain hazardous materials. Don't throw them in regular trash.

**Options:**

**Manufacturer take-back programs:**
Many electronics manufacturers have recycling programs. Mail old device to them or drop off at store.

**Retailer programs:**
Electronics stores often accept old devices for recycling.

**Municipal e-waste collection:**
Many cities have designated e-waste drop-off locations or collection days.

**Certified e-waste recyclers:**
Look for recyclers certified to handle data destruction and environmental disposal.

**Before recycling:**

1. Back up any data you want to keep
2. Securely wipe device
3. Remove SIM cards and memory cards
4. Remove any accounts (log out of cloud accounts, remove device from account lists)

**What not to do:**

- Don't throw electronics in regular trash
- Don't leave devices in recycling bin without wiping
- Don't abandon old devices in drawer forever (batteries degrade and can swell/leak)

### Common Mistakes

**Thinking "delete all" is enough**
Deleted files are recoverable. Use proper wipe tools.

**Selling laptop without removing accounts**
Even if you wipe drive, if laptop is still linked to your cloud account, buyer might see your files sync down when they log in.

**Forgetting about external drives and USB sticks**
That USB stick you're throwing away has years of documents on it. Wipe it first.

**Not backing up before wiping**
Once you wipe, data is gone. Make sure you have backups of anything important.

**Giving away device with "just factory reset"**
Factory reset is better than nothing but not sufficient for sensitive data.

**Leaving SIM card in old phone**
Remove SIM card before selling or disposing. It can contain contacts and messages.

### Quick Wins

- **10 minutes:** Locate all old devices you no longer use (old phones, laptops, tablets, drives).
- **30 minutes:** Back up any data you want to keep from old devices.
- **Variable time:** Securely wipe one old device and recycle it.
- **5 minutes:** Remove SIM cards and memory cards from old devices.

_Security is a journey, not a destination. Each device you secure makes your entire digital life more resilient._

---

[← Back to Protocol Zero README](README.md)
