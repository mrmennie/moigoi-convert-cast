# Moi Goi Convert Cast sender

This repository hosts the small HTTPS page used by Moi Goi Convert to start an official Google Cast session in Chrome.

- The page uses Google's Default Media Receiver; it does not host a custom receiver.
- Convert passes temporary session details in the URL fragment, which is not sent to this web host.
- Selected media remains on the user's Mac and is served directly to the chosen receiver through a temporary, token-bound local address.
- The source-of-truth copy is `apps/convert/CastSender/index.html` in the Convert candidate lineage.

The published sender is intentionally static. Product changes require a matching Convert source change, verification, and a new evidence receipt.
