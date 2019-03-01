# Martyno Kezio Pokemon Guru

## Description
This Guru is a way of easily accessing and modifying information about pokemon of the first generation

## Pokemon
Atributes:
- ID : Pokemon ID, mandatory (number, 0<ID<152)
- Name : Pokemon name, mandatory (String, <20 char)
- Type : Pokemon type, mandatory (Array, size = 18)
- Type2 : Pokemon secondary type (Array, size = 18)
- Ability : Pokemon special abillity (String, <50 char)
- Size : Pokemon size in cm (number, 0<Size<900)
- Weight : Pokemon weight in kg (number, 0<Weight<500)
- Description : Pokemon description (String, <100)

## API
Possibilities:
- Get a pokemon by its ID. Method: Get, /api/pokemon/:id
- Get a pokemon list by their type. Method: Get, /api/pokemon/:type
- Delete a pokemon. Method: Delete, /api/pokemon/:id
- Edit a pokemon. Method: Put, /api/pokemon/:id
- Create a new pokemon. Method: Post, /api/pokemon/

## UI
There will be two windows : main, second

- Second:
  - A single pokemons data
  - Possible actions:
    - New: Creates a new pokemon with all fields empty (except ID) and shows it in the window
    - Delete: Deletes the pokemon and opns the Main window
    - Cancel: Does not save the changes and opens Main window
    - Create/Edit: is named depending on the window mode (Edit, Create). Saves the changes on the pokemon

- Main:
  - A list of all pokemon, visible data: ID, Name, Type, Type2. 
  - Possible actions: 
    - New: opens Second window
    - Find: Opens pokemon second window if the ID is found (from the text box)
    - Type: Filters the list by selected type
    - Edit: Opens second window with the pokemon in edit mode
    - Delete: Deletes the pokemon

The layout: https://wireframe.cc/HgUJp5
