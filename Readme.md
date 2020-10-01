# The Weather Dataset

The weather dataset is a timeseries data set with per-hour information about the weather conditions at a particular location. It records temperature, dew point temperature, relative humidity, wind speed, visibility, pressure and conditions.

Here I only analyse the data given by using guided questions, written as comments.

### Findings
The dataset has 8784 rows and 8 columns. The columns are a record of Date/Time, Temperature (Temp_C), Dew point (Dew Point Temp_C), Relative Humidity (Rel Hum_%), Wind Speed(Wind Speed_km/h) Visibility(Visibility_km) Pressure(Press_kPa) Weather conditions(Weather). 

**Temperature** : The average temperature recorded was 8.798144 degrees celsius with a maximum of 33.0 and a minimum of -23.3 degrees celsius.
**Dew Point** : The average dew point recorded was 2.555294 degrees celsius with a maximum of 24.4 and a minimum of -28.5 degrees celsius.
**Relative Humidity** : Average relative humidity was 67.431694% with a maximum of 100% and a minimum of 18%.
**Wind Speed** : Average wind speed recorded was 14.945469 km/h with a maximum of 83 km/h and a minimum of 0.0 km/h.
**Visibility** : Average visibility recorded was 27.664447 km with a maximum of 48.3 km and a minimum of 0.2 km.
**Pressure** : Average pressure recorded was 101.051623 kPa with a maximum of 103.65 kPa and a minimum of 97.52 kPa.
**Weather Conditions** : There are 50 unique values of weather conditionns:
 
| **Weather Conditions** | **Frequency** |
| ---------------------- | ------------- |
| Mostly clear | 2106 |
| Mostly cloudy | 2069 |
| Cloudy | 1728 |
| Clear | 1326 |
| Snow | 390 |
| Rain | 306 |
| Rain Showers | 188 |
| Fog | 150 |
| Rain,Fog | 116 |
| Drizzle,Fog | 80 |
| Snow Showers | 60 |
| Drizzle | 41 |
| Snow,Fog | 37 |
| Snow,Blowing Snow | 19 |
| Rain,Snow | 18 |
| Haze | 16 |
| Thunderstorms,Rain Showers | 16 |
| Drizzle,Snow,Fog | 15 |
| Freezing Rain | 14 |
| Freezing Drizzle,Snow | 11 |
| Freezing Drizzle | 7 |
| Snow,Ice Pellets | 6 |
| Freezing Drizzle,Fog | 6 |
| Snow,Haze | 5 |
| Snow Showers,Fog | 4 |
| Rain,Snow,Ice Pellets | 4 |
| Freezing Rain,Fog | 4 |
| Moderate Snow | 4 |
| Freezing Fog | 4 |
| Thunderstorms,Rain | 3 |
| Freezing Drizzle,Haze | 3 |
| Rain,Haze | 3 |
| Thunderstorms,Rain Showers,Fog | 3 |
| Moderate Snow,Blowing Snow | 2 |
| Thunderstorms | 2 |
| Freezing Rain,Haze | 2 |
| Rain Showers,Snow Showers | 2 |
| Drizzle,Snow | 2 |
| Thunderstorms,Rain,Fog | 1 |
| Moderate Rain,Fog | 1 |
| Snow Pellets | 1 |
| Thunderstorms,Heavy Rain Showers | 1 |
| Rain,Snow,Fog | 1 |
| Rain,Ice Pellets | 1 |
| Freezing Rain,Snow Grains | 1 |
| Drizzle,Ice Pellets,Fog | 1 |
| Thunderstorms,Moderate Rain Showers,Fog | 1 |
| Rain,Snow Grains | 1 |
| Freezing Rain,Ice Pellets,Fog | 1 |
| Rain Showers,Fog | 1 |

We can therefore conclude by the data collected over 8784 days(24.1 years) that this is usually a cold, calm and humid area.