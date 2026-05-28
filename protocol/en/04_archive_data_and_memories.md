# 📖 PART IV: ARCHIVE – DATA AND MEMORIES

## 12. The 3-2-1 Rule: The Sacred Backup Principle

### Why Backups Matter

Hard drives fail. Phones get stolen. Laptops break. Files get accidentally deleted. Ransomware encrypts everything. House fires destroy computers.

Without backups, you lose everything.

Photos of deceased loved ones. Years of work documents. Tax records. Passwords. Email history. Creative projects. Irreplaceable memories.

**If data only exists in one place, it doesn't exist.**

You need backups. Not someday. Now.

### **[CRITICAL]** 3 Copies, 2 Media Types, 1 Offsite

The 3-2-1 rule is simple and effective:

**3 copies of your data**

- 1 primary (the files you actively use)
- 2 backups

If one backup fails, you have another.

**2 different media types**
Don't store all copies on the same type of device.

Examples:

- Computer hard drive + external hard drive + cloud storage
- Phone + computer + external drive
- Computer + NAS + cloud

Why: If one type of media has a vulnerability (all external drives from same manufacturer have defect, cloud service shuts down), you're not completely compromised.

**1 copy offsite**
At least one backup must be physically separate from primary location.

Why: Fire, flood, theft, natural disaster can destroy everything in one location.

Offsite options:

- Cloud storage
- External drive at friend/family member's house
- Safety deposit box
- Second home/office

### What This Looks Like in Practice

**Example 1: Basic Home User**

- Primary: Laptop hard drive (daily work)
- Backup 1: External hard drive connected to laptop (automatic daily backup)
- Backup 2: Cloud storage service (automatic continuous sync)

**Example 2: Photographer/Creative**

- Primary: Computer internal drive (active projects)
- Backup 1: External SSD (weekly manual backup)
- Backup 2: NAS (network-attached storage) at home (daily automatic backup)
- Backup 3: Cloud storage (monthly offsite backup of completed projects)

**Example 3: Minimal Setup**

- Primary: Phone (photos, documents)
- Backup 1: Computer (sync photos and files weekly)
- Backup 2: Cloud storage (automatic backup from phone)

The specific setup matters less than following the principle: multiple copies, different types, at least one offsite.

### Frequency: What to Back Up Daily vs Once a Year

Not all data needs same backup frequency.

**Continuous/Daily:**

- Active work documents
- Photos and videos (if you take many)
- Email (usually automatically backed up by email provider)
- Any data that changes frequently and would be painful to lose

**Weekly:**

- Personal documents
- Project files
- Browser bookmarks and settings

**Monthly:**

- Completed projects you no longer actively work on
- Archives of old files
- System settings and configurations

**Annually:**

- Full system image/clone
- Verification that old backups are still readable
- Review what needs to be backed up vs deleted

**After major events:**

- Before system updates or hardware changes
- After completing major project
- When organizing or consolidating files

### **[CRITICAL]** Recovery Testing: A Backup That Doesn't Work Isn't a Backup

Most people set up backups and never verify they work.

Then disaster strikes. They try to restore. Backup is corrupted. Or incomplete. Or they can't figure out how to access it.

**Test your backups regularly.**

**Every 3-6 months:**

1. Choose a random file from backup
2. Restore it to a different location
3. Verify file opens and is intact
4. Document the restoration process (write down steps)

**Annually:**

1. Restore entire backup to verify completeness
2. Practice full system recovery on test machine if possible
3. Update restoration instructions if process has changed

If you can't restore your backup, you don't have a backup.

### What to Back Up

**Essential (must backup):**

- Photos and videos
- Documents (tax records, contracts, receipts, medical records, legal documents)
- Creative work (writing, art, music, code)
- Passwords (export from password manager periodically)
- Email archives (if not using cloud email)
- Contacts and calendar (export periodically)
- Financial records

**Important (should backup):**

- Browser bookmarks
- Application settings and preferences
- Work files
- Messages/chat history (if important)

**Optional (can backup):**

- Downloaded files (can be re-downloaded)
- Applications (can be reinstalled)
- System files (can be restored from OS installation)

Don't waste backup space on things you can easily replace. Focus on irreplaceable data.

### Common Mistakes

**Backing up to only one external drive and keeping it connected**
Drive can fail, get infected with malware, be stolen with computer. Not truly protected.

**Cloud-only backup**
Cloud services can shut down, lock your account, raise prices, lose data. Always have local backup too.

