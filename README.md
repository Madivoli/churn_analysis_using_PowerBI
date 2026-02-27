# ANALYSING CUSTOMER CHURN IN POWER BI
For subscription-based businesses, reducing customer churn is a top priority. In this Power BI project, I investigated a 6,687-dataset from a fictitious telecom company, Airtel, and analysed their churn rates. Analysing churn doesn’t just mean knowing the churn rate: it’s also about understanding why customers are churning/leaving at that rate and how to reduce churn. I have been hired as a consultant, and my task is to analyse why customers are churning, i.e., leaving Airtel. 

#
**Required:**
1.	To calculate the total churn rate for "Airtel". 
2.	To investigate the different reasons why customers churned. What are the top 3 churn reasons?
3.	To identify segments that are showing revenue "leakage" (that is, high usage but suspiciously low billing)? 
4.	To display all churn categories in one clear visualisation. What's the most prevalent churn category? 
5.	Our competitors have launched aggressive promos in certain states, and Airtel is wondering if it has impacted customers. Create a map in Power BI to investigate the churn rate by         state. Which state has the highest churn rate? USE MAPS TO YOUR ADVANTAGE
6.	Analyse the different demographic fields from the dataset. What's the churn rate for senior citizens? ANALYZING DEMOGRAPHICS
7.	Analyse if customers that are part of a group indeed have a lower phone bill, and if it has an impact on the churn rate. Which group size has the lowest churn rate? INSPECTING GROUPS
8.	Airtel has a hypothesis that people who are not on an unlimited data plan are more likely to churn. Investigate how the Unlimited Data Plan influences the churn rate. What's the          churn rate for people on an unlimited plan who consume less than 5 GB of data? UNLIMITED PLAN
9.	Analyse the international activity of customers and their relationship to churn. Senior Management is curious about the behaviour of customers who call internationally, and whether       paying for an international plan influences their loyalty. For the state with the highest churn rate, what percentage of customers who actively make international calls but do not        have an international plan churn? INTERNATIONAL CALLS
10.	Airtel also wants to improve its customer service since there have been some reported issues. Your job is to investigate three important topics related to customers: the payment          method, the contract type, and how many months a person has been a customer. CONTRACT TYPE
11.	What are the average extra data charges (two decimal points) for customers who are not on an unlimited data plan and consume 10 or more gigabytes? INTERNATIONAL AND DATA PLAN
12.	Create a report with a scatter plot visual showing the contract and payment type, and combine it with two card visuals related to customer service calls. What's the average number of     customer service calls for customers who are on a monthly contract and pay by direct debit? What is the churn rate for those customers? PAYMENT METHOD AND CONTRACT CATEGORY
13.	Which state has the highest churn rate and yet the lowest sum of customer service calls? And what is the total number of customer service calls for that state? MORE INSIGHTS

#
**KPIs**

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/f6e5bff2-998a-44ef-8318-8b6fdb80f9b7" />

## **Insights**

- **Customer Loss:** Out of 6,687 customers, 1,796 stopped using the Airtel service. This means about 27% of customers left.
- **Contract Impact:** Customers on monthly plans leave much more often (46.29%) than those on yearly contracts (6.62%).
- **Most Likely to Leave:** Women on monthly plans have the highest dropout rate at over 47%. On the other hand, men on yearly contracts leave slightly more often than women on the same      plan (7.21% vs. 6.02%, respectively).
- **Support Calls:** Customers made over 6,100 calls to customer service. This averages nearly one call per customer (0.92), which is a very high level of service friction. It shows many     people are having issues with their service.
- **Support Trends:** While the total number of calls is similar between men and women, women call slightly more often on average (0.93 vs. 0.91 calls, respectively). Additionally,           customers on monthly plans call for help nearly three times as often as those on yearly plans (4,467 vs 1,656, respectively).
- **Unexpected Fees:** Customers without an international plan spend an average of $33.64 extra on international calls.
- **Monthly Spending:** The average customer is charged $31.03 per month for their basic services.
- **Data Charges:** Customers without an unlimited data plan pay an average of $3.37 in extra fees for data downloads.

## **Business Implications**

* **The Contract Gap:** Customers paying month-by-month leave at a much higher rate (46%) than those committed to a year (6%). This suggests that monthly plans do not provide enough          value to keep people long-term.
* **Service Friction:** With customers calling support nearly once a month on average, there is a clear sign of frustration. High call volumes usually mean the product or the billing         process is confusing.
* **Gender & Plan Risk:** Women on monthly plans are the most likely to leave the service. This highlights a specific group of customers whose needs are not being met by the current          monthly offers.
* **Hidden Costs:** Customers without international plans are being hit with over $30 in extra fees. These "surprise" charges are a major reason why people lose trust and switch to           competitors.
* **Data Pricing Issues:** People without unlimited plans are paying extra for data downloads. Even small extra charges can make a customer feel like they are being treated unfairly.

