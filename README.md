Earthquake Visualization on a 3D Interactive Globe (2020–2024):

This project visualizes global earthquake occurrences from 2020 to 2024 using an interactive 3D globe in Python. It offers an engaging way to explore earthquake distribution based on magnitude, depth, and location, making it useful for education, research, and geospatial data enthusiasts.

Overview
Earthquakes are natural geological phenomena occurring worldwide. This project leverages data from the USGS Earthquake API to create a dynamic 3D visualization, where:

Marker size represents earthquake magnitude.
Marker color reflects intensity (higher magnitudes appear redder).
Interactive features allow users to explore detailed earthquake information.
Key Features
Interactive 3D Globe – Rotate, zoom, and explore earthquake data dynamically.
Visual Encoding – Marker size and color dynamically represent earthquake magnitude.
Colorbar Legend – Displays magnitude range for quick reference.
High-Resolution Mapping – Customizable globe projection with coastlines, landmasses, and oceans.
Libraries Used
This project utilizes several Python libraries for data processing and visualization:

pandas – Data manipulation and handling.
plotly – Creating the interactive 3D globe.
imageio – Generating animations (if required).
imageio[ffmpeg] – Encoding video animations.
kaleido – Exporting visualizations as static files (PNG, PDF, etc.).
Data Source
Earthquake data is retrieved from the USGS Earthquake Catalog using the following API:

Base URL: https://earthquake.usgs.gov/fdsnws/event/1/query
Key Parameters:
format=geojson – Data format.
minmagnitude=5.0 – Filters earthquakes of magnitude 5.0 or higher.
orderby=time – Sorts results by time (most recent first).
starttime & endtime – Define the date range.
Insights & Findings
Earthquakes predominantly occur along tectonic plate boundaries.
The Pacific Ring of Fire shows a dense distribution of high-magnitude earthquakes.
Interactive geospatial visualizations enhance the intuitive exploration of large datasets.
Future Enhancements
This project can be expanded further with:

Time-based animations showing earthquake occurrences dynamically.
Integration with additional datasets (e.g., tsunami warnings, population density, infrastructure risk).
