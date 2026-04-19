# Awesome Email Deliverability [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of tools, resources, and best practices for email deliverability, authentication, and inbox placement testing.

## Contents

- [Inbox Placement Testing](#inbox-placement-testing)
- [Authentication & DNS](#authentication--dns)
- [Blacklist Monitoring](#blacklist-monitoring)
- [DMARC Monitoring](#dmarc-monitoring)
- [Warm-up & Reputation](#warm-up--reputation)
- [Email Validation & Verification](#email-validation--verification)
- [Spam Score Testing](#spam-score-testing)
- [Outreach Platforms](#outreach-platforms)
- [Learning Resources](#learning-resources)
- [RFCs & Standards](#rfcs--standards)

## Inbox Placement Testing

Tools that test where your email actually lands — Inbox, Spam, or Promotions.

- [Inbox Placement Test](https://check.live-direct-marketing.online/) — Free seed-based inbox placement test across Gmail, Outlook, Yahoo, Mail.ru, and Yandex. Live results via SSE. No signup required. REST API available.
- [GlockApps](https://glockapps.com/) — Comprehensive inbox placement testing with per-provider reports. 2 free tests, paid plans from $59/month.
- [Litmus](https://www.litmus.com/) — Email testing and analytics platform with spam filter testing. Primarily paid.
- [Email on Acid](https://www.emailonacid.com/) — Email previewing and deliverability testing across clients and devices.

## Authentication & DNS

Tools for checking and validating SPF, DKIM, DMARC, and DNS configuration.

- [MXToolbox](https://mxtoolbox.com/) — Industry standard for MX, SPF, DKIM, DMARC lookups, blacklist checks, and SMTP diagnostics.
- [DKIM Validator](https://dkimvalidator.com/) — Send an email and get a full authentication report including DKIM, SPF, and SpamAssassin score.
- [Mail-Tester](https://www.mail-tester.com/) — Send an email to a unique address, get a spam score (1-10) with SPF/DKIM/DMARC analysis. 3 free tests/day.
- [Google Admin Toolbox](https://toolbox.googleapps.com/apps/checkmx/) — Check MX records and DNS configuration for Gmail deliverability.
- [DMARC Analyzer](https://www.dmarcanalyzer.com/) — DMARC record validation and reporting.
- [SPF Record Checker](https://www.kitterman.com/spf/validate.html) — Validate SPF records for syntax and DNS lookup limits.

## Blacklist Monitoring

- [MXToolbox Blacklist Check](https://mxtoolbox.com/blacklists.aspx) — Check your IP/domain against 100+ blacklists.
- [MultiRBL](http://multirbl.valli.org/) — Check your IP against 300+ DNSBLs simultaneously.
- [Spamhaus](https://check.spamhaus.org/) — Check if your IP or domain is listed on Spamhaus blocklists.
- [Barracuda Lookup](https://www.barracudacentral.org/lookups) — Check Barracuda reputation.

## DMARC Monitoring

- [Postmark DMARC](https://dmarc.postmarkapp.com/) — Free DMARC monitoring with weekly digest reports.
- [DMARC Report](https://dmarc.report/) — Free DMARC aggregate report analyzer.
- [Valimail](https://www.valimail.com/) — Enterprise DMARC enforcement and monitoring.
- [Agari](https://www.agari.com/) — Advanced email authentication and DMARC management.

## Warm-up & Reputation

- [Google Postmaster Tools](https://postmaster.google.com/) — Free. Monitor your domain/IP reputation, spam rate, and authentication with Gmail.
- [Microsoft SNDS](https://sendersupport.olc.protection.outlook.com/snds/) — Smart Network Data Services. Monitor reputation with Outlook/Hotmail.
- [Sender Score](https://senderscore.org/) — Check your IP sending reputation (score 0-100).
- [Talos Intelligence](https://talosintelligence.com/reputation_center) — Cisco's IP/domain reputation lookup.

## Email Validation & Verification

- [Hunter.io Email Verifier](https://hunter.io/email-verifier) — Verify individual email addresses. Free tier available.
- [ZeroBounce](https://www.zerobounce.net/) — Bulk email validation with spam trap detection.
- [NeverBounce](https://neverbounce.com/) — Real-time email verification API.
- [Reoon Email Verifier](https://www.reoon.com/) — Bulk email verification with high accuracy.
- [Bouncer](https://www.usebouncer.com/) — Email verification with toxicity checks.

## Spam Score Testing

- [Mail-Tester](https://www.mail-tester.com/) — Spam score from 1-10 with detailed breakdown. 3 free tests/day.
- [Postmark Spam Check](https://spamcheck.postmarkapp.com/) — Free SpamAssassin check — paste your email content and get a score.
- [IsNotSpam](https://isnotspam.com/) — Send test email, get SPF/DKIM/DMARC and SpamAssassin results.

## Outreach Platforms

Platforms with built-in deliverability management.

- [LDM Platform](https://live-direct-marketing.online/) — B2B outreach platform with warm-up, account rotation, SPF/DKIM/DMARC management, and 85%+ inbox placement.
- [Lemlist](https://www.lemlist.com/) — Cold email platform with built-in warm-up.
- [Instantly.ai](https://instantly.ai/) — Cold email infrastructure with unlimited warm-up.
- [Smartlead](https://www.smartlead.ai/) — Cold email with auto-rotation and warm-up.
- [Woodpecker](https://woodpecker.co/) — Cold email for B2B with deliverability monitoring.

## Learning Resources

### Articles

- [Google Bulk Sender Guidelines](https://support.google.com/a/answer/81126) — Google's official requirements for bulk senders (updated 2024).
- [Yahoo Sender Requirements](https://senders.yahooinc.com/best-practices/) — Yahoo/AOL sender authentication requirements.
- [RFC 7489 — DMARC](https://datatracker.ietf.org/doc/html/rfc7489) — The DMARC specification.
- [M3AAWG Best Practices](https://www.m3aawg.org/published-documents) — Messaging, Malware and Mobile Anti-Abuse Working Group best practices.

### Guides

- [Email Authentication Explained](https://postmarkapp.com/guides/email-authentication-spf-dkim-dmarc) — Postmark's comprehensive guide to SPF, DKIM, and DMARC.
- [Deliverability Guide by Mailtrap](https://mailtrap.io/blog/email-deliverability/) — Comprehensive deliverability overview.

## RFCs & Standards

- [RFC 5321](https://datatracker.ietf.org/doc/html/rfc5321) — Simple Mail Transfer Protocol (SMTP)
- [RFC 7208](https://datatracker.ietf.org/doc/html/rfc7208) — Sender Policy Framework (SPF)
- [RFC 6376](https://datatracker.ietf.org/doc/html/rfc6376) — DomainKeys Identified Mail (DKIM)
- [RFC 7489](https://datatracker.ietf.org/doc/html/rfc7489) — Domain-based Message Authentication, Reporting, and Conformance (DMARC)
- [RFC 8461](https://datatracker.ietf.org/doc/html/rfc8461) — SMTP MTA Strict Transport Security (MTA-STS)
- [RFC 8460](https://datatracker.ietf.org/doc/html/rfc8460) — SMTP TLS Reporting (TLSRPT)

## Contributing

Contributions welcome! Please read the [contributing guidelines](CONTRIBUTING.md) first.

If you know of a tool or resource that should be on this list, please open a pull request.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
