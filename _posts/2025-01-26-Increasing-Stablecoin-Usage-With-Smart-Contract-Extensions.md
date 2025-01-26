*This post will be subject to ongoing change*

### Mission

To proliferate stablecoin usage by providing users with a decentralised payment system which requires only a soft wallet and runs on a set of smart contract extensions under the hood and enables them to securely swap, buy or sell with another party and subscribe to services by embedding clauses such as uploading evidence and reversing tokens back to owners when clauses are breached.

### Stablecoins

Stablecoin issuers such as Tether and Circle offer a 1 to 1 dollar stablecoin conversion which allows holders to use the dollar on the blockchain for cross border transfers or purchasing digital assets such as Bitcoin from exchanges. Stablecoins provide access to high inflation countries and citizens of countries with banking or currency restrictions to purchase, save or transfer value backed by the reserve currency without the need for traditional centralised authorities to verify and approve transactions. However, we believe there are limitations in global acceptance such as security concerns in holding and transfering stablecoins and a lack of options for utilising stablecoins for purchasing goods and services in the real world. This blog post will propose some extensions that utilise smart contracts that can help foster the growth of a decentralised p2p payment system across the world.

### Swaps

One problem that occurs lies with the safe transfer of a large amount of tokens in exchange with stablecoins from another party that satisfies concerns from both parties. An extension, which will be part of a decentralised payment portal that requests users' wallets to connect and then provides options of which one is to swap tokens with another wallet. An escrow smart contract with a condition to hold both amounts of tokens until both sides are shown a screen with the amount being held and are requested to confirm whether or not they accept the amount planned to be sent to them. If both do not confirm within a specified time period, such as 30 minutes, then the smart contract reverses the amount sent to it back to the original owners.

### Buy/Sell

Decentralised purchases or selling of goods and services is more tricky but can be overcome with the acceptance of criteria/clauses by both parties. For example, the seller can provide the clauses they are happy to work with and this will be displayed transparently before buyers proceed with the purchase. Each clause is approved by the buyer after viewing. For example; a picture of the goods and a delivery receipt from a third party company such as UPS (this may require locking in some amount to compensate the seller in case the buyer is not happy). Delivery company APIs can be used initially alongside an oracle network that can search up if the tracking number shows delivery status and a photo of the delivery. 

Ideally this would be supplemented with a product id registered on the blockchain which would provide the buyer some historical info regarding the product however this is a development that may not happen for some time. It would also be ideal if the address could be directly placed on the delivery via an api without the seller needing to access it. This is possible, but will require further research.

A mock up can be seen below:

![Mock Up](/images/mockup.png)

### Subscription

Owners of applications or content who wish to use a decentralised payment system to manage and provide access to their content or services can mint a unique token that expires and send to their subscribers who can then access content by a smart contract confirming they own the right token.

### Native token fees

To remove friction paying for blockchain fees and oracle fees, a transaction fee in the same stablecoin/token will be taken and swapped automatically via a decentralised liquidity pool in order to pay for these fees. 



