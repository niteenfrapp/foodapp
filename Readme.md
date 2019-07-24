# Problem Statement
Aditya works in Mumbai. Just before the lunch hour, he wishes to place an order on a food ordering app. The thousands of food options available on the app everyday have now started to bore him.

He approaches you to use your programming knowledge of **ReactJS** to hack this problem by building an app that can randomly suggest food from a database. 

## Rules for your solution : ##
- User is asked for his preference on the first screen i.e **veg or non-veg**. If non-veg is chosen, both veg as well as non-veg items can be suggested on the next screen.

- Food is divided into multiple categories and sub-categories. **Some of the items have dependency on another item, due to which the an item might have to be ordered along with it's dependency in the same parent category in order to complete a meal.** e.g *Indian* Bread like Roti has a dependency on an *Indian* Main Course Gravy item like Potato Curry.

- **Same meal should not have been suggested in the last 7 days.**

You are given access to a food database in the form of a json file and you need to build a list of 30 cards which showcase the meal for the next 30 days.
There should be **2 buttons** at the top.
1) Randomize
2) Accept

This Randomize button changes every meal in the list as per your devised algorithm.
On the click of the Accept button, the 30 day meal plan should be stored in the local storage and the randomize button should be disabled. Refreshing the page should not change the result.

## Judgement ##
Length of code doesn't matter but the functionality does.
Your knowledge of ReactJS, UI/UX along with your devised algorithm for the problem will be judged.

Happy Fooding!