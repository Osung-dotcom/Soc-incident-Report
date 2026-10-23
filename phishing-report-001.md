# SOC Incident Report 001 - Phishing

**Analyst:** Osung (Lagos SOC)
**Date:** 2026-10-23
**Severity:** High
**Status:** Closed

## Summary
Phishing email pretending to be Microsoft 365. Link leads to fake login.

## IoCs
- Sender: security@micros0ft-verify.com
- Fake URL: micros0ft-verify-login.com
- Subject: Your Account Will Be Disabled

## Actions
1. Blocked domain at gateway
2. Blocked URL at firewall
3. No user clicked - safe
4. Reported to L2

## Recommendation
Enable MFA and user training.
