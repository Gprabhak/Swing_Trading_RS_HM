Strategy: Weekly Buying based on Relative Strength [RS] and Hilega-Milega
Initial Screen Stocks from quarterly OHLC [Stocks Outperforming Index]
    - RS [compared with Nifty50] 
    - Trade Window: (RS > 0) to (RS < RS[-1])
    - Lookback 3 quarter
Weekly Screen from weekly OHLC
    - Buying HM-1 [Evaluates Price, Strength, Momentum and Volume]
    - WMA21 > WMA21[-1] (or) WMA21 > SMA3[WMA21]
    - Positive RS and (RS[SMA5] > RS[-1][SMA5]) [Slope from Linear Regression should be tried]
Trade Parameter:
Entry Price
    - Type 1: Weekly Close
    - Type 2: 1/3 * [Entry Price - Stop Loss]
Stop Loss
    - Weekly Close < Swing Low Weekly     
Target [Needs to be determined]
    - Type 1: 11 % 
    - Type 2: 3 * [Entry Price - Stop Loss]
    
Input files: 
    - nse_total_list.csv
    - Datasets - quarterly and weekly OHLC (/raw_data/monthly_ohlc)
Output file: swing_RS_HM_signals.csv
