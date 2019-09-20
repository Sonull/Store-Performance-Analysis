## Goal of the Project
Analyze the performance of the store using Tableau

## HeatMap on Sales
![Worksheet%201](https://github.com/Sonull/Store-Performance-Analysis/blob/master/Worksheet%201.png)
* California made the highest sales - $ 1.1Mn which was 13% of the overall sales
*	The state with lowest sales was Delaware with only $3,543 which was 0.04% of the overall sales   
* California made around 300 times more sales than Delaware
*	The top 5 states – California, New York, Illinois, Texas and Washington, made 42% of the overall sales


![Worksheet%202](https://github.com/Sonull/Store-Performance-Analysis/blob/master/Worksheet%202.png)
*	The maximum sales in the product category ‘Technology’ was made in Central region followed by the West. This can be attributed to major presence of technological companies in both these regions
*	The Southern region had the lowest sales across all three categories

![Worksheet%203](https://github.com/Sonull/Store-Performance-Analysis/blob/master/Worksheet%203.png)
*	The Customer segment ‘Corporate’ had $3.2Mn sales which was the highest across all customer segments
*	The ‘Home office’ segment had second highest sales which was $1.1Mn less than the ‘Corporate’ segment
* The ‘Small Business’ segment had the lowest sales of $1.7Mn, around $156K less than the ‘Consumer’ segment but made around $109K more in profit


## Overall product category level KPIs
![worksheet%204](https://github.com/Sonull/Store-Performance-Analysis/blob/master/worksheet%204.png)
*  The average sales in the Product Category ‘Furniture’ is the highest : $1,664.40
*  On an average, the sales in ‘Furniture’ and ‘Technology’ were 4 times the sales in ‘Office Supplies’  respectively
*  The Minimum sales in each of the categories was less than or equal to ~ $5
*  The standard deviation of sales of ‘Furniture’ is 224% of the average sales. In other words, the coefficient of variation is = 224% :
    * CV = ($ 3680.29/$ 1644.40) * 100 = 224%
*	The coefficient of variation for sales of ‘Office Supplies’ is 336% while for Technology, it is 209% calculated as :
    *	CV for ‘Office Supplies’ = ($ 1465.10/$ 435.89) * 100 = 336%
    *	CV for ‘Technology’ = ($ 3173.58/$ 1520.32) * 100 = 209%
*	Thus, there is more variability in the sales within the ‘Office Supplies’ category as compared to both ‘Technology’ and ‘Furniture’. This can be attributed to the range of product sub categories of different price points in ‘Office Supplies’ as compared to the ‘Furniture’ and ‘Technology’
*	The Maximum sales in ‘Furniture’ was $100,119.16 which can be considered as an outlier as it is more than the 3 sigma upper limit:
    *	 Average + 3* std dev = $1644.40 + 3* $3680.29 = $12,684.4
*	Similarly, the maximum sales in the other two categories can also be considered as the corresponding outliers since they are more than the corresponding 3 sigma limits:
    *	 Upper limit for ‘Office Supplies’ = $435.89 + 3* $1465.10 = $4,831.19 < the maximum sales = $45,737.33
    *	 Upper limit for ‘Technology’ = $1520.32 + 3* $3173.58 = $11,041.06 < the maximum sales = $50,332.66
*	The  Minimum sales in ‘Furniture’ was $2.77 which can be considered for the analysis as it is more than the 3 sigma lower limit:
    *	 Average - 3* std dev = $1644.40 - 3* $3680.29 = -$9,396.47
*	Similarly, the minimum sales in the other two categories can also be can be considered for the analysis since they are more than their corresponding 3 sigma limits:
    *	 lower limit for ‘Office Supplies’ = $435.89 - 3* $1465.10 = -$3,959.41 < the minimum sales = $1.32
    *  lower limit for ‘Technology’ = $1520.32 + 3* $3173.58 = -$8,000.42 < the minimum sales = $5.46
*	On an average, the profit earned in ‘Technology’ product category was $295.56 which is three times the profit earned in both ‘Office Supplies’ and ‘Furniture’ categories respectively
*	At least 50% of the sales within ‘Furniture’ as well as ‘Office Supplies’ product category earned no profit to the store. They were in fact made at a loss.
*	Highest profit, which is $16,332.41 was earned within ‘Office Supplies’ category which is around twice the profit made within both ‘Technology’ as well as ‘Furniture’ categories respectively
*	The standard deviation of profit of ‘Furniture’ is 1138.25% of the average profit. In other words, the coefficient of variation is = 1138.25% :
    *	 CV = ($ 1044.35/$ 91.75) * 100 = 1138.25%
* The coefficient of variation for profit of ‘Office Supplies’ is 860% while for ‘Technology’, it is 461% :
    *  CV for ‘Office Supplies’ = ($ 750.33/$ 87.24) * 100 = 860%
    *	 CV for ‘Technology’ = ($ 1363.78/$ 295.46) * 100 = 461%
*	That is, there is huge variability in the profit within each of these three product categories.
*	The Maximum profit in ‘Furniture’ was $7,635.84 which can be considered as an outlier as it is more than the 3 sigma upper limit:
    *	 Average + 3* std dev = $91.75 + 3* $1,044.35 = $3,224.8
*	Similarly, the maximum profit in the other two categories can also be considered as the corresponding outliers since they lie outside their corresponding 3 sigma limits:
    *  Upper limit for ‘Office Supplies’ = $87.24 + 3* $750.33 = $2,338.23 <  the maximum profit = $16,332.41
    *  Upper limit for ‘Technology’ = $295.46 + 3* $1363.78 = $4,386.7 < the maximum profit = $9,195.97
*	The minimum profit in ‘Furniture’ was - $13,706.46 which can be considered as an outlier as it is less than the  3 sigma lower limit:
    *	 Average - 3* std dev = $91.75 - 3* $1,044.35 = -$3,041.3
*	Similarly, the minimum profit in the other two categories can also be considered as the corresponding outliers since they lie outside their corresponding 3 sigma limits:
    *	 lower limit for ‘Office Supplies’ = $87.24 - 3* $750.33 = -$2,163.75 >  the minimum profit = -$14,369.12
    *  lower limit for ‘Technology’ = $295.46 - 3* $1363.78 = -$3,795.88 > the minimum profit = -$16,476.84

## Dashboard on Store Performance
![Dashboard%201](https://github.com/Sonull/Store-Performance-Analysis/blob/master/Dashboard%201.png)
