# Analyse traffic accident data to identify patterns related to road conditions, weather and time of the day. visualize accident hotspots.
# Dataset
**ID:** Unique identifier for each accident.                     
**Source:** Platform or system providing accident data.                                
**Severity:** Numeric representation of accident severity (1 = minor, 4 = severe).                                 
**Start_Time:** Timestamp when the accident started.                                  
**End_Time:** Timestamp when the accident ended.                                  
**Start_Lat:** Latitude at the start of the accident.                                  
**Start_Lng:** Longitude at the start of the accident.                                     
**End_Lat:** Latitude at the end of the accident (if applicable).                                      
**End_Lng:** Longitude at the end of the accident (if applicable).                                
**Distance (mi):** Distance over which the accident occurred (in miles).                           
**Roundabout:** Boolean indicating whether a roundabout was nearby.                                
**Station:** Boolean indicating whether a station was nearby.                                  
**Stop:** Boolean indicating whether a stop sign was nearby.                                              
**Traffic_Calming:** Boolean indicating whether traffic calming measures (e.g., speed bumps) were nearby.                                     
**Traffic_Signal:** Boolean indicating whether a traffic signal was nearby.                     
**Turning_Loop:** Boolean indicating whether a turning loop was nearby.                                 
**Sunrise_Sunset:** Indicates if the accident happened during day or night.
**Civil_Twilight:** Indicates if the accident happened during civil twilight (early morning/late evening).                            
**Nautical_Twilight:** Indicates if the accident happened during nautical twilight.                                
**Astronomical_Twilight:** Indicates if the accident happened during astronomical twilight.

# Visualizations
**1. Accident Hotspots:** Heatmaps highlighting areas with high accident concentrations.                                        
**2. Accidents by Time of Day:** Bar charts showing the distribution of accidents throughout the day.                                              
**3. Accidents by Weather Condition:** Visual representation of accidents under different weather conditions.                           
**4. Accident Severity Distribution:** Visualization of accident severity levels.                            
**5. Accidents by Road Conditions:** Charts showing the influence of road infrastructure on accidents.

# Key Analysis
**1. Accident Hotspots Visualization**                         
I used geographical coordinates (Start_Lat, Start_Lng) to create a heatmap of accident hotspots on U.S.A map. This map helps identify high-risk areas that require targeted interventions to improve road safety.

**2. Accident Patterns by Time of Day**                                              
By extracting the hour from the Start_Time, then analyzed accidents across different times of the day (morning, afternoon, evening, night). Afternoon, followed by the Morning and then Evening, recorded the highest number of accidents. On the other hand, the least number of accidents occurred during Midnight. 

**3. Weather Influence on Accidents**
The dataset includes information about weather conditions during the accident. By categorizing accidents by weather (e.g., clear, rainy, snowy), we observed how different weather types contribute to accident likelihood and severity. The analysis revealed that fair weather, followed by cloudy conditions, recorded the highest number of accidents. In contrast, accidents occurring during fog conditions were the least frequent

**4. Severity of Accidents**                        
The severity of traffic accidents was categorized into four levels, where 1 indicates the least impact and 4 indicates the most significant impact on traffic. The analysis revealed the following distribution of accident severities:                               

  Severity 2: 79.5% of accidents               
  Severity 3: 16.9% of accidents                            
  Severity 4: 2.6% of accidents                            
  Severity 1: 0.9% of accidents                             

**5. Road Conditions and Accidents**                 
Upon examining the impact of road features on accident frequency and severity, it was found that the most accidents occur in areas with traffic signals, crossings, and junctions.This suggests that these locations, which involve complex traffic movements and interactions, pose a higher risk for accidents.
