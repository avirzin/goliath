<img src="./images/goliath_logo.png" alt="Goliath logo" width="200"/>


# Goliath


An index-based fund on the blockchain allows investment in a diversified, low-cost portfolio using smart contracts, ensuring transparency and accessibility for people in Brazil and abroad. This project was originally start being for the [Blockchain Rio Hackathon 2024](https://taikai.network/blockchainrio/hackathons/blockchainriohack24), but I joined too late, so I'm currently developing it for my conclusion of the [Alchemy University Ethereum Dev Bootcamp](https://www.alchemy.com/university/courses/ethereum).


## The Problem


This project aimed to solve several key problems faced by individual investors, particularly those seeking long-term growth and financial security.


1. **Lack of Diversification** - Many individual investors struggle to achieve sufficient diversification in their portfolios, exposing themselves to higher risk by concentrating investments in a few stocks or sectors.

2. **High Investment Costs** - High fees and expenses can significantly erode investment returns over time, especially in actively managed funds.

3. **Complexity of Stock Picking** - Choosing individual stocks requires substantial research, time, and expertise, which can be challenging and overwhelming for many investors.

4. **Market Timing Risks** - Trying to time the market—buying low and selling high—is notoriously difficult and often leads to poor investment decisions.

5. **Inconsistent Performance of Actively Managed Funds** - Actively managed funds often fail to consistently outperform the market after accounting for fees, leading to disappointing returns.

6. **Transparency and Trust** Lack of transparency in some investment vehicles can lead to mistrust and uncertainty among investors.

7. **Long-Term Financial Goals** Achieving long-term financial goals such as retirement, education funding, or wealth accumulation requires a disciplined and reliable investment strategy.


## The Solution


Following the structure and strategy of one of the world’s largest and most respected investment companies the idea is structure an index-based fund in DeFi is designed to replicate the performance of a specific market index (top 100 crypto assets), providing a diversified, low-cost investment option. Here are the highlights:

1. **Diversification** - By investing in an index fund, you are effectively investing in a broad range of companies, spreading your risk across multiple sectors and industries;

2. **Low Costs** - The main focus is to benefit investors providing low expense ratios, resulting in more of your funds staying invested and result in potential grow over time;

3. **Long-Term Performance** -  Performance Explanation: Historically, index funds have consistently delivered solid returns over the long term, outperforming many actively managed funds;

4. **Simplicity and Transparency** - Index funds are straightforward to understand and manage, with clear objectives and transparent holdings;

5. **Passive Management** - The fund is passively managed, meaning it does not require active trading or stock picking, reducing costs and minimizing the risk of underperformance;

6. **Transparency and Trust** - The blockchain technology ensures transparency and trust, allowing investors to verify the fund’s holdings, performance, and fees at any time.

As an example, we consider investing in top 100 crypto assets with equal weight, and the fund will be rebalanced every quarter to maintain the target allocation. The fund will be managed by a professional fund manager who will oversee the fund’s operations, rebalancing, and performance tracking.

This is the [dataset](./data/crypto_top100_20240720.csv) that was extracted from CoinGecko and CoinMarketCap:

|Symbol|Name|Volume($)|Market Cap|Market Cap Rank|7D Change(%)|24H Change(%)|
|---|---|---|---|---|---|---|
|btc|Bitcoin|29170932924|1316155386703|1|13.8463024353|1.6455094063|
|eth|Ethereum|13854006879|421641087230|2|11.2073976248|1.3613438677|
|bnb|BNB|1148430002|91200416504|4|11.530399447|2.0263956427|
|...|...|...|...|...|...|...|
|ena|Ethena|112330718|851076112|99|26.056214969|4.5431090342|
|neo|NEO|21686471|829930552|100|15.5835334306|2.7088383571  |
|xtz|Tezos|33404385|793273762|101|2.4239090784|-2.2068254177|



[TODO: Insert chart here]


### Architecture


[TODO: Insert chart here]


### General Flow

The general flow of the solution is as follows:

1. **Investor Registration** - Investors register on the platform, providing their personal information and wallet address.

[TODO: RECHECK KYC/AML]
2. **KYC/AML Verification** - The platform verifies the investor’s identity and performs KYC/AML checks to comply with regulatory requirements.

3. **Investment** - Investors deposit funds into the index fund using DREX, which are converted into the fund’s shares.

4. **Fund Management** - The fund manager uses the deposited funds to purchase the underlying assets of the index fund, which are held in a smart contract.

5. **Index Fund Performance** - The index fund’s performance is tracked in real-time, reflecting the performance of the underlying assets.

6. **Redemption** - Investors can redeem their shares at any time, receiving the equivalent value in DREX.

7. **Reporting and Transparency** - The platform provides real-time reporting on the fund’s performance, holdings, and fees, ensuring transparency and trust.

8. **Compliance and Regulation** - The platform complies with regulatory requirements, ensuring investor protection and legal compliance.

## Additional diagrams

 

### Sequence Diagram



## Challenges and Risk



### The solution considering the Brazilian market

## References

- Book [from Vanguard];
- OpenBB Terminal index performance;