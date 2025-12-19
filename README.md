📧 Mail Extractor Pro

Mail Extractor Pro is a modern Windows desktop application for extracting, analyzing, verifying, and managing email data efficiently. Built with .NET 8.0 and WinUI 3, it delivers high performance with a clean, modern user interface.

🚀 Features

Email Extraction
Extract email addresses from text-based files using advanced parsing logic.

Data Visualization
View extracted emails in a sortable, searchable, and responsive data grid.

Email Verification
Check email validity and deliverability.

DNS & MX Lookup
Verify domain DNS and mail exchange records.

Statistics & Analytics
Analyze total emails, unique domains, and distribution insights.

Export Options
Export data to:

TXT

CSV

Excel (.xlsx)

Word (.docx)

Modern UI
WinUI 3 interface with dark mode support.

Secure License System
Online license activation and periodic verification.

Performance Optimized
Handles large datasets efficiently.

🖥 System Requirements

Minimum

Windows 10 (version 1809+) or Windows 11

4 GB RAM (8 GB recommended)

500 MB free disk space

1280×720 display

Recommended

Windows 11

8 GB+ RAM

1920×1080 display

Internet connection required for:

License activation

License re-verification

Email & DNS verification

📦 Installation
End Users (MSIX)

Download the .msix package

Double-click to install

Launch Mail Extractor Pro from Start Menu

Activate using your license key

The MSIX package includes all required dependencies, including .NET 8.0.

Developers (Source Code)

Requirements

Visual Studio 2022 (17.x or later)

.NET Desktop Development workload

Windows App SDK workload

Steps

git clone https://github.com/Alpha-xp5-ai/Mail-Extractor-Pro.git


Open Mail Extractor.sln

Restore NuGet packages

Configure LicenseConfig.cs

Build and run (F5)

⚙ Configuration (License)

Edit LicenseConfig.cs:

public static class LicenseConfig
{
    public static readonly bool RequireLicense = true;
    public static readonly string ProductName = "Mail Extractor Pro";
    public static readonly string SupportEmail = "support@yourcompany.com";
}


License verification is performed online and securely stored locally.

🔐 Privacy & Security

All file processing is local

No background data collection

No advertising or tracking

Internet usage limited to verification services only

See full privacy policy in the Microsoft Store listing.

🛠 Tech Stack

Framework: .NET 8.0

UI: WinUI 3

Packaging: MSIX

Platform: Windows 10 / 11

📄 License

This project is distributed as a commercial application.
Unauthorized redistribution or resale is prohibited.

📬 Support

Email: support@yourcompany.com

Platform: Microsoft Store

GitHub: https://github.com/Alpha-xp5-ai

🔮 Roadmap

Support for CSV & Excel input files

Batch email verification

Advanced filtering rules

API integration support

If you want next:

README badges (Store, .NET, WinUI)

A short README for CodeCanyon

GitHub release notes template

Store description optimized from this README

Just say the word.
