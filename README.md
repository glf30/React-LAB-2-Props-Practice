# React-LAB-2-Props-Practice

## Project 1: Menu App

Build a simple restaurant-style menu that displays a list of items.  
Each item should have a **name**, **price**, an **availble** boolean, a **sale** boolean, and a button to “Add to Order.”

### Requirements
- In your App.jsx create an array of at least 5 food items (name + price + id + available (boolean)).
- Create a `Menu` component to display each Food Item.
- Pass the individual item as props to a `MenuItem` component.
- Each `MenuItem` should display:
  - The food name
  - The price
  - A button (like “Add to Order”)
  - A way to indicate to the user whether the item is available or not
  - A way to indicate to the user whether the item is on sale.
- When the button is clicked, call a function passed down from the parent (e.g. `handleAdd(itemName)`).
- The parent function should `console.log` or `alert` something like:  
  `"Added [itemName] to order!"

### Project 2: Song List App
Create a simple music playlist app that displays songs and allows the user to “play” them (just a console message or alert is fine).

### Requirements
- Create a SongList component that holds an array of 10 songs.
- Each song should have at least:
  - A title
  - An artist
  - An ID
  - A property **favorite** that indicates whether the song has been favorited
  - **appearsOn** an array of strings displaying which playlist names the song appears on.
- Render a Song component for each song.
- Each Song should display the information as well as a play button

When the button is clicked, call a parent function passed as a prop (e.g. handlePlay(title)) that logs:
"Now playing: [songTitle]"
