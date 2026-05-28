# Appendix A: Tools – Essential List

**Note:** This appendix contains specific tool recommendations current as of December 2025. 

**⚠️ Tools change constantly.** Companies evolve, new options emerge, security situations shift. This list is updated quarterly, but you should always:
- Research current reputation before choosing any tool
- Check recent security audits and incidents
- Verify the tool still exists and is actively maintained
- See the latest version in this repository (protocol/en/a_tools_essential_list.md) or in Releases for offline copies

**Inclusion here is not endorsement**—evaluate based on your needs, threat model, and jurisdiction. Principles matter more than specific tools.


## Password Managers

**Cloud-Based (Recommended for Most Users):**

**Bitwarden**
- Type: Open source, cloud-synced
- Pricing: Free tier (excellent), Premium $10/year, Family $40/year
- Platforms: Windows, Mac, Linux, iOS, Android, browser extensions
- Key features: E2E encryption, 2FA support, password generator, secure notes, emergency access
- Best for: Most users, privacy-conscious, budget-conscious

**1Password**
- Type: Commercial, cloud-synced
- Pricing:  Personal $36/year, Family $60/year
- Platforms: All major platforms
- Key features: Travel mode, Watchtower (breach monitoring), family sharing, polished UI
- Best for: Families, users who value UX, those wanting premium support

**Dashlane**
- Type:  Commercial, cloud-synced
- Pricing: Premium $60/year, Family $90/year
- Platforms: All major platforms
- Key features: VPN included, dark web monitoring, password health reports
- Best for: Users wanting all-in-one security suite

**LastPass**
- Type: Commercial, cloud-synced (freemium)
- Pricing: Free (limited), Premium $36/year
- Note: Multiple serious security breaches (2015, 2021, 2022 - master passwords exposed in latest incident). Many security experts no longer recommend. Evaluate alternatives (Bitwarden, 1Password) before choosing.
- Best for: Previously popular but evaluate alternatives first

**Local/Self-Hosted:**

**KeePassXC**
- Type: Open source, local database
- Pricing: Free
- Platforms: Windows, Mac, Linux
- Key features: Complete control, no cloud dependency, highly secure
- Best for: Advanced users, those requiring air-gapped security, self-hosters

**KeePass** (original)
- Type: Open source, local database
- Pricing: Free
- Platforms: Windows (unofficial ports for others)
- Note: Interface dated but highly trusted in security community

**Built-In (Basic):**

**Apple Keychain**
- Platforms: iOS, macOS
- Pricing: Free
- Best for: Apple ecosystem users, basic needs, convenience over features

**Google Password Manager**
- Platforms: Chrome, Android
- Pricing: Free
- Best for: Google ecosystem users, basic needs
- Note: Privacy concerns due to Google's advertising business model


## Two-Factor Authentication (2FA)

**Authenticator Apps:**

**Authy**
- Type:  TOTP authenticator with cloud backup
- Pricing: Free
- Platforms: iOS, Android, Windows, Mac, Chrome
- Key features: Multi-device sync, encrypted backups, desktop apps
- Best for: Users wanting cloud backup of 2FA codes

**Google Authenticator**
- Type: TOTP authenticator with optional cloud backup
- Pricing: Free
- Platforms: iOS, Android
- Key features: Simple, cloud sync added in 2023 (can be disabled)
- Best for: General users

**Microsoft Authenticator**
- Type:  TOTP authenticator with push notifications
- Pricing: Free
- Platforms: iOS, Android
- Key features: Cloud backup, passwordless sign-in for Microsoft accounts
- Best for: Microsoft ecosystem users

