# int20h-2023 test assignment
task description in: int20h-ds-test.pdf <br>
dataset in: int20h-ds-test-dataset.csv <br>
notebook with solution: int20h_test_assignment.ipynb <br>

# Data Set Description
This data set represents the behavioral data of a utility app designed for car-related
transactional services. The app is subscription-based, and users are charged monthly or
annually.

# Assignment
Identify a set of events and parameters with the highest or lowest correlation with the potential
account cancellation. Prioritize the events, event properties or user properties, which have
highest or lowest correlation with the account cancellation

# Results

The user intending to write to Help Desk will likely cancel his subscription. <br>
Interest to Balance Sheet (e.g., Wallet Opened / Transactional Refund) <br>
also negative sign (may be an expression of user`s unsatisfaction of service) <br>

Active (high number of orders) and loyal (many subscription renews) users are naturally less prone to Subscription Premium Cancel

We can see that Subscription Premium Cancel higly relatated with Refunds(reminder: amount is negative number!) <br>
A yearly subscription is a tiny bit better than a monthly (maybe because a long-term subscription is a sign of firm intention to use the app)<br>
Opening Chat Conversation from Menu is a signal for anxiety about user loyalty <br>

Due to our analysis, regions of users and platforms are insignificant <br>
