BMW Models

This project allows users to view and interact with a list of BMW car models. Users can search, filter, view details, and add comments to specific models. Comments are saved locally using localStorage.

Features

Dynamic Model List: Displays a list of BMW car models fetched from a JSON file.

Model Details: Clicking on a model displays detailed information, including name, image, and description.

Comments: Users can add comments to each model, which are persisted in localStorage.

Search Functionality: Search for models by name.

Filtering Options: Filter models based on year and engine type.

How It Works

Fetching Data: Model data is retrieved from a db.json file containing information about BMW car models.

{
  "BMWs": [
    {
      "id": 1,
      "model": "",
      "image": "url-to-image",
      "Description": "",
    "comments":
    }
  ]
}

Display Model List: The list of models is dynamically populated in an HTML <ul> element.

Show Model Details: Clicking a model name displays its details in a separate section.

Comments: Users can add comments to each model. Comments are stored locally and retrieved when the model is revisited.



File Structure

root
├── index.html        # HTML structure of the project
├── styles.css        # Styling for the project
├── script.js         # Main JavaScript logic
├── db.json           # JSON file with model data

Setup



Click on a model to view its details.

Add comments to the model, which will be saved locally.

Dependencies

JSON Server (for simulating API data fetching)



