# REDKIT — The Crypto Wild West

Static, responsive REDKIT concept website. No build step, wallet access, or network APIs required. Includes interactive local-only bounty demo. No token contract deployed.

## Publish free on GitHub Pages

1. Create a **public** repository named `redkit` under your GitHub profile.
2. Upload the contents of this folder (`index.html`, `README.md`, `.nojekyll`) to the **root** of the repository, or push using git.
3. In the repository, open **Settings > Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**; select **main** and **/(root)**, then **Save**.
5. GitHub should publish to `https://YOUR_USERNAME.github.io/redkit/` after the deployment succeeds.

If username is `Yamtarcavus`, expected address is `https://yamtarcavus.github.io/redkit/` (not verified as live until publishing finishes).

## Customize

- Replace placeholder planned tokenomics with approved details after launch decisions.
- Add only official, verified social links.
- Do not add a BUY link or a contract address before official deployment and verification.
- `REDKIT` and `$REDKIT` branding used as requested. The illustration is a generic CSS/SVG cowboy, not an existing cartoon character.

## Legal & security

The name REDKIT and character associations can present trademark/IP concerns. Obtain appropriate legal review and licenses before commercial launch. The website is not affiliated with Lucky Luke/Red Kit rights holders.

## v2 — Trade / Bridge / Stake sections

- **Swap Saloon:** functional network, pair and amount controls. Opens the verified Uniswap app in a new tab for live quoting and transaction handling; does **not** execute trades on the REDKIT site.
- **Frontier Bridge:** selects networks and asset, opens the independent Across app for verification and execution; no bridge transfers from REDKIT.
- **Staking Ranch:** working staking selection and preview, with no invented APY or active deposit operation.
- **Connect Wallet:** optionally requests only an EVM account address (`eth_requestAccounts`). It does not request signatures or private keys.
- Token has not been deployed and no staking contract, chain ID, token address or authorized bridge route has been provided; these features cannot legitimately execute REDKIT transactions yet.

Never treat a preview as a completed on-chain operation.