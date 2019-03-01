# Martyno Kezio Pokemon Emporium

## Description
This Emporium is a way of easily giving information about pokemon of the first generation

## Pokemonas
Atributes:
- ID : Pokemon ID, mandatory (number, 0<ID<152)
- Name : Pokemon name, mandatory (String, <20 char)
- Type : Pokemon type, mandatory ()
- Type2 : Pokemon secondary type ()
- Atribute : Pokemon special abillity ()
- Size : Pokemon size in cm ()
- Weight : Pokemon weight ()
- Description : Pokemon description ()

## API
Possibilities:
- Get a pokemon by its ID
- Get a pokemon list by their type
- Delete a pokemon
- Edit a pokemon
- Crate a new pokemon

## UI
There will be display of the first pokemon (by ID) and its information and some buttons and a select box at the top:
- "New": Buttons "Edit", "Delete", "List by Type", "Select Box" are no longer visible. A new pokemon is created with all the fields empty and the user will be able to enter the info and press one of two buttons:
  - "Create": Vadilate the creation
  - "Cancel": Delets the created pokemon
- "Edit": Buttons "New", "Delete", "List by Type", "Select Box" are no longer visible. All the fields are editable and the user will be able to enter the info and press one of two buttons:
  - "Edit": Saves the changes
  - "Cancel": Delets the changes pokemon
- "Delete": the current pokemon is deleted
- "List by Type": Buttons "New", "Edit", "Delete", "List by Type", "Select Box" are no longer visible. Displays all the pokemon of the selected type (from "Select Box") in a list
- "Select Box": A list of all the types of pokemon
