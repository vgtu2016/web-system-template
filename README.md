# Martyno Kezio Pokemonų Emporiumas

## Aprašas
Šio Emporiumo prasmė pateikti patogią Pokemon visatos pirmosios generacijos sąrašą ir jų aprašus

## Pokemonas
Atributai:
- ID : Pokemono ID pagal jo sąrašą, kiekvienam yra unikalus ir yra nustatytas, PRIVALOMAS
- Name : Pokemono vardas, PRIVALOMAS
- Type : Pokemono tipas, PRIVALOMAS
- Type2 : Pokemono antrinis tipas
- Atribute : Pokemono special abillity
- Size : Pokemono dydis
- Weight : Pokemono svoris
- Description : Pokemono aprašymas

## API aprašymas
Galima bus:
- Gauti pokemoną pagal ID
- Gauti pokemonų sąrašą pagal tipą
- Ištrinti pokemoną
- Koreguoti pokemoną
- Sukurti pokemoną

## UI
Idėja:
Bus pagrindinis langas, kuriame bus eilutėje:
Mygtukas "Pokemonas" Mygtukas "Pokemonų sąrašas pagal tipą"

Paspaudus "Pokemonas":
Bus matomas pokemonas ir bus galima daryti paiešką pagal Name, ID, bus galima paspausti mygtuką "Koreguoti" pokemoną, bus galima paspausti mygtuką "Ištrinti" pokemoną.

Paspaudus "Pokemonų sąrašas pagal tipą":
Pasirinkus tipą, bus galima gauti sąrašą pokemonų, kurie atitinka tą tipą.
