# Twitter_Sentiment_Analysis

With this project I have tried to check if there is a way to predict stocks's rates of return after 4, 5 or 10 days 
using Twitter post sentiment. This has been done based on the research of Sul et al.( 2017) [^1] and Duz & Tas (2020) [^2]
which stated that there is indeed a connection between sentiment and rate of return, especially in the case of
small companies or companies with an outstanding social media interest.


Thus, in order to verify and highlight these characteristics, I have chosen to study the effects of 
Twitter sentiment on AMD's, Nvidia's, Tesla's and Nasdaq's rates of return.


My findings thus far confirm the existing research, as the easiest to predict rates of return are those of
AMD and Tesla, a small company and a company that attracts a significant amount of attention, while the 
worst performing models where those of Nasdaq and Nvidia, a stock index and a large corporation.

The analyses used are:
* a series of linear regressions between the Twitter sentiment and the 4, 5 and 10 rates of return
* a multiple linear regression where it was attempted to predict Nasdaq's rate of return using AMD's, Nvidia's and Tesla's stock sentiment
* a series of logistical regressions that tried to predict if the rate of return would be higher than the median or not



Sources:
[^1]: Sul H. K., Dennis, A. R., & Yuan L. (2017). Trading on twitter: Using social media sentiment to predict stock returns. Decision Sciences, 48(3), 454-488.
[^2]: Duz Tan S., & Tas O. (2020). Social Media Sentiment in International Stock Returns and Trading Activity. Journal of Behavioral Finance, 1-14
