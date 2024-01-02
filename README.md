# Car Insurance Claims Optimisation Storyboard
Data Visualisation using Tableau


## Tableau link for the Claims Optimisation Storyboard:
https://public.tableau.com/app/profile/vivek.sagar7834/viz/DVTProjectCarinsuranceClaims/CLAIMOPTIMISATIONSTORY?publish=yes


## Problem Statement:

Here we have been provided with Car Insurance Claims dataset. Our task is to explore the data, create different plots and interpret useful insights/findings. Our end goal here will be to create a storyboard to be presented to the Senior Management and the story has to have an end objective and should follow a logical flow. 

This will help the Senior Management in taking some decisive actions on the current claims system in place. This storyboard will be an open-ended story for us to explore various features in the data and try to showcase different plots. The storyboard should have minimum clutter in the plots & should follow a consistent color scheme across all the plots, while using proper colors to highlight a specific insight.

## Steps followed:

* Created multiple charts, tables &calculated fields for representing useful insights/findings. 
* Created Parameters & filters which added meaningful value along with multiple Interactive Dashboards.
* Finaly, created a Storyboard representing logical flow of the story, first dashboard contains the project details and objective. Next 2-3 with basic EDA of various variables followed by in-depth analysis using parameters, filters and multi dimensional views with final insights and recommendations at the end.

## Calculated fields used:

* **Age of Cars:** Car age had an anomaly as it was starting from -3 , this was rectified.
* **Dimension selection:** this was used to select categorical dimensions along with the parameter “Dimensions” to make the chart interactive and enable multi view.
* **Claim type Selection:** this is used along with the parameter “Historical/Current Claims” to switch between the two across charts.
* **Total claim= [Old claim + Current claim]:** This is used along with parameter  ”Top N customers by claim”.
* Other calculated fields like Claim rate, Current claim amount, Overall claim amount were made for the first dashboard namely “Claims analytics dashboard”


## Insights based on data visualisation in Tableau:

* 50% of the customers who have the insurance have never claimed. This number is quite large and focus should be given to the reason for this. Feedbacks from customers can immensly help in this regard.
* Customers with high school degree and bachelors degree amount for 60% of the total claims each contributing 30%. Hence they should be placed as preferred customers moving forward.
* Females have a higher claim frequency than males.
* SUVs account for 50% of the total claim frequency for the last 5 years.This number is too high for one car type alone, hence SUV customers can be charged a higher premium after a detailed analysis.
* Private SUVs and Private Minivans are highest in number but almost 60% of these SUVs and 70% of these Minivans have had Zero claims in last 5 years. Thus Private SUVs and Minivans are priority targets. Again in this case feedback and customer friendly approach should help overturn this issue.
* Commercial vehicles only account for 23% of the customers, 77% are private customers. To increase participation of Commercial vehicles perhaps a tie up with local companies as customers can help immensely.
* Single parent customers account for only 13%. This is too less and one of the reasons for this can be lack of customer centric service delivery as single parents usually have to manage the household on their own. Services like pickup and drop, faster issue handling time can help here.
* Females heavily dominate the SUVs(96%) and Sports car(98%) whereas Males dominate the Panel trucks(95%) and Van(87%).
* Since SUVs makeup 30% of customers alone this makes Female customers relatively more important than male customers.
* There is no clear correlation between claims and age of cars as well as years on the job and income. But there is a clear positive correlation between income and home value. There is also a somewhat positive correlation between income and car value but it is not as sharp as with home value.
* Customers with highschool degree have the highest claim amount but their avg. income is on the lower side whereas PhD holders have the highest avg. income yet they have the lowest claim amount.
* Thus we should **target customers with PhD degree by focussing on the service delivery side of things** like home pickup and drop , quick resolution of issues etc and they maybe willing to pay more for such premium services.
* Blue collar customers have the most claims across all car types , SUVs being at the top. Also SUV customers are the one with most claims car type wise. This can be used as an opportunity to increase revenue as well as avoid any losses due to repititive high cost claims by increasing the insurance premium for Blue collar customers as well as SUV customers.
* Customers with no kids are more likely to claim insurance.
* But among the customers who have atleast one kid, **SUV owners are to be targeted as they have highest number of kids as well as highest claims.**
* Occupationwise Blue collar customers have highest homekids as well as highest claims and Doctors have lowest homekids as well as lowest claims.
* Thus we can establish that even though customers with no kids are more likely to claim insurance, for those customers who have kids they tend to claim more if the number of kids they have is more. Hence **we can target those customers who have no kids as well as those who have more number of kids than the average.**
* Customers who have no kids driving are more likely to claim insurance. But among the Customers who have atleast one kid driving, customers with high school degree are to be targeted as they have highest number of kids driving as well as highest claims.
* **Hence we can conclude by saying that our target customers are the high income group of PhD holders as well as Doctors as they are are the ones with least claims . Female SUV customers (as they dominate SUVS(96%)) and Blue collar customers are also to be targeted but with purpose of charging high premiums as they are the ones who are claiming the insurance more frequently. Also even though SUV and Minivan Customers are the ones with most claims, 60% of private SUVs and Minivans customers haven't claimed even once in last 5 years which should also be looked into.**
  

## Few snapshots of the storyboard:
* ### Claim Analytics Dashboard:
<img width="1680" alt="Screenshot 2024-01-01 at 11 56 06 PM" src="https://github.com/VivekSagarSingh/Car-Insurance-Claims-Optimisation-Storyboard/assets/153344691/0d5bb6b0-c347-4fd5-97d8-3d1581f8e57a">

* ### Occupation Dashboard:
<img width="1680" alt="Screenshot 2024-01-01 at 11 56 40 PM" src="https://github.com/VivekSagarSingh/Car-Insurance-Claims-Optimisation-Storyboard/assets/153344691/19541341-5ef7-4dc1-88cf-01198bc288e6">


* ### Family Dashboard:

<img width="1680" alt="Screenshot 2024-01-01 at 11 57 10 PM" src="https://github.com/VivekSagarSingh/Car-Insurance-Claims-Optimisation-Storyboard/assets/153344691/194dbe83-0994-467f-91dc-287b38c93dcb">



* ### Top N customers Dashboard:
<img width="1680" alt="Screenshot 2024-01-01 at 11 57 25 PM" src="https://github.com/VivekSagarSingh/Car-Insurance-Claims-Optimisation-Storyboard/assets/153344691/3716ba73-b61c-43d9-8cb8-e64714a32ada">




