## **Strategic Recommendations**

1. **Promote Yearly Commitment:** Offer a discount or a small reward to monthly users who switch to a yearly contract. This stabilizes revenue and keeps customers loyal for longer.
2. **Proactive Problem Solving:** Identify customers who call support more than twice in 30 days. Reach out to them personally to fix their issues before they decide to cancel.
3. **Smart Plan Matching:** Reach out to customers who are paying high extra fees for international calls or data and move them to a plan that covers those costs. Saving them money            builds long-term loyalty.
4. **Fix Service Issues:** Analyze the top reasons for customer calls. If a specific region has a high call volume, fixing the local network or simplifying the bill in that area will          stop more people from leaving than any discount would.

#
**INVESTIGATING CHURN REASONS**

The investigation into why 1,796 customers left Airtel reveals that competition and service quality are the primary drivers of attrition.

<img width="1365" height="738" alt="image" src="https://github.com/user-attachments/assets/45489bd3-6c8a-496f-b89c-ac086a7703f3" />


## **Insights on why customers are leaving:**

1.	**Primary Churn Drivers:** The top five reasons for customer churn are competitors making better offers (16.87%), competitors providing superior devices (16.54%), the negative              attitude of support staff (11.30%), unknown reasons (6.85%), and competitors offering more data (6.12%).
2.	**Gender-Based Variance:** Churn motivations differ by gender; the majority of female customers (17.61%) left because of better competitor offers, while 17.28% of male customers left       due to superior competitor devices.
3.	**Age-Specific Trends:**
    - *Seniors (55+):* This demographic is most affected by competitor offers (18.22%), superior devices (17.44%), and poor support staff attitude (12.40%).
    - *Youth (Under 25):* Younger customers are more driven by technical utility, citing better offers (18.94%), more data (7.58%), and higher download speeds (6.82%) as their top               reasons for leaving.
6.	**Contractual Influence:**
    - *Monthly Contracts:* These customers mirror the general trend, leaving primarily for better offers (17.29%), better devices (17.29%), and poor staff attitude (11.79%).
    - *Yearly Contracts:* Interestingly, long-term customers churned due to technical limitations, specifically better data offers (7.83%), higher download speeds (7.83%), and general           product dissatisfaction (6.91%).


## **Business Implications**
1. **Vulnerable to Competitors:** Customers are leaving because competitors offer better deals, devices, or data plans. Since this accounts for 39% of the churn, the current offerings are not strong enough to compete in the market.
2. **Customer Service is a Problem, Not a Solution:** Poor support staff attitudes are a top three reason for customers leaving. When you add this to the fact that customers call for support nearly once every month, it is clear that the service is actually driving customers away instead of helping them stay.
3. **Falling Behind Power Users:** Yearly contract holders and younger customers are leaving because they are unhappy with data speeds and limits. This shows that the current plans and technology cannot keep up with the needs of the most active users.
4. **Service Impacts Seniors More:** Seniors generally prefer stability, but they are very sensitive to negative service interactions. Poor service is causing the company to lose this group faster than others.

## **Strategic Recommendations**
1. **Create "Win-Back" Offers:** Since competitor offers are the main reason customers leave, the company should offer immediate incentives to stay. If a customer — especially a young person or a woman — calls to discuss their plan, give support staff the power to offer them better data or a device upgrade on the spot.
2. **Improve Staff Training:** Because poor staff attitude causes so many customers to leave, mandatory training is required that focuses on empathy and solving problems. This is especially important for staff who deal with monthly contract customers.
3. **Upgrade Data and Infrastructure:** To keep younger users and those on yearly contracts, the company must improve download speeds and increase data limits. Moving these customers to "Unlimited" plans can help prevent them from leaving due to data dissatisfaction.
4. **Launch a Device Upgrade Program:** Many customers leave because competitors have better devices. Introduce an upgrade program for customers at their 12-month contract mark. This will give them a reason to stay with the company rather than switching to a competitor for new hardware.



#
**REVENUE LEAKAGE**

The objective is to find the "disconnect" between a customer’s consumption (Data and Minutes) and their financial contribution (Total Charges). 

Even though the "High Leakage Risk" group (the purple dots) looks small in number compared to the total 6,687 customers, their financial density is what matters.

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/9380d56d-76fb-4ba1-affb-523fc9cfbcb0" />

1.	Which demographics have high ARPU but low international charges (potential for upsell)?
2.	




#
**DIGGING DEEPER INTO CHURN CATEGORIES**
