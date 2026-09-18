# white label ai sdr: How Agencies Resell AI Appointment Setters Under Their Own Brand — Pricing, Margins, and Setup

Selling AI as an agency has a predictable failure mode. A client buys "AI lead qualification," the agent invents a discount that doesn't exist, or the API bill lands higher than the retainer. The demo was great. The monthly margin wasn't.

That's the gap a white label AI SDR is supposed to close: you sell the outcome under your logo, the software stays unseen, and the markup is yours. The catch is that "white label" gets used loosely. Some platforms mean you can rename the dashboard. Others mean clients can log in through your domain, pay you through your own Stripe account, and never see the vendor's name at all. Those are very different products with very different margins.

CloseBot sits in the second category, and it's worth looking at closely because its agency plan is built specifically around reselling rather than around your own pipeline. Below is what the term actually covers, what the current plans cost, where the money really comes from, and where this model breaks.

## What "white label AI SDR" actually means

Most buyers searching this term are trying to answer one question: can I sell this under my brand without the client seeing where it comes from?

There are three layers of white labeling, and vendors blur them constantly:

- **Cosmetic.** Your logo replaces theirs on the login screen. Clients still see the vendor's domain, emails, and footer.
- **Portal-level.** Clients log in through a domain you control, with your colors and branding, and see metrics scoped to their own account only.
- **Commercial.** Clients pay you, not the vendor. You buy usage wholesale, set your own markup, and the vendor never invoices your customer.

The commercial layer is the one that determines whether you have a business or a referral fee. It's also the hardest to get, because it requires the vendor to hand over the billing relationship — which means connecting your own payment account and rebilling usage on top of your subscription.

CloseBot's agency plan does all three, and the mechanism is Stripe Connect: you connect your Stripe account, then rebill message volume, user seats, and knowledge-base storage at whatever rates you set. Your client tops up a wallet, that money pays you, and you pay CloseBot separately at wholesale. The gap is yours.

## Why most white-label AI SDR offers fall apart

Three things tend to eat the margin, and none of them show up in a demo.

**Per-message costs that scale faster than the retainer.** If your client's lead volume triples in a good month, a metered vendor bill can outrun a flat retainer in weeks. CloseBot's own site frames this bluntly — the AI "cost more in API fees than you charged" is the standard agency story.

**Model costs you can't predict.** Newer conversational AI products often require your own OpenAI or Anthropic API keys, which means token spend is your exposure. CloseBot tracks provider token usage and lets agencies rebill it, which turns a cost you absorb into one you pass through. Worth reading the current docs carefully, though: message costs and AI provider token costs are separate line items, and the exact configuration has changed between product versions.

**Hallucinated terms.** An agent that invents a discount costs a client money and costs you the account. CloseBot's Smart FAQ flags questions the agent can't answer confidently instead of guessing, then re-engages every lead who asked once you answer — a small feature that matters more than it sounds when you're managing someone else's inbound.

## Where CloseBot fits in the white-label equation

CloseBot is a conversational AI that qualifies leads and books appointments across the text-based channels inside a CRM — SMS, email, live chat, and social channels connected through HighLevel, HubSpot, LeadConnector, or a custom CRM. It also claims to work standalone without a CRM, which matters if you have clients who don't run one.

For agency work, the relevant pieces are:

- **White-labeled client portal** on your domain, with your branding, showing client-scoped dashboards rather than your agency numbers.
- **Rebilling on four cost types** — messages, seats, storage, and AI provider tokens — each with its own markup you set per client.
- **Client seats at $5/user**, which you can mark up (the docs use a $100 rebill example, which is aggressive but legally yours to set).
- **One agent across many clients** in the same niche. You build the workflow once, define variables like business name, services, and amenities, and each client fills in their own values from their portal. They can't break the logic.

That last point is the actual operational advantage. In the earlier version of the product, sub-accounts could build their own agents and routinely broke things. The current version puts agent construction entirely on the agency side, which is what makes managing 20 clients viable instead of a support job.

