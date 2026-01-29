# TripleTen_11---Event_Analysis_Project

## Integrated Project 2



The activity consists of working for a fictional startup that sells food products. You need to analyze user behavior for the company's app.

First, study the sales funnel. Find out how users reach the purchase stage. How many users actually reach this stage? How many get stuck in the previous stages? Which stages in particular?

Next, look at the results of the A/A/B test. The designers would like to change the fonts throughout the app, but the managers fear that users will find the new design intimidating. They decide to make the decision based on the results of an A/A/B test.

Users are divided into three groups: two control groups receive the old fonts and one test group receives the new ones. Find out which set of fonts produces the best results.
Data description

Each log entry is a user action or event.

    EventName — event name
    DeviceIDHash — unique user identifier
    EventTimestamp — event time
    ExpId — experiment number


## Conclusion:

The average user of the app performs the following sequence:

    > Accesses the main screen
    > Accesses the offers screen
    > Accesses the cart screen
    > Makes the payment.

A/B testing revealed that changing the font did not alter user behavior. This change did not alter the conversion rate or frequency of any funnel events.