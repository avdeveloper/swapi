# React Interview - Load Data From API

### Directions

To complete this exercise, open `app/page.tsx` and modify it to produce a user interface that:

- Has a 2 column layout
- Left column should load the first 10 people from the api and display:

  - Name
  - have a next page button to load the next first 10 people of the 2nd page of the api
  - ability to go back to the first page

- Right column should display the information for this person (character)
  - Include the name, gender, hair color, height (cm), mass (kg).
  - List the species under the name
  - List films: display title and episode id
  - List vehicles: display name and model
  - List starships: display name and model

### Notes

- Be creative on how the data is presented.
- Typing and code cleanness is important.

### API Documentation

https://swapi.py4e.com/

### Output

+-----------------------------+ +-------------------------+
| +-----------------------+   | | John Doe                |
| | John Doe              |   | | Gender:                 |
| +-----------------------+   | | Hair Color:             |
|                             | | Height:                 |
| +-----------------------+   | | Mass:                   |
| | Jane Doe              |   | | Films:                  |
| +-----------------------+   | | +---------------------+ |
|                             | | | Film 1 - Episode #1 | |
| +-----------------------+   | | +---------------------+ |  
| | Bobby Doe             |   | | Vehicles:               |
| +-----------------------+   | | +---------------------+ |  
|                             | | | Supercar - Space M  | |
|                             | | +---------------------+ |  
|                             | | Starships:              |
| +-----------------------+   | | +---------------------+ |
| | Next Page             |   | | | Rocket - Mars X     | |
| +-----------------------+   | | +---------------------+ |
+-----------------------------+ +-------------------------+

# Instructions for Glider

This was created using node v16.15.1

### Commands

- `npm run dev` runs the project
- `npm run test` runs the tests and outputs the test results in `./testOutput.json`
