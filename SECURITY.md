# Security Policy

## Overview

Study Tracker is a **client-side only** HTML application. It runs entirely in your browser with no server, no database, and no user accounts.

## What Data is Stored

| Data | Where | Notes |
|------|-------|-------|
| Chapter progress | Browser `localStorage` | Stays on your device only |
| AI API keys | Browser `localStorage` | Stays on your device only |
| Chat history | Browser memory (RAM) | Cleared when you close the tab |

**No data is ever sent to our servers** because there are no servers. Your API keys go directly from your browser to the AI provider (Google, Groq, etc.).

## Reporting a Vulnerability

If you find a security issue (e.g. XSS vulnerability, API key exposure risk), please:

1. **Do NOT open a public issue**
2. Contact the maintainer directly by opening a **private** issue or reaching out via the social links in the README

Please include:
- Description of the vulnerability
- Steps to reproduce
- Potential impact

We'll respond within 72 hours and credit you in the fix.

## Supported Versions

| Version | Supported |
|---------|-----------|
| Latest  | ✅ Yes |
| Older   | ❌ Please update to latest |

## Responsible Disclosure

We appreciate responsible disclosure. Please give us a reasonable amount of time to fix the issue before making it public.
