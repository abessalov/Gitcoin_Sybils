# Gitcoin Exploratory Data Analysis Bounty to Defend Public Goods Funding from Sybil attacks
The link: https://gitcoin.co/issue/29675

## Files description

- README.md - challenge and files description.
- Gitcoin.pdf - solution presentation.
- startup.py - initial script that executed in every notebook when started (libraries loading).
- 01.data_preprocessing.ipynb - Merge all Gitcoin grant votes datasets together.
- 02.data_statistics.ipynb - General statistics of the past Gitcoin rounds.
- 03.sybil_searching.ipynb - Hash popularity distribution method to find potential Sybil attacks.
- 11.parse_etherscan.ipynb - getting Ethereum transactions by using etherscan API.
- 12.get_transactions.ipynb - Collecting and preprocessing transactions table from the Etherscan API requests.
- 13.generate_features.ipynb - feature generation on the Ethereum transactions dataset.
- 14.explore_wallets.ipynb - generating the final output and statistics calculation.

---

## Challenge Description

In this challenge, you will analyze any sources you find relevant, likely to include the data sets from the Fantom and Unicef Gitcoin public goods rounds. This bounty in particular rewards innovative exploratory data analysis - including your approach to analysis and the data sets that you select. The goal is to more efficiently find Sybils.

ALSO - a bonus to anyone that can provide some initial impressions of the Alpha Grants Round kicked off by Gitcoin on January 17th, 2023. Are there Sybils that were active in the Fantom and/or Unicef rounds or elsewhere appearing on the current Gitcoin hackathon? Please reach out directly to any of the organizers on Discord, including me - epowell101 - or directly to Gitcoin FDD members such as Disruption Joe with your initial reactions.