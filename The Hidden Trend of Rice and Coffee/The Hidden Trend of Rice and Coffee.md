# The Hidden Trend of Rice and Coffee

**By** Wenying Wu, 06/05/2022

## Context

Looking at the previous post’s finding, which is that the consumption of meat per capita is increasing over time, I wondered what the historical trend of price change in food is. Therefore, this post utilizes a dataset from Kaggle, which contains both historical price and historical price adjusted for inflation of beef, coffee, and rice to examine the trends of historical price change. And I will be using the price adjusted for inflation records because the adjusted price is more capable of comparison with the price at a different time.

## Data Narrative

The plot of historical prices shows the trend of adjusted prices for beef, coffee, and rice. One interesting finding is that the coffee price was higher than the beef price around 2011. While rice price is the lowest all the time. One of the underlying reasons might be that rice is a kind of staple commodity grain while the others are not. 

The spike in coffee prices around 2011 was a surprise to me as I did not expect the coffee price will be higher than the beef price at any point in time. But after some research, I realized that the spike in price is a consequence of the [growing demand for coffee from developing countries and disappointing coffee yields in Colombia](https://www.theguardian.com/business/2011/apr/21/commodities-coffee-shortage-price-rise-expected)


<p align="center">
  <img src="https://github.com/Wenying-Wu/Data-Visualization-and-Analysis/blob/main/src/The%20Hidden%20Trend%20of%20Rice%20and%20Coffee/image001.png">
</p>

The only obvious peak in the rice price is the one in 2008, and the reason I plot the percentage of difference graph (comparison with the price in 2000) is to examine this change further. We can see that the percentage change for rice is more than 200%, and the price difference for beef is more than 50%. I was confused about this trend because the price of these two commodities is changing drastically, but the coffee price has not changed much, and why the economic crisis is driving the price up instead of bringing the price down. Thanks to some further research, I realized that the cause of this price peak was not the economic crisis but the [2007-2008 world food price crisis](https://en.wikipedia.org/wiki/2007%E2%80%932008_world_food_price_crisis). And the great recession is instead the driving force behind the sharp drop in price in late 2008. 

## Conclusion

In conclusion, this story tells us that the relevant knowledge of the data is very important for getting the correct analysis, and we should always research for any uncertainties. More importantly, we should pay more attention to those data with different scales. For example, the rice price is much lower than the coffee and beef price in this dataset, but the percentage change in rice price is huge in a spike that is not that obvious compared to those spikes in beef and coffee. 
 
## Reference

Guardian News and Media. (2011, April 21). Coffee prices expected to rise as a result of poor harvests and growing demand. The Guardian. https://www.theguardian.com/business/2011/apr/21/commodities-coffee-shortage-price-rise-expected 

Wikimedia Foundation. (2022, April 28). 2007–2008 world food price crisis. Wikipedia. https://en.wikipedia.org/wiki/2007%E2%80%932008_world_food_price_crisis 

 
