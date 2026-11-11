# Smart India Hackathon Workshop
# Date: 11/11/2026
## Reference Number: 26008206
## Name: Saravanan R

## Problem Title
SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices.

## Problem Creater's Organization
Ministry of Consumer Affairs, Food & Public Distribution

## Theme
Agriculture, FoodTech & Rural Development

## Problem Description
Expected Solution: Create a digital marketplace that:

• Connects farmers/FPOs directly with consumers and bulk buyers.
• Provides logistics support.
• Uses AI for demand forecasting and route optimization.

Benefits:

• Better prices for farmers.
• Lower prices for consumers.
• Reduced supply chain inefficiencies.

## Proposed Solution
1.<b>My solution<\b>: benefit for farmers is a website where buyers and farmers agree on a deal before the crop is even grown.
2.<b>how we address this<\b>:
Big buyers like hostels, hospitals, canteens, hotels and food companies post what they need. For example: 50 quintal onions, grade A, needed in January, at this price.
Farmers or FPOs (Farmer Producer Organizations) log in, see the demands for their area and crop, and commit to supply.
If one farmer can’t fill the whole order, a few farmers can join together and supply it as a group.
A digital contract is made with the quantity, quality, price and delivery date.
The buyer pays a small advance (10 to 20%) into a safe escrow account. The rest is paid after delivery and quality check.
3. <b>Innovation and uniqueness of the solution<\b>:
Farmers deal directly with buyers, so agents and wholesalers are not needed.
The price is fixed before harvest, so farmers are not forced to sell cheap.
The advance payment gives farmers some security and money to start farming.
Small farmers can reach big buyers by working as a group.

## Technical Approach
1.<b>Technologies we will use<\b>:
Frontend: React (or Next.js) with Tailwind CSS
Backend: Node.js with Express (or Django)
Database: PostgreSQL
Login: OTP verification and DigiLocker for identity
Mandi price data: Agmarknet and eNAM open data
Contracts: auto-generated PDF with eSign
Payments: UPI and Razorpay escrow
Alerts: SMS and email
Hosting: AWS or Render
2. Methodology :
<b>Flow chart<\b>:
  Buyer registers on the website
                      |
                      v
        Buyer posts demand (crop, quantity,
         quality, price, delivery date)
                      |
                      v
        System finds farmers/FPOs growing
          that crop in the same region
                      |
                      v
         Farmers accept and commit supply
          (alone or as a group)
                      |
                      v
        System compares offered price with
             mandi price / MSP
                      |
                      v
                Is the price fair?
               /                 \
             No                  Yes
             |                    |
             v                    v
     Buyer changes         Contract is created and
     the offer             signed by both sides
     (goes back up)                |
                                   v
                       Buyer pays advance to escrow
                                   |
                                   v
                     Farmers grow and harvest the crop
                                   |
                                   v
                   Delivery to buyer + quality check
                                   |
                                   v
                           Quality okay?
                          /            \
                        No             Yes
                        |               |
                        v               v
               Problem is sent     Remaining payment goes
               to FPO / inspector  to farmers through UPI
                                        |
                                        v
                              Ratings given to both sides

## Feasibility and Viability
1. <b>Analysis of the feasibility of the idea<\b>:
Technical feasibility: The portal needs only normal web technology (React, Node.js, PostgreSQL). Mandi price data from Agmarknet and eNAM is free and open. Login, eSign and payments can use ready-made services like DigiLocker, eSign and Razorpay, so we do not need to build them from scratch.
2. <b>Potential challenges and risks<\b>:
Contract breaking: A farmer or buyer may not follow the contract.
Low digital literacy: Many farmers may not know how to use a website.
Crop failure: Weather, pests or disease may reduce the harvest.
Quality disputes: Buyer and farmer may disagree on the quality at delivery.
Slow buyer adoption: Buyers may not join in the beginning.
Unfair prices: A buyer may offer a very low price.
Lack of trust: Farmers may not trust a new online system.
Poor internet: Network connectivity in villages can be weak.
3.<b> Strategies for overcoming these challenges<\b>:
 Contract breaking: Keep the advance payment in escrow, give ratings to both sides, and write penalty rules in the contract.
Low digital literacy: Provide simple pages in regional languages, and help from CSC and FPO operators.
Crop failure: Allow partial delivery in the contract, and link crop insurance through PMFBY.
Quality disputes: Use AGMARK grade standards in the contract, and a third-party inspector for disputes.
Slow buyer adoption: Start with institutions that already buy in bulk, such as hostels, hospitals and mid-day meal schemes.
Unfair prices: Compare every offer with the mandi price and MSP, and ask the buyer to revise low offers.


## Impact and Benefits
1. <b>Potential impact on the target audience<\b>:
  Farmers: They know their buyer and price before harvest, so there is less risk and better income.
Buyers: Regular supply of the quality they need, at a lower cost than buying through many middlemen.
FPOs and CSC centres: A new role in organising farmers and helping them use the platform.
Consumers: Fewer sudden price jumps.
2.<b> Benefits of the solution (social, economic, environmental, etc.)<\b>:
Economic: Farmers earn more per crop, and buyers spend less on procurement.
Social: Small farmers get access to big buyers and depend less on agents and moneylenders.
Environmental: When farmers grow what is actually needed, less produce is wasted.


## Research and References
1.<b> Details / Links of the reference and research work <\b>:
Model Contract Farming Act, 2018 (NITI Aayog)
Agmarknet and eNAM websites for mandi prices
Ministry of Agriculture and Farmers Welfare: FPO scheme
NABARD and NITI Aayog reports on agricultural marketing
