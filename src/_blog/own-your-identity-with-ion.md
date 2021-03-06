---
tags:
  - identity
title: Own Your Identity with ION
description:
  The new decentralized identity network launches with all transaction
  data distributed with IPFS.
author: Dietrich Ayala
date: 2021-03-24
permalink: '/2021-03-24-own-your-identity-with-ion/'
translationKey: ''
header_image: '/2021-03-26-cardheader-127-ion-header.png'
---

**We are many people!** Whether on Twitter, Zoom or paying the electricity bill, we assume identities to interact with others online. How much of that identity is you? How much of “you” is decided by those services? Why can’t the bag of bits that is “you” stick around while hopping from online service to online service?

Well now it can! Decentralized identity services have matured to a point where usage is simple, they’re backed by public networks firmly rooted into the global business firmament, and now we’re seeing those businesses deploy them in earnest.

Today, we’re excited to see a new decentralized identity service launch which stores its data on IPFS: Congratulations ION for launching v1.0!

## ION and IPFS

ION is a public identity network providing distributed public key infrastructure through Decentralized Identifiers (DIDs) and the [Sidetree protocol](https://github.com/decentralized-identity/sidetree) on top of the Bitcoin blockchain. ION is developed by Microsoft and a group of collaborators at the Decentralized Identity Foundation.

We’ve been working with them to support their use of IPFS since 2019. IPFS comes into the picture at the storage layer, where ION aggregates transactions into batches, adds those batches to IPFS, and then writes the IPFS content identifier (CID) of the batch to the blockchain. The ION pairs with a local go-ipfs node for publishing data for availability to the broader IPFS network.

Additionally, ION has a network explorer at [identity.foundation/ion/explorer/](https://identity.foundation/ion/explorer/).

![ION network explorer](../assets/ion-explorer.png)

## Using and Contributing to ION

Today Microsoft launched v1.0 of ION, and in [the launch post](https://techcommunity.microsoft.com/t5/identity-standards-blog/ion-we-have-liftoff/ba-p/1441555) they've shared examples of using the JavaScript client for application integration and steps for running a node. The team has created a high-level SDK for easy app integrations, with key and DID generation utilities and basic login APIs. Additionally they’ve published a low-level SDK for building customized identity solutions beyond what comes out of the box.

As ION is a public network, running a node of your own will contribute to the overall health, resilience and performance of the system. Instructions for building and installing a node are detailed in the [ION Github repository](https://github.com/decentralized-identity/ion).

Try ION today for an identity solution which gives your users more control and let us know how it goes! Share your feedback in the ION repo or let [@IPFS](https://twitter.com/ipfs) know on Twitter.
