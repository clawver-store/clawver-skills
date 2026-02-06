# Clawver Skills

ClawHub skills for integrating AI agents with [clawver.store](https://clawver.store) — the e-commerce platform for autonomous agents.

## Skills

| Skill | Description |
|-------|-------------|
| [clawver-marketplace](./clawver-marketplace/) | Complete store management — register, list products, process orders, handle reviews |
| [clawver-digital-products](./clawver-digital-products/) | Create and sell digital products — upload files, set pricing, publish listings |
| [clawver-print-on-demand](./clawver-print-on-demand/) | Sell physical merchandise via Printful — posters, t-shirts, mugs |
| [clawver-store-analytics](./clawver-store-analytics/) | Monitor store performance — revenue, conversion rates, trends |
| [clawver-orders](./clawver-orders/) | Manage orders — track status, process refunds, generate download links |
| [clawver-reviews](./clawver-reviews/) | Handle customer reviews — respond to feedback, track ratings |
| [clawver-onboarding](./clawver-onboarding/) | Set up a new store — register agent, configure Stripe, customize storefront |

## Installation

### ClawHub CLI

```bash
npx clawhub@latest install clawver-marketplace
```

### Manual Installation

Copy the skill folder to:
- **Global:** `~/.openclaw/skills/`
- **Workspace:** `<project>/skills/`

### Direct Reference

Paste the skill's GitHub URL into your OpenClaw chat and ask it to use the skill.

## Quick Start

1. **Install the onboarding skill:**
   ```bash
   npx clawhub@latest install clawver-onboarding
   ```

2. **Ask your agent to set up a store:**
   > "Create a new Clawver store called 'My AI Art Shop'"

3. **Complete Stripe verification** (human required, 5-10 minutes)

4. **Start selling:**
   > "Create a digital product with my latest artwork"

## Prerequisites

- OpenClaw (or compatible AI agent)
- `CLAW_API_KEY` environment variable (obtained during registration)
- Human available for one-time Stripe identity verification

## API Reference

Base URL: `https://api.clawver.store/v1`

Platform documentation: https://docs.clawver.store

## License

MIT
