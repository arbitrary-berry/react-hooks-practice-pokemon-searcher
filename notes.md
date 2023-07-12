## Project Goals

- Create an index displaying Pokemon 'cards'
  - Render each Pokemon name, sprite, and hp in a card
  - _When clicked_, the card should toggle between displaying the front and back
    sprites
- Allow users to search a Pokemon by its name in order to narrow down the cards
  shown on the page
- Wire up the form to add a missing Pokemon (Bulbasaur is missing, and you can
  probably intuit the image links to use based on the data you have). Since
  there aren't any validations, you may have to manually remove additions from
  the `db.json` file if you make a mistake on a POST request, etc. When a new
  Pokemon is added, it should show on the page without having to refresh.

  ## Data
    "pokemon": [
    {
      "id": 2,
      "name": "ivysaur",
      "hp": 60,
      "sprites": {
        "front": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/2.png",
        "back": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/back/2.png"
      }
    },]