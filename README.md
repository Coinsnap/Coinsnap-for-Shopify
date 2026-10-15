# Coinsnap for Shopify

**Bitcoin payment integration for Shopify — accept Bitcoin and Lightning with Coinsnap or your own BTCPay Server.**

Coinsnap for Shopify enables merchants to add Bitcoin payments to Shopify while keeping the existing Shopify checkout and order workflow intact.

Shopify does not natively support decentralized Bitcoin payments or direct wallet settlement. Coinsnap bridges this gap through a structured payment flow that fits Shopify's checkout architecture and links Bitcoin payments back to the corresponding Shopify order.

Customers can pay with **Bitcoin via Lightning or on-chain**. Payments can be settled to a connected Bitcoin wallet or, depending on the merchant setup, converted and settled to a bank account through supported partners.

Coinsnap is **Bitcoin payment software for merchants** and a brand of **Onlineshop24 d.o.o., Serbia**.

## Key features

- Accept **Bitcoin and Lightning payments** in Shopify
- Support for **Lightning and Bitcoin on-chain**
- Works with Shopify's existing checkout logic
- Keeps Shopify order management intact
- No Shopify theme or storefront modifications required
- No own Lightning node or Bitcoin payment infrastructure required when using Coinsnap
- Support for **Coinsnap** and **BTCPay Server**
- Optional **Bitcoin discount** with fixed or percentage-based discounts
- **Non-custodial / self-custody** approach
- Settlement to a compatible Bitcoin wallet
- Optional settlement to a bank account through supported partners
- Free Shopify integration service available
- Open source and free to use

## Requirements

To use the Shopify integration you need:

- A **Shopify store** with administrator access
- Administrator access to the **Shopify Partner Portal** for DIY setup
- A **Coinsnap merchant account**, or a compatible **BTCPay Server**
- The Coinsnap for Shopify integration

