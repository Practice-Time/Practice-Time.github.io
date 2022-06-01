---
layout: default
title: BPoint
#next_section: <tbc>
layout: default
---

[Bpoint developer reference](https://www.bpoint.com.au/developers/v3/)

## Water Corporation

WaterCorp uses BPoint integration in two areas:
- [Pay My Bill](https://www.watercorporation.com.au/Bill-and-account/Pay-my-bill)
- [Direct Debit](https://www.watercorporation.com.au/Bill-and-account/Set-up-direct-debit)

To be PCI compliant, **Javascript - Advanced** transaction must be used for both Transactions (payment) and Tokens (direct debit).

The web page receives user credit card details and talks directly to BPoint. **There must not be any middleman in between** as that will make it non PCI compliant.

VERIFY_ONLY transaction is applicable only to Visa / Mastercards. American Express is not supported.

Getting auth key and looking up transaction result were done by calling Azure function apps.

Lessons learned:
- When integrating with BPoint, all failed scenarios must be considered and tested properly. e.g. auth key timeout, wrong parameters, failed transactions, etc.
- BPoint UAT has been the difficulty in testing as it slightly differs with production as sometimes the banks process things differently in production. Test credit cards with simulated error codes were used for testing. To promote confidence, test production page (hidden from user) was set up temporarily to PVT in production.

Talk to Johnson/Andreas or any Insight people working on Public Website if you require for more information.