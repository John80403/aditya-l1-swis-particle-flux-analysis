**Solar Particle Flux Analysis using Aditya-L1 SWIS Data**

**Overview**

This project analyzes solar wind particle flux measurements obtained from the SWIS instrument of the ASPEX payload onboard India’s Aditya-L1 mission.

The dataset is provided in Common Data Format (CDF), a standard scientific format widely used in space physics and astrophysics research.

The objective is to explore solar particle activity and identify transient disturbances in solar wind measurements using time-series analysis techniques.

**Objectives**

Load and process scientific CDF datasets
Extract particle flux measurements across energy channels
Convert multidimensional data into a time-series signal
Visualize solar wind particle activity
Detect sudden disturbances using statistical anomaly detection
Tech Stack
Python
Pandas
NumPy
Matplotlib
cdflib (for handling CDF datasets)
Dataset

The analysis uses SWIS Level-2 particle data from the Aditya-L1 mission.

**Variables analyzed:**

Particle flux measurements
Energy channel data
Spacecraft position
Timestamped particle observations

CDF is a widely used format in scientific missions and space data archives.

**Workflow**

1. Load CDF dataset using Python
2. Inspect dataset variables and metadata
3. Extract particle flux across energy channels
4. Aggregate flux values into a time-series signal
5. Visualize solar particle flux over time
6. Apply rolling averages to observe trends
7. Detect transient disturbances using statistical thresholds
Results and Visualizations

**The project generates the following outputs:**

Time-series plots of solar wind particle flux
Rolling average trend analysis
Detection of transient disturbances
Energy versus flux heatmaps

These visualizations help identify periods of increased solar particle activity that may correspond to solar events.

**Key Learnings**

Working with scientific datasets in CDF format,
Applying time-series analysis to space physics data,
Handling multidimensional data transformation,
Using statistical techniques for anomaly detection,

**Use Cases**
Space weather monitoring,
Satellite safety analysis,
Communication system reliability,
Research in heliophysics,


**Conclusion**

This project demonstrates the application of data analysis and time-series techniques to space science data, enabling the identification of solar activity patterns using real mission datasets.
