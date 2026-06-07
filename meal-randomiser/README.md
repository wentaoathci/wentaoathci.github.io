# Fat Loss Meal Randomiser

A simple single-page HTML + JavaScript tool that randomly builds a balanced fat-loss meal.

Each generated meal includes:

- Protein
- Vegetables
- Whole grains / 粗粮
- Main carbohydrate / 主食
- Legumes / 豆类

## Features

- Randomly selects 1–2 foods from each category
- Avoids repeating ingredients from the previous meal where possible
- Low / medium / high calorie level toggle
- Vegetarian mode filter
- Rough calorie estimate per item and total meal
- Clean, minimal local-browser UI

## Run locally

Open `index.html` directly in your browser.

No build step, server, or dependencies are required.

## Extend the food lists

Edit the `foodCategories` object in `script.js`.

Each food item uses this shape:

```js
{ name: "tofu", calories: 95, vegetarian: true }
```

Calories are rough estimates and should be adjusted for your preferred serving sizes.
