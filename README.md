# Description
In this Jupyter Notebook, I analyzed a dataset from the UCI Machine Learning repository. The dataset was collected by Amazon with the intention of determining whether, when offered a coupon for an establishment near a driver's location, a driver would accept or decline the coupon.

# Objective
I looked at two different types of coupons: bar coupons and coffee house coupons. In both cases, my goal was to determine which factors increased the likelihood of a driver accepting the coupons.

# Findings
## Bar Coupons
### Frequency of Bar Visits
Acceptance of the bar coupons generally increased with the monthly frequency that the driver visited bars.

### Passenger Type
When we consider the effect passenger type had on acceptance, we saw that having a kid as a passenger reduced the acceptance rate for bar coupons, while having a friend as a passenger increased the acceptance rate for bar coupons.

### Marital Status
With regards to marital status, single drivers were most likely to accept the bar coupons.

### Age
There wasn't a drastic difference between acceptance of different age groups, but it's worth noting that drivers in their early twenties were most likely to take advantage of the bar coupons.

### Other Columns
Of the other columns we looked at, there wasn't as strong of a correlation between acceptance and either income or occupation.

## Coffee Coupons
### Frequency of Coffee House Visits
Drivers who visit coffee houses at least once a month were much more likely to accept the coupon than those who visited coffee houses less than once per month.

### Age
Drivers who were under 21 years old accepted the coupon more often than any other age group.

### Time Coupon was Issued
Coupons offered at 10AM had the greatest acceptance rate. Coupons offered at 2PM had the second greatest acceptance rate. Coupons offered at other times were accepted a little less than half of the time.

### Expiration of Coupon
Coupons issued with a 2 hour expiration were less likely to be accepted than coupons issued with a 1 day expiration.

### Driver Destination
Drivers who had no urgent destination accepted the coupon more often than drivers with a destination in mind.