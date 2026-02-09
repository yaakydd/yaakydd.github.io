USA GDP Growth Visualization
A dynamic, interactive data visualization of the United States' Gross Domestic Product (GDP) growth over time, built using D3.js. This project transforms raw economic data into an intuitive graphical format to help identify historical trends and economic cycles.

🚀 Live Demo
yaakydd.github.io

📊 Project Overview
This visualization displays the yearly GDP of the United States. It provides a clear view of economic expansions and contractions (recessions), allowing users to explore specific data points through interactive elements.

Key Features
Interactive Tooltips: Hover over data points to see the exact date and GDP value (in billions of USD).

Responsive Scaling: Uses D3 scales to map data values accurately to the SVG coordinate system.

Dynamic Axes: Automatically generated X and Y axes based on the dataset's time range and value magnitude.

Transitions: Smooth animations when the data loads or updates.

🛠️ Built With
D3.js: A JavaScript library for producing dynamic, interactive data visualizations in web browsers.

HTML5/CSS3: For structure and styling the visualization container and tooltips.

JavaScript (ES6): For data processing and DOM manipulation.

📁 Data Source
The data used in this project is sourced from the Federal Reserve Economic Data (FRED) via [FreeCodeCamp's API/JSON dataset].

Format: JSON

Key Fields: date (YYYY-MM-DD) and gdp (Billions of Dollars).

⚙️ Setup & Installation
To run this project locally, follow these steps:

Clone the repository:

Bash

git clone https://github.com/yaakydd/yaakydd.github.io.git
Navigate to the project folder:

Bash

cd usa-gdp-visualization
Open the project: Simply open index.html in your favorite web browser, or use a local server like Live Server in VS Code.

🧠 Technical Implementation Notes
Scales: I used d3.scaleTime() for the x-axis to handle dates and d3.scaleLinear() for the y-axis to represent the GDP values.

Axes: Implemented d3.axisBottom() and d3.axisLeft() to provide context to the data points.

Data Parsing: Used new Date(item[0]) to convert string dates into JavaScript Date objects for accurate plotting.

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

🤝 Contact
Your Name – 

Project Link: https://github.com/your-username/usa-gdp-visualization
