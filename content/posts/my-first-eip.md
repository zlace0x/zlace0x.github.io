---
title: "Writing my first EIP"
date: 2022-10-30
description: "Ethereum Improvement Proposal"
tags: ["EIP"]
---

Suberra is a web3 payment gateway specialising in subscription payments. One of the key requirement of subscriptions is pulling funds from users' at recurring intervals.
In midst of designing a secure solution, we decided a generalised standard can come in useful for others. Our EIP extends ERC-20 to add an auto-renewable allowance so that funds can be spent over time.


## Draft Submission & Discussion

One of the prerequisite of an EIP is having open discourse. We submitted our draft EIP on [Ethereum Magician](https://ethereum-magicians.org/t/eip-5827-auto-renewable-allowance-extension/10392) had little comments, thus we seeked feedback from our contacts.

## Assigning a EIP number
Typically EIP numbers are assigned by the next PR number of github. 
We use the next number in line, #5824 when we first started our draft EIP, by the time we opened a PR we gotten [#5827](https://github.com/ethereum/EIPs/pull/5827).

## Publishing our EIP

The review process is manual, handled by a handful of folks at EF. The key areas of comments revolves around terminologies used such as `allowance recovery` vs `renewable allowance` and various formatting conventions.

After weeks of revision, we finally merged and published [EIP-5827](https://eips.ethereum.org/EIPS/eip-5827)