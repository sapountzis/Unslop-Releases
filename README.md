```text
 _   _                 _
| | | |               | |
| | | | _ __   ___    | |  ___   _ __
| | | || '_ \ / __|   | | / _ \ | '_ \
| |_| || | | |\__ \   | || (_) || |_) |
 \___/ |_| |_||___/   |_| \___/ | .__/
                                 | |
                                 |_|
```

> The social web should feel human again.

Unslop is a Chrome extension that filters low-value feed posts so you can focus on signal instead of algorithmic noise.

This repository is the public release channel for extension builds.

## Current status

- Available now for LinkedIn
- X (Twitter) and Reddit support are in active development

## Install from release

1. Download the latest zip from the [Releases](../../releases) page.
2. Unzip `unslop-extension-vX.Y.Z.zip`.
3. Open `chrome://extensions`.
4. Enable **Developer mode**.
5. Click **Load unpacked** and select the unzipped folder.

## Privacy, in plain language

- Unslop uses account email for sign-in.
- Posts selected for filtering are sent to the Unslop API for keep/hide decisions.
- Classification input may be processed by an LLM inference provider.
- Data is used for filtering, cache efficiency, quota enforcement, and reliability.
- No ad targeting, no analytics tracking scripts, no data resale.
- No model training on user data in v0.1.

Read full policy: https://getunslop.com/privacy  
Support: support@getunslop.com

## Plans

- Free plan for trying the product
- Paid plan for higher monthly usage and continued development

See current plan details in the extension UI and on https://getunslop.com.

---

Built by a human.  
https://getunslop.com
