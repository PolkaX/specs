> origin paper https://blog.0xproject.com/a-beginners-guide-to-0x-81d30298a5e0

# A beginner’s guide to 0x

## What is 0x?

As an advisor to the Ethereum project 0x (“zero-ex”), I’ve spent a lot of time thinking about and answering questions about how the technology works and its potential impact. Hopefully, this beginner’s guide will provide a clear introduction to the project and how it will allow anyone in the world to operate an exchange for Ethereum tokens.Before learning about 0x, it is important to first understand the basics of Ethereum tokens. Please see my beginner’s guide for those new to this concept entirely.

According to the 0x whitepaper, 0x is “an open protocol for decentralized exchange on the Ethereum blockchain.” 0x is creating a protocol using Ethereum smart contracts for anyone in the world to operate a decentralized exchange. The team believes that there will be thousands of Ethereum tokens in the future and there will be a need to trustlessly and efficiently exchange them. This post should help those who are new to 0x to understand how it is different than a centralized or decentralized exchange.

## Centralized vs. Decentralized Exchanges

If you have ever purchased digital currencies with traditional payment methods like a bank account or wire, then you used a centralized exchange. Centralized exchanges are necessary for providing a fiat on-ramp to the cryptocurrency markets.
They typically are easy to use, offer high performance trading, and advanced tools. However, the downsides to centralized exchanges include the downsides to any centralized service that requires trust: the central party could get shut down, hacked, or run away with customer funds. These risks led to the development of decentralized exchanges like EtherDelta and OasisDEX which allow people to trustlessly exchange through the Ethereum blockchain without needing to deposit their funds into the custody of a central party. Another key difference between centralized and decentralized exchanges is that centralized exchanges can potentially be held legally accountable should any issues occur whereas in a decentralized exchange the accountability is not as apparent as the code could be considered law. Ultimately, I believe that centralized and decentralized exchanges will co-exist as they each provide their own unique benefits.

## Decentralized Exchanges vs. 0x

The primary downsides to many existing decentralized exchanges are that they are illiquid, slow, expensive, and inoperable with one another. For those operating order books on the blockchain, every new order or adjustment to an order goes through the blockchain. This means that they rely entirely on block times and incur network transaction fees for every single transaction. 0x tries to solve for these inefficiencies by creating a standard protocol of orders being relayed off of the blockchain and only having them brought back onto the blockchain when the order needs to be settled. 0x doesn’t charge any fees to use the protocol but anyone who decides to build a decentralized exchange on top of the protocol can decide to charge their own fees.

## 0x Project

0x was co-founded by Will Warren and Amir Bandeali in October 2016. They envision a world in which every asset can be represented as a token on the Ethereum blockchain including fiat currencies, stocks, gold and digital game items. This tokenization will lead to thousands of tokens that need a method of trustless exchange. Decentralized exchanges have been a major step forward but there are still the remaining inefficiencies and lack of operability between decentralized exchanges. 0x aims to create a standard protocol on the Ethereum blockchain that allows any Ethereum token to be traded and for anyone to operate a decentralized exchange. These parties building on top of 0x are referred to as Relayers as they host off blockchain order books and can charge fees for their services.

While 0x is a protocol, the team also built a consumer facing product 0x OTC that uses the protocol. 0x OTC allows for peer-to-peer exchange of Ethereum tokens without the need for a Relayer, as long as you are able to connect directly with a counterparty. It is live on the Ethereum test network (Kovan) and anyone can generate and broadcast their order by sending a link to their counterparty. Since the order is relayed off of the blockchain, the link can be sent through any method the person issuing the order prefers, ranging from email to Twitter to even writing it down on a piece of paper. For example anyone can fill this order through 0x OTC which I am broadcasting through this Medium post.

![img](https://miro.medium.com/max/2132/1*3jVbysAGgCzmzlffW2qiiA.gif)

### 0x Token

0x has its own Ethereum token, ZRX, which is used to pay trading fees to Relayers for their services. However, the main purpose for ZRX is decentralized governance over 0x protocol’s upgrade system, meaning owning ZRX gives you a say proportional to your holdings in how the protocol should be improved over time. 0x community member Brock Petrie explained this nicely in the 0x slack channel:

> it’s inevitable that the 0x protocol will need to change over time, to accommodate changes in both token standards and changes to Ethereum’s technology stack. when the need for change comes up, it poses a problem because entities will have built products on top of the protocol, products that would likely be impacted from any changes. the 0x team could choose to be BDFLs\* for the protocol, but they would risk angering people with their decision-making, and people could be dissuaded from using them in the first place out of fear of the protocol changing on a whim without public discourse. now imagine people using the protocol could actively vote on its future. these tokens allow for that. if an organization wants to influence the direction of the protocol, they can obtain a stake by acquiring tokens. more tokens = more influence, basically. this governance mechanism is still in the process of being worked out

\*BDFLs refers to the term “benevolent dictators for life” which are leaders of an open source project who typically make the final call in disputes.

## Resources

0x is an exciting project with a strong team focused on development. Below are some links that may help you understand 0x further and keep up with the exciting development.
Understanding 0x
**0x Whitepaper**

- 0x FAQ
- 0x Protocol Analysis
- Will Warren’s talk at Coinbase
  **Keeping up with 0x**
- 0x Chat
- 0x Twitter
- 0x Medium
  Thank you to Will Warren, Adam White, and Daniel Roseman for reviewing this post.
  Disclaimer: I own ZRX.
