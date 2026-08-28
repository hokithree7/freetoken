# Privacy boundary

## Browser-direct tools

For supported browser-direct checks, Key Doctor, Playground, and compatible comparison flows send user-initiated requests from the browser to the selected provider. FreeToken does not use a server proxy to collect plaintext provider keys or prompts for those checks. Provider and browser CORS support can limit which routes work this way.

## Shared configuration

Shared URLs and downloaded templates use placeholders. They do not embed API keys.

## Optional Vault

Vault encryption happens in the browser. The service stores ciphertext and cryptographic parameters, not the passphrase or plaintext provider key.

## Watchlist

The subscription flow requires anonymous email subscribers to confirm before becoming active. When delivery is configured, management links are signed, deliveries are deduplicated, and messages include a management or unsubscribe path.

## Public issues

Never post credentials, private account responses, or personal information in this repository. Use private vulnerability reporting for sensitive security findings.

Live security overview: https://freetoken.link/security
