# Directing_Customers_To_Subscription Through App Behaviour Analysis

## Challenge

In this case study we will be working for a fintech company that wants to provide it's customers with a paid mobile app subscription that will allow them to track all of their finances in one place.

To attract customers, the company releases a free version of their app with some of the main features unlocked.

The task is to identify which users will most likely NOT enroll in the paid product, so that additional offers can be given to them. Because of the Cost of these offers, the company does not want to offer them to everybody, especially the customers who were going to enroll anyways.

We have the access to each customer's app behavior data. This data allows us to see the date annd time of app insallation, as well as the features users engaged with within the app. App behavior is characterized as the list of app screens the user looked at, and whether the user played the financial mini-games available.

The app usage data is only from the user's first day in the app. This limitation exists because users can enjoy a 24-hour free trial of the premium features, and the company wants to target them with new offers shortly after the trial is over.


## Conclusion

Our efforts has given us a model that will label every new user as "highly likely" (or "unlikely") to subscribe. Further we can validate our results by running our predictions on daily new installs, and see whether our accuracy is consistent. From there, we can narrow our marketing efforts only to those users who are "unlikely" to subscribe, and thus increase the subscription rate.

The increase in overall subscriptions can measure the benefit of this model to the company. Recall that those already "likely" to subsribe will do so, and, although we can still give them offers,we don't have to go all out. On the other hand, users who are likely to leave may convert to paid users if we give them an offer they cannot refuse. For example, these offers can come in the form of 'first month free', or '50% off yearly subscriptions'. The latter shows that great offers can still be constructed in a way that brings overall benefit to the company because we are locking the user in for an extended period!
