#  Dataset Details
* The dataset is converted to zip file using 7-Zip file manager.

* You can download the software [here](https://www.7-zip.org/a/7z2301-x64.exe).

* Data is in **CSV** file format for the year 2022.

## Dataset Description

The dataset used in this case study contains bike-share data from Cyclistic, a bike-sharing company. The dataset includes information about bike rides, user types (member or casual), ride duration, bike types, start and end times, and other relevant attributes.

### Original Dataset Overview

- **Folder Name**: Data CSV
- **Data Size**: Approximately 1 GB
- **Columns**:
  - `ride_id`: Unique identifier for each ride
  - `member_type`: User type (member or casual)
  - `bike_type`: Type of bike used (classic bike, docked bike, electric bike)
  - `start_time`: Start time of the ride
  - `end_time`: End time of the ride
  - `start_station_name`: Name of the start station
  - `end_station_name`: Name of the end station
  - `start_station_id`: ID of the start station
  - `end_station_name`: ID of the end station
  - `start_lat`: Latitude of start station
  - `end_lat`: Latitude of end station
  - `start_lng`: Longitude of start station
  - `end_lng`:  Longitude of end station


### Data Quality and Preprocessing

Before performing the analysis, some data preprocessing steps were applied to ensure data quality and consistency. This included removing any missing or erroneous values, converting data types, and creating additional derived variables for analysis purposes.  


### Data Source

The dataset was sourced from Cyclistic and represents a sample of bike rides taken during a specific period. Due to privacy and confidentiality reasons, certain attributes and personally identifiable information may have been anonymized or omitted.

### Final Dataframe Overview

- **File Name**: bike_data.csv
- **File Size**: Approximately 400 MB
- **Number of Rows**: 500,000+
- **Columns**:
  - `member_type`: User type (member or casual)
  - `ride_length`: Duration of the ride in seconds
  - `ride_length_time`: Duration in  hh:mm:ss format
  - `bike_type`: Type of bike used (classic bike, docked bike, electric bike)
  - `date`: Date on which ride started
  - `hour_of_day`: Hour of day at which ride started
  - `time_of_day`: Morning/Afternoon/Evening/Night
  - `month`: Month(Jan-Dec)
  - `day`: Day of the ride
  - `day_of_week`: Which day(1-7) of the week the ride was on
  - `season`: The season during the ride
