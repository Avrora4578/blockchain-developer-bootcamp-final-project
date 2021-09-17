# blockchain-developer-bootcamp-final-project

# Decentralized Auction

## Concept

This project aims to create an auction platform without any charge by an auctionieer or third party. It is based on a permissioned blockchain which accepts only credit worthy bidders. Each auction on the platform is identified by a non-fungible token assigned to it (or an Event in Solidity. I will fix details later), and each auctioned item is to be tokenized too. A bidder who has offered a highest price would obtain a token linked to an auctioned item and get it physically delivered later.

## User Flow

1. A User registers with the auction site as a seller or bidder using his Ethereum account address.
2. A bidder uploads her item on the site with its photo, token, and/or a signed contract form to transfer the item/token.
3. Users registered as a bidder can tender a bid by a specified deadline, and the highest bidder automatically receives a token associated with the item (and/or the contract form to transfer the item).
4. Simultaneously with the token transfer above, the seller receives the price offered by the highest bidder without any charge, and will deliver the actual item to the bidder.

## To Consider
1. Should there be some penalty on a seller in the case of selling a fake item?
2. How does the smart contract secure a delivery of an item after an auction? One possbile way is to hire an escrow agent which stores an item until a highest bidder requests its delivery. However, it would reslt in introducing a third party into this platform, which contradicts the concept of autonomous auction system.

