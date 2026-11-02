Revenue % of Total = DIVIDE(\[Total\_Revenue],CALCULATE(\[Total\_Revenue],all(ecommerce\_sales\_analytics\_5000)))



Revenue LY = CALCULATE(\[Total\_Revenue],SAMEPERIODLASTYEAR(Calender\[Custom\_date]))

Revenue YoY % = DIVIDE(\[Total\_Revenue]-\[Revenue LY],\[Revenue LY])

Revenue YTD = TOTALYTD(\[Total\_Revenue],Calender\[Custom\_date])

Total\_Revenue = SUM(ecommerce\_sales\_analytics\_5000\[revenue])

Unique Customers = DISTINCTCOUNT(ecommerce\_sales\_analytics\_5000\[customer\_id])

Unit\_Sold = SUM(ecommerce\_sales\_analytics\_5000\[quantity])



Avg Delivery Days = AVERAGE(ecommerce\_sales\_analytics\_5000\[delivery\_days])

Avg Discount = AVERAGE(ecommerce\_sales\_analytics\_5000\[discount])

Avg Order Value = DIVIDE(\[Total\_Revenue],\[Orders],0)

Avg Rating = AVERAGE(ecommerce\_sales\_analytics\_5000\[customer\_rating])

Orders = COUNTROWS(ecommerce\_sales\_analytics\_5000)



