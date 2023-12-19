# Unicorn-companies
I analysed data to learn about unicorn companies.

According to this dataset, there are 1221 unicorns (companies with a market capitalisation of over USD1 billion). https://www.kaggle.com/datasets/tahzeer/unicorn-startup-companies-july-2023
This data was collected in July 2023 thus is relatively recent. A unicorn company must meet the conditions of having a valuation of over 1 billion US dollars and it must be privately held thus hasn’t undergone an Initial Public Offering (IPO).  As a result of unicorns being privately held companies, they often secure funding from venture capitalists, private equity firms, or institutional investors. Therefore, I will analyse which investors are the most prominent in funding unicorn companies. Unicorns are often startups thus the dataset doesn’t include established companies such as Apple. 
The purpose of this research is to learn more about unicorn companies as well as improving my data analysis skills.



Which countries have the most unicorn companies?
![image](https://github.com/AdamH489/Unicorn-companies/assets/122322345/fef6383f-14a3-417c-aff3-9d81bcfe41bb)

As seen, the United States is by far the country with the most unicorns with 656 and China is second with 173. Unicorn companies are rare as there are only 11 countries which have more than 10 unicorns.

Which industries have the most unicorns?
![image](https://github.com/AdamH489/Unicorn-companies/assets/122322345/da701e3c-a3ff-4937-a102-64bca69b2fb7)
The industry which has the most unicorns is ‘Enterprise Tech’ with 370 unicorns. This is by far the industry with the most unicorns with ‘Financial Services’ second with a value of 216 closely followed by ‘Consumer & Retail’ with 215 unicorns. It should be noted that there are only 7 industries in the whole dataset thus there may be some mis categorisation when the dataset was prepared thus leading to less accurate results. For example, is a financial technology firm in the ‘Enterprise Tech’ or ‘Financial Services’ industry? 

What is the average valuation of a unicorn company in each industry?
Before answering this question, the dataset had to firstly be cleaned as the ‘Valuation ($B)’ column gives values with a $ before each value. Data cleaning was done within excel by utilising the find and replace function to find $ and replace with a blank space. When applied to the entire column, this has now made the data suitable to perform the operation. Having done this and ran the code I got the following output:
![image](https://github.com/AdamH489/Unicorn-companies/assets/122322345/d6016f7a-4b51-440e-b251-86b2daf630f3)
The industry which has the highest average valuation for unicorn companies is ‘Media & Entertainment’ with a value of $6.15 billion and this is by far the highest average valuation as second is ‘Financial Services’ with a value of $3.27 billion. There were only 81 unicorn companies in the ‘Media & Entertainment’ industry, but these companies are of a high value on average. There are 216 unicorns in the ‘Financial Services’ and these companies also have a high valuation. ‘Insurance’ has the lowest average valuation of unicorns as well as the lowest number of investments into unicorns in the dataset. 

Who are the main investors into unicorn companies?
![image](https://github.com/AdamH489/Unicorn-companies/assets/122322345/3eb8cde2-980f-4e0d-a19d-0ed159724c3c)
As shown, the firms which are most prominent in investing in unicorns are Andreesen Horowitz and Accel who have both invested into 64 unicorns respectively. Other prominent unicorn investors include Tiger Global Management, Sequoia Capital, and Insight Partners.  It’s worth noting that Sequoia Capital also have ‘Sequia Capital India’ and ‘Sequoia Capital China’ within the dataset with 25 and 49 investments respectively thus including all their branches, Sequoia Capital have invested into the most unicorns out of all the unicorn investors. 

What is the average valuation of the unicorn for each active investor?
I have decided to define an active investor as an investor with more than 20 investments into unicorns. Having incorporated this into the code, I got the following output:
![image](https://github.com/AdamH489/Unicorn-companies/assets/122322345/6a1cb179-e477-4526-85f0-154fd0b5d2c5)
SoftBank Group and Sequoia Capital China have both seen their investments into unicorn companies have the highest average valuation with average valuations of $10.87 billion and 10.03 billion respectively. There is a correlation of 0.77 between the average valuation and number of investments which suggests that as investors invest into more unicorns, the average valuation of the company increases strongly. This correlation may occur because investors may increase their number of investments as their unicorn investments succeed. Another possible reason for this may be because established investors with a track-record of successful high-valued investments might attract more opportunities.

How many unicorns were there in each year?
In the ‘Date Joined’ column, there were multiple formats for this, there was the format of just the year the company became a unicorn and there was the date including the month and year. In my code, I had to standardise it to show the data in the format of just the year as I wasn’t interested in the specific day that the company became a unicorn. The code bought the following output:
![image](https://github.com/AdamH489/Unicorn-companies/assets/122322345/7ad59b45-c2a8-4315-ba42-fc4e77a1c6c2)
As seen, there were no new unicorns from 2008 to 2010 which could be explained due to the global recession caused by the subprime mortgage crisis. However, as seen the number of unicorns is increasing dramatically with the number of unicorns increasing by 809 between 2020 and 2023. This is interesting as there have been many recessions in countries around the world due to the lockdowns from many country’s governments. However, this shows that due to the lockdowns perhaps there are more unicorns due to many more people relying on the internet for working from home or increased technology usage from the lockdowns. As a result, there are more technology companies from these changing consumption patterns caused by the lockdowns thus explaining why the lockdowns has only increased the speed at which the number of unicorns is increasing. 

How many unicorns were there in each year broken down by industry?
![image](https://github.com/AdamH489/Unicorn-companies/assets/122322345/4ceb0417-822e-4008-bf7e-116b355f9913)
Note that this output shows how many unicorns there were in each year cumulatively thus for ‘Consumer & Retail’, there wasn’t an extra unicorn joining in 2011 from 2007, there were 0 new unicorns, the same unicorn that joined in 2007. This output is interesting for discovering which industries were responsible for a dramatic increase in unicorns from 2020 to 2023. We can see that there were 270 new ‘Enterprise Tech’ unicorns from 2020 to 2023 thus aligning with my explanation earlier that there were many new technology unicorns possibly due to changing consumer habits over the global lockdowns. There are also some interesting results from this output, for example, the number of ‘Financial Services’ unicorns increased from 49 in 2020 to 216 which is an increase by 167. 
Also, there was a large increase in ‘Consumer & Retail’ unicorns from 108 in 2020 to 215 in 2023; an increase by 107. This is surprising as consumption levels fell dramatically globally due to the recessions caused by lockdowns thus it is surprising that the number of retail unicorns increased so much. Perhaps a reason for this is due to people consuming retail products online thus providing opportunities for retail firms to sell online.

How long has by average each company been a unicorn in each industry?
![image](https://github.com/AdamH489/Unicorn-companies/assets/122322345/76c64970-a7b0-4350-85f9-31e14c8e1a2b)
We can learn from this output that ‘Consumer & Retail’ unicorns have been unicorns the longest out of the industries studied. ‘Healthcare & Life Sciences’ have been unicorns for the shortest period of time. As mentioned, unicorns are relatively new companies who are usually increasing in size at a rapid pace thus this explains why the average time spent as a unicorn in every industry is not for long. As there has been a significant increase in the number of unicorns from 2020 to 2023, it is not surprising that the average amount of time which a company has been a unicorn across all the industries is roughly 2 years and 9 months. 



