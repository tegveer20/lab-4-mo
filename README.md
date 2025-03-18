# lab-4-MA

This Lab is about pokemon cards (application that will load data from an API and populate data in your User Interface)

we Use the Pokémon TCG API to list the pictures along with names in a ListView.
When the user clicks on the card picture, it should enlarge the picture.

Fetching Data from the Pokémon TCG API

Use the Pokémon TCG API (https://pokemontcg.io/) to fetch a list of Pokémon cards.
The API returns JSON data containing card details like names, images, and IDs.
You'd typically use fetch() (in JavaScript) or an HTTP client (like Axios) to retrieve this data.
Displaying the Cards in a ListView

Use a ListView component (depending on your framework, e.g., React, Flutter, or Android's native ListView) to display the fetched Pokémon card images along with their names.
Each item in the ListView would show a thumbnail image and the name of the Pokémon.
Handling Click Events for Enlarging Images

When the user clicks on a card image, update the UI to display a larger version of the image.
This could be done using a modal, a separate screen, or an overlay.
In React, you might use state (useState) to track the selected image and display it in an enlarged view.
