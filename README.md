#  *Traffic Violations Exploration*

This repository contains an exploration of traffic violations data, aiming to understand patterns and trends in traffic violations.

The analysis focuses on exploring various aspects of traffic violations, including demographics, types of violations, gender disparities, racial distribution, and trends over time.

## About Dataset: 
This dataset contains around 65k+ traffic related violation records. Attribute Information:

1. `stop_date` - Date of violation
2. `stop_time` - Time of violation
3. `driver_gender` - Gender of violators (Male-M, Female-F)
4. `driver_age` - Age of violators
5. `driver_race` - Race of violators
6. `violation` - Category of violation :
- Speeding
- Moving Violation (Reckless driving, Hit and run, Assaulting another driver, pedestrian, improper turns and lane changes etc)
- Equipment (Window tint violations, Headlight/taillights out, Loud exhaust, Cracked windshield, etc.)
- Registration/Plates
- Seat Belt
- Other (Call for Service, Violation of City/Town Ordinance, Suspicious Person, Motorist Assist/Courtesy, etc.)
7. `search_conducted` - Whether search is conducted in True and False form
8. `stop_outcome` - Result of violation
9. `is_arrested` - Whether a person was arrested in True and False form
10. `stop_duration` - Detained time for violators approx (in minutes)
11. `drugs_related_stop` - Whether a person was involved in drugs crime (True, False)

## Libraries Used
`Python` `Pandas` `Numpy` `Matplotlib` `Searborn` 

## Exploratory Analysis
#### 1. Demographics and Violations

- Identified that individuals aged 18-40 are more prone to traffic violations, with speeding being the most prevalent offense.
- Males are consistently more involved in violations compared to females.
#### 2. Racial Distribution

- Explored racial distribution among individuals involved in traffic incidents, highlighting disparities across different racial groups.
#### 3. Gender Disparities

- Investigated gender-specific trends in traffic violations, noting higher instances of drug-related offenses among males.
#### 4. Trends Over Time

- Observed a steady decrease in the overall number of violations over time, with speeding violations remaining consistently high.
#### 5. Arrest Outcomes

- Analyzed pre-search and post-search arrest rates during traffic stops, indicating a significant increase in arrest occurrences post-search.
