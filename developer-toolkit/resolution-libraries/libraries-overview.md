---
title: Resolution Libraries
description: This page reviews the different resolution libraries that can be used for resolving a domain. The libraries are fully supported and maintained by UD.
---

# Resolution Libraries

Resolution libraries are used for interacting with blockchain domain names. They can be used to retrieve [payment addresses](../../crypto-payments/index.md), IPFS hashes for [decentralized websites](../../d-websites/index.md), DNS records and other [records types](../../getting-started/domain-registry-essentials/records-reference.md). Each Resolution Library is built and maintained by Unstoppable Domains, so updates happen automatically.

:::warning Important
Unstoppable Domains periodically releases new TLDs, and our Resolution libraries and APIs will automatically detect and support any new TLDs. It is imperative for future proofing your resolution integration to allow all domain inputs to pass through rather than implementing a front end filter (e.g. avoid hard coding domains or placing a regex filter for just .crypto, .nft, etc.).
:::

## Supported Domains for Resolution Libraries

The Resolution Libraries support decentralized domains across two main zones:

| Name Service                   | Supported Domains                                                                      |
| ------------------------------ | -------------------------------------------------------------------------------------- |
| Zilliqa Name Service (ZNS)     | `.zil`                                                                                 |
| Unstoppable Name Service (UNS) | `.crypto`, `.nft`, `.blockchain`, `.bitcoin`, `.coin`, `.wallet,` `.888`, `.dao`, `.x` |

## List of UD Resolution Libraries

The following table lists the UD Resolution Libraries along with links to each respective GitHub Repository.

| Resolution Library | GitHub Repository                                                                                                |
| ------------------------------------------ | ---------------------------------------------------------------------------------------------------------------- |
| [JavaScript](./resolution.md)   | [https://github.com/unstoppabledomains/resolution](https://github.com/unstoppabledomains/resolution)             |
| [Java](./resolution-java.md)               | [https://github.com/unstoppabledomains/resolution-java](https://github.com/unstoppabledomains/resolution-java)   |
| [Swift](./resolution-swift.md)             | [https://github.com/unstoppabledomains/resolution-swift](https://github.com/unstoppabledomains/resolution-swift) |
| [Golang](./resolution-go.md)               | [https://github.com/unstoppabledomains/resolution-go](https://github.com/unstoppabledomains/resolution-go)       |

## Support

If you have any questions or need assistance with using UD resolution libraries, join our [Discord channel](https://discord.gg/b6ZVxSZ9Hn) for real-time support from us and the community.