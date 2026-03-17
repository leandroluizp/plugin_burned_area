🛰️ Burned Area Monitoring & Fire Risk Analysis (v1.0)
This QGIS plugin was developed to automate the processing of burn severity indices (dNBR) and meteorological fire risk analysis based on INPE and Sentinel-2 data.

🚀 Features
dNBR Calculation: Automated processing of Sentinel-2 bands for fire scar detection.

Dynamic Threshold: Fine-tuning of severity levels for different biomes.



🛠️ Requirements
QGIS 3.22 or higher.

Python Libraries: processing, numpy (built-in with QGIS).

📥 Installation (Cloud-based)
Open QGIS.

Go to Plugins > Manage and Install Plugins.

In the Settings tab, click Add to create a new repository.

Enter the repository URL (once the cloud setup is complete).

📖 How to Use
dNBR Processing: Select pre- and post-fire bands and define the threshold.

Risk Report: Load the INPE .nc file and the municipal boundaries layer. The plugin will generate a list of alerts in the console or print layout.

