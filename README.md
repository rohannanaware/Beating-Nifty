
# Plan for investment

- [Value investing](#value-investing)
- [Stock investment and trading](#stock-investment-and-trading)
- [Mutual fund investment](#mutual-fund-investment)
- [Reference](#reference)

## Value investing

- [5 Must-Have Metrics for Value Investors](https://www.investopedia.com/articles/fundamental-analysis/09/five-must-have-metrics-value-investors.asp)

## Stock investment and trading

- Document all content related to investment and trading of scripts
- Include details for mutual funds as well
- Reference material

### Identifying stocks to invest in

- Industries wih the low P/E
- Industries with strong financials - Fundamental analysis
- Industries in sectors that show highest growth prospects
- Industries without any legal cases against thier management
- Industries with no significant competitors in near future

1. PNB - 
    - Key support level at 75. Current price `29th Apr 2018` stands at ₹ 93.4
    - Stock not on an uptrend but on a sidewise pattern. Still current price makes a good case for point of entry
    - Wait for the stock to go lower(85-90). Check if news supports uptrend
    - `Update - 09th Jun 2018` - Goof call, although I entered early. Also the stock did bounce back from the critical support level
    - The projected growth rate from PNB is ~11%. Advisable to pull money out, cut losses and invest in stocks with higher growth projections. Also wait for the time it takes to clear out the scam details
    - **Wait for the quarterly results of Jun 2018. Since there was money kept in reserves I belive the profit in this quarter will show growth and the stock may rise** - read for predictions and choose a point of entry - If money isnt available, study the effects of either case - rise/ fall 
    
2. HEG - 
    - `09th Jun 2018` - Stock at a low P/E also the growth shown is more than 30% in net profits. Need to read through the financials in more detail. Whats the dept to equity and plan for growth and who are the other players in category. Money unavailable for investment
    - `08th Jul 2018` - Stock has reported high growth rate consistently. Plans to leverage the increase in demand of graphite electrodes from China. China is planning to increase the share of Iron and Stell produced from Electrical Arc Furnance from current 9% to 20% by the year 2020. It has also reduced it's exports so other countries adopt the same production technique to meet demand. Entered at 3323.90
3. Graphite India - `09th Jun 2018` - Same as HEG. But able to leverage the Graphite demand better. Entered at 832.47
4. Sanwaria Consumer - `09th Jun 2018` - Bought 190 shares at a price of ₹13.15. Good financials. Need to define target. Clear resistance level at ₹22 and ₹29
5. Prakash - `09th Jun 2018` - Slightly late from point of entry perspective, but good potential for grwoth. Need to perform FA and category comparison
6. JSW Steel : `17th Jun 2018` - Industry shows strong growth but the level of debts show concerns. Plans to reduce the level of debts is something the industry is working on by creating efficient plants, recent aquisitions may put stress on next quarterly results
7. Manpasand Beverages : `05th Jul 2018` - Strong balance sheet. Virtually debt free, high unpledged promoter holding. Has partnered with Parle to increase market reach. Has outlook for becoming international brand. Entered at 155.75

## Mutual fund investment

### Identifying mutual funds to invest in

- Metrics to be considered :
    - Returns vs. Category average vs. Nifty(compare for last 5 years)
    - AUM
    - How old the stock is (>3years)
- List as of Apr 2018    
    - HDFC Small Cap Fund (G)
    - Axis Focused 25 Fund(G)
    - IDFC Tax Advantage (ELSS) Fund - Direct Plan (G)
    - Any of the 4 stocks already invested in
    - IDFC Focused Equity - Direct (G)
    - Axis Midcap Fund(G) - Crisil rank 5
    - Kotak Select Focus Fund - Direct Plan (G)

- List of metrics(from reference material 2.1)
    - Popular funds suffer as the fund managers are forecase to invest at least 65% of the available cash
    - Few funds have shown attractive growth in last 2 years due to their higher risk taking behaviour but the probabilty of their strategy to always work is low
    - **Track record for last 10 years** : 
        - Look into the track of funds for last 10 years, the fund need not be the top in the list but rather a part of top 25(above average within category) consistently. Eg. - Aditya Birla Sunlife : This fund has outperformed both the index and category average. Also it's ranked in top 25 consistently
            <img src = "https://raw.githubusercontent.com/rohan193/Trading/master/images/Aditya-Birla-Sunlife.png">
        - Has the fund been under the same fund manager? What is the track record of the fund manager across all the funds that he is managing?
        - What was the AUM in the fund then and now? Has there been an increase in the AUM in recent years? Will that create a problem for the fund manager?
            - AUM limits - LC(5k crores); MC(2k crores)
        - Check the track record of Risk vs. Return
            - Less risk and more return preferred
            - LC are less risky than MC
        - <img src = "https://raw.githubusercontent.com/rohan193/Trading/master/images/2018%20MF%20SIP.png">
        
 - Reference material 2.2
    - SUNDARAM SELECT FOCUS FUND
    - TEMPLETON INDIA GROWTH FUND
    - TATA INDIA TAX SAVING FUND

# Web scraping

- Objective - Build a framework that can help shortlist sripts good for investment in the upcoming quarter. This framework will filter the amount of scripts that will be fed into the algorithmic trading

- **Phase 1** Scrape the details that can help assess the fundamental health of a stock entity
- **Phase 2** Build an app/ screener/ health tracker that can suggest scripts using fundamental analysis
- **Phase 3** Monetize by deployement or app development

#### Phase 1

- Start with scraping data from moneycontrol - 
  - Scrpit - [Sanwaria Consumer Ltd.](http://www.moneycontrol.com/india/stockpricequote/edible-oils-solvent-extraction/sanwariaconsumer/SAO)
  - Details to be scraped - Financials, Balance sheet, PnL, Financial ratios
  
- Next steps - 
  - Share details for the script and braistorm on the metrics to be calculated on top of the data
  - Understand what goes into coming up with a metric, its significance
  - Parameterize the code for any script
  - Get a view on the code run time and methods to improve the same
  - Fix on the frontend layout

## Reference 

1. Rupeevest
    - [Methodology](https://www.rupeevest.com/Mutual-Funds/Rating)
    - [Top MFs](https://www.rupeevest.com/Mutual-Funds-India/Best-Mutual-Funds)

2. Youtube
    - [How to Select Best Mutual funds - Pranjal Sharma](https://www.youtube.com/watch?v=RJdxuaR4cKU)
    - [Best mutual funds in India for 2018 - Pranjal Sharma](https://www.youtube.com/watch?v=Okrd_rqi8Fs)
    - [How The Economic Machine Works by Ray Dalio](https://www.youtube.com/watch?v=PHe0bXAIuk0)
    - [Principles For Success by Ray Dalio (In 30 Minutes)](https://www.youtube.com/watch?v=B9XGUpQZY38)

3. Metrics to select mutual funds
    - [What are the best mutual funds to buy?](https://www.quora.com/What-are-the-five-best-mutual-funds-in-2018)
    - [5 Must-Have Metrics for Value Investors](https://www.investopedia.com/articles/fundamental-analysis/09/five-must-have-metrics-value-investors.asp)
 
4. Zerodha
    - [Fundamental analysis](https://zerodha.com/varsity/)
    
5. [Screener](https://www.screener.in/)
