# Scratch Pad - A Healthcare-Focused Word Processor

A dual-mode word processor designed specifically for healthcare environments, offering both fast general-purpose editing and secure encrypted document handling.

## 🏥 Perfect for Healthcare Environments

> Scratch Pad is intuitive enough for anyone — from the front desk to clinical staff. A custom word processor designed for everyday workflow, with an option of privacy-first features ready if you need them.
> 
## 🚀 Getting Started
1. Download the latest release
2. Launch SecureWord (no admin rights required)
3. Configure settings as needed

Version 1.0.0b — Friends & Family Edition
Absolutely free to use — no telemetry, no data mining, no annoying ads, and zero tracking. We handpicked third-party libraries with privacy in mind, but hey, don’t just take our word for it—feel free to audit away. 🗽🦅

## 🆕 Current Features

### General Mode (*Mostly Ready Now)
- **Modern Dark UI** with MaterialDesign styling and opacity toggle
- **Multiple File Formats** - .txt, .rtf, .md, .docx support
- **Smart Features** - Auto-save, spell check, find/replace, undo/redo
- **Print Support** with proper formatting
- **Recent Files** management
- **Customizable Settings** - fonts, word wrap, opacity, auto-save intervals
- **No Telemetry** - completely private, local-only operation
- **Password-Protected Access** - secure login to encrypted documents
- **AES File Encryption** - military-grade encryption for sensitive documents saved as a custom *.secx format
- **Visual Security Indicators** - clear UI showing when in secure mode
- **File Integrity Verification** - ensures documents haven't been tampered with

## 🎯 Target Use Cases
### Healthcare Administration
- **HR Documents** - Employee reviews, disciplinary actions, salary negotiations
- **Financial Planning** - Budget discussions, cost analysis, vendor negotiations
- **Internal Communications** - Sensitive memos, policy drafts, meeting notes
- **Compliance Documentation** - Internal audits, process improvements
- **Vendor Contracts** - Negotiations, terms discussions, pricing analysis

## 🗝️ Key Benefits
- ✅ **HIPAA-Adjacent Compliance** (for non-ePHI administrative documents)
- ✅ **Zero Vendor Lock-in** - all files stored locally
- ✅ **No Subscription Fees** - one-time purchase, no ongoing costs
- ✅ **Privacy-First Design** - no analytics, no cloud dependencies
- ✅ **IT-Friendly** - minimal installation, no network requirements

## 🏗️ Architecture Overview
### Current Stack
- **Framework:** WPF with .NET 6 LTS
- **UI Library:** MaterialDesignInXamlToolkit
- **Pattern:** MVVM with CommunityToolkit.Mvvm
- **File Handling:** DocumentFormat.OpenXml for .docx support
### Security Stack
- **Encryption:** AES-256-GCM for authenticated encryption
- **Key Derivation:** PBKDF2 with high iteration count
- **File Format:** Custom binary format with encrypted content + metadata
### Security Best Practices
- **No Key Storage** - Passwords never stored, only derived keys in memory
- **Secure Memory** - Sensitive data cleared from memory after use

### System Requirements
- Windows 10/11
- .NET 6 Runtime
- 50MB disk space
- 512MB RAM minimum
