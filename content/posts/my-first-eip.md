---
title: "Writing my first EIP"
date: 2022-10-30
description: "Ethereum Improvement Proposal"
tags: ["EIP"]
---

Suberra is a Web3 payment gateway specializing in subscription payments. One key requirement for subscriptions is pulling funds from users at recurring intervals. In designing a secure solution, we saw the need for a generalized standard that could benefit others. Our EIP extends ERC-20 to include an auto-renewable allowance, enabling funds to be spent over time.

## Draft Submission & Discussion

A prerequisite for an EIP is open discourse. We submitted our draft EIP on [Ethereum Magicians](https://ethereum-magicians.org/t/eip-5827-auto-renewable-allowance-extension/10392) and received limited feedback, prompting us to seek input from our contacts.

## Assigning an EIP Number

EIP numbers are typically assigned based on the next GitHub PR number. We initially used #5824 for our draft, but by the time we opened a PR, we received [#5827](https://github.com/ethereum/EIPs/pull/5827).

## Publishing Our EIP

The review process is manual and handled by a few individuals at the Ethereum Foundation. Feedback mainly focused on terminology, like `allowance recovery` vs. `renewable allowance`, and formatting conventions. After several weeks of revisions, we finally merged and published [EIP-5827](https://eips.ethereum.org/EIPS/eip-5827).

## Conclusion

Navigating the EIP process was a valuable learning experience that highlighted the importance of collaboration and precision. Publishing EIP-5827 marks a significant milestone for Suberra, reinforcing our commitment to enhancing the Web3 payment ecosystem. We look forward to seeing how our contribution evolves and benefits the community.