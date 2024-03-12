---
title: Accepting Monero for Businesses
has_children: false
---

# Accepting Monero for Businesses

This is for businesses that want to accept Monero in an automated way, including:

* merchants
* service providers
* exchanges

## About Converting to Fiat (USD, EUR, etc)

Many merchants prefer to immediately convert their received XMR to fiat. This is possible by using a native integration, or by using an auto-forward and auto-conversion tool for your preferred Monero exchange.

## Overview

| Name | Self-Custody | Open-Source | Convert to Stable | Convert to Fiat |
| --- | --- | --- | --- | --- |
| [BTCPay Server](https://btcpayserver.org/) | ✅ | ✅ | ⚠️ Requires plugin and/or additional work | ⚠️ Requires plugin and/or additional work |
| [MoneroPay](https://moneropay.eu/) | ✅ | ✅ | ❌ Must do manually | ❌ Must do manually |
| [NOWPayments](https://nowpayments.io/) | ❌ | ⚠️ Some plugins are open source | ✅ | ✅ Yes, with Guardarian (KYC required) |
| [CoinPayments](https://www.coinpayments.net) | ❌ | ⚠️ Some plugins are open source | ✅ | ❌ Must do manually |
| [Cryptomus](https://cryptomus.com/white_label) | ❌ | ❌ | ✅ | ❌ Must do manually |
| [ForgingBlock](https://forgingblock.io/) | ❌ | ❌ | ✅ | ❌ Must do manually |
| [Monero Integrations](https://monerointegrations.com/) | ✅ | ✅ | ❌ Must do manually | ❌ Must do manually |
| Manual Wallet Processing | ✅ | ✅ | ❌ Must do manually | ❌ Must do manually |

## BTCPay Server

[BTCPay Server](https://btcpayserver.org/) is a comprehensive self-hosted option for those who wish to receive payments directly.

BTCPay Server allows you to accept Monero, Bitcoin, Litecoin, and other assets. You need to run a node for each asset you wish to accept. There are exchange plugins which allow users to spend other assets, and you will receive the asset of your choice, such as Monero.

You will need to set up your own server, such as a VPS. As of 2024-03-08, you will need approximately 100 GB of local storage to accept Monero, and additional space if you wish to run other nodes to accept other coins. You do not need these additional nodes to run an exchange plugin.

## MoneroPay

[MoneroPay](https://moneropay.eu/) is a lightweight self-hosted option for those who wish to receive payments directly.

MoneroPay only supports XMR.

## NOWPayments

[NOWPayments](https://nowpayments.io/) is one of the easiest ways to accept Monero. They have [plugins](https://nowpayments.io/payment-tools) for PretaShop, WooCommerce, Magneto 2, WHMCS, OpenCart, Ecwid, Zen Cart, Shopify, and Shopware. You can choose to have the XMR settle in another cryptocurrency, such as a stablecoin.

NOWPayments fees are approximately 1%, though exchange spreads will vary.

You can receive automatic settlement in EUR through Guardarian. Additional EUR conversion fees apply.

NOWPayments allows customers to pay with many different cryptocurrencies, not just XMR.

## CoinPayments

[CoinPayments](https://www.coinpayments.net) most directly competes with NOWPayments. You can receive XMR and other cryptocurrencies on your website, and they can be automatically converted to another cryptocurrency such as a stablecoin. They have [plugins](https://www.coinpayments.net/merchant-tools-plugins) for most store types.

## Cryptomus

[Cryptomus](https://cryptomus.com/) is a payment processor service that supports payments in many cryptocurrencies including XMR. These can automatically be converted to another cryptocurrency such as a stablecoin.

In testing, there is a ~2.5% hidden exchange rate spread for the purchaser (and possibly for the automatic cryptocurrency conversion), and a 0.4% fee for the seller.

## ForgingBlock

[ForgingBlock](https://forgingblock.io) is a payment processor service that supports payments in many cryptocurrencies including XMR. These can automatically be converted to another cryptocurrency such as a stablecoin.

Pricing starts at $599.

## Monero Integrations

[Monero Integrations](https://monerointegrations.com/) is a set of plugins for WooCommerce, PretaShop, and WHMCS. They are relatively basic.

## Manual Wallet Processing

If you only need to accept Monero in rare cases, you can skip the complicated invoicing and use any Monero wallet to check for incoming payments. You can post a Monero address that your customers can pay to, and you can check your wallet when they inform you that they have paid.

This manual process works fine for farmers markets and other low-volume situations.
