<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Project Title

Meal Prep Assistant

## Summary

Describe briefly in 2-3 sentences what your project is about. About 250 characters is a nice length! 
The Meal Prep Assistant helps users plan low-calorie, high-protein meals for the week (or more) ahead. Choose dishes, get a shopping list and ingredient prep list. Cook and freeze ahead of time, or prep ahead to reduce cooking time on busy days in the week.

## Background

As someone who can't cook and yet needs proper nutrition to meet my fitness goals, planning macros, choosing dishes, buying groceries, prepping ingredients, and cooking are all hurdles to overcome. Having something to do all the calculating, planning, and thinking for me, so I only had to follow instructions, would lower the barrier of entry to nutrition and cooking. It combines a nutritionist/dietician and personal (grocery) shopper in one.

The Meal Prep Assistant helps:
* People new to dieting - Meal Prep Assistant calculates macros and suggests recipes
* Save money - Buy only what you need at the grocery store
* Save time - Prep ingredients or meals in bulk

## How is it used?

1. User enters profile information (height, weight, bodyfat % (if known), activity level, goals, dietry requirements, etc.) of people eating the meals
2. User selects dishes for meals in the week (or any time period), e.g. only dinners on Monday to Friday
	- Meal Prep Assistant suggests dishes, e.g. after selecting Breakfast and Lunch, suggests a Dinner that fits macros
	- Meal Prep Assistant gives suggestions on how to adjust ingredient quantities to hit macros, if dishes selected are over or under
3. Meal Prep Assistant then compiles a list of:
	- Groceries (veg, meat, others) e.g. 6 potatoes, 500g chicken breast, etc.
	- Prep list (veg, meat) e.g. 3 potatoes diced, 3 potatoes sliced into wedges, etc.
	- Assembly (dishes) - which prepped ingredients go into which dish
	- Cooking instructions (dishes)
	- Portion instructions (dishes) - for >1 people
4. User rates recipes so Meal Prep Assistant can learn preferences and make suggestions based on more than just macro suitability

## Data sources and AI methods

Recipe lists can come from:
* [The Felu Cookbook](https://payhip.com/b/7ubMY)
* [The Recipe E-Book By Dave Fell Fitness](https://www.fellfitnesscommunitystore.com/products/the-recipe-e-book-by-dave-fell-fitness)

## Challenges

Meal Prep Assistant cannot shop for and prep the meals for you - a ready-to-eat meal service would be better for that. It is for people who are willing to put in some time and effort and/or save some money. Nutritional information of recipes may not be 100% accurate, as ingredients sourced by users may differ from that used in the recipes. Recommended macros will also not be 100% accurate, as each individual's needs can only be _estimated_ based on parameters (e.g. height, weight, bodyfat %).

## What next?

I imagine a mobile application would be most accessible. However, I do not have the coding and app development skills required to construct such a recipe database, and a program that learns user preferences.

## Acknowledgments

* Raffaele Colonna aka Felu for [The Felu Cookbook](https://www.felu.co/)
* Dave Fell for [The Recipe E-Book By Dave Fell Fitness](https://www.fellfitnesscommunitystore.com/products/the-recipe-e-book-by-dave-fell-fitness)
* nao [nao_stock.recipe](https://www.instagram.com/nao_stock.recipe/) for the shopping and prep list idea
