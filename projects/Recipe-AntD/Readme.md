####
https://github.com/ChickenKyiv/recipe-antd

```
import { chickenKyiv } from '@groceristar/groceristar-fetch'

function getRandomRecipe () {
  return chickenKyiv.getRandomRecipe()
}

function getFirstFiveRecipes () {
  return chickenKyiv.getFirstFiveRecipes()
}

function getFiveRandomIngredients () {
  return chickenKyiv.getFiveRandomIngredients()
}

// @TODO i don't like this name too
function getRecipeChickenKyivById (id) {
  return chickenKyiv.getRecipe()[id]
}
```
