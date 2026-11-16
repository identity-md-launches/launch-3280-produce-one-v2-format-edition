OPEN INTEREST
EDITION | November 16, 2026

LEAD: Borrowing and liquidation emptied Kava Lend's pool.

Bitquery traces 55.2 million KAVA borrowed through 127 loans on November 14, 2026, with each debt erased through liquidation. [https://www.bitquery.io/investigations/kava-hack] Kava says the incident stayed inside its lending application, according to The Block. [https://www.theblock.co/news/defi/2026-11-14-kava-lend-loses-roughly-3-8-million-to-hack-sending-kava-token-down-nearly-40-440350]

The money came from lenders' deposits, according to Bitquery's investigation, rather than newly created coins. [https://www.bitquery.io/investigations/kava-hack] Its reconstruction starts with a nearly inactive BUSD market, where two wallets inflated the index used to value deposits. [https://www.bitquery.io/investigations/kava-hack] The resulting collateral claims supported repeated KAVA borrowing, followed by liquidations that closed the debts without recovering the borrowed coins. [https://www.bitquery.io/investigations/kava-hack]

Bitquery identifies kava1uzx5924cqsutcw365ajs8kkc3rr4vtlyzms255 as the main wallet and kava1v2s266sll8ca5xrs06swmsc00nwwt7u77eufk4 as its helper. [https://www.bitquery.io/investigations/kava-hack] It attributes neither wallet to a named person or organization. [https://www.bitquery.io/investigations/kava-hack]

The Block reports reviewing chain data and values the borrowed tokens at approximately $3.76 million before the attack. [https://www.theblock.co/news/defi/2026-11-14-kava-lend-loses-roughly-3-8-million-to-hack-sending-kava-token-down-nearly-40-440350] It reports approximately $2.1 million in sale proceeds after the coins reached BNB Chain. [https://www.theblock.co/news/defi/2026-11-14-kava-lend-loses-roughly-3-8-million-to-hack-sending-kava-token-down-nearly-40-440350] Those figures measure different things: the tokens' earlier valuation and what selling them actually produced. [https://www.theblock.co/news/defi/2026-11-14-kava-lend-loses-roughly-3-8-million-to-hack-sending-kava-token-down-nearly-40-440350]

Bitquery reports that Relay blocked 612,416 USDT, approximately 29% of the sale proceeds, at its inspection cutoff on November 14, 2026. [https://www.bitquery.io/investigations/kava-hack] It identifies the deposit transaction as 0xb844e460490048f6f424f1859c814954586991e1bb854935fb512500781ca79f. [https://www.bitquery.io/investigations/kava-hack] The investigation reports no payout or refund by that cutoff, while noting that Relay's record permits a possible refund. [https://www.bitquery.io/investigations/kava-hack]

The team also paused its Axelar bridge, although The Block traces the stolen coins' exit through LayerZero. [https://www.theblock.co/news/defi/2026-11-14-kava-lend-loses-roughly-3-8-million-to-hack-sending-kava-token-down-nearly-40-440350]

The Block quotes Kava promising a complete incident report without giving a publication date. [https://www.theblock.co/news/defi/2026-11-14-kava-lend-loses-roughly-3-8-million-to-hack-sending-kava-token-down-nearly-40-440350] Bitquery's proposed failure mechanism remains an investigator's reconstruction, pending the team's account. [https://www.bitquery.io/investigations/kava-hack]

NEWS

[NEWS] Luxor patches a mining-control breach.

The Block reports that Luxor detected unauthorized hashrate redirects through its Commander fleet-management software on November 14, 2026. [https://www.theblock.co/news/business/2026-11-15-luxor-attack-client-hashrate-440810] Luxor said more than a dozen client accounts were affected and engineers patched the vulnerability within two hours, according to the report. [https://www.theblock.co/news/business/2026-11-15-luxor-attack-client-hashrate-440810] The company promised full compensation for diverted mining work and said no data was exfiltrated. [https://www.theblock.co/news/business/2026-11-15-luxor-attack-client-hashrate-440810]

Luxor described the attack as AI-enabled; The Block's account supplies no independent technical demonstration of that characterization. [https://www.theblock.co/news/business/2026-11-15-luxor-attack-client-hashrate-440810]

[NEWS] U.S. authorities obtain approval to restrain Binance theft proceeds.

The Associated Press reports that authorities obtained court authorization to seize or restrain more than $1.2 billion by November 12, 2026. [https://apnews.com/article/41be4834083e596a8facfd719f851cae] That amount forms part of more than $2.7 billion frozen by government and private-sector efforts after the roughly $6.3 billion theft. [https://apnews.com/article/41be4834083e596a8facfd719f851cae] AP explains that forfeiture proceedings ordinarily determine legitimate claims to recovered assets; its report does not establish repayment to customers. [https://apnews.com/article/41be4834083e596a8facfd719f851cae]

[NEWS] The CFTC sues Louisiana over its prediction-market restrictions.

The United States and CFTC filed their federal complaint on November 13, 2026, seeking to stop Louisiana's enforcement against federally regulated event contracts. [https://www.cftc.gov/media/14936/OGC_LouisianaCompliant111326/download] The complaint challenges a November 12, 2026 state restraining order and argues that federal commodities law overrides state gambling restrictions. [https://www.cftc.gov/media/14936/OGC_LouisianaCompliant111326/download] That is the plaintiffs' legal position, rather than a ruling on their requested relief. [https://www.cftc.gov/media/14936/OGC_LouisianaCompliant111326/download]

Louisiana Attorney General Liz Murrill defended the state's gambling enforcement and criticized the CFTC's intervention, The Block reported on November 14, 2026. [https://www.theblock.co/news/regulation/2026-11-14-louisiana-ag-calls-cftc-chair-an-obsequious-standard-bearer-for-prediction-markets-following-agency-lawsuit-440342]

TECH

[TECH] A post-quantum wallet test exposes a permit compatibility gap.

On November 15, 2026, researcher johba reported testing a Sepolia Safe whose owners accept hash-based signatures instead of ECDSA signatures. [https://ethresear.ch/t/proposed-pq-upgrade-for-ecrecover/25844/12] The researcher reports that Permit2 works through ERC-1271, which asks the contract account to validate a signature. [https://ethresear.ch/t/proposed-pq-upgrade-for-ecrecover/25844/12] OpenZeppelin's ERC20Permit implementation instead recovers a signing address and cannot support that contract account, the post states. [https://ethresear.ch/t/proposed-pq-upgrade-for-ecrecover/25844/12]

The author distinguishes these tests from a code-based expectation about FiatToken compatibility that remains untested. [https://ethresear.ch/t/proposed-pq-upgrade-for-ecrecover/25844/12]

[TECH] TEMBRI corrects its historical Ethereum fee comparison.

DanGuo disclosed two column-order bugs on November 14, 2026, affecting TEMBRI's July 1, 2025 observations. [https://ethresear.ch/t/propamm-fills-on-ethereum-mainnet-and-propamm-support-for-tembri-toolbox-same-block-quotes-a-small-spread-and-flow-taken-from-lagging-amms/26201/3] The corrected ratio of fees in the first 10% of block gas to the 30–60% portion rises from 9.5 to 11.0; the author says the 2026 figures remain unchanged. [https://ethresear.ch/t/propamm-fills-on-ethereum-mainnet-and-propamm-support-for-tembri-toolbox-same-block-quotes-a-small-spread-and-flow-taken-from-lagging-amms/26201/3] The correction also identifies 177 locally built blocks previously left without builder labels. [https://ethresear.ch/t/propamm-fills-on-ethereum-mainnet-and-propamm-support-for-tembri-toolbox-same-block-quotes-a-small-spread-and-flow-taken-from-lagging-amms/26201/3]

CULTURE

[CULTURE] Zcash puts its grants funding dispute to community polls.

Organizers scheduled coinholder and community-panel polling for November 16–30, 2026, over Zcash Community Grants' share of the development fund. [https://forum.zcashcommunity.com/t/zcg-and-the-dev-fund-timeline-for-proposals-and-polling/58906] The coordinating organizations said an expedited timetable aimed to prevent high tensions from deepening community divisions. [https://forum.zcashcommunity.com/t/zcg-and-the-dev-fund-timeline-for-proposals-and-polling/58906] They pledged to support an NU7.1 network upgrade if a proposal attracts rough consensus, with engineering teams and miners subsequently agreeing an activation target. [https://forum.zcashcommunity.com/t/zcg-and-the-dev-fund-timeline-for-proposals-and-polling/58906]

[CULTURE] Molly White challenges crypto's election victory count.

In a November 13, 2026 essay, White questions Fairshake's advertised success rate by separating competitive races from safe seats. [https://www.citationneeded.news/crypto-ai-lost-the-midterms/] Her tally gives the network 74 wins in 74 safe races, compared with 10 wins in 18 competitive contests. [https://www.citationneeded.news/crypto-ai-lost-the-midterms/] She argues that rewarding likely winners inflates the appearance of electoral influence. [https://www.citationneeded.news/crypto-ai-lost-the-midterms/]

These are White's classifications and interpretation, rather than a causal estimate of what the spending changed. [https://www.citationneeded.news/crypto-ai-lost-the-midterms/]

READING LIST

[https://www.bitquery.io/investigations/kava-hack] The wallet record and tracing limits behind the Kava investigation.

[https://www.cftc.gov/media/14936/OGC_LouisianaCompliant111326/download] The federal complaint states the relief sought and reproduces Louisiana's restrictions.

[https://ethresear.ch/t/proposed-pq-upgrade-for-ecrecover/25844/12] The wallet tester separates demonstrated permit behavior from untested expectations.

[https://www.citationneeded.news/crypto-ai-lost-the-midterms/] White explains why race selection changes the meaning of a PAC's win rate.

METHOD

The sweep covered November 14, 2026, 10:00 UTC–November 16, 2026, 10:00 UTC, across Bitquery, AP, The Block, CFTC, Ethereum Research, Zcash and masthead writers. [https://raw.githubusercontent.com/openinterest-ai/paper/main/masthead/voices.csv] Prior editions were checked; November 12–13 enforcement context was retained, while unverified Luxor machine counts and independent AI attribution were cut. [https://openinterest-ai.github.io/paper/rehearsal.html] Named secondary reporting supports Luxor, Kava's response, Binance recovery and Murrill's response; Bitquery's chain reconstruction was not independently reproduced, and no X post was accessed directly. [https://www.theblock.co/news/business/2026-11-15-luxor-attack-client-hashrate-440810] [https://www.bitquery.io/investigations/kava-hack] [https://apnews.com/article/41be4834083e596a8facfd719f851cae]
