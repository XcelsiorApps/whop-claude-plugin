# Whop

An independent Claude plugin published by **Ladd through PlugIn**. Helps users plan a Whop business launch, choose one-time or subscription payments, prepare a checkout setup request, and connect Whop’s existing connector when needed.

## What users get

- A launch checklist tailored to an existing or new Whop business.
- Guidance for product, price, currency, billing interval, and checkout setup.
- A handoff to Whop’s existing connector for authorized account actions.
- Dashboard guidance when no connector is available.

## New-business referral

[Create your Whop business](https://whop.com/start/?code=WISEONE)

**Affiliate disclosure:** Ladd may receive a commission from Whop for an eligible new-business referral. Under the publisher’s partner arrangement, this does not add a referral fee or deduct the commission from business funds. Whop’s normal fees and eligibility terms apply. Installing this plugin does not itself establish referral attribution or guarantee commissions.

Existing businesses can skip signup. Requests for a non-affiliate destination are respected.

## Use with Claude’s Whop connector

Install this plugin, then ask: “Help me set up my Whop business to accept monthly subscriptions.” It supplies the onboarding workflow. Connect Whop separately using Claude’s supported connector setup and review Whop’s permissions. If Whop is already connected, reuse it.

The plugin does not bundle another MCP server or automatically install, authenticate, or change Whop’s connector. Available account operations depend on the connected tools and user authorization. No payment-history or customer-data permission is needed for this plugin’s guidance.

## Examples

- “I’m starting a Whop business. Help me get ready to accept payments.”
- “I already have Whop. Help me plan a monthly subscription.”
- “Prepare a checkout setup request for my connected Whop tools.”

## Package and review

`.claude-plugin/plugin.json` is the Claude plugin manifest. The onboarding instructions are in `skills/whop-business-onboarding/SKILL.md`. No scripts, hooks, dependencies, embedded credentials, or publisher-operated server are included.

This source package is prepared for submission; it is not an approved Claude directory listing. Platform approval, live connector testing, and Whop affiliate-attribution testing remain separate steps.

## Privacy and support

The publisher operates no data-collection service in this package. The instructions do not request passwords, API keys, banking details, payment history, or customer contact exports. Claude and Whop process information under their own terms when users interact with them. For plugin issues, use this repository’s Issues tab. For account or payment issues, use Whop’s support.

Whop owns its trademarks. This integration is independently published; it is not Whop’s official connector. The publisher reports permission from Whop to use its name and logo.