**Bitwarden Authenticator** (Premium feature)
- Integrated into Bitwarden password manager
- Best for:  Consolidation (though some argue 2FA and passwords shouldn't be in same place)

**Aegis Authenticator**
- Type: Open source, local
- Pricing: Free
- Platforms: Android
- Key features: Encrypted backups, no cloud, highly customizable
- Best for: Privacy-focused Android users

**Raivo OTP**
- Note: Acquired in 2023 by an untrusted company. Many security experts advise against using it. Evaluate alternatives (like Ente Auth or Aegis) before choosing.
- Best for: Previously popular but evaluate alternatives first

**Hardware Keys:**

**YubiKey** (Yubico)
- Type: Physical 2FA device (USB, NFC, Lightning)
- Pricing: $25-$90 depending on model
- Standards: FIDO2, U2F, OTP, PIV, OpenPGP
- Best for: High-security needs, phishing resistance, professionals

**Titan Security Key** (Google)
- Type: Physical 2FA device
- Pricing: ~$30-50
- Standards: FIDO
- Best for: Google ecosystem, budget hardware key

**OnlyKey**
- Type: Hardware password manager + 2FA
- Pricing: ~$50
- Key features: Stores passwords and 2FA, PIN-protected
- Best for: Advanced users wanting hardware password storage


## Backup Solutions

**Cloud Backup:**

**Backblaze**
- Type:  Unlimited cloud backup
- Pricing: $9/month or $99/year per computer
- Platforms: Windows, Mac
- Key features: Unlimited storage, continuous backup, 30-day version history
- Best for: Set-it-and-forget-it backup, large data volumes

**IDrive**
- Type: Cloud backup with versioning
- Pricing: ~$80/year for 5TB
- Platforms: Windows, Mac, Linux, iOS, Android
- Key features:  Multiple devices, 30 versions, disk image backup
- Best for: Multiple devices, families

**Cloud Storage (with sync, not pure backup):**

**Google Drive**
- Pricing: 15GB free, 100GB $2/month, 2TB $10/month
- Platforms: All
- Best for: Google ecosystem users
- Note: Privacy considerations (Google scans content)

**iCloud**
- Pricing: 5GB free, 50GB $1/month, 200GB $3/month, 2TB $10/month
- Platforms: Apple devices, Windows (limited)
- Best for: Apple ecosystem
- Note: Proprietary, limited outside Apple devices

**Dropbox**
- Pricing: 2GB free, Plus 2TB $12/month, Family 2TB $20/month
- Platforms: All
- Best for: File sharing, collaboration
- Note: More expensive than competitors

**Microsoft OneDrive**
- Pricing: 5GB free, 100GB $2/month, bundled with Microsoft 365
- Platforms: All
- Best for: Microsoft ecosystem, Office users

**Privacy-Focused Cloud Storage:**

**ProtonDrive**
- Type: Encrypted cloud storage
- Pricing: Free tier, paid plans from $4/month
- Key features: End-to-end encryption, zero-access encryption
- Best for: Privacy-conscious users, Proton ecosystem

**Sync.com**
- Type: Encrypted cloud storage
- Pricing:  5GB free, 2TB $8/month
- Key features: Zero-knowledge encryption
- Best for: Privacy + convenience balance

**Tresorit**
- Type: Encrypted cloud storage
- Pricing: Premium ~$12/month
- Key features: Swiss jurisdiction, E2E encryption, business-grade
- Best for: Professionals, high privacy requirements

**Local Backup:**

**External Hard Drives:**
- Brands: Western Digital, Seagate, Samsung, Crucial (SSD)
- Capacity: 1TB-5TB typical for personal use
- Type: HDD (cheaper, larger) vs SSD (faster, more durable, expensive)
- Best for: Local backup, 3-2-1 rule compliance

**NAS (Network Attached Storage):**
- Brands: Synology, QNAP, Western Digital, Asustor
- Best for: Tech-savvy users, families, automatic local backup, home media servers
- Complexity: Requires setup and maintenance

**Backup Software (Local):**

**Time Machine** (macOS)
- Built-in, free, automatic
- Best for: Mac users

**Windows Backup** (Windows)
- Built-in, free
- Best for: Windows users, basic needs

**Acronis True Image**
- Type: Commercial backup software
- Pricing: ~$50/year
- Features: Disk imaging, cloud backup, ransomware protection
- Best for:  Complete system backup, disaster recovery

**Duplicati**
- Type: Open source backup
- Pricing: Free
- Platforms: Windows, Mac, Linux
- Features: Encrypted, incremental, supports many cloud destinations
- Best for: Advanced users, customization needs


## Security Software

**Antivirus/Anti-Malware:**

**Built-In Protection:**

**Windows Defender** (Windows)
- Free, built-in
- Quality: Good for most users as of recent years
- Best for: Most Windows users

**XProtect** (macOS)
- Free, built-in
- Best for: Most Mac users

**Third-Party Antivirus:**

**Malwarebytes**
- Pricing: Free (scanner), Premium $45/year
- Platforms: Windows, Mac, Android
- Best for:  Malware removal, supplement to built-in protection

**Bitdefender**
- Pricing:  ~$40-90/year depending on tier
- Platforms: Windows, Mac, iOS, Android
- Best for:  Comprehensive protection, low system impact

**ESET**
- Pricing:  ~$40-60/year
- Platforms: Windows, Mac, Linux, Android
- Best for: Low system impact, advanced users

**Kaspersky**
- Note: Geopolitical concerns regarding Russian jurisdiction; research current status
- Previously highly regarded technically

**Norton, McAfee**
- Note: Often bundled with new computers, historically resource-heavy
- Evaluate alternatives first

**VPN Services:**

**Privacy-Focused VPNs:**

**Mullvad VPN**
- Pricing: €5/month, no subscriptions
- Jurisdiction: Sweden
- Key features: No account creation (anonymous), accepts cash/crypto, open source clients
- Best for: Maximum privacy, anonymity-focused

**ProtonVPN**
- Pricing: Free tier (limited), Plus $10/month
- Jurisdiction: Switzerland
- Key features: No-logs, Secure Core, NetShield (ad blocking), from Proton team
- Best for: Privacy-conscious, Proton ecosystem

**IVPN**
- Pricing: ~$6-10/month
- Jurisdiction: Gibraltar
- Key features: No logs, minimal data collection, transparent
- Best for: Privacy purists

**General Use VPNs:**

**NordVPN**
- Pricing: ~$4-12/month depending on term
- Key features: Large server network, good speeds, extra features
- Best for: General use, streaming

**ExpressVPN**
- Pricing: ~$7-13/month
- Key features: Fast, reliable, good support
- Best for: Non-technical users, streaming, ease of use

**Note on Free VPNs:**
- Almost always bad for privacy
- Free VPNs make money by selling your data, injecting ads, or worse
- Exceptions: Free tiers from reputable paid services (ProtonVPN, Windscribe limited free)

**Encryption Tools:**

**Cryptomator**
- Type: Client-side encryption for cloud storage
- Pricing: Free (donations appreciated), iOS/Android apps ~$10 one-time
- Platforms: Windows, Mac, Linux, iOS, Android
- Best for:  Encrypting files before uploading to cloud

**VeraCrypt**
- Type:  Disk encryption software
- Pricing: Free, open source
- Platforms: Windows, Mac, Linux
- Best for:  Encrypted containers, full disk encryption (advanced users)

**BitLocker** (Windows Pro)
- Built-in full disk encryption
- Best for: Windows Pro/Enterprise users

**FileVault** (macOS)
- Built-in full disk encryption
- Best for: Mac users


## Communication

**Messaging Apps (E2E Encrypted):**

**Signal**
- Type: Open source, E2E encrypted messenger
- Pricing: Free (donation-funded)
- Platforms: iOS, Android, Windows, Mac, Linux
- Key features: E2E encryption default, minimal metadata, open source, disappearing messages
- Best for: Privacy-focused communication, security professionals
- Note: Requires phone number

**WhatsApp**
- Type: E2E encrypted messenger (owned by Meta/Facebook)
- Pricing: Free
- Platforms: iOS, Android, Windows, Mac, web
- Key features: E2E encryption, large user base, voice/video calls
- Best for: Communication with non-technical users (high adoption)
- Note: Metadata collected by Meta, privacy concerns despite E2E encryption

**Telegram**
- Type: Cloud-based messenger with optional E2E encryption
- Pricing: Free
- Platforms: All
- Key features: Secret chats (E2E), large groups, channels, bots
- Best for: Groups, channels, general messaging
- Note: E2E only in "secret chats," not default; metadata concerns

**iMessage** (Apple)
- Type: E2E encrypted (between Apple devices)
- Pricing: Free
- Platforms: iOS, macOS
- Best for: Apple ecosystem users
- Note: Fallback to SMS if recipient not on Apple device

**Threema**
- Type: E2E encrypted messenger
- Pricing:  One-time purchase (~$5)
- Platforms: iOS, Android
- Key features: No phone number required, Swiss-based, minimal metadata
- Best for:  Maximum privacy, willing to pay upfront

**Email (Privacy-Focused):**

**ProtonMail**
- Type:  Encrypted email
- Pricing: Free tier, paid from $5/month
- Jurisdiction: Switzerland
- Key features: E2E encryption (between ProtonMail users), zero-access encryption, easy to use
- Best for: Privacy-conscious email, non-technical users

**Tutanota**
- Type:  Encrypted email
- Pricing: Free tier, paid from €3/month
- Jurisdiction: Germany
- Key features: E2E encryption, calendar, contacts, affordable
- Best for: Budget-conscious privacy seekers

**StartMail**
- Type: Privacy-focused email
- Pricing:  $60/year
- Key features: Unlimited aliases, PGP support
- Best for: Alias management, privacy

**Note:** Standard email providers (Gmail, Outlook, etc.) are not private.  Providers can read your emails. Use for general purposes, not sensitive communication.


## Browser Extensions

**Ad Blockers:**

**uBlock Origin**
- Type: Open source ad blocker
- Pricing: Free
- Browsers: Firefox, Chrome, Edge, Opera
- Best for: Most users, efficient, customizable
- Note: Not "uBlock" (different developer)

**AdGuard**
- Type: Ad blocker with privacy features
- Pricing: Free extension, paid app for system-wide blocking
- Best for: Advanced users wanting more control

**Privacy & Tracking Protection:**

**Privacy Badger** (EFF)
- Type:  Tracker blocker
- Pricing: Free
- Best for: Learning tracker blocking (blocks trackers algorithmically)

**DuckDuckGo Privacy Essentials**
- Type:  Tracker blocker + search
- Pricing: Free
- Best for: Simple all-in-one privacy extension

**HTTPS Everywhere** (EFF)
- Type: Forces HTTPS connections
- Pricing: Free
- Note: Less necessary now (many browsers have HTTPS-only mode built in)

**Decentraleyes**
- Type: Local CDN emulation
- Pricing: Free
- Best for: Preventing CDN tracking

**ClearURLs**
- Type:  Removes tracking parameters from URLs
- Pricing: Free
- Best for:  Cleaning tracking from links

**Script Blockers [ADVANCED]:**

**uBlock Origin (Advanced Mode)** [ADVANCED]
- Type: Dynamic filtering for browser
- Pricing: Free
- Best for: Advanced users wanting granular control over scripts and frames

**NoScript**
- Type: JavaScript blocker
- Pricing: Free
- Best for:  Security-focused users, breaks many sites until configured


## File Management & Organization

**Cloud Sync with Client-Side Encryption:**

**Cryptomator** (listed above in Encryption)

**rclone**
- Type: Command-line cloud sync
- Pricing: Free, open source
- Best for: Technical users, scripting, automation

**Duplicate File Finders:**

**dupeGuru**
- Type: Duplicate file finder
- Pricing: Free, open source
- Platforms: Windows, Mac, Linux
- Best for: Finding and removing duplicate files

**Gemini Photos** (Mac/iOS)
- Type: Duplicate photo finder
- Pricing: ~$20 one-time (Mac), subscription (iOS)
- Best for: Mac users, photo libraries

**CCleaner** (use with caution)
- Type: System cleaner
- Note: Had security incident in past; evaluate alternatives
- Alternatives: BleachBit (open source, Windows/Linux)

**File Synchronization:**

**Syncthing**
- Type:  Peer-to-peer file sync
- Pricing: Free, open source
- Platforms: Windows, Mac, Linux, Android
- Best for: Syncing between your own devices without cloud

**FreeFileSync**
- Type: File synchronization
- Pricing: Free, open source
- Best for: Scheduled backups, folder mirroring


## Digitization & Scanning

**Mobile Scanning Apps:**

**Adobe Scan**
- Type: Document scanner
- Pricing: Free
- Platforms: iOS, Android
- Features: OCR, PDF creation, cloud storage
- Best for: Most users, quality OCR

**Microsoft Lens**
- Type: Document scanner
- Pricing: Free
- Platforms: iOS, Android
- Features: OCR, Office integration
- Best for: Microsoft ecosystem

**Scanner Pro**
- Type: Document scanner
- Pricing:  Subscription ~$20/year
- Platforms: iOS
- Best for: iOS users, quality scanning

**OCR Software:**

**Tesseract OCR**
- Type: Open source OCR engine
- Pricing: Free
- Best for:  Developers, batch processing, integration

**ABBYY FineReader**
- Type: Professional OCR software
- Pricing: ~$120 one-time or subscription
- Best for: High-volume scanning, accuracy critical

**Adobe Acrobat Pro DC**
- Type: PDF editor with OCR
- Pricing:  ~$15-20/month
- Best for: Professional PDF work, OCR included

**Built-in OCR:**
- Preview (macOS): Basic OCR on scans
- Windows: Office apps include basic OCR


## Metadata Management

**Metadata Removal:**

**ExifTool**
- Type: Command-line metadata editor
- Pricing: Free, open source
- Platforms: Windows, Mac, Linux
- Best for: Advanced users, batch processing, comprehensive metadata control

**mat2** (Metadata Anonymization Toolkit)
- Type: Metadata remover
- Pricing: Free, open source
- Platforms: Linux (GUI and CLI)
- Best for: Privacy-focused Linux users

**ImageOptim** (Mac)
- Type: Image optimizer with metadata removal
- Pricing: Free
- Best for: Mac users, optimizing images + removing metadata

**Scrambled Exif** (Android)
- Type: Metadata remover for Android
- Pricing: Free, open source
- Best for: Android users sharing photos

**Metapho** (iOS)
- Type: Metadata viewer/editor
- Pricing: Free (in-app purchases)
- Best for: iOS users wanting to see/edit metadata

**Built-in options:**
- Windows: Right-click → Properties → Details → Remove Properties
- macOS: Preview → Tools → Show Inspector → GPS tab (delete)


## System Utilities

**Activity Monitoring:**

**Screen Time** (iOS, macOS)
- Built-in usage tracking
- Best for: Apple users

**Digital Wellbeing** (Android)
- Built-in usage tracking
- Best for: Android users

**RescueTime**
- Type:  Time tracking and productivity
- Pricing: Free (basic), $12/month (premium)
- Platforms: Windows, Mac, Linux, Android, browser
- Best for: Detailed productivity tracking

**Disk Space Analysis:**

**WinDirStat** (Windows)
- Type: Disk usage visualizer
- Pricing: Free, open source
- Best for: Finding what's consuming disk space on Windows

**DaisyDisk** (Mac)
- Type: Disk usage visualizer
- Pricing: ~$10
- Best for: Mac users, visual disk analysis

**Password Security Audits:**

**Have I Been Pwned** (website)
- Type: Breach notification service
- Pricing: Free
- URL: haveibeenpwned.com
- Best for: Checking if your email/passwords appeared in breaches

**Firefox Monitor**
- Type: Breach notification
- Pricing: Free
- Best for: Firefox users


## Miscellaneous

**Temporary/Disposable Email:**

**SimpleLogin**
- Type: Email alias service
- Pricing: Free tier (10 aliases), Premium $30/year (unlimited)
- Best for: Managing aliases, privacy

**Firefox Relay**
- Type: Email alias service (Mozilla)
- Pricing: Free tier (5 aliases), Premium $12/year (unlimited)
- Best for: Firefox users, simple aliasing

**Guerrilla Mail, 10 Minute Mail**
- Type:  Temporary disposable email
- Pricing: Free
- Best for: One-time signups

**Account Deletion Resources:**

**JustDeleteMe**
- Type: Directory of account deletion instructions
- URL: justdeleteme.xyz
- Best for: Finding how to delete accounts

**AccountKiller**
- Type: Similar to JustDeleteMe
- Best for: Account deletion guidance


**Note:** This list is not exhaustive and will become outdated. Before choosing tools: 
1. Research current reviews and security audits
2. Check if tool is still maintained/updated
3. Read privacy policy and terms of service
4. Evaluate based on your specific threat model
5. Prefer open source when security/privacy is critical
6. Don't trust, verify

Tools are means to implement principles in main Protocol Zero document.  Principles are timeless.  Tools change.


[← Back to Protocol Zero README](README.md) 
