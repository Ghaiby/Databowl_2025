# Databowl 2025 Submission Files
---
Data:
  - Tracking_Audibles.zip: Dataset with all potential audible plays labled as is_audible == True.
  - Tracking_Audibles1500: Dataset narrowed down to 1500 potential audible plays labled as is_audible == True using more sensitive detection.
  - defensive_formations.zip: Dataset including the defensive formation of each team by: number of player on line of scrimmage, number of players in the second level, and number of deep defenders

Images: 
  - contains all images and gifs used in the submission report
Notebooks:
- DataAnalysisDefense.ipynb: Script for obtaining the most common audible plays and other audible insights for defenses 
- DataAnalysisOffense.ipynb: Script for obtaining the Audible effectiveness and other audible insights for offenses
- audible_detection.ipynb: Script for detecting algorithms from tracking data set 
- defensive-tracking.ipynb: Script for obtaining the defensive formation from tracking data, including individual player locations. 
