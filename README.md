# Belly Button Biodiversity Dashboard

This project is an interactive web application that visualizes data related to belly button biodiversity. It allows users to explore various bacterial cultures found in the human navel and their frequency across different samples. The application uses Plotly for interactive charts and D3.js for data handling.

## Project Structure

The project consists of the following files:

- **index.html**: The main HTML page that renders the dashboard layout and links the required JavaScript files and libraries.
- **samples.json**: The dataset containing sample IDs, metadata, and bacteria cultures data.
- **app.js**: The JavaScript file handling data processing, rendering charts, and updating the metadata panel using D3.js and Plotly.

## Features

- **Dropdown Selection**: Users can select different test subjects by ID to view related data.
- **Demographic Information Panel**: Displays metadata related to the selected test subject (e.g., age, gender, location, washing frequency).
- **Bar Chart**: Displays the top 10 most common bacteria cultures found for the selected test subject.
- **Bubble Chart**: Displays all bacteria cultures for the selected test subject with marker size indicating the sample value and marker color indicating the OTU ID.

## Libraries Used

- **D3.js** for handling JSON data and updating the DOM.
- **Plotly** for generating interactive charts.

## Data Source

The dataset `samples.json` is statically hosted and loaded via D3.js. It contains:

- `names`: An array of sample IDs.
- `metadata`: Metadata for each sample, including demographic information.
- `samples`: The bacterial culture data for each sample ID.

## How to Use

- Open the `index.html` file in a browser to view the dashboard.
- Select a test subject ID from the dropdown menu.
- View demographic information and related bacteria cultures via the interactive charts.

## Future Improvements

- Add additional visualization types to enhance data exploration.
- Improve responsiveness for various device sizes.
- Integrate real-time data updates.