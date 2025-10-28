---
cover: ../../.gitbook/assets/header_02_test.png
coverY: 0
layout:
  cover:
    visible: true
    size: hero
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# 🍄 Take a Self-Repaying Loan

Now that you’ve made a deposit into Alchemix, your deposit will automatically start earning yield. You can choose to borrow against it or leave it to accrue credit.

This guide explains how to take a self-repaying loan (borrow alAssets against your deposited collateral), what limits apply, and useful tips to avoid common pitfalls.

## Quick overview

- Available Credit: the amount you can borrow against your deposited collateral.
- Total Deposit: sum of collateral across your vaults.
- Debt: total amount you have borrowed.
- Interest: yield earned; can increase your available credit (interest taken as credit does not need to be repaid).
- Debt limit: the maximum borrowable amount based on collateral ratios.

You can view your Available Credit and other balances on the Vaults page.

<figure><img src="../../.gitbook/assets/image (5) (1).png" alt=""><figcaption><p>Available Credit</p></figcaption></figure>

If you have positions across several vaults, use the tab filters to inspect credit per vault.

<figure><img src="../../.gitbook/assets/image (6) (1).png" alt=""><figcaption><p>alAsset Tab Filters</p></figcaption></figure>

The borrowable amount is determined by the collateral ratio of the deposited tokens and the vault-specific debt limits. Check the Vaults page for per-vault debt details.

<figure><img src="../../.gitbook/assets/image (7) (1).png" alt=""><figcaption><p>Debt limit</p></figcaption></figure>

## Step-by-step: take a self-repaying loan

1. Open the Vaults page and confirm your Available Credit for the vault you want to borrow from.
2. Click the "Borrow" button at the top of the vault page to open the borrow modal.

<figure><img src="../../.gitbook/assets/image (9) (1).png" alt=""><figcaption><p>The Borrow modal</p></figcaption></figure>

3. In the modal:
   - Choose the alAsset you want to receive (only alAssets backed by your deposited token will be listed — e.g., deposited wETH → borrow alETH).
   - (Optional) Toggle "Send to another address" and paste the recipient address if you want the proceeds sent elsewhere.
   - Enter the amount to borrow or click "Max" to use your full Available Credit.
4. Confirm the transaction in your wallet and pay the gas fee. Wait for the transaction to be mined.
5. After confirmation:
   - Your wallet balance will update with the borrowed alAssets (unless you sent them to another address).
   - The Vaults page will reflect your increased debt.

<figure><img src="../../.gitbook/assets/image (10) (1).png" alt=""><figcaption></figcaption></figure>

## Using your alAssets

- Find efficient ways to use or earn with alAssets at: https://alchemix-stats.com/earn
- Swap alAssets via the suggested links on our swap page: https://alchemix.fi/swap, or use Curve: https://curve.fi, or any supported DEX.

## Important considerations & best practices

- Collateral ratio & liquidation: borrowing increases your debt; monitor collateral ratios to avoid undercollateralization. Keep a safety margin below max debt limits.
- Gas & confirmation: ensure you have native chain token (e.g., ETH) for gas. Transactions can take time depending on network congestion.
- Slippage & swaps: when swapping alAssets, set appropriate slippage tolerances.
- Sending to other addresses: double-check recipient addresses — blockchain transfers are irreversible.
- Support: for help, contact the official Discord: https://alchemix-finance.gitbook.io/user-docs/resources

## Next steps

When you're ready to repay (partially or fully), see the repay guide: link to repay docs or the relevant section of this site.

<figure><img src="../../.gitbook/assets/header_02_test.png" alt=""><figcaption></figcaption></figure>
