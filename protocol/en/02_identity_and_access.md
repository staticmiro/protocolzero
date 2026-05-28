# 📖 PART II: IDENTITY AND ACCESS

## 2. Password Managers: The End of "Password123"

### Why Your Brain Is Not a Vault

You cannot remember strong, unique passwords for 50+ accounts. Nobody can.  

So people reuse passwords. Same password for email, bank, social media, shopping sites. This is catastrophic.  

When one website gets hacked (and they do, constantly), attackers try your leaked email and password combination everywhere else. Bank. Email. Social media. Payment accounts. 

One breach. Total compromise.  

**The solution is not a better memory. It's a password manager.**

A password manager is an encrypted vault that stores all your passwords. You remember one strong master password. The manager generates and remembers everything else.

Every account gets a unique, random, strong password. When one site gets breached, only that account is affected. 

### **[CRITICAL]** How to Choose a Password Manager

There are three types:

**Cloud-Based (Recommended for Most People)**  
Your passwords are encrypted and stored on the company's servers. You can access them from any device. If you forget your master password, your data is gone forever. Companies cannot recover it (this is good—it means they can't read your passwords).

Options exist at various price points, from free to premium subscriptions. Research current options before choosing.

**Local/Self-Hosted [ADVANCED]**  
Store encrypted database file on your device. You manage syncing (via cloud storage or USB). Maximum control, more complexity.  

**Built-In (Basic, Better Than Nothing)**  
Operating systems and browsers include basic password storage. Works well within their ecosystem but limited outside it. Less features than dedicated managers.

**Recommendation:** Start with a reputable cloud-based option. Research current highly-rated options that are open source, cross-platform, and have strong security track records.

