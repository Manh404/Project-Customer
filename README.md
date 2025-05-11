# Project-Customer


This project involves end-to-end data analysis on a real-world dataset including customer profiles, ticket purchase history, device usage, campaign details, and status logs. The data is cleaned, merged, and visualized to uncover patterns in ticket purchases, customer demographics, and campaign performance. The notebook generates actionable insights into which customer segments respond to promotions and how behavior varies over time.

# Summary of the project
## Age distribution
* 95% are genZ and genY
* Common age range from 20 to 35 years old
## Gender distribution
* Gender is not clearly differentiated

<img width="600" alt="Image" src="https://github.com/user-attachments/assets/388a052c-0422-4d11-857f-2cf5173d0486" />
<img width="600" alt="Image" src="https://github.com/user-attachments/assets/b4608dac-8019-4f11-8cbb-c8034afdfc00" />

## Time Analysis
* Trend Over 4 Years
 Observed overall trends across 4 years.
→ Note: Traffic was impacted by COVID-19 during 2020–2021.

* Day-of-Week Analysis
→ Noticed higher traffic from Thursday to Sunday.

* Hourly Analysis
→ Customer activity spans from 9 AM to 11 PM, with a peak at 7 PM.

* Holiday & Movie Release Periods
→ Spikes in traffic coincide with blockbuster movie releases and festive seasons.

<img width="600" alt="Image" src="https://github.com/user-attachments/assets/51d2f3aa-33ad-4435-95fc-1dec0e5b63d9" />

## 1. Device and Platform Usage

<img width="326" alt="Image" src="https://github.com/user-attachments/assets/18b5f877-fd3b-4361-b951-5c7370918bcd" />

<img width="622" alt="Image" src="https://github.com/user-attachments/assets/b2dfd544-77c8-4955-93aa-80f3688705d5" />

<img width="600" alt="Image" src="https://github.com/user-attachments/assets/726dbbc8-b283-44c7-baea-2de92bb22b90" />

* Mobile dominates: 86% of users access via mobile, only 11% use websites.

* App-based usage is dominant; website use significantly dropped in 2022.



Operating System:

<img width="600" alt="Image" src="https://github.com/user-attachments/assets/ef45fd7e-2bd8-44a4-afcf-98d6813ec3e6" />

* 45% Android, 40% iOS, remaining users unidentified (likely due to device tracking limitations).

Time of Usage:

* Many unknown devices due to lack of trackable info during payment phase.

* Hypothesis: Most untracked transactions come from app-based payments.


## 2. Payment Method Behavior

<img width="1014" alt="Image" src="https://github.com/user-attachments/assets/90e4ae14-8fed-4ead-a718-efd60e3ba1fd" />

Preferred Payment Channels:

* Bank cards and apps are the most common.

* App-based direct payment grew strongly in 2022.

* Some users likely skip login or skip wallet binding.

* Cash usage is minimal.

Conclusion: Mobile app with embedded payment is key to conversion.

## 3. Promotional Program Impact
Main Types:

<img width="1019" alt="Image" src="https://github.com/user-attachments/assets/ca1ef69f-f232-4b61-9c3e-96c4d8d1ffe7" />

* Voucher, Discount, Reward Points.

* Discounts became increasingly popular in 2022 — possibly a strategic move.

* Nearly 60% of businesses used promotions as a sales strategy.

## 4. Popular Movie Genres and Audience Behavior

<img width="1339" alt="Image" src="https://github.com/user-attachments/assets/08ed2883-b416-4814-9e24-fbaf782aa475" />

<img width="568" alt="Image" src="https://github.com/user-attachments/assets/d1359e27-d2e7-4043-9db6-64cfda4841ce" />

* Users tend to favor action or blockbuster films.

Seasonal trends:

* Viewership spikes during school holidays, festive seasons.

* Promotions are often aligned with major releases.

## 5. Customer Behavior Insights
<img width="772" alt="Image" src="https://github.com/user-attachments/assets/316d58f3-58d4-4c92-95b2-05dc06a00821" /> 

Some customers only respond to one-time promotions (likely new users).

Promotions related to specific products or marketing campaigns are most effective.

<img width="533" alt="Image" src="https://github.com/user-attachments/assets/43302af3-d2e4-4c2f-b2b4-47bea42df4e7" />

* ~50% of users respond to promotions just once.

* ~90% of users who engage in promotions opt for direct discounts over points or bundles.


## 6. Segment-Specific Behavior
Certain customer groups:

* Have a 10% share rate (SR), possibly tied to profits.

* Appear unaffected by overly complex promotions — keep it simple.

* Promotions that are too frequent or vague may result in low conversion.

## 7. Customer Retention
<img width="565" alt="Image" src="https://github.com/user-attachments/assets/cc5196e2-41a8-44fd-bf63-a54a409819c3" />

<img width="564" alt="Image" src="https://github.com/user-attachments/assets/c86b4794-2f05-4719-a9fe-2516a4c2483b" />

* Retention in 2019 and 2022 does not have many changes, because the new film market has not recovered.

* There is no difference in retention between organic and promotional groups ( 97% promotion in 2022 is for NEW CUSTOMERS , Only 13% customers comeback , The rate in the organic group is 12% )

## 8. Payment success rate
<img width="675" alt="Image" src="https://github.com/user-attachments/assets/4dce93e4-36d5-4d07-bb6b-77ddf619579e" />

* Good system and products to serve customers

*Common errors (bank errors, account identification errors)
* <img width="711" alt="Ảnh màn hình 2025-05-11 lúc 10 45 34" src="https://github.com/user-attachments/assets/a9b8f070-076c-4e3c-90c1-85073eb3a5c7" />


* <img width="805" alt="Ảnh màn hình 2025-05-11 lúc 10 45 59" src="https://github.com/user-attachments/assets/54f804be-e858-43ff-86b5-bea26108bf63" />


## 9 A/B testing

Null Hypothesis (H₀): Conversion rates for vouchers and discounts are equal.

Alternative Hypothesis (H₁): Conversion rates differ between voucher and discount promotions.
<img width="343" alt="Ảnh màn hình 2025-05-11 lúc 15 30 56" src="https://github.com/user-attachments/assets/51a2ab12-7fd4-4132-ace0-38d2b81487b4" />

Discount campaigns performed significantly better and should be prioritized in future marketing strategies.



