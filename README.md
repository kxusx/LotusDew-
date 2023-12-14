I have meticulously crafted a trading strategy that leverages historical stock prices, employing a moving average approach(giving lesser weightage to older prices) to determine optimal selling prices for each stock. By capturing the last 300 prices for each stock and organizing them into a dictionary with the stock symbol as the key and prices as a vector, I establish a comprehensive foundation for analysis.

My strategy revolves around buying and selling stocks that have exhibited percentage changes above the 90th percentile of consecutive time intervals. A key refinement involves incorporating a condition: if the moving average falls below the buying price, I exercise patience and refrain from selling, anticipating a more opportune moment in the market.
