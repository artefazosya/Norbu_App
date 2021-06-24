# Norbu app analysis

## Project's goal
Provide recommendations on retention rate increase based on app data analysis. Data available: user activity logs, user ltv, geography, devices, traffic source.

## Product 
Norbu is a healthcare mobile app, which provides different techniques to cope with stress: meditation, breathing, games to improve focus. The app profits from paid subscriptions, bought by users.

### What does Norbu promise to the user? 
Help control stress

Behaviour -> Barrier -> Benefit 


## First open/Onboarding
<img src="What worries you.jfif" alt="drawing" width="200"/>
- Options do not correspond to the question, recommendations or question should be reformulated: 
 "what worries you" - "trouble falling asleep"
or
 "what would you like to achieve" - "Improve sleep"

- Reduce decision fatigue, simplify behavior: add default options here and on exercise screen, e.g. "training of the day".

## Event funnel
Most popular exercices are: breathing and ball game. Let's investigate breathing exercise:

{% include event_funnel_breathe.html %}

8% of people do not proceed from the exercise screen to the exercise itself.

- There should be less barriers between intention to exercise and the exercise itself: more screens/clicks - more opportunities for the user to change one's mind. Remove one screen between choosing the exercise and starting the exercise. There should be just 2 clicks: choose the exercise and start the exercise.
- 30% of users who started breathing exersice do not finish it. Use in app messaging as an extrinsic motivation, e.g. praise for good effort or focus on the goal (which user selected during onboarding or smth general): "One step closer to your goals" or "Thank you for taking care of oneself". Or promote social connection: "". [Reference](https://www.braze.com/resources/articles/in-app-message-best-practices)


## App removal
Share of users who remove the app is around 50% which corresponds to average uninstall rate in mobile app industry. [Source](https://www.mobileappdaily.com/reduce-mobile-app-uninstall-rates). That's why I did not dig into reasons of app removal, as the rate is pretty normal. I think it's better to concentrate on inactive users - they might still return to the app.

## Inactive users
I decided to consider users who haven't used an app for more than 10 days, nut haven't uninstalled the app - to be inactive users.
There are around 30% of inactive users.

## Geographical distribution
{% include geo_distr.html %}
Middle East and Europe are leading regions in number of unique users.

{% include users_geo_distr.html %}
Germany and Iran take are responsible for 50% of all unique users.

{% include cities_distr.html %}
The most active city is Tehran.




