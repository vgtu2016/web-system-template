# Martyno Kezio Pokemon Infomration Center Extravaganza

## Description
This Infomration Center Extravaganza is a way of easily accessing and modifying information about pokemon of the first generation

## Pokemon
Atributes:
- ID : Pokemon ID, mandatory (number, 0<ID<152)
- Name : Pokemon name, mandatory (String, <20 char)
- Type : Pokemon type, mandatory (Array, size = 18)
- Type2 : Pokemon secondary type (Array, size = 18)
- Atribute : Pokemon special abillity (String, <50 char)
- Size : Pokemon size in cm (number, 0<Size<900)
- Weight : Pokemon weight in kg (number, 0<Weight<500)
- Description : Pokemon description (String, <100)

## API
Possibilities:
- Get a pokemon by its ID. Method: Get, /api/pokemon/:id
- Get a pokemon list by their type. Method: Get, /api/pokemon/:type
- Delete a pokemon. Method: Delete, /api/pokemon/:id
- Edit a pokemon. Method: Post, /api/pokemon/:id
- Crate a new pokemon. Method: Put, /api/pokemon/

## UI
There will be display of the first pokemon (by ID) and its information and some buttons, ID field and a select box at the top:
- "New": Buttons "Edit", "Delete", "ID Field", "Find", "List by Type", "Select Box" are no longer visible. A new pokemon is created with all the fields empty and the user will be able to enter the info and press one of two buttons:
  - "Create": Vadilate the creation
  - "Cancel": Delets the created pokemon
- "Edit": Buttons "New", "Delete", "ID Field", "Find", "List by Type", "Select Box" are no longer visible. All the fields are editable and the user will be able to enter the info and press one of two buttons:
  - "Edit": Saves the changes
  - "Cancel": Delets the changes pokemon
- "Delete": the current pokemon is deleted
- "ID Field": an ID can be entered
- "Find": Finds a pokemon by specified ID in the "ID Field"
- "List by Type": Buttons "New", "Edit", "Delete", "ID Field", "Find", "List by Type", "Select Box" are no longer visible. Displays all the pokemon of the selected type (from "Select Box") in a list
- "Select Box": A list of all the types of pokemon
