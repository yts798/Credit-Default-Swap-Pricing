# Credit-Default-Swap-Pricing
Credit Default Swap Pricing Python Implementation
The task involves calibrating a survival curve based on observed market CDS spreads and a term structure of interest rates. We employ a bootstrap method with linear interpolation and the Nelson-Siegel model to capture the term structure dynamics. The process includes calculating the value of protection and premium legs of a CDS and determining the mark-to-market value.

## Model Overview

The pricing model calculates the present values of both cash flow legs of a CDS contract:
- The **protection leg** reflects the present value of potential credit event payouts.
- The **premium leg** reflects the present value of periodic premiums paid by the protection buyer.

The difference between these two legs gives the mark-to-market value of the CDS contract. This value can be adjusted for accrued interest to obtain the clean mark-to-market value.

## Results

The valuation process reveals the cost of protection versus the income from premiums over the life of the CDS. It provides insight into the perceived credit risk of the reference entity and the fair value of credit protection in the current market.