**Local-only backup**
Fire, flood, theft destroys local backups. Always have offsite backup.

**Never testing restores**
Backup appears to run successfully for years. When needed, files are corrupted or process is broken.

**Encrypting backup but losing encryption key**
Backup is useless if you can't decrypt it. Store encryption keys separately and securely.

**Backing up malware along with files**
If system is infected before backup, you're backing up infection. Keep multiple historical backups so you can restore from before infection.

### Quick Wins

- **10 minutes:** Plug in external drive and start first backup.
- **15 minutes:** Enable cloud backup for photos on phone.
- **30 minutes:** Document your backup system (what's backed up, where, how to restore).
- **20 minutes:** Test restoring one file from each backup location.

## 13. Cloud Under Control

Cloud storage is convenient. Access files from any device. Automatic sync. Offsite backup without effort.

But cloud storage means your data lives on someone else's computers. You're trusting them with everything.

### Benefits and Risks

**Benefits:**

- Automatic offsite backup
- Access from multiple devices
- Sharing files easily
- Protection from local hardware failure
- Often includes version history (restore old versions of files)

**Risks:**

- Service can lock your account (policy violation, payment issue, security concern)
- Service can shut down or change terms
- Data can be accessed by service employees (with or without your knowledge)
- Government can subpoena your data
- Account compromise gives attacker all your files
- Privacy policies change over time
- You're dependent on internet connection

Cloud storage is useful. But it's not under your complete control.

### **[RECOMMENDED]** How Not to Get Locked Out

Account lockouts happen. Sometimes legitimate (security concern), sometimes mistaken (algorithm false positive), sometimes unfair (policy dispute).

**Protection strategies:**

**Diversify cloud providers.**
Don't put all data with one provider. Use multiple services for different purposes. If one locks you out, you don't lose everything.

**Keep local copies.**
Cloud should be one backup, not the only copy. Sync or download important files to local storage regularly.

**Understand terms of service.**
Know what can get you locked out. Most services prohibit:

- Illegal content
- Copyright infringement
- Excessive sharing
- Violating local laws
- Suspicious automated activity

**Don't share account credentials.**
Multiple people using same account can trigger security locks.

**Enable 2FA.**
Protects account from compromise. But save recovery codes—if you lose 2FA device and don't have recovery codes, you're locked out.

**Pay for service if storing critical data.**
Free tier accounts are more likely to be flagged, limited, or terminated. Paid accounts get better support.

**Export data regularly.**
Use takeout/export features to download complete archive of your data periodically. Store locally.

**Keep documentation.**
Save confirmation emails, receipts, account numbers. If you need to contact support about lockout, you'll need proof of ownership.

### Encryption Before Upload

Cloud providers can read your files. Their employees can access them. Law enforcement can subpoena them.

**Client-side encryption** solves this.

You encrypt files on your device before uploading. Cloud service stores encrypted data. They can't read it. Only you have the encryption key.

**How it works:**

You install encryption software. It creates encrypted vault. You put files in vault. Vault automatically syncs to cloud in encrypted form.

If cloud provider is hacked, gets subpoenaed, or has rogue employee, they only see encrypted gibberish.

**Trade-offs:**

Pros:

- Complete privacy from cloud provider
- Protection from cloud breaches
- Peace of mind for sensitive data

Cons:

- Slightly more complex setup
- If you lose encryption key, data is permanently lost (cloud provider cannot recover it)
- Can't use cloud provider's web interface to preview files (must decrypt locally first)
- Slightly slower sync (encryption overhead)

**When to use:**

- Financial documents
- Medical records
- Legal documents
- Personal photos/videos you want completely private
- Any data you wouldn't want strangers to see

**When not necessary:**

- Data that's already public
- Data you need to access from web interface
- Data you're okay with provider seeing

### Limits and Costs: How Not to Overpay

Cloud storage seems free or cheap. Then you exceed limits and face unexpected costs.

**Common pricing models:**

**Free tier with limits:**
Usually 5-15 GB free. Enough for documents, insufficient for photos/videos.

**Subscription tiers:**
Pay monthly/yearly for more storage. Costs increase significantly at higher tiers.

**Pay-per-use:**
Charge based on storage amount and data transfer. Can become expensive fast if you store a lot or download frequently.

**Strategies to control costs:**

**Know your storage needs.**
Check current data size. Calculate annual growth. Choose tier accordingly.

**Use free tiers effectively.**
If you only need 10 GB, use free tier from reputable provider instead of paying.

**Separate cold vs hot data.**
Active files in premium cloud. Archives in cheaper/slower storage.

**Compress files before upload.**
Videos, photos, archives can often be compressed significantly.

**Delete old files.**
Don't pay to store things you no longer need. Audit cloud storage annually.

**Use multiple free accounts strategically.**
Create separate accounts for different purposes if acceptable under terms of service (many prohibit this).

**Compare providers.**
Prices vary widely. Shop around. Consider:

- Storage amount
- Number of devices
- Speed
- Privacy policy
- Additional features (version history, file sharing)

**Watch for automatic renewals.**
Annual subscriptions auto-renew at full price. Set reminders to review before renewal.

**Download and cancel if changing needs.**
If you no longer need cloud storage, download everything and cancel.

### Common Mistakes

**Storing only in cloud with no local backup**
Cloud is one backup, not the only one. Always maintain local copies.

**Uploading sensitive files without encryption**
Financial, medical, legal documents deserve encryption.

**Not reading privacy policy**
You might be granting provider rights to scan, analyze, or use your files.

**Sharing links without expiration or passwords**
Shared link becomes permanently accessible to anyone who has it. Set expiration dates and passwords for sensitive shares.

**Syncing everything automatically**
Not all files need cloud backup. Be selective. Saves space and money.

**Using work/school cloud account for personal files**
You lose access when you leave. Employer/school can see everything.

**Exceeding free tier without noticing**
Automatic upgrades to paid tier. Monitor storage usage.

### Quick Wins

- **10 minutes:** Review current cloud storage usage and delete old files.
- **15 minutes:** Enable 2FA on all cloud accounts.
- **20 minutes:** Export complete archive of data from primary cloud provider.
- **30 minutes:** Set up encrypted folder for sensitive documents.

## 14. Digitization: Analog World in the Computer

Old photos. Birth certificates. Contracts. Letters. Journals. Family records. Medical documents.

Paper degrades. Photos fade. Documents get lost in moves. Fires and floods destroy everything.

Digitization preserves these items and makes them accessible.

### **[RECOMMENDED]** Scanning Documents

**What to scan:**

**Critical documents (scan immediately):**

- Birth certificates, passports, ID cards
- Marriage certificates, divorce decrees
- Property deeds, titles
- Wills, powers of attorney
- Medical records, vaccination records
- Diplomas, certifications
- Tax returns (at least 7 years)
- Insurance policies

**Important documents (scan when convenient):**

- Receipts for major purchases (for warranty, insurance)
- Contracts and agreements
- Bank statements
- Utility bills (if needed for proof of address)

**Sentimental items (scan for preservation):**

- Old family photos
- Letters and cards
- Children's artwork
- Journals and diaries
- Newspapers and clippings

**Equipment:**

**Flatbed scanner:**
Best quality for photos and documents. Slow but precise.

**Document feeder scanner:**
Fast for multi-page documents. Lower quality than flatbed.

**Phone camera:**
Sufficient for basic document capture. Many scanning apps enhance quality.

**Professional scanning service:**
For large collections (thousands of photos) or delicate items.

### File Formats: PDF/A, JPEG, PNG

Different formats for different purposes.

**PDF (Portable Document Format):**
Best for: Documents with text, multi-page files

Use **PDF/A** variant for archival (designed for long-term preservation, embeds all fonts and images).

Pros: Universal compatibility, preserves layout, searchable if OCR applied
Cons: Larger file size than plain text

**JPEG (Joint Photographic Experts Group):**
Best for: Photos

Pros: Small file size, universal compatibility, good for images with many colors
Cons: Lossy compression (quality degrades with each save), not ideal for text

**PNG (Portable Network Graphics):**
Best for: Screenshots, images with text, graphics, images you'll edit

Pros: Lossless compression (no quality loss), supports transparency
Cons: Larger file size than JPEG

**TIFF (Tagged Image File Format):**
Best for: Archival of high-quality scans when file size isn't a concern

Pros: Lossless, very high quality, industry standard for archival
Cons: Very large files, not all devices can open

**Recommendation:**

- Documents (text): **PDF/A** (if available) or **PDF**
- Photos: **JPEG** for storage, **PNG** if you'll edit
- Archival masters: **TIFF** or **PNG**, then create **JPEG** versions for everyday use
- Multi-page documents: **PDF**

### Resolution and Quality: How Much Is Enough

**Resolution** is measured in DPI (dots per inch) or pixels.

**For documents with text:**

- Minimum: 300 DPI (readable, decent OCR)
- Better: 400-600 DPI (very clear, excellent OCR)
- Overkill: 1200+ DPI (unnecessarily large files unless scanning tiny print)

**For photos:**

- Minimum: 300 DPI or 2000+ pixels on longest side
- Better: 600 DPI or 4000+ pixels
- Professional: Original photo size at 1200+ DPI

**For color:**

- Documents: 24-bit color (millions of colors) or 8-bit grayscale if black and white
- Photos: 24-bit color minimum

**Balance quality and file size.**

Higher resolution = larger files = more storage needed = slower to open/transfer.

Scan important items at high quality. Scan routine documents at sufficient quality.

### OCR: Turning Scans into Searchable Text

OCR (Optical Character Recognition) analyzes scanned images and converts visible text into actual selectable, searchable text.

**Why OCR matters:**

Scanned PDF without OCR is just an image. You can't:

- Search for words
- Select and copy text
- Use screen readers (accessibility)

Scanned PDF with OCR contains invisible text layer. You can search, select, copy.

**When to use OCR:**

- Multi-page documents you'll want to search (contracts, manuals, books)
- Documents you might need to extract text from
- Archives where you want to find specific documents by searching contents

**When OCR isn't necessary:**

- Pure photographs
- Single-page items you'll identify by filename
- Handwritten documents (OCR often fails on handwriting)

**How to apply OCR:**

Many scanning apps and PDF software include OCR. Quality varies.

Scan document → run OCR → verify accuracy (especially for important documents) → save.

**Limitations:**

- Accuracy depends on print quality and scan quality
- Fails on handwriting, unusual fonts, poor contrast
- May misread numbers, special characters
- Multiple languages can confuse OCR

Proofread OCR results for important documents.

### Common Mistakes

**Scanning at too low resolution**
Can't read small text. Can't enlarge without pixelation. Defeats purpose of scanning.

**Scanning everything at maximum resolution**
Unnecessary file sizes. Slows down storage, backup, sharing.

**Deleting original after scanning once**
Scans can have errors. Keep original until you've verified scan quality. For truly irreplaceable items, keep originals even after scanning.

**Not organizing scans**
Folder named "scans" with 500 files named "scan001.jpg" is useless. Organize and rename (we'll cover this in next chapter).

**Not backing up scans**
You digitized to preserve. Back up the digital copies following 3-2-1 rule.

**Using phone camera without stabilization**
Blurry scans. Use tripod or scanning app that guides alignment.

**Scanning sensitive documents then sharing carelessly**
Scanned passport or bank statement contains same information as original. Protect digital copies.

### Quick Wins

- **30 minutes:** Scan all critical documents (ID, passport, insurance, medical records).
- **1 hour:** Scan important financial documents (tax returns, property documents).
- **Variable:** Start scanning family photos, a few each week.

## 15. File Organization: The Naming System

You have thousands of files. Documents, photos, downloads, work files, personal projects.

Without organization, you'll never find anything. You'll have duplicates. You'll lose important files in chaos.

**Good file organization is invisible when it works and catastrophic when it doesn't.**

### **[RECOMMENDED]** Folder Structure: Year/Category/Subcategory

Consistent folder structure makes files findable.

**Recommended hierarchy:**

```
Documents/
├── Personal/
│   ├── Financial/
│   │   └── YYYY/
│   ├── Medical/
│   ├── Legal/
│   └── Home/
├── Work/
│   ├── Projects/
│   │   ├── Project_A/
│   │   └── Project_B/
│   └── Admin/
├── Creative/
│   ├── Writing/
│   ├── Photos/
│   └── Art/
└── Reference/
    ├── Manuals/
    └── Articles/
```

**Key principles:**

**Broad to specific:**
Top level is broad categories (Personal, Work). Deeper levels are more specific.

**Year-based for time-sensitive items:**
Financial documents, tax records, work projects benefit from year folders.

**Topic-based for timeless items:**
Reference materials, creative work, photos by subject rather than date.

**Consistent depth:**
Don't nest too many levels. 3-4 levels deep maximum. Beyond that becomes confusing.

**Parallel structure:**
Similar items in similar locations. All financial documents under Financial, all medical under Medical.

**Adapt to your needs.**
Above is template. Modify for your life. Photographer might organize by shoot date. Writer by project. Student by semester and course.

### **[CRITICAL]** Naming Convention

Filenames should tell you what's inside without opening.

**Recommended format:**

```
YYYY-MM-DD_description_version.extension
```

**Examples:**

```
YYYY-MM-DD_contract_lease_apartment_final.pdf
YYYY-MM-DD_photo_family_christmas.jpg
YYYY-MM-DD_budget_YYYY_v2.xlsx
YYYY-MM-DD_receipt_laptop_purchase.pdf
```

**Why this format:**

**Date first (YYYY-MM-DD):**
Files sort chronologically automatically. Year-month-day ensures proper sorting (YYYY-01-15 comes before YYYY-02-01).

International standard. No confusion about date order (month/day vs day/month).

**Descriptive name:**
What is this file? Use clear, specific words. Separate words with underscores or hyphens.

Good: `contract_lease_apartment`
Bad: `document1`

**Version if applicable:**
For files you'll revise, add version number or status.

Examples: `_v1`, `_v2`, `_draft`, `_final`, `_revised`

**When dates aren't necessary:**

Some files are timeless:

- Reference documents: `manual_dishwasher_model123.pdf`
- Templates: `template_invoice.docx`
- Photos by subject: `photo_grandma_portrait.jpg`

Use dates when they add value (when was this created/received, which version is newest).

### How Not to Get Lost in Chaos in 10 Years

**Rules for sustainable organization:**

**One canonical location.**
Each file type has a home. Financial documents go in Financial folder, always. Don't scatter randomly.

**No "misc" or "other" folders.**
These become dumping grounds. If something doesn't fit, create proper category or reconsider if you need the file.

**No files on desktop.**
Desktop is workspace, not storage. Files on desktop get lost, forgotten, accidentally deleted.

**Regular maintenance.**
Set recurring reminder (quarterly or annually) to:

- Delete files you no longer need
- Move downloads to proper folders
- Consolidate duplicates
- Update folder structure if needs changed

**Document your system.**
Create a text file explaining your organization logic. Future you will thank you.

**Consistent habits.**
When you save a file, put it in the right place immediately. Don't plan to "organize later." You won't.

### Tagging and Metadata (Optional)

Some operating systems and apps support tags or metadata for additional organization.

**Tags:**
Keywords you assign to files. One file can have multiple tags.

Example: Photo might be tagged `family`, `vacation`, `YYYY`, `beach`

Useful when file could belong to multiple categories. Search by tag finds all related files.

**Metadata:**
Information embedded in file (author, creation date, location, camera settings for photos).

Can be useful for searching and filtering. But also privacy risk (we'll cover in next chapter).

**When to use:**

If your workflow benefits from finding files by multiple criteria, tags help.

If you use applications that support tag-based workflows (photo management, research), leverage them.

For most people, good folder structure and naming is sufficient. Tags add complexity.

### Common Mistakes

**No system at all**
Files scattered everywhere. Downloads folder with 5000 items. Desktop covered in files. Chaos.

**Overly complex system**
20-level deep folder nesting. Elaborate naming scheme nobody remembers. Spend more time organizing than working.

**Inconsistent naming**
Sometimes `YYYY-MM-DD`, sometimes `MM-DD-YYYY`, sometimes `Jan 15 YYYY`. Files don't sort properly.

**Spaces in filenames**
`My Important Document.pdf` can cause issues in command line tools, web servers, some software. Use underscores or hyphens: `My_Important_Document.pdf`

**Special characters in filenames**
Avoid: `/ \ : * ? " < > |`
These are forbidden or problematic on various systems.

**Filename too long**
Operating systems have filename length limits. Keep under 100 characters to be safe.

**Never reviewing or cleaning**
Organization systems decay over time. Regular maintenance keeps them functional.

### Quick Wins

- **30 minutes:** Create basic folder structure for your main file categories.
- **20 minutes:** Rename 10 most important files to follow naming convention.
- **15 minutes:** Clear desktop and downloads folder, move files to proper locations.
- **10 minutes:** Document your folder structure in a README file.

## 16. Metadata: Invisible Information in Files

Files contain more than you see.

### What's Hidden in a Photo

When you take a photo with your phone, the image file contains:

**EXIF data (Exchangeable Image File Format):**

- Date and time
- Camera make and model
- Camera settings (aperture, shutter speed, ISO)
- GPS coordinates (where photo was taken)
- Phone orientation
- Software version
- Sometimes: photographer name

**Why this matters:**

You share a photo online. Anyone who downloads it can see:

- Exact location of your home (if taken at home)
- When you're on vacation (date/time stamps show you're away)
- What device you use
- Patterns of your movements

This is not theoretical. People have been stalked, robbed, or harassed because metadata revealed their location.

### **[RECOMMENDED]** How to Remove Metadata Before Sharing

**When to remove metadata:**

- Photos shared publicly (social media, forums, dating apps)
- Photos that reveal location you want private (home, work, school)
- Documents shared with people who don't need to know who created them or when
- Any file where metadata could compromise privacy or security

**When metadata is useful:**

- Personal photo archives (helps you remember when/where)
- Professional photography (proves authorship, shows camera settings)
- Legal documents (proves creation date, author)

**How to remove metadata:**

**Built-in OS tools:**
Many operating systems let you view and remove properties/metadata in file properties dialog.

**Dedicated tools:**
Software exists specifically for stripping metadata from images and documents.

**Export/re-save:**
Some apps let you export "clean" version without metadata.

**Screenshots:**
Taking screenshot of photo removes original metadata (but creates new metadata). Not ideal but works in a pinch.

**Social media platforms:**
Most strip metadata when you upload. But don't rely on this—strip it yourself before uploading to be certain.

**Process:**

1. Make a copy of original file (preserve original with metadata for your archive)
2. Remove metadata from copy
3. Verify metadata is removed
4. Share the cleaned copy

### Tools and Methods

**Manual inspection:**
Right-click file → Properties (Windows) or Get Info (Mac) → Details tab shows metadata.

**Batch processing:**
If you have many files, use tools that can strip metadata from multiple files at once.

**Command-line tools:**
Advanced users can script metadata removal for automation.

**Online tools:**
Websites that strip metadata. Convenient but means uploading your file to unknown server. Not recommended for sensitive files.

### When Metadata Is Useful vs Risky

**Useful:**

**Personal archive:**
Knowing when and where family photos were taken helps organize and remember.

**Work files:**
Author, creation date, edit history helps track document versions.

**Evidence:**
Metadata can prove when something was created or by whom (useful in legal, copyright, or verification contexts).

**Photography:**
Camera settings help you learn and improve. Geotags help you remember locations.

**Risky:**

**Public sharing:**
Don't reveal your home location, patterns, or device info to strangers.

**Sensitive documents:**
Metadata might reveal you created a document you want to remain anonymous about (whistleblowing, activism).

**Hiding mistakes:**
Document metadata might show it was created at time you claimed to be doing something else.

**Professional context:**
Metadata might reveal document was created using pirated software, or edited many times when you claimed it was quick work.

### Common Mistakes

**Never checking metadata before sharing**
Most people don't even know metadata exists. They share photos with full location history.

**Relying on platform to strip metadata**
Some platforms do, some don't, some do it inconsistently. Strip it yourself to be certain.

**Removing metadata from originals**
Keep original with metadata for your records. Remove from copies you share.

**Not verifying removal worked**
Some tools fail or only remove some metadata. Check after stripping to confirm.

**Metadata in documents overlooked**
Everyone thinks about photo metadata. Fewer think about author names, revision history, and hidden data in documents.

### Quick Wins

- **5 minutes:** Check metadata of a photo on your phone.
- **10 minutes:** Find and install metadata removal tool for your platform.
- **15 minutes:** Strip metadata from photos before posting online (retroactively for recent posts if possible).

## 17. File Formats: What Will Survive Decades

You save a document today. Will you be able to open it in 20 years?

### Open vs Closed Formats

**Open formats:**
Specification is public. Anyone can create software to read and write the format. Not controlled by single company.

Examples:

- Plain text (. txt)
- PDF (though PDF/A specifically designed for archival)
- PNG, JPEG
- HTML
- ODF (Open Document Format)

**Closed/Proprietary formats:**
Specification is secret or controlled by one company. Only their software (or licensed software) can properly handle the format.

Examples:

- Certain word processor formats
- Specialized database formats
- Proprietary image formats
- Application-specific project files

**Why this matters for archival:**

Company that controls proprietary format can:

- Discontinue support
- Go out of business
- Change format in incompatible ways
- Require ongoing subscription to access files

Open formats are more likely to remain accessible long-term. If one program stops supporting it, others can.

### **[RECOMMENDED]** Why JPEG/PNG/PDF Better Than Others for Long-Term Storage

**For photos:**

**JPEG:**
Universal support. Every device and program can open JPEG. Will remain openable for decades.

Drawback: Lossy compression. Each time you edit and re-save, quality degrades. For archival, save original and never re-save JPEG.

**PNG:**
Lossless. Edit and save without quality loss. Universal support.

Drawback: Larger file sizes than JPEG.

**Recommendation:** Archive important photos as PNG or TIFF. Create JPEG copies for sharing and everyday use.

**For documents:**

**PDF/A:**
PDF subformat specifically designed for archival. Embeds fonts, images, everything needed to display document identically on any system forever.

Widely supported. Open standard.

**Plain text (.txt):**
Ultimate in longevity. Human-readable. Can be opened on any computer ever made.

Drawback: No formatting, images, or layout.

Use for: notes, logs, data you want guaranteed accessibility.

**For data/spreadsheets:**

**CSV (Comma-Separated Values):**
Plain text format for tabular data. Universal, simple, will work forever.

Drawback: No formulas, formatting, multiple sheets.

**Recommendation:** Export important spreadsheets to CSV in addition to native format.

**For archives:**

**ZIP:**
Universal compression format. Supported everywhere.

Drawback: No error correction. If ZIP file corrupts, you may lose everything.

**Recommendation:** Keep both compressed and uncompressed copies for critical data.

### Formats to Avoid for Archival

**Proprietary formats tied to specific software:**
If software is discontinued, files become unreadable.

**Obscure formats:**
Even if open, if nobody uses it, future software won't support it.

**Heavily compressed or encrypted formats without documentation:**
If you lose the key or algorithm changes, data is gone.

**Formats dependent on cloud services:**
Files that only work when uploaded to specific online platform.

### Converting Files Before Archiving

If you have important files in risky formats, convert to open, stable formats.

**Process:**

1. Identify files in proprietary or obscure formats
2. Open in original software while you still can
3. Export/Save As to open format
4. Verify converted file is complete and correct
5. Keep both original and converted version
6. Document what software/version was used for original (in case you ever need to reference)

**Examples:**

- Proprietary word processor → PDF/A or plain text
- Proprietary spreadsheet → CSV (for data) + PDF (for formatted reports)
- Proprietary image format → PNG or TIFF
- Proprietary video format → MP4 (widely supported)

**Don't delete originals immediately.**
Keep original format for some time in case conversion missed something.

### How to Read Old Formats

You find old files from 20 years ago. Format is obsolete. Software doesn't exist anymore.

**Strategies:**

**Find old software:**
Archived versions of old software sometimes available. Run in virtual machine if modern OS doesn't support it.

**Format converters:**
Tools exist specifically to convert ancient formats to modern ones.

**Emulation:**
Run old operating system in emulator with old software to open files, then export to modern format.

**Data recovery services:**
For truly critical files, professional services can sometimes extract data from obsolete formats.

**Physical media:**
Old floppy disks, CDs, Zip disks need working hardware. USB drives exist that can read these formats. Act before the hardware becomes completely unavailable.

**Prevention is easier than recovery.**
Migrate files to current formats every few years. Don't wait until format is so old that migration is nearly impossible.

### Common Mistakes

**Saving everything in latest trendy format**
New formats are risky. They might not have long-term support. Stick with established, widely-used formats for archival.

**Compressing archives too aggressively**
Exotic compression formats may not be readable in future. Use common formats (ZIP, gzip).

**Encrypting archives and losing key**
Encrypted archive without key is useless. If encrypting, have robust key management and backup.

**Never migrating old files to new formats**
Files sit untouched for 20 years in obsolete format. When you finally need them, unreadable.

**Trusting cloud service to preserve format**
Service might convert your files without telling you, potentially losing quality or features.

**Deleting originals after conversion without verifying**
Conversion might have errors. Keep originals until you've thoroughly verified conversions.

### Quick Wins

- **15 minutes:** Identify your most important documents and verify they're in archival-friendly formats.
- **30 minutes:** Convert critical documents to PDF/A if they're in proprietary formats.
- **20 minutes:** Export important spreadsheets to CSV as backup.
- **1 hour:** Go through old files from 5+ years ago, convert any in risky formats.

_Your data is your legacy. Organize it, protect it, preserve it. Future you will be grateful._

---

[← Back to Protocol Zero README](README.md)
