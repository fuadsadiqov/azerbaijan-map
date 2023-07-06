# Map of Azerbaijan

This project utilizes an SVG format map of Azerbaijan to provide a comprehensive view of the country, including the names of each city and district. Users can explore the map and access detailed information about specific locations.

## Getting Started

To use this project, follow these steps:

1. Download the project files.
2. Add the `countrymap.js` and `mapdata.js` files to your `index.html` file.
3. Create a `<div>` element with the id `map` in your HTML file to serve as the container for the map.

## Customization

The `mapdata.js` file contains the configuration settings for the map. You can modify this file to customize various aspects of the map's layout, including size and color. Within the `main_settings` object, you can adjust properties such as:

- `width`: Set the desired width of the map (e.g., "500" or "700" for a responsive width).
- `background_color`: Change the background color of the map.
- `state_color` and `state_hover_color`: Define the color of the states/districts and their hover state.
- `location_color` and `location_hover_opacity`: Customize the color and opacity of the locations (cities, districts) on the map.
- `label_color`: Set the color of the labels for cities and districts.
- `zoom`: Enable or disable the zoom functionality of the map.

Feel free to experiment with these settings to achieve the desired visual appearance of the map.

## Example Usage

```html
<!DOCTYPE html>
<html>
<head>
    <title>Azerbaijan Map</title>
    <script src="countrymap.js"></script>
    <script src="mapdata.js"></script>
    <style>
        #map {
            width: 100%;
            height: 500px;
        }
    </style>
</head>
<body>
    <div id="map"></div>
</body>
</html>
```
In this example, the countrymap.js and mapdata.js files are included in the HTML file, and a <div> element with the id map is added to serve as the container for the map. The CSS style sets the width and height of the map container.

Credits
The map data and JavaScript code used in this project are provided by Simplemaps. The SVG map of Azerbaijan is sourced from their library and customized for this project.

For more information and additional maps, please visit their website.

License
This project is licensed under the MIT License.
You can copy and paste this text into your `README.md` file on GitHub.