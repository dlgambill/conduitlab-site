# CONDUIT LAB -- MASTER INDEX
Last Updated: April 11, 2026

## Business Overview
- Company: Conduit Lab LLC, Kansas City, Missouri
- Founder: Danny Gambill
- Mission: Build and launch AI-powered SaaS tools for underserved professional niches

## Active Product: ClauseCheck
- Status: FULLY LIVE at https://clausecheck.conduitlab.ai
- What it does: AI contract review for solo attorneys and small law firms
- Modes: Standard Review (generic AI analysis) + Playbook Review (structured clause-by-clause analysis)
- Playbook contract types: NDA, Employment Agreement, Vendor/Services Agreement, Commercial Lease, IC Agreement
- Pricing: Standard $20/month (LIVE -- real payments active)
- Pro: Coming soon at $49/month
- Trial: 5-day free trial, no credit card required
- Infrastructure: Railway (frontend), Cloudflare Worker (backend), Supabase, Resend, PostHog, Stripe live mode
- OCR: iLovePDF integration for scanned PDFs (added April 10, 2026)

## Current Sprint Goal
Get the first 10 paying customers on the Standard plan.

## Go-To-Market Status
- Apollo.io prospect list: 500 solo attorneys built and active
- Cold email sequence: 3-email sequence running, 40+ emails sent as of April 10, 2026
- Sender: outreach@conduitlab.ai
- Sequencer: Apollo.io built-in sequences
- Social media: Accounts to be created -- LinkedIn, X/Twitter, Reddit (u/ConduitDanny), Facebook, Instagram

## SMIT (Single Most Important Task)
Monitor cold email replies and convert first trial signups to paying customers.
Create social media accounts and add credentials to Sovereign OS .env.

## Target Customer
- Solo attorneys and firms with 2-5 attorneys
- Job titles: Attorney, Lawyer, Partner, Associate
- Industry: Legal Services, United States
- Pain point: Contract review is slow and expensive. ClauseCheck does it in 60 seconds for $20/month.

## Competitive Positioning
- goHeather: $99+/month
- Spellbook: $179/user/month
- Harvey: $100-400/user/month
- ClauseCheck: $20/month

## Completed Milestones
- ClauseCheck Standard fully built and live
- Stripe live mode active (Standard and Pro price IDs configured)
- Transactional email via Resend (confirmation, trial warning, payment receipt)
- PostHog analytics on all pages
- Dashboard, terms, privacy pages complete
- iLovePDF OCR for scanned PDFs (Worker v4.1)
- conduitlab.ai landing page built (ready to deploy)
- Sovereign OS v3.0 running autonomously via Windows Task Scheduler at 9:00 AM daily
- Apollo prospect list of 500 attorneys built
- Cold email sequence launched

## Social Media Accounts
- LinkedIn: (not created yet)
- X/Twitter: (not created yet)
- Reddit: (not created yet) -- use personal account u/ConduitDanny
- Facebook: (not created yet)
- Instagram: (not created yet)

## Next Steps (Prioritized)
1. Create 5 social media accounts using SOCIAL_PROFILES.md
2. Add social credentials to X:\Sovereign_OS\.env
3. Set up Gmail App Password for Sovereign approval polling
4. Deploy conduitlab.ai landing page to Railway
5. Start Twilio A2P 10DLC registration (background task)
6. Add PostHog and Apollo API keys to Sovereign .env for real metrics
7. Build Pro tier features (The Vault, unlimited length, Claude Sonnet)
8. Med Mal Chronology Tool -- after ClauseCheck hits 10 paying customers
9. 3D Printing Business -- future Sovereign OS project
