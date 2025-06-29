# AIRCRAFT SAFETY AND RISK RECOMMENDATION FOR NEW INVESTORS  
## Introduction  
As our company considers entering the aviation sector, it is essential to understand the safety records of different aircraft types. Certain aircraft models have demonstrated consistent reliability, while others present elevated operational risks.

This analysis uses historical accident data to identify aircraft with strong safety profiles and to understand the contributing factors behind aviation incidents. The goal is to inform aircraft acquisition decisions with evidence-based insights, minimizing exposure to financial, legal, and operational risk.  

#### For a non-technical presentation of the data, check this [link](https://github.com/patsi-dev/Phase-1-Project-Repository/blob/main/Aircraft_Safety_Presentation_Final.pdf)  
#### For a Tableau presentation, refer to this [link]()

---

### Objectives  

- Clean up the aircraft accident dataset and remove all noise  
- Find aircraft with the least number of accidents  
- Check which ones have fewer fatalities and are more survivable  
- Look into causes like weather and flight phase to see patterns  
- Finally, give a shortlist of safe aircraft to consider buying  

---

## Business Understanding  

Aviation carries inherent risk, but these risks can be mitigated through informed decision-making. As new participants in this industry, we aim to identify aircraft models that offer the most favorable safety records.

Key questions guiding this analysis:

1. What aircraft types have the lowest risk based on data?  
2. Which ones have the most deaths and which are survivable?  
3. When are accidents most likely to happen during takeoff?, landing?  
4. Are there weather patterns that show up in the data often?  
5. Can we really say that flying is becoming safer with time?  
6. What models should we be careful about based on their track record?

---

## Data Understanding  

This project utilizes publicly available aircraft accident data compiled by the National Transportation Safety Board (NTSB). The dataset includes civil aviation accidents and selected incidents in the United States from the 1960s through the early 2020s.

Each record in the dataset represents a unique aviation incident.

Key fields used in this analysis include:

- `Event.Date` – when it happened  
- `Make`, `Model` – what kind of plane  
- `Total.Fatal.Injuries`, `Total.Serious.Injuries`, `Total.Minor.Injuries` – how bad it got  
- `Aircraft.Damage` – was it wrecked or repairable  
- `Weather.Condition` – clear skies or not  
- `Broad.phase.of.flight` – was the plane taking off, cruising or landing  
- `Purpose.of.flight` – was it for training, personal or business  

There’s a lot more in the dataset, but we stuck to the stuff that would help us figure out what planes are safer to use if we’re trying to enter the market smartly.
