# Spaceship-Titanic


# Description:

Welcome to the year 2912, where your data science skills are needed to solve a cosmic mystery. We've received a transmission from four lightyears away and things aren't looking good.
The Spaceship Titanic was an interstellar passenger liner launched a month ago. With almost 13,000 passengers on board, the vessel set out on its maiden voyage transporting emigrants from our solar system to three newly habitable exoplanets orbiting nearby stars.
While rounding Alpha Centauri en route to its first destination—the torrid 55 Cancri E—the unwary Spaceship Titanic collided with a spacetime anomaly hidden within a dust cloud. Sadly, it met a similar fate as its namesake from 1000 years before. Though the ship stayed intact, almost half of the passengers were transported to an alternate dimension!

![spaceship](https://user-images.githubusercontent.com/121724612/216773699-37087809-50ef-4736-8b2c-f8dad15283a7.jpg)

To help rescue crews and retrieve the lost passengers, you are challenged to predict which passengers were transported by the anomaly using records recovered from the spaceship’s damaged computer system.
Help save them and change history!


# About Dataset:

**train.csv** - Personal records for about two-thirds (~8700) of the passengers, to be used as training data.<br>
**PassengerId** - A unique Id for each passenger. Each Id takes the form gggg_pp where gggg indicates a group the passenger is travelling with and pp is their number within the group. People in a group are often family members, but not always.<br>
**HomePlanet** - The planet the passenger departed from, typically their planet of permanent residence.<br>
**CryoSleep** - Indicates whether the passenger elected to be put into suspended animation for the duration of the voyage. Passengers in cryosleep are confined to their cabins.<br>
**Cabin** - The cabin number where the passenger is staying. Takes the form deck/num/side, where side can be either P for Port or S for Starboard.<br>
**Destination** - The planet the passenger will be debarking to.<br>
**Age** - The age of the passenger.<br>
**VIP** - Whether the passenger has paid for special VIP service during the voyage.<br>
RoomService, FoodCourt, ShoppingMall, Spa, VRDeck - Amount the passenger has billed at each of the Spaceship Titanic's many luxury amenities.<br>
**Name** - The first and last names of the passenger.<br>
**Transported** - Whether the passenger was transported to another dimension. This is the target, the column you are trying to predict.<br>
**test.csv** - Personal records for the remaining one-third (~4300) of the passengers, to be used as test data. Your task is to predict the value of Transported for the passengers in this set.
