Solar Particle Flux Analysis using Aditya-L1 SWIS Data

This project analyzes solar wind particle flux measurements from the SWIS instrument of the ASPEX payload onboard India's Aditya-L1 mission.

The dataset is stored in CDF (Common Data Format), a scientific format commonly used in space physics missions.

The goal of this project is to explore solar particle activity and identify transient disturbances in solar wind measurements using time-series analysis.

Project Objectives

• Load and process scientific CDF datasets
• Extract particle flux measurements across energy channels
• Convert multidimensional flux data into a time-series signal
• Visualize solar wind particle activity
• Identify sudden disturbances using statistical anomaly detection

Technologies Used

Python
Pandas
NumPy
Matplotlib
cdflib (for reading CDF scientific datasets)

Dataset

The analysis uses SWIS Level-2 particle data from the Aditya-L1 mission.

Variables analyzed include:

• particle flux measurements
• energy channel data
• spacecraft position
• timestamped particle observations

CDF data format is widely used in space physics missions and NASA data archives.

Analysis Workflow

Load CDF scientific dataset using Python

Inspect dataset variables and metadata

Extract particle flux measurements across energy channels

Aggregate flux values to create a time-series signal

Visualize solar particle flux patterns over time

Apply rolling averages to observe trends

Detect transient disturbances using statistical thresholds

Example Output

The project produces visualizations of:

• solar wind particle flux over time
• rolling average trends
• detected transient flux disturbances
• energenergy-flux heatmaps

These visualizations help identify periods of increased solar particle activity that may correspond to solar events.