👉 [Start a free CloseBot agency trial and see the white-label portal with your own branding](https://app.closebot.com/a?fpr=li87)

## Current CloseBot plans and prices

The plans page shows three plan families: Free, Core (which branches into a business track and an agency track), and Growth. The business track scales by job flows and message ceiling, and the agency track is a single flat plan aimed at resellers. Annual billing is discounted across the board.

| Plan | What it's for | Price | Billing | Get it |
| --- | --- | --- | --- | --- |
| Free | Testing, or low-volume use under 100 messages/month | $0 | Always free | [Claim the free plan](https://app.closebot.com/a?fpr=li87) |
| Core — Business, 1 Job Flow | Your own pipeline, message costs included in the base price | $64/mo ($53/mo billed as $640/yr) | Monthly or annual | [Start with the $64 business plan](https://app.closebot.com/a?fpr=li87) |
| Core — Business, 3 Job Flows | Same as above, more simultaneous flows | $197/mo | Monthly | [Compare the business tiers](https://app.closebot.com/a?fpr=li87) |
| Core — Business, 10 Job Flows | Higher-volume business use | $297/mo | Monthly | [See higher business tiers](https://app.closebot.com/a?fpr=li87) |
| Core — Business, Unlimited Job Flows | Maximum business-tier flows | $397/mo | Monthly | [Go unlimited on business](https://app.closebot.com/a?fpr=li87) |
| Core — Agency | White-label portal, rebilling, unlimited agents across unlimited sources | $397/mo (third-party breakdowns report roughly $331/mo equivalent on annual billing) | Monthly or annual | [Start the agency plan free for 7 days](https://app.closebot.com/a?fpr=li87) |
| Growth | SLAs, HIPAA, quarterly audits, priority uptime, high volume | Custom (contact sales) | Custom | [Request Growth pricing and a demo](https://app.closebot.com/a?fpr=li87) |

A few details that don't fit in a table column:

The **free plan** includes 100 messages a month, 1 agent, 1 user seat, 1 MB of storage, and unlimited account connections. Overage runs $0.08 per message if you go past 100.

**Business plans** include 500 messages in the base price, with the ceiling adjustable upward. Overages are billed at a 2x rate drawn from a wallet. Add-on storage runs $0.10 to $3.00 per MB per month depending on volume, and extra users are $5 each.

**Agency accounts** are billed a flat $0.012 per message, and that entire amount is rebillable. Storage is billed to you at $0.006 per MB per day, also rebillable. The plans page notes unlimited agents and unlimited sources on the agency track.

**Growth** is the only tier where HIPAA compliance is available — CloseBot's healthcare page states this explicitly — along with quarterly audits and priority 99.99% uptime. If you're selling into clinics or dental practices, the agency plan alone won't cover the compliance requirement.

Two policy details worth knowing before you promise a client anything: every paid plan includes a **7-day trial**, and CloseBot states plainly that it **does not issue refunds**. Plans are month to month with no contract, so downgrading is possible, but money already paid isn't coming back. The free plan and trial are where you do your testing.

There's also an official discount code, `CLOSEBOT100OFF`, listed on CloseBot's own blog, which takes $100 off a first payment. It applies to both business and agency plans. That's a one-time saving, not a recurring discount.

## Where the margin actually comes from

Agency pricing only works if the numbers stack. Here's the honest version, using CloseBot's published rates.

Take a client doing 20,000 messages a month — a busy inbound operation, not an outlier.

- Your wholesale message cost: 20,000 × $0.012 = **$240/month**
- Rebill at $0.03/message: 20,000 × $0.03 = **$600/month**
- Gross spread on messages: **$360/month** for that one client
- Plus the $397 agency base plan, spread across your whole book

That $600/message revenue is your pricing decision, not CloseBot's. The platform just needs to let you set it, which it does through per-client rebill rates. You can also rebill seats and storage.

Which is why the coupon matters less than it looks. $100 off a first payment is noise against a spread that repeats monthly across every client.

The counterweight is that your base plan is $397/month regardless of how many clients you have. At three clients, that's $132 per client in overhead before any usage. At ten clients, it's $40. The agency plan gets cheaper per client the more clients you run — and more expensive per client if you don't fill the seats. If you're planning to sell AI to two clients, do the arithmetic honestly before committing; the business track at $64/month may serve you better until volume justifies the agency tier.

A useful reference point: CloseBot's own site cites an average billing figure of $500 per client per month across polled CloseBot agencies, and claims agencies on the platform earn up to 5x more per client than HighLevel-only shops. Those are vendor numbers, not audited ones. Treat them as a ceiling people reach, not a floor you're guaranteed.

👉 [Run the agency plan trial free for 7 days and test rebilling before you sell it](https://app.closebot.com/a?fpr=li87)

## What setup actually involves

The version of "white label AI SDR" that exists on a landing page and the version that exists on a Monday morning are different things. Here's the real sequence.

**1. Build the agent once, for a niche.** Set the objective, add knowledge, attach tools. Personas control tone, formatting, even typo frequency — you're defining how the messages read, not just what they say.

**2. Create variables clients fill in.** Anything that changes between clients becomes a variable: business name, service list, pricing, service area. One agent then serves every client in that vertical.

**3. Connect sources.** HubSpot, HighLevel, or a custom CRM. This is where the platform's philosophy shows: CloseBot doesn't connect to Instagram or WhatsApp itself — your CRM does, and CloseBot answers whatever lands in the CRM inbox. Clients without a CRM need the standalone path.

**4. Connect Stripe and enable rebilling.** Add your Stripe account, set markup rates for messages, seats, and storage, then turn rebilling on per source. Clients top up a wallet; you get paid directly.

**5. Point the client portal at your domain.** This is the layer clients see. They get dashboards scoped to their own performance and costs, and they can upload knowledge-base content themselves — which you rebill by the MB.

**6. Test before it touches a real lead.** There's an in-flow testing portal for running conversations before going live, and you can pause the AI mid-conversation for a human takeover.

Most teams get a first agent running the same day. The part that takes longer is the boring part nobody sells: writing knowledge content that's actually accurate, and reviewing the first hundred conversations for the discount-invention problem.

## Who this model suits, and who it doesn't

**It fits if** you already run client accounts in a CRM, you're selling AI appointment setting as a productized service, and you want the billing relationship to stay yours. The rebilling model is the strongest part of the offer.

**It doesn't fit if** you don't run a CRM and don't want to. That's an architecture mismatch, not a quality problem — adding a CRM subscription just to run one agent doubles your stack and your setup time. If your clients' leads arrive as WhatsApp messages and nothing else, a channel-native tool is a shorter path.

**Also worth flagging:** relying on the free plan for real client work. 100 messages is a testing budget, not a delivery budget, and a client who blows through it on day three is a client you'll be explaining overage charges to.

## Questions people ask before switching

**Can I really put my own brand on the client portal?**
Yes, on agency accounts. You set the domain, colors, and logos. Clients see their own dashboards, not your agency-wide numbers.

**Do clients need their own CloseBot subscription?**
No. They log in as seats under your agency account. Seats cost you $5 per user per month and you can mark that up when rebilling.

**Is HIPAA compliance included?**
No. HIPAA is available on Growth plans only, per CloseBot's healthcare page. If you're selling into healthcare, budget for a Growth conversation with sales.

**What happens if a client's message volume spikes?**
On agency plans you pay $0.012 per message wholesale and rebill at your own rate, so a spike increases both your cost and your revenue. Business plans work differently — a 500-message base with 2x overage drawn from a wallet.

**Is there a refund if it doesn't work out?**
No refunds. There is a permanently free plan and a 7-day trial on paid plans. Use them.

**How do I know if the economics work for my book of clients?**
Add your $397 base plus projected message costs at $0.012, then compare against what you'd charge. If the spread per client doesn't clear a few hundred dollars monthly, you're selling software, not a service — and software margins don't survive churn.

👉 [Check current CloseBot agency pricing and start the white-label trial](https://app.closebot.com/a?fpr=li87)