**For specific tool recommendations, see [Appendix A: Tools – Essential List](a_tools_essential_list.md#password-managers).**

### **[CRITICAL]** First Steps: Installation and Master Password

**1. Install the password manager**
- Download from official website or official app store only.  
- Install browser extension and mobile app.  

**2. Create your master password**

This is the most important password you'll ever create. Requirements:
- At least 16 characters
- Mix of words, numbers, symbols
- Memorable to you but unguessable to others

Good method: **Passphrase** – String of random words with numbers and symbols. 

Example pattern: `Word1-Word2-Word3-Word4-Number! ` (create your own, don't use common phrases)

Bad: `MyDog1234` (too short, too guessable)  
Better: `MyDog-Loves-Walking-In-Rain-42!`  
Best: `7-Clouds-Dance-Above-Mountain-River-42!`

Write it down. Put the paper somewhere safe (safe, locked drawer). You need it to access everything. If you forget it, everything is gone.

**3. Secure your account**
- Enable two-factor authentication on the password manager itself (we'll cover this in next chapter)
- Save recovery codes somewhere safe (on paper/offline, not digital)

### How to Safely Migrate Old Passwords

Don't try to change everything in one day. You'll burn out.  

**Week 1: Critical Accounts**  
Update passwords for:  
- Primary email
- Bank/financial accounts
- Password manager itself
- Any account with payment methods

**Week 2: Important Accounts**  
- Secondary email addresses
- Social media
- Work/school accounts
- Shopping sites with saved payment info

**Week 3+: Everything Else**  
- Old accounts you barely use
- Forums, subscriptions, niche sites

**Process for each account:**
1. Log into the account
2. Go to security/password settings
3. Let password manager generate a new password (20+ characters, random)
4. Save it in password manager
5. Verify you can log in with new password

Some password managers can import from browsers. Convenient but check each password—many will be duplicates or weak.

### Passwords for Passwords: What to Write on Paper

Write these down on paper and store securely: 

1. **Master password** for password manager
2. **Recovery codes** for password manager
3. **Recovery codes** for primary email
4. **Recovery codes** for bank accounts

Where to store:  
- Home safe
- Locked drawer only you can access
- Safety deposit box at bank (for backups)

Never store these digitally unless encrypted in password manager (circular dependency problem for master password).

### Common Mistakes

**"I'll remember the master password, don't need to write it down"**  
You won't. Stress, illness, time—memory fails. Write it down.

**"I'll use a simple master password and change it to complex later"**  
You won't change it later. Start strong.  

**"Password managers got hacked, they're not safe"**  
Password manager companies are breached less often than the 50+ other sites where you'd otherwise reuse passwords. Even when breached, strong encryption means your passwords stay safe. Much safer than reusing passwords.

**"Too much work to change all passwords"**  
Start with critical accounts. Even 5 accounts with unique passwords is infinitely better than 50 accounts with the same password.

### Quick Wins

- **10 minutes:** Research and install a password manager, create master password, save it on paper.  
- **30 minutes:** Add and update passwords for email and bank.  
- **1 hour:** Update top 10 most important accounts. 


## 3. Two-Factor Authentication (2FA): The Second Line of Defense

### **[CRITICAL]** Why Passwords Alone Are Not Enough

Passwords get stolen. Phishing, data breaches, malware, shoulder surfing, guessing. 

Two-factor authentication (2FA) adds a second requirement: something you have, not just something you know.

Even if someone steals your password, they can't access your account without the second factor.  

### How Different Methods Compare

There are several types of 2FA. They are not equally secure.  

**SMS / Text Message [BASIC]**  
A code is sent to your phone number via text message. 

Pros: Easy, works on any phone  
Cons: Vulnerable to SIM swapping (attacker convinces your phone carrier to transfer your number to their SIM card), SMS interception

Use SMS 2FA only if nothing better is available. It's better than no 2FA, but not by much.

**Authenticator Apps [RECOMMENDED]**  
App on your phone generates time-based codes that change every 30 seconds. 

Multiple authenticator apps exist with different features—some sync across devices with cloud backup, others store codes only locally. 

**For specific authenticator app recommendations, see [Appendix A: Tools – Essential List](a_tools_essential_list.md).**

Pros: Much more secure than SMS, works offline  
Cons: Lose phone without backup equals locked out

**Hardware Keys [ADVANCED]**  
Physical device you plug into computer or tap on phone. 

Dedicated security keys are available from various manufacturers. 

Pros: Most secure option, phishing-resistant, works offline  
Cons: Costs money, can be lost (buy 2, keep backup in safe place)

**Recommendation:** Use authenticator app for most accounts. Use hardware key for most critical accounts if you're comfortable with the complexity.

### **[EMERGING]** Passkeys: The Future of Authentication

**Passkeys** are a newer standard replacing passwords entirely. Instead of typing a password, your device proves it's you using cryptographic keys.

**How passkeys work:**

You create a passkey for a website or app. Your device generates two keys:
- **Private key** - stays on your device, never shared
- **Public key** - stored by the service

When you log in, your device uses the private key to prove identity without sending the password.

**Advantages:**
- No password to remember or type
- Phishing-resistant (attackers can't steal what you never type)
- Easier than passwords + 2FA
- Works with biometrics (face, fingerprint) or device PIN

**Current limitations:**
- Not all services support passkeys yet (but adoption growing rapidly)
- Syncing across devices depends on your ecosystem (Apple, Google, Microsoft, or password manager)
- Backup/recovery varies by platform

**Should you use passkeys?**

**Yes, when available.** Passkeys are more secure and more convenient than passwords.

Enable passkeys for services that support them. Keep password manager as backup until passkeys are universal.

**Note:** Passkey support varies by service. If a service doesn’t support passkeys yet, keep using a unique password + 2FA and enable passkeys when they become available.

### **[CRITICAL]** Recovery Codes: The Most Important Paper in Your Home

When you enable 2FA, services give you recovery codes (also called backup codes). Usually 8-12 random codes. 

These codes let you access your account if you lose your phone or 2FA device. 

**You must save these.**  Print them. Write them down. Store them with your master password.

Without recovery codes, losing your 2FA device means permanent lockout from your account.

### Where to Enable 2FA First

Don't try to enable everywhere at once. Prioritize.  

**Priority 1: [CRITICAL]**
- Primary email (this protects everything else)
- Password manager
- Bank and financial accounts

**Priority 2: [RECOMMENDED]**
- Secondary email addresses
- Social media (especially if linked to other accounts)
- Cloud storage
- Work/school accounts

**Priority 3: [OPTIONAL]**
- Shopping sites
- Gaming accounts
- Forums and communities

### How to Set Up 2FA (General Process)

Each service is different, but the pattern is similar:

1. Go to account security settings
2. Look for "Two-Factor Authentication" or "Two-Step Verification"
3. Choose method (app-based recommended)
4. Scan QR code with authenticator app
5. Enter the 6-digit code to confirm it works
6. **Save recovery codes** (write down on paper / store offline)
7. Test logging out and back in

Some services force you to set up SMS as backup. If possible, disable SMS 2FA after setting up app-based 2FA.

### Common Mistakes

**Not saving recovery codes**  
You will lose your phone eventually. Breakage, theft, upgrade. No recovery codes equals locked out forever.

**Only using SMS 2FA**  
Better than nothing, but vulnerable. Use app when possible.

**Enabling 2FA on email but not password manager**  
If someone gets into your password manager, they get everything. Protect it.

**Using same 2FA app across multiple devices without understanding backup**  
Some authenticator apps don't sync. Lose phone equals lose all codes. Others sync but require remembering the app's password. Understand which type you're using.

### Quick Wins

- **5 minutes:** Enable 2FA on primary email.  
- **10 minutes:** Enable 2FA on password manager and bank.  
- **20 minutes:** Collect all recovery codes and store them offline in one place (paper, kept securely).


## 4. Email Strategy: Identity Division

### Why One Email for Everything Is Dangerous

Your email is the master key to your digital life. 

"Forgot password" links go to email. Account confirmations go to email. Security alerts go to email. Receipts, documents, personal messages—everything.  

If someone compromises your email, they control everything connected to it. 

Also: using the same email everywhere means one data breach exposes all your accounts. Companies know all your activities. Spam follows you everywhere.

**Solution: Multiple email addresses for different purposes.**

### **[RECOMMENDED]** Three Inboxes: Banking, Personal, Disposable

**Email 1: Financial/Critical [SECURE]**  
Use only for:  
- Banks and payment cards
- Government services
- Medical/insurance
- Password manager
- Tax and legal

Never use for: Shopping, social media, newsletters, signups

Security: 
- Strongest unique password
- 2FA with authenticator app (not SMS)
- Check regularly for security alerts
- Never click links in emails—go directly to website

**Email 2: Personal [EVERYDAY]**  
Use for:  
- Friends and family
- Social media
- Work/school (if you don't have work email)
- Trusted services

Security: 
- Strong unique password
- 2FA enabled
- Regular monitoring

**Email 3: Disposable/Spam [BURNER]**  
Use for:  
- Online shopping
- One-time signups
- Newsletters
- Anything you don't fully trust

Security:
- Unique password (stored in password manager)
- Expect spam, phishing attempts
- Check occasionally, ignore most of it

### Aliases and Temporary Emails

You can create unlimited variations of your email without making new accounts.

**Plus Addressing**  
Many email providers support adding "+tag" to your address:   
`yourname+shopping@emailprovider.com`  
`yourname+newsletter@emailprovider.com`  

All mail goes to your main address, but you can filter and see who sold your email.  

Weakness: Easy to strip the "+tag" part. Not all websites accept + in email addresses.

**Alias Services [RECOMMENDED]**  
Dedicated services let you create unlimited forwarding addresses that hide your real email. You create random aliases that forward to your real email. If an alias gets spam, delete it. Your real email stays hidden.

Multiple services exist at various price points, from free tiers to paid plans.

**Temporary/Disposable Emails [OPTIONAL]**  
Services provide email addresses that self-destruct after short time (10 minutes, 1 hour, etc.).

Use for one-time signups when you don't even want an alias.

### How to Regain Control of Your Primary Email

If you've been using one email for everything for years:

**Step 1: Audit**  
Find out what accounts are connected to your email. 
- Check your inbox for "welcome" and "confirm" emails
- Search for "password" "account" "verification"
- Some services can show accounts linked to your email

**Step 2: Prioritize**  
Make a list:  
- Critical accounts (banks, government, medical)
- Important accounts (social media, work, main shopping)
- Unimportant accounts (old forums, one-time purchases)

**Step 3: Migrate Critical Accounts**  
Create new secure email. Update critical accounts to use it. Enable 2FA.  

**Step 4: Gradually Migrate Others**  
Over weeks/months, update important accounts to use appropriate email (personal or disposable).

**Step 5: Maintain**  
New account equals think first which email to use.  

### Common Mistakes

**Using work/school email for personal accounts**  
When you leave, you lose access. Employer can read everything. Keep separate.  

**Giving real email to every website**  
Use aliases or disposable emails. Protect your real address.

**Not enabling 2FA on all email accounts**  
If one email gets hacked, attacker can reset passwords for everything connected to it.

**Forgetting to update important accounts after email change**  
You change email address but forget to update bank. Security alerts go to old email you don't check.

### Quick Wins

- **5 minutes:** Create a second email address for financial accounts. 
- **15 minutes:** Enable 2FA on all email accounts.  
- **30 minutes:** Set up an email alias service and create first 5 aliases.


## 5. Sessions and Devices: Who's Logged In as You

### The Problem You Don't See

You log into streaming service at a friend's house. You use social media on a library computer. You sign into email on your old phone that's now in a drawer. 

All of these are still logged in. Active sessions. Open doors into your accounts.

If someone accesses that device, they access your account. No password needed.

### **[RECOMMENDED]** How to Check Active Sessions

Most major services show you where you're logged in.  

**How to access:**  
Account security settings usually include "Active sessions," "Where you're logged in," "Devices," or similar section.

Check what you see:  
- Unfamiliar locations?  
- Devices you don't own? 
- Old sessions from years ago?

**What to look for:**
- Device type (phone, computer, tablet)
- Location (approximate)
- Last activity date/time
- IP address (sometimes)

### **[CRITICAL]** Logging Out of All Devices at Once

Most services have a "sign out everywhere" or "sign out all other sessions" button. 

Use this:  
- After checking active sessions and seeing something suspicious
- After losing a device
- When changing your password
- Once every few months as good hygiene

**Important:** This will sign you out on all devices, including your own. You'll need to log back in everywhere.

**Steps (general pattern):**
1. Change your password (in case someone has it)
2. Click "sign out all devices" or "sign out other sessions"
3. Log back in on your legitimate devices
4. Enable or verify 2FA is active

### Managing Trusted Devices

Some services let you mark devices as "trusted."

Trusted devices: 
- Don't ask for 2FA every time
- Can approve logins on other devices
- Can receive security alerts

**Rules for trusted devices:**
- Only mark devices you physically control
- Never mark public computers, friend's devices, work devices
- Remove old devices you no longer own
- Review trusted device list every 6 months

### What to Do When You See Unknown Login Activity

**If you see a login you don't recognize:**

1. **Don't panic, but act quickly.**

2. **Check the details:** Location, device, time. Could it be you? VPNs can show strange locations. Mobile data sometimes shows wrong city.

3. **If definitely not you:**
   - Change password immediately (strong, unique)
   - Sign out all sessions
   - Enable 2FA if not already enabled
   - Check account activity for unauthorized changes (sent emails, purchases, messages, settings changes)
   - Review recovery email and phone number—attackers often change these

4. **Check other accounts:** If one account is compromised, try other accounts with same password.  

5. **Check for data breach:** Visit breach notification services to see if your password was leaked in a breach.

**If account was compromised:**
- Document what happened (screenshots)
- Report to the service (most have "my account was hacked" flows)
- Warn contacts if attacker might have sent messages from your account
- Consider if any sensitive data was exposed

### Common Mistakes

**Never checking active sessions**  
Most people log in everywhere and never look back. Sessions can stay active for years.

**Staying logged in on public/shared computers**  
Always log out. Better: use private/incognito mode and close all windows when done.

**Trusting devices you don't fully control**  
Work laptop, shared family computer, friend's phone—don't mark as trusted, don't save passwords, log out when done.

**Ignoring security alerts**  
Email says "new login from unknown device" and you ignore it. These alerts exist for a reason. Check them.

### Quick Wins

- **5 minutes:** Check active sessions on your most important accounts. 
- **10 minutes:** Sign out all sessions on your 5 most important accounts.
- **15 minutes:** Review and remove old trusted devices.


## 6. Aliases and Pseudonyms: Living Under Different Names

### When to Use Your Real Name vs a Nickname

Not every online interaction requires your real identity. 

**Use real name for:**
- Government services
- Banking and finance
- Medical services
- Legal documents
- Professional networking
- Accounts tied to real-world identity

**Use pseudonym/nickname for:**
- Social media (if you want separation from real identity)
- Forums and communities
- Gaming
- Creative work (writing, art) if you want privacy
- Political or controversial discussion
- Any situation where exposure could cause harm

**The key question:** If this account were publicly connected to my real name, would it cause professional, social, or personal problems?

If yes: use a pseudonym. 

### Professional/Personal/Public Separation

Many people benefit from separating identities:

**Example 1: Professional**  
- Real name for professional network, work email, professional portfolio
- Pseudonym for personal social media, hobbies, forums

Why: Employers search your name. Clients search your name. You don't want them seeing every opinion, photo, or personal detail. 

**Example 2: Creative**  
- Real name for day job
- Pen name for writing/art

Why: Freedom to create without professional or personal consequences. Privacy for family.  

**Example 3: Activist/Sensitive Topics**  
- Real name for everyday life
- Anonymous identity for activism, support groups, whistleblowing

Why: Safety from retaliation, harassment, or discrimination.  

**This is not deception. This is healthy boundaries.**

### How Not to Connect Your Identities by Accident

If you want to keep identities separate, avoid these mistakes:

**Using the same email**  
Data breaches, email searches, and correlation can link accounts. Use separate emails for separate identities.

**Using the same username**  
Same username across platforms equals easily linked. 

**Using the same profile photo**  
Reverse image search can connect accounts. Use different photos or none.

**Posting same content on multiple accounts**  
Unique phrases, specific details, timestamps—these can link identities.

**Using the same payment method**  
Some services leak payment info in data breaches. Use different cards or payment methods for different identities.

**Login from same device/IP without protection**  
Platforms can correlate accounts that log in from the same device or location. Use separate browsers, containers, or VPN if this is a concern.

**Mentioning one identity from another**  
Referencing your other accounts from one account equals linked.  

### Tools for Managing Multiple Identities

**Separate Browsers**  
Different browser for each identity. Each browser has separate cookies, history, logins.  

**Browser Containers**  
Some browsers offer container features that let you separate identities within one browser. Different containers have isolated cookies and sessions.

**Separate Devices [ADVANCED]**  
Different phone or computer for different identities. Maximum separation but expensive and inconvenient.

**Different Password Manager Vaults [OPTIONAL]**  
Some password managers let you create separate vaults for different identities.  

### Common Mistakes

**Thinking pseudonyms are illegal or unethical**  
They're not. Pen names have existed for centuries. Privacy is legitimate.

**Using pseudonym but linking all your real info**  
Nickname on platform but real name in bio, link to professional profile, use work email equals not separate.  

**Overthinking it**  
For most people, separation is simple: work email for work, personal email for personal, nickname for forums. Done.

**Trusting platform privacy settings alone**  
Settings change. Bugs happen. Breaches occur. True separation requires separate accounts and careful habits.

### Quick Wins

- **5 minutes:** Create a pseudonym for use on forums and communities.
- **10 minutes:** Set up browser features to separate work and personal browsing.
- **20 minutes:** Audit your online presence—search your real name, see what's public, decide what should be under a pseudonym instead.

*Remember: Perfect security doesn't exist. Progress over perfection. Each step makes you significantly safer.*

---
[← Back to Protocol Zero README](README.md)
