---
title: 'Token bridging overview'
description: An overview of token bridging resources
author: dzgoldman
user_story: As a developer, I want to understand how the token bridge works and what options exist to bridge assets between layers.
content_type: overview
sidebar_position: 1
---

Token bridging is a fundamental aspect of any Layer 2 (L2) protocol. Arbitrum uses its ability to pass messages between L1 and L2 (see [Cross-chain messaging](/build-decentralized-apps/cross-chain-messaging)) to allow projects to trustlessly move assets from Ethereum to an Arbitrum chain and back. Any asset and asset type can in principle be bridged, including Ether, ERC-20 tokens and ERC-721 tokens among others.

This section offers a series of conceptual documents explaining how asset bridging works and what options exist to bridge ether (ETH) and other types of asset between layers.

This section is divided in 2 main pages:

- [ETH bridging](/build-decentralized-apps/token-bridging/token-bridge-ether): explains how Arbitrum handles bridging ETH, the native token of Ethereum and the Arbitrum chains, between L1 and L2.
- [ERC-20 token bridging](/build-decentralized-apps/token-bridging/token-bridge-erc20): explains the architecture of the token bridge for this type of asset, describing the different options available to make a token bridgeable.

For a more practical approach, there are [How-to pages](/build-decentralized-apps/token-bridging/get-started) that go over the process of making an ERC-20 token bridgeable using the different types of gateway available in the token bridge.
