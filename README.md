# Recipe Creator and Manager

**Category:** Classes

## Problem

Create a recipe class with ingredients and a put them in a recipe manager program that organizes them into categories like deserts, main courses or by ingredients like chicken, beef, soups, pies etc.

## Solution

`Ingredient` and `Recipe` are dataclasses; scaling a recipe multiplies every ingredient quantity by the serving ratio. `RecipeManager` indexes recipes by name and supports category filtering, ingredient search and a consolidated grocery list that sums quantities by ingredient and unit.

## How to run

Requires Python 3.8+ and no third-party packages.

```bash
python3 main.py --demo
```

## Example

```text
Pancakes (breakfast, serves 8)
  - 400 g flour
  - 600 ml milk
  - 4 eggs
  - 4 tbsp sugar
  1. Whisk the dry ingredients.
  2. Add milk and eggs.
  3. Cook on a hot griddle.
breakfast recipes: ['Pancakes']
recipes with chicken: ['Chicken Curry']
grocery list: 800 g chicken; 400 ml coconut milk; 3 tbsp curry paste; 4 eggs; 400 g flour; 600 ml milk; 4 tbsp sugar
```

## Attribution

The problem statement is from [karan/Projects](https://github.com/karan/Projects), a list of practical projects that anyone can solve in any programming language (MIT License, Copyright (c) 2013 Karan Goel). The Python solution in this repository was implemented by [bspreston-esq](https://github.com/bspreston-esq).

This repository is part of the [Projects-Python-All](https://github.com/bspreston-esq/Projects-Python-All) collection.
