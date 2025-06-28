# AIRCRAFT SAFETY AND RISK RECOMMENDATION FOR NEW INVESTORS  
## Introduction  
Not every aircraft is made the same. Some planes have proven over time to be safer than others. Others may fly well but when something goes wrong, things go really bad. As we look into entering the aviation space — whether private or commercial — we need to know which aircraft give us the least stress.

It’s not just about looks or speed. Even the most basic things like weather, type of flight or how many people are onboard can change everything. We want something safe, reliable and that won’t turn into a legal or financial nightmare down the road.

In this project, we used historical data to check which planes make sense to start with.  

#### For a simple overview of the analysis, check this [link](#)  
#### The full Python notebook is available here [link](#)

---

### Objectives  

- Clean up the aircraft accident dataset and remove all noise  
- Find aircraft with the least number of accidents  
- Check which ones have fewer fatalities and are more survivable  
- Look into causes like weather and flight phase to see patterns  
- Finally, give a shortlist of safe aircraft to consider buying  

---

## Business Understanding  

Flying will always carry some risk. But we don’t want to go into it blind. Some models just do better. Some crash less. Some crash but people survive. Some crash and it’s over. We need to know the difference before we buy.

We’re asking:

1. What aircraft types have the lowest risk based on data?  
2. Which ones have the most deaths and which are survivable?  
3. When are accidents most likely to happen — during takeoff? landing?  
4. Are there weather patterns that show up in the data often?  
5. Can we really say that flying is becoming safer with time?  
6. What models should we be careful about based on their track record?

We’re not just looking at numbers — we’re looking for peace of mind.

---

## Data Understanding  

The data was pulled from an open aviation source. It includes reported accidents and incidents involving aircraft mainly in the US from the 1960s up to recent years.

Each row is a different accident. We’re talking about mechanical failures, weather issues, human error, etc. Some small, some fatal.  

Some of the columns we focused on are:

- `Event.Date` – when it happened  
- `Make`, `Model` – what kind of plane  
- `Total.Fatal.Injuries`, `Total.Serious.Injuries`, `Total.Minor.Injuries` – how bad it got  
- `Aircraft.Damage` – was it wrecked or repairable  
- `Weather.Condition` – clear skies or not  
- `Broad.phase.of.flight` – was the plane taking off, cruising or landing  
- `Purpose.of.flight` – was it for training, personal or business  

There’s a lot more in the dataset, but we stuck to the stuff that would help us figure out what planes are safer to use if we’re trying to enter the market smartly.
