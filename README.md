# Will-the-Customer-Accept-the-Coupon

**Jupyter Notebook** https://github.com/sheetal-vartak/Will-the-Customer-Accept-the-Coupon/blob/main/prompt.ipynb


**Goal of the Assignment**

The goal of this project is to use what you know about visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those that did not.


**Summary of Findings**
1. Data cleaning
    - Renamed the column "passanger" to "passenger"
    - Ignored the "car" column since it has ~99% of NaN values
    - Filled the NaN values with mode() in columns "Bar", "CoffeeHouse", CarryAway", "RestaurantLessThan20", "Restaurant20To50"
3. Overall coupon acceptance rate in the whole data set = **0.56**. This signifies that the data is not skewed. 
4. Established that the venue being in the same direction as the destination had no bearing on coupon acceptance rate.
5. Single and Married drivers were more likely to accept coupons.
6. 'Coffee House', 'Restaurant(<20)' and 'Carry out/Take away' are the more popular choices of coupons among Single and Married drivers
7. Bar Coupon Analysis
    - Bar coupon acceptance rate of passengers who go less than 3 times a month to those who go more is  0.81
    - Age groups 21 and 26 are more likely to accept Bar coupons
    - Acceptance rate of drivers who go to a bar more than once a month and are over the age of 25 =  0.69
    - Drivers who go to bars more than once a month and who did not have a passenger that were a kid and were not widowed, have a high Bar coupon acceptance rate
8. CoffeeHouse coupon Analysis
    - Overall acceptance rate of Coffee House coupons =  0.5
    - Age groups of 21-25 and 26-30 seem to accept the Coffee House coupon more.
    - With a driving time GEQ than 5 min, drivers highly likely to accept Coffee House coupon.
    - With a driving time GEQ than 25 min, the acceptance rate reduces drastically.
    - Venue in the same direction as destination, does not seem to influence the Coffee House acceptance rate.