For Bitcoin settlement with Coinsnap, you can use a compatible Bitcoin or Lightning wallet. One option is the [Coinsnap Wallet](https://coinsnap.io/wallet/), which combines a self-custodial Bitcoin wallet with merchant and point-of-sale functionality.

## How it works

1. The customer selects **Bitcoin / Lightning** as the payment method in Shopify.
2. Shopify completes the order through its normal checkout flow.
3. The customer is guided to the Bitcoin payment page.
4. The customer pays via QR code using Lightning or Bitcoin on-chain.
5. The payment is linked back to the Shopify order.
6. The Shopify order status is updated after payment confirmation.

This approach keeps Shopify's order workflow intact while Bitcoin payment processing happens through Coinsnap or BTCPay Server.

## Coinsnap or BTCPay Server

The Shopify integration supports two payment-provider setups:

- **Coinsnap** — for merchants who want to accept Bitcoin without operating their own Bitcoin or Lightning payment infrastructure.
- **BTCPay Server** — for merchants who want to use their own BTCPay Server and retain full control over their payment infrastructure.

## Bitcoin discount

The Shopify Bitcoin payment integration supports an optional discount for customers who choose Bitcoin or Lightning.

Merchants can configure either:

- a **percentage-based discount**, or
- a **fixed discount**

This can be used to encourage customers to choose Bitcoin at checkout.

## Installation options

Coinsnap offers two ways to connect Shopify.

### Option 1: DIY setup

Merchants familiar with Shopify can connect the integration themselves using the detailed Coinsnap Shopify user guide.

The setup uses the Shopify Partner Portal and Shopify Developer tooling to connect the Shopify store with Coinsnap.

### Option 2: Free Shopify integration service

Coinsnap can perform the integration for you free of charge.

The merchant grants temporary Shopify administrator access to Coinsnap for the installation and configuration. After the integration is complete, the temporary Coinsnap admin user can be removed again.

## DIY setup overview

The DIY setup includes the following steps:

1. Prepare your Shopify store and Shopify Partner access.
2. Create a Shopify app in the Shopify Developer Portal.
3. Enable the required checkout and account UI extension access.
4. Open the Coinsnap merchant account and go to the Shopify settings.
5. Enter the Shopify **Client ID**, **Client Secret** and app name.
6. Deploy and authorize the Shopify integration.
7. Add the Coinsnap checkout extension to the Shopify **Thank you** page.
8. Create a custom manual payment method for Bitcoin / Lightning.
9. Perform a test purchase before going live.

For the complete step-by-step process, use the official Shopify Bitcoin User Guide.

## Shopify checkout flow

Coinsnap is designed around Shopify's closed checkout architecture.

- Customers complete the normal Shopify checkout.
- Bitcoin is offered as an additional payment method.
- After order creation, the customer is directed to the Bitcoin payment page.
- The customer pays using a Bitcoin or Lightning wallet.
- The payment is associated with the Shopify order.
- Shopify order management remains unchanged.

No separate order system is required.

## Settlement

Merchants can receive settlement according to their configuration:

- to a compatible **Bitcoin or Lightning wallet**
- through their own **BTCPay Server**
- or, where supported, converted and settled to a **bank account** through partner integrations

Coinsnap follows a non-custodial approach and does not hold merchant Bitcoin.

## Resources

- [Coinsnap for Shopify product page](https://coinsnap.io/shop-systems/shopify/)
- [Shopify Bitcoin User Guide](https://coinsnap.io/user-guides/shopify-bitcoin-user-guide/)
- [Coinsnap Wallet](https://coinsnap.io/wallet/)
- [Coinsnap API documentation](https://docs.coinsnap.io/)
- [Coinsnap merchant account](https://app.coinsnap.io/register)
- [Coinsnap website](https://coinsnap.io/)
- [Telegram community and support](https://t.me/coinsnap)

> **Brand note:** Coinsnap is Bitcoin payment software for merchants and is not the provider of the similarly named coin identifier app "CoinSnap".

## Frequently Asked Questions

### Does Shopify support Bitcoin payments natively?

No. Shopify does not natively support direct Bitcoin or Lightning payments. Coinsnap provides a structured integration that works within Shopify's checkout architecture.

### Can customers pay with both Lightning and Bitcoin on-chain?

Yes. The Shopify integration supports Bitcoin payments via both the Lightning Network and Bitcoin on-chain.

### Can I use my own BTCPay Server?

Yes. The Shopify integration is compatible with BTCPay Server.

### Can I offer a Bitcoin discount?

Yes. Merchants can configure a fixed or percentage-based discount for Bitcoin payments.

### Do I need my own Lightning node?

No. When using Coinsnap, you do not need to operate your own Lightning node or Bitcoin payment server.

### Does the integration change my Shopify theme?

No. The integration works with the Shopify checkout flow and does not require changes to the storefront theme.

### How are Shopify orders handled?

Orders remain created and managed in Shopify. Bitcoin payments are processed separately and linked back to the corresponding Shopify order.

### Does Shopify charge additional transaction fees for Coinsnap Bitcoin payments?

The Coinsnap Shopify setup uses a manual payment method, so Shopify does not charge an additional Shopify transaction fee for this Bitcoin payment method.

### Which Bitcoin or Lightning wallets can I use?

You can use a compatible Bitcoin or Lightning wallet for settlement. One option is the [Coinsnap Wallet](https://coinsnap.io/wallet/).

Other compatible wallets may include solutions such as Wallet of Satoshi, Blink and Zeus, depending on the settlement setup you choose.

### Can I receive settlement in euros?

Depending on the merchant setup and supported partner integrations, Bitcoin payments can be converted and settled to a bank account.

### Can Coinsnap install the Shopify integration for me?

Yes. Coinsnap offers a **free Shopify integration service**.

### Is the integration open source?

Yes. The Shopify integration is provided as an open-source solution and is free to use.

### Where can I get support?

Use the support area in your Coinsnap merchant account or join the official [Coinsnap Telegram channel](https://t.me/coinsnap).
