# USD-Coin-Solana-Hackaton-2022
USD Coin Point of Sale project submitted to Solana Summer Hackaton 2022

The project allows medium and small business owners of the world to
accept USD Coin payments and have them deposited in the non-custodial wallet.
A typical arrangement will have a phone with optional bluetooth receipt 
printer or Android Point of Sale operated by a clerk to receive payments,
and linked to a Solana compatible wallet in the store owners phone or PC.
The application stores transactions records in the terminal and generates
receipts and reports. It can configurable tipping amounts and donations.

You will find here the Android source code used to develop and test the code.
The code has been incorporated in the Technoprepay's point of sale terminal
which you can download soon from google play using this link:
https://play.google.com/store/apps/details?id=com.technoprepay.solanapos

The application works on a regular Android phone and can interface with an optional
bluetooth receipt printer. It also works on Android Point of Sale terminals.
The Application has been tested with Sumni V2 POS and Wisenet N5 POS, those are
low cost non banking POS that you can buy in Amazon.com

Technoprepay is a Canadian company owned by Juan C Vera, orignary from El Salvador,
Central America and with 25 years in point of sales and programming experience.
Technoprepay isbased in Vancouver Canada. 
Our goal is to bring point of sale payment solutions for medium and small companies
of the world.

We experimented with Solana Pay as you can see in the sample code and pictures,
but opted for monitoring the balance to detect when mayment is made in order
to avoid the need to set up a server or web solution. The application uses
https://solscan.io/ to monitor the balances and obtain the transactions, and
it could be speed up by connecting directly to a node to obtain the early
changes in the account and deposits.

Project Video:
https://youtu.be/oNOpWVkN3jo




