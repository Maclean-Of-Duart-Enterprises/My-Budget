# My-Budget
A multi purpose local only feature full budget app 
# My Budget

**My Budget** is a privacy-first, open-source Android budgeting and personal finance application designed to keep financial data entirely on your device.

It combines transaction management, receipt and bank-statement OCR, customizable budgets, reports, multiple bank accounts, and an offline learning agent without requiring an Internet connection, cloud account, subscription, or external AI service.

## Features

- Income and expense tracking
- Fully customizable income and expense categories
- Single and bulk transaction editing and management
- Multiple bank-account support
- Receipt and paystub scanning from photos and PDFs
- Bank-statement import from images and PDFs
- Multi-file document importing
- On-device multilingual OCR
- Review and edit extracted transactions before importing
- Duplicate transaction detection
- Internal-transfer detection and exclusion
- Encrypted financial-document storage
- Attach receipts, paystubs, and statements to transactions
- Searchable and sortable transaction history
- Weekly and monthly budgeting
- Separate manual and automatically generated budgets
- Category-specific budgets and reports
- Offline adaptive budgeting agent based on transaction history
- Income, spending, savings, recurring-charge, and spending-trend analysis
- Weekly and monthly financial reports
- Previous-period comparisons
- PDF report generation
- PDF and CSV transaction exports
- Customizable first day of the week
- English, Russian, Ukrainian, Kazakh, and Spanish interfaces
- Multilingual financial-document recognition
- Configurable app passcode and automatic locking
- Custom backgrounds and photos
- Adjustable colors, opacity, and text size
- Avatar support
- Storage and cache management
- Complete local-data deletion

## Privacy

My Budget is designed for **offline operation**.

The application requests no Internet or network-state permission. Financial records, budgets, OCR results, reports, receipts, paystubs, and bank statements remain on the Android device.

Imported financial documents are encrypted in private application storage using Android Keystore-backed AES-GCM encryption.

The budgeting agent operates locally and does not transmit financial information to a cloud AI service.

## Local Budgeting Agent

My Budget includes an explainable local learning system that analyzes transaction history to:

- Estimate weekly and monthly category limits
- Analyze income and expenses
- Identify spending trends
- Detect likely recurring expenses
- Suggest savings targets
- Account for essential and discretionary spending
- Combine transaction history across bank accounts
- Exclude detected internal transfers
- Flag unusually large transactions for review

It operates entirely on-device without API keys or subscriptions.

## Application Information

**Version:** 1.7.2  
**Package:** `com.macleanofduartenterprises.mybudget`  
**Minimum Android:** Android 8.0  
**Developer:** Maclean Of Duart Enterprises

## License

My Budget is free and open-source software licensed under the **GNU Affero General Public License v3.0 (AGPL-3.0-only)**.

The complete AGPLv3 license is included with the source and is available offline inside the application under:

**Settings → License**

Copyright © 2026 Maclean Of Duart Enterprises.
