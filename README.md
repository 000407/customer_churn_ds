# Customer Churn Dataset

This repository contains a dataset of 50000 customers of an eCommerce web application, that contains data such as personal info, purchase habits and whether they have already churned from the business.

## Data Dictionary

|Column Name|Data Type|Comment|
|---|---|---|
|user_id|int(11)|ID of the record (Unique to the dataset)|
|has_churned|tinyint(4)|Whether the user has churned (1=YES, 0=NO)|
|tenure|int(11)|Number of months that user has been with the business|
|pref_login_device|int(11)|Preferred login device (1=Computer, 2=Phone)|
|city_tier|int(11)|City tier|
|wh_to_home|int(11)|Distance from warehouse to home)|
|pref_payment_method|varchar(255)|Preferred payment method|
|gender|varchar(255)|Gender of the user|
|hrs_spent_on_app|int(11)|Number of hours spent in the app|
|no_of_devices|int(11)|Number of devices registered with the app|
|pref_category|varchar(255)|Preferred category of items|
|satisfaction_score|int(11)|Score that grades users satisfaction (1=HATES, 5=LOVES)|
|marital_status|varchar(255)|User's marital status|
|no_of_addresses|int(11)|Number of addresses that the user has registered with the app|
|complain|int(11)|Whether there are complaints from the user (1=YES, 0=NO)|
|order_amt_hike|int(11)|Difference between the number of orders of last year and this year)|
|coupon_used|int(11)|Number of coupons that the user has used|
|order_count|int(11)|Total number of orders placed for the entire lifetime|
|time_since_last_order|int(11)|Number of weeks since last order|
|total_lifetime_loyalty_points|int(11)|Total number of loyalty points earned by the user|
|time_since_last_login|int(11)|Number of weeks since last login|
|total_lifetime_expenditure|decimal(10,2)|Total amount that the user has spent with the vendor|
