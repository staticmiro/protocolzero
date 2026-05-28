# 📖 PART VI: DIGITAL FINANCES

## 25. Electronic Banking: Vault in Your Pocket

Your bank account on your phone. Convenient. Powerful. Dangerous if compromised.

### **[CRITICAL]** Banking App Security: Phone vs Computer

**Phone banking:**

Pros:
- Convenient, always with you
- Biometric authentication (fingerprint, face)
- Push notifications for suspicious activity
- Can disable quickly if phone lost

Cons:
- Easy to lose phone
- Apps can be malicious or compromised
- Screen shoulder-surfing in public
- Malware targeting mobile banking

**Computer banking:**

Pros:
- Larger screen, easier to review transactions carefully
- Better for complex tasks (reviewing statements, setting up transfers)
- Less likely to lose computer than phone

Cons:
- More vulnerable to malware if computer poorly maintained
- No biometric authentication on most computers
- Easier to fall for phishing on email-heavy computer workflow

**Recommendation:**

Use both strategically: 
- Quick checks and urgent transactions on phone (with all security features enabled)
- Detailed review, large transfers, important changes on computer (with updated security)
- Never on public/shared devices

### **[CRITICAL]** SMS and Push Alerts: First Line of Detection

Enable every alert your bank offers: 

**Transaction alerts:**
- Every purchase above certain amount
- Every withdrawal
- Every transfer
- International transactions
- Online purchases

**Security alerts:**
- Login from new device
- Password change
- Contact information change
- New payee added
- Failed login attempts

**Why this matters:**

You'll know within minutes if someone accesses your account. 

See transaction you didn't make? Immediately: 
1. Contact bank
2. Freeze account/card
3. Review recent transactions
4. Change passwords
5. Check for unauthorized changes to account settings

**Minutes matter. ** Faster you respond, less damage occurs.

**Alert fatigue:**

