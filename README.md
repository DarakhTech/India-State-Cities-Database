# India State Cities Database

This repository contains a JSON file with data for the states and cities of India. This data can be used to populate a dropdown or any other user interface element requiring information about Indian states and cities.

## Data Format

The data is structured in JSON format, organized by states, their codes, and their respective cities. Each state object contains a name, a code, and an array of cities associated with that state.

### Example:

```json
{
  "states": [
    {
      "name": "Andhra Pradesh",
      "code": "AP",
      "cities": ["Hyderabad", "Vijayawada", "Visakhapatnam", "Guntur", "Nellore"]
    },
    // Add more states and cities as needed
  ]
}


### Usage
Feel free to use the provided JSON data in your projects. You can use it to dynamically populate dropdowns, select boxes, or any other user interface elements requiring information about Indian states and cities.