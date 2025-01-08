# belly-button-challenge

Belly Button Biodiversity Dashboard

Project Overview

The Belly Button Biodiversity Dashboard is an interactive web application designed to explore the dataset of microbes that colonize human navels. This dashboard visualizes the distribution of microbial species across individuals, providing insights into biodiversity trends and individual sample data.

The project uses D3.js, Plotly.js, and Bootstrap to create an interactive experience with demographic information, a bar chart, and a bubble chart.

Features

Metadata Panel:

Displays demographic information about the selected individual.

Horizontal Bar Chart:

Shows the top 10 microbial species (OTUs) found in the selected sample.

X-axis: Sample values.

Y-axis: OTU IDs (formatted as OTU ####).

Hovertext: OTU labels.

Bubble Chart:

Visualizes all OTUs found in the selected sample.

X-axis: OTU IDs.

Y-axis: Sample values.

Marker size: Sample values.

Marker color: OTU IDs.

Hovertext: OTU labels.

Dropdown Menu:

Allows the user to select a test subject ID.

Updates all charts and metadata dynamically.

Interactive Elements:

Responsive UI for a seamless user experience.

Technologies Used

HTML5

CSS3

JavaScript

D3.js

Plotly.js

Bootstrap

GitHub Pages for deployment

File Structure

.
├── index.html           # Main HTML file for the dashboard
├── static/
│   ├── js/
│   │   └── app.js      # JavaScript logic for the dashboard
│   └── css/
│       └── style.css   # Custom styles for the dashboard
└── README.md            # Project documentation

How to Run

Clone the repository to your local machine:

git clone https://github.com/Maika7/belly-button-challenge.git

Navigate to the project directory:

cd belly-button-challenge

Open index.html in your browser to view the dashboard.

Deployment

The project is deployed to GitHub Pages and can be accessed here.

Data Source

The dataset used in this project is hosted at:
https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json

Contributions

Author: Emeka Michael Osasah

Acknowledgments

This project was completed as part of the Data Visualization module. Special thanks to the instructional team and peers for their guidance and support.