Too many alerts and you'll ignore them. Balance: 
- Enable all security alerts (always pay attention)
- Customize transaction alerts to meaningful amounts (you don't need alert for every coffee purchase, but do need one for purchases over $100)

### Limits and Blocks: Damage Control

**Set transaction limits:**

Daily withdrawal limit, transfer limit, international transaction limit.

If card compromised, attacker can only steal limited amount before limit triggers.

**Geographic restrictions:**

If you never travel internationally, block international transactions. Enable when needed for trip.

**Transaction type restrictions:**

Block ATM withdrawals if you never use ATMs.   
Block online purchases if card is only for in-person use.  
Block contactless if you don't use it.

**Temporary freezing:**

Most banking apps let you freeze card instantly. Transactions declined until you unfreeze.

Use when: 
- You can't find your card (freeze while you search)
- Card is lost and you're ordering replacement
- Traveling and want extra security at night
- Suspicious activity and you're investigating

Freeze is reversible. Better to freeze unnecessarily than leave compromised card active.

### **[CRITICAL]** Two-Factor Authentication in Banking

If your bank offers 2FA, enable it. No exceptions.

**Common methods:**

**SMS codes:**  
Not ideal (SIM swapping risk) but better than nothing.

**Authenticator app codes:**  
Better. More secure than SMS.

**Hardware keys:**  
Best. Phishing-resistant. 

**Push notifications:**  
App on your phone asks "Are you trying to log in?" Approve or deny.

**Enable strongest option your bank supports.**

**Without 2FA:**  
Someone with your password can drain your account from anywhere in the world.

**With 2FA:**  
They need your password AND your phone/security key. Massive improvement.

### Common Mistakes

**Using same password for bank and other accounts**  
Bank password must be unique, strong, stored in password manager.

**Ignoring security alerts**  
"Login from new device" email gets ignored. Could be attacker.

**No transaction monitoring**  
Never checking statements. Fraudulent charges go unnoticed for months.

**Banking on public WiFi without VPN**  
Network operator can intercept. Use cellular data or VPN for banking on untrusted networks.

**Saving banking password in browser**  
Browser password storage is less secure than dedicated password manager.

**Giving bank details over phone to unsolicited callers**  
Bank will never call asking for full password, PIN, or 2FA codes.

**Using banking app on jailbroken/rooted phone**  
Removes security protections. Banking apps often refuse to run on modified devices for good reason.

### Quick Wins

- **5 minutes:** Enable 2FA on all bank accounts. 
- **10 minutes:** Enable transaction and security alerts.
- **15 minutes:** Review and set transaction limits and geographic restrictions.
- **10 minutes:** Install banking app if you haven't, verify biometric login works.


## 26. Phishing: How to Recognize a Fake

Phishing is the most common cyberattack. Fake emails, messages, and websites designed to steal your credentials.

Technical security measures help. But most phishing succeeds because of human error.

### **[CRITICAL]** Typical Signs of Fraud

**Urgency and fear:**

"Your account will be closed in 24 hours!"  
"Suspicious activity detected, verify immediately!"  
"You've won a prize, claim now or lose it!"  
"Unusual login attempt, confirm your identity!"

Legitimate companies don't operate this way. Creating panic makes you act without thinking.

**Spelling and grammar errors:**

Professional companies proofread. Phishing emails often contain: 
- Awkward phrasing
- Grammatical mistakes
- Spelling errors
- Wrong company name or terminology

**Generic greetings:**

"Dear Customer" or "Dear User" instead of your name. 

Legitimate companies use your name (they have it in their system).

**Mismatched sender address:**

Email appears from "Your Bank" but sender address is `@gmial.com` or `@yourbank-security.net`

**Suspicious links:**

Hover over link (don't click). Check URL in bottom corner of browser or email client.

Does it match the supposed sender? 

`https://paypa1.com` (with number 1 instead of letter l)  
`https://secure-amazon-account.net` (not amazon.com)  
`https://appleid.security-check.com` (not apple.com)

**Unsolicited attachments:**

Email from unknown sender with attachment, especially:
- ZIP files
- Executable files (. exe, .bat, .scr)
- Office documents with "enable macros" instruction

Don't open attachments unless you're expecting them and verified sender.

**Requests for sensitive information:**

No legitimate company asks for:
- Full password
- PIN
- payment card CVV
- Social security number
- 2FA codes

Via email, text, or phone call. Never. 

### **[CRITICAL]** Checking Sender Address and Links

**Email address inspection:**

Look at full sender address, not just display name. 

Display name can say "PayPal Security" but actual address is `scammer@randomdomain.com`

**Verify domain:**

Legitimate: `noreply@company.com`  
Phishing: `noreply@company-support.net` or `noreply@company.co.uk` (when you're in US)

**Check for typos:**

`@amazoon.com`, `@paypa1.com`, `@microsft.com`

**Link inspection:**

Hover over link without clicking. URL preview appears. 

Does domain match company? 

Watch for:
- Extra words: `https://login-paypal.com` (paypal doesn't own `login-paypal.com`)
- Subdomains: `https://paypal.fake-site.com` (this is `fake-site.com`, not `paypal.com`)
- Misspellings: `https://amaz0n.com`

**When in doubt:**

Don't click link in email. Go directly to website by typing address yourself or using bookmark.

Log in normally. If there's really an issue, you'll see it there.

### What to Do If You Click a Suspicious Link

**If you clicked but didn't enter information:**

1. Close browser tab immediately
2. Clear browser cache and cookies
3. Run antivirus scan
4. Monitor for unusual behavior

Likely no harm done. Just visiting a website usually doesn't compromise you (unless browser is very outdated and has unpatched vulnerabilities).

**If you entered credentials (username/password):**

1. Change password immediately on legitimate website
2. Check account for unauthorized changes
3. Enable 2FA if not already enabled
4. Log out all sessions
5. Check connected devices and apps
6. Monitor account for suspicious activity
7. Alert the company (they track phishing attempts)

**If you entered financial information (card number, bank account):**

1. Contact bank/card issuer immediately
2. Freeze or cancel card
3. Monitor account for fraudulent charges
4. Request new card
5. Set up fraud alerts
6. File police report if money was stolen
7. Check credit report for identity theft

**If you downloaded and opened attachment:**

1. Disconnect from network (WiFi and ethernet)
2. Run full antivirus scan
3. If malware found, follow removal instructions
4. Change all passwords from a different, clean device
5. Consider professional malware removal if antivirus doesn't resolve
6. In severe cases, wipe device and restore from clean backup

### **[RECOMMENDED]** Reporting Phishing

**Report to the impersonated company:**

Most companies have abuse or phishing report email: 
- `phishing@company.com`
- `abuse@company.com`
- Report options in account security settings

Forward the phishing email or provide details.

**Report to email provider:**

Mark as phishing/spam. Helps provider filter similar messages for others.

**Report to authorities:**

Depending on jurisdiction: 
- National cybersecurity centers
- Consumer protection agencies
- Police (for financial fraud)
- Anti-phishing working groups

**Forward and delete:**

After reporting, delete phishing message. Don't keep it around to accidentally click later.

### Common Mistakes

**Clicking first, thinking later**  
Urgency in message makes you react. Pause. Examine. Verify. 

**Trusting sender display name**  
"Amazon Security" can be anyone. Check actual email address.

**Assuming HTTPS means legitimate**  
Phishing sites use HTTPS too. Padlock just means encrypted connection, not trustworthy site.

**Entering 2FA code from email/text into suspicious website**  
Attacker uses your real password and the 2FA code you just gave them to access your real account immediately. Never enter 2FA code prompted by unexpected login.

**Thinking "I'm too smart to fall for this"**  
Everyone is vulnerable when rushed, stressed, distracted, or when phishing is sophisticated.

**Not reporting**  
Silence helps attackers. Reporting protects others.

**Trusting message because it mentions personal information**  
"We noticed activity on your account ending in 1234." Attackers scrape partial account numbers from data breaches. Doesn't prove legitimacy.

### Quick Wins

- **10 minutes:** Practice hovering over links in emails to check URLs without clicking.
- **5 minutes:** Check sender addresses of recent "official" emails you received.
- **15 minutes:** Educate family members about phishing (show examples, explain red flags).
- **Ongoing:** Before clicking any link in email, ask: "Was I expecting this? Does it look legitimate?"


## 27. Payment Cards: Physical and Virtual

Credit and debit cards are convenient targets. Physical theft, number theft, data breaches. 

### **[RECOMMENDED]** Disposable and Virtual Cards

**Virtual cards:**

Card number generated digitally. Used for online purchases. Can be: 
- Single-use (expires after one transaction)
- Merchant-specific (locked to one vendor)
- Time-limited (expires after certain date)
- Amount-limited (maximum charge limit)

**How they work:**

Your bank or card provider generates temporary card number linked to your real account. 

You use virtual number for purchase. Merchant never sees your real card number.

If merchant is breached or sells your number, virtual card is useless to attacker (already expired or locked to that merchant).

**Benefits:**

- Real card number protected
- Limit damage from breaches
- Easy to cancel if compromised (without canceling real card)
- Control spending (set limits per card)

**When to use:**

- Online shopping (especially unfamiliar merchants)
- Subscriptions (cancel virtual card to end subscription)
- Free trials (prevents automatic charging)
- Any situation where you don't fully trust merchant

### Cards for Different Purposes

**Primary card:**  
For trusted, recurring expenses. Real card number minimally exposed.

**Shopping card:**  
For online purchases. Virtual or separate physical card. Lower limit. Easy to replace if compromised.

**Subscription card:**  
Dedicated card for subscriptions. Makes tracking easy. Cancel card to cancel all subscriptions at once if needed.

**Travel card:**  
Used only when traveling. Keeps primary card safe at home. Easier to manage fraud alerts (you know all charges should be in travel location).

**Burner card:**  
Virtual, single-use for sketchy websites or free trials you'll forget to cancel.

**Why separate:**

Compartmentalization limits damage. 

Shopping card compromised? Only affects shopping card. Primary card for bills still works.

Easy to track spending by category. 

Easier to spot fraud (unexpected charge on card you only use for subscriptions stands out).

### **[RECOMMENDED]** Blocking and Freezing Cards in App

Most card issuers offer instant controls via app:

**Freeze:**  
Temporarily disable card. All transactions declined. Reversible with one tap.

Use when:
- Card misplaced
- Traveling and card is at home
- Suspicious activity under investigation
- Extra security overnight or when not using card

**Block categories:**  
Disable certain transaction types: 
- International
- Online purchases
- ATM withdrawals
- Contactless
- Recurring charges

**Set limits:**  
Daily spending limit, per-transaction limit. 

**Lock to device:**  
Card only works when near your phone (using phone's location). Prevents use if stolen.

**Instant notification + instant freeze = powerful protection.**

See suspicious charge, freeze card immediately from phone, prevent further fraud.

### Reporting Unauthorized Charges

**Act quickly:**

Most card issuers have zero liability for fraud if reported promptly. Delays can complicate disputes.

**Process:**

1. **Freeze card** (prevent additional charges)
2. **Contact card issuer** (phone number on back of card or in app)
   - Report specific fraudulent transactions
   - Request investigation
   - Get new card issued
3. **Document everything** (case number, representative name, date/time of report)
4. **Follow up in writing** (email or letter confirming fraud report and disputed charges)
5. **Monitor account** (check for additional fraudulent charges that appeared before freeze)
6. **Check credit report** (ensure no new accounts opened in your name)

**Temporary credits:**

Most issuers provide temporary credit while investigating (amount of fraudulent charges returned to your account pending investigation).

Investigation can take weeks. Keep documentation.

**If dispute denied:**

Request explanation. Provide additional evidence. Escalate if necessary.

### Common Mistakes

**Using debit card for online shopping**  
Debit card fraud drains your bank account directly. payment card fraud is the bank's money until resolved. Use payment cards online. 

**Saving card info on every website**  
Convenient but risky. Each saved card is another breach point.  

**Not monitoring transactions**  
Small fraudulent charges go unnoticed. Criminals test with small amount, then make large purchases.

**Ignoring fraud alerts from card issuer**  
Text: "Did you make a purchase at [store]?" Don't ignore. Respond immediately.

**Writing PIN on card**  
Never. Memorize PIN. If you must write it down, store separately from card.

**Giving card number over phone to unsolicited caller**  
Card issuer will never call asking for full number. They already have it.

**Using same card for everything**  
No compartmentalization. One compromise affects everything.

### Quick Wins

- **10 minutes:** Request virtual card feature from your card issuer (or switch to one that offers it).
- **15 minutes:** Create dedicated virtual card for online shopping.
- **5 minutes:** Enable transaction notifications for all cards.
- **10 minutes:** Freeze cards you're not actively using.


## 28. Subscriptions: Silent Budget Eaters

Small monthly charges accumulate. You forget what you're paying for. Money disappears.

### **[RECOMMENDED]** How to Inventory All Subscriptions

**Check bank and card statements:**

Go back 3-6 months. Look for recurring charges:
- Same merchant every month
- Similar amounts
- Obvious subscription services (streaming, software, apps, memberships)

Make a list:
- Service name
- Monthly cost
- Annual cost (multiply monthly by 12)
- Last charge date
- What card is charged

**Check email:**

Search for: 
- "subscription"
- "receipt"
- "monthly charge"
- "annual renewal"
- "payment confirmation"

**Check app subscriptions:**

Phone app stores have subscription management: 
- Active subscriptions
- Canceled subscriptions
- Upcoming renewals

**Check password manager:**

Accounts in password manager might indicate subscriptions. 

**Ask your bank:**

Some banks categorize recurring charges and can generate report.

**Use tracking tools:**

Apps and services exist that scan your transactions and identify subscriptions automatically.

### Cancellation Strategy: What You Really Need

**Review each subscription:**

Ask:
- Have I used this in the last month?
- Would I pay for this again if I didn't already have it?
- Can I accomplish the same thing for free or cheaper? 
- Is this a duplicate of another service I have? 
- Was this a free trial I forgot to cancel?

**The unused subscription rule:**

If you haven't used it in 60 days, cancel it. 

You can always resubscribe if you actually need it later.

**Annual vs monthly:**

Annual subscriptions are cheaper per month but lock you in. 

If you're unsure you'll use it all year, pay monthly. Cancel when not needed.

**Negotiation:**

Contact service before canceling. Many offer: 
- Discounts to retain you
- Pause option (suspend subscription without losing account)
- Downgrade to cheaper tier

"I'm thinking of canceling" often unlocks offers not publicly available.

**Actual cancellation:**

Don't just delete app or remove card. Subscription continues and goes to collections if unpaid.

Cancel properly:
1. Log into account
2. Find subscription/billing settings
3. Cancel subscription
4. Confirm cancellation email
5. Save confirmation
6. Verify charge stops (check statement next month)

### Reminders for Expiring Trials

Free trials convert to paid subscriptions automatically. This is intentional. Companies profit from forgotten trials.

**Strategy:**

**Calendar reminder:**

When you start free trial, immediately create calendar event:
- Day before trial ends
- Title: "Cancel [service] trial"
- Include cancellation link in event notes

**Virtual card:**

Use virtual card with spending limit or expiration for trials.

When trial ends and tries to charge, payment fails. Subscription doesn't activate.

**Trial tracking:**

Spreadsheet or note listing:
- Service name
- Trial start date
- Trial end date
- Cancellation instructions

Review weekly. 

**Cancel immediately:**

Some services let you cancel trial but continue using service until trial period ends.

Start trial → cancel immediately → still get full trial period → can't forget to cancel.

Not all services allow this. Check terms.

### Common Mistakes

**Forgetting trials exist**  
Sign up for free trial, forget, charged monthly for service never used.

**Assuming deleting app cancels subscription**  
It doesn't. Subscription continues until explicitly canceled.

**Putting off cancellation**  
"I'll cancel before it renews." You won't remember. Do it now or set reminder.

**Not reading cancellation terms**  
Some require 30 days notice. Cancel on last day of billing period and you're charged for another month.

**Multiple subscriptions for same category**  
Three streaming services, four cloud storage services. Consolidate.

**Never reviewing subscriptions**  
Annual audit mandatory. Spending on subscriptions creeps up over time.

**Feeling obligated to continue**  
Sunk cost fallacy. You already paid doesn't mean you should keep paying.

**Subscribing individually instead of family/group plans**  
Many services offer family plans cheaper than multiple individual subscriptions.

### Quick Wins

- **30 minutes:** Create complete list of all current subscriptions with monthly costs.
- **20 minutes:** Cancel 3 subscriptions you haven't used in 60 days.
- **10 minutes:** Set calendar reminders for any active free trials.
- **15 minutes:** Calculate total annual subscription cost (often surprisingly high, motivates cutting).


## 29. Cryptocurrency (Optional): Protect the Seed Phrase, Avoid Scams

If you don’t use cryptocurrency, skip this chapter. Protocol Zero focuses on **digital hygiene and protecting your data**—crypto is only here because some people hold it and can lose it permanently.

### The only thing you must understand: seed phrase = full access
When you create a self-custody wallet, you get a **seed phrase** (usually 12 or 24 words). Whoever has it can take all funds. If you lose it, you may lose access forever.

### **[CRITICAL]** Seed phrase rules (simple, non-negotiable)
1. Write it down offline (paper or metal).  
2. Store it securely (safe / deposit box), and consider a second backup location.  
3. Never type it into websites, chats, forms, email, or “support” conversations.  
4. Never take a photo of it or store it in cloud notes/backups.  
5. Test recovery with a small amount before storing significant value.

### Common mistakes
- Keeping large amounts on an exchange and assuming it’s “like a bank”  
- Storing seed phrases in photos/notes/cloud backups  
- Installing random wallet apps or falling for “support” impersonators  
- Sending to the wrong address (transactions are usually irreversible)

### Quick wins (if you use crypto)
- **15 minutes:** Find where your seed phrase is stored and verify it’s offline + secure.  
- **10 minutes:** Write down who should be able to access it if you’re incapacitated (see Part XI: Digital Legacy).  

---
[← Back to Protocol Zero README](README.md)
