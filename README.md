# Bookeeper - AI Receipt Scanner and Expense Approval System

Bookeeper is an AI receipt scanner and expense approval system sold as source code by Coderobotics. It is built with PHP 8.2, Laravel 12, Livewire 3, Alpine.js, Tailwind CSS v4 and MySQL. Employees upload PDF, JPG or PNG receipts up to 10 MB, or take photos of them. Google Gemini AI, with OCR.space and Tesseract as fallbacks, reads the vendor, date, amount and tax, suggests a category and gives a confidence score. Every expense goes to an administrator, who reviews it next to the original receipt and then approves it, rejects it with a reason or requests more evidence. The system flags duplicate receipts and records every change in a full audit trail. Reports by category, employee, status and month export to CSV, Excel or PDF. Bookeeper installs as a Progressive Web App on phones and desktops and can capture receipts offline. It uses role-based access, private file storage and admin-created accounts. It suits small businesses, accounting firms, startups and finance teams that want to replace paper receipts and spreadsheets. The one-time purchase includes the complete unencrypted source code, one year of free updates and one year of email support.

<img src="https://www.coderobotics.com/frontend/assets/icon/bookeeper-php-software-source-code.jpg">

Paper receipts get lost, spreadsheets go out of date, and checking every expense by hand takes hours. Bookeeper fixes this. An employee uploads or photographs a receipt, the AI reads it in about a minute, and the administrator reviews it next to the original before approving. Approved expenses go straight into the ledger and into reports for accounting.

What You Get
 
Automatic receipt extraction: AI and OCR read the vendor, date, amount and tax, and suggest a category. Google Gemini is the main reader, with OCR.space and Tesseract as fallbacks.
Confidence scoring: each receipt gets a confidence score, and fields the AI is unsure about are highlighted for review.
Upload or snap: PDF, JPG and PNG files up to 10 MB each. Several receipts can be uploaded at once, and each one becomes its own expense.
Four-step approval workflow: Upload ? AI reads it ? Admin reviews ? Done & reported.
Status tracking: every expense shows where it stands: Processing, Pending, Evidence Requested, Evidence Submitted or Approved.
Evidence requests: admins can ask for more detail, and employees reply with notes and extra documents for as many rounds as needed.
Duplicate warnings: a file uploaded twice, or a receipt with the same vendor, date and amount, is flagged automatically.
Side-by-side review: admins see the receipt next to the extracted data, then approve, reject with a reason, or request evidence.
Bulk approval: admins can approve several expenses at once and move straight to the next item.
Reports & exports: reports by category, employee, status and month, plus an approved ledger, exported to CSV, Excel or PDF.
Full audit trail: every edit, approval and rejection is recorded with who made it, when, and the old and new values.
Progressive Web App (PWA): install it on a phone or desktop, capture receipts with the camera, and keep snapping offline. Photos upload when the device is back online.
Employee portal: employees track every expense in real time, get notified when they need to reply, and can view and download their own receipts.
Admin controls: manage employee logins and expense categories, set the AI/OCR keys (stored encrypted), and get a daily email digest.
Secure by design: no public sign-up, role-based access, private file storage, forced change of temporary passwords, and blocking after repeated failed logins.

Why This Tool?
 
Most expense tools are either too complex for small teams or too basic to trust. Bookeeper is simple for employees and gives admins full control:

AI does the data entry, and a person checks every expense before approval.
Employees can’t edit their expenses after upload, so the ledger stays trustworthy.
Evidence requests replace long email threads about missing receipts.
Free AI/OCR providers keep running costs low.
It works like a native app on any phone without an app store.
It comes with 99 automated tests covering auth, roles, uploads, extraction, workflow, reports and audit.

Perfect For
 
Small and medium businesses managing employee expense claims
Accounting and bookkeeping firms handling receipts for clients
Startups and agencies replacing spreadsheet-based expense tracking
Field, sales and travel teams who need to capture receipts on the go
Finance and HR departments that need an approval workflow and audit log
Developers building a SaaS expense management product

Tech Stack
 
PHP 8.2+
Laravel 12
Livewire 3
Alpine.js
Tailwind CSS v4
Vite
MySQL / MariaDB
Google Gemini AI (primary receipt reader)
OCR.space API and Tesseract OCR (fallbacks)
Laravel DomPDF (PDF exports)
Laravel Excel (CSV/Excel exports)
Intervention Image
Spatie Laravel Activitylog (audit trail)
Pest (automated testing)
PWA (Service Worker + Web App Manifest, offline upload queue)

Prerequisites
 
PHP 8.2 or higher
Composer
Node.js & npm
MySQL or MariaDB
A free Google Gemini API key and/or OCR.space API key (Tesseract optional)
A queue worker (php artisan queue:work) for receipt extraction and emails
A scheduler (php artisan schedule:work) for the admin daily digest (optional)

More details and download link:
https://www.coderobotics.com/product/ai-receipt-scanner-and-expense-approval-system
