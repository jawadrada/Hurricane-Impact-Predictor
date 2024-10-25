### **Column Info for Hurricane Dataset**

1. **Unnamed: 0**: This is likely an index column that was automatically created when the data was read into a DataFrame. It may not have any meaningful information.

2. **Year**: The year when the hurricane or storm data was recorded.

3. **Time**: The specific time (usually in UTC) when the data was recorded.

4. **Storm Name/Record Identifier**: The name of the storm or a unique identifier for the record.

5. **Number of Entries/Status**: This could indicate the number of data entries related to a specific storm or the current status of the storm (e.g., tropical storm, hurricane).

6. **Latitude**: The latitude coordinate of the storm's location at the recorded time.

7. **Longitude**: The longitude coordinate of the storm's location at the recorded time.

8. **Maximum Sustained Wind**: The maximum sustained wind speed of the storm, typically measured in knots.

9. **Minimum Pressure**: The minimum atmospheric pressure recorded for the storm, usually measured in millibars (mb).

10. **34-knot Wind Radii NE**: The distance from the storm's center to the outer edge of the 34-knot wind speed in the northeast quadrant.

11. **34-knot Wind Radii SE**: The distance from the storm's center to the outer edge of the 34-knot wind speed in the southeast quadrant.

12. **34-knot Wind Radii SW**: The distance from the storm's center to the outer edge of the 34-knot wind speed in the southwest quadrant.

13. **34-knot Wind Radii NW**: The distance from the storm's center to the outer edge of the 34-knot wind speed in the northwest quadrant.

14. **50-knot Wind Radii NE**: The distance from the storm's center to the outer edge of the 50-knot wind speed in the northeast quadrant.

15. **50-knot Wind Radii SE**: The distance from the storm's center to the outer edge of the 50-knot wind speed in the southeast quadrant.

16. **50-knot Wind Radii SW**: The distance from the storm's center to the outer edge of the 50-knot wind speed in the southwest quadrant.

17. **50-knot Wind Radii NW**: The distance from the storm's center to the outer edge of the 50-knot wind speed in the northwest quadrant.

18. **64-knot Wind Radii NE**: The distance from the storm's center to the outer edge of the 64-knot wind speed in the northeast quadrant.

19. **64-knot Wind Radii SE**: The distance from the storm's center to the outer edge of the 64-knot wind speed in the southeast quadrant.

20. **64-knot Wind Radii SW**: The distance from the storm's center to the outer edge of the 64-knot wind speed in the southwest quadrant.

21. **64-knot Wind Radii NW**: The distance from the storm's center to the outer edge of the 64-knot wind speed in the northwest quadrant.

These columns contain key information about the location, intensity, and spatial extent of the storm at different points in time, which will be crucial for analyzing the impact of hurricanes on vessel movements.

------------------------

### **Column Info for Vessel Dataset**

1. **MMSI**: The Maritime Mobile Service Identity, a unique identifier for the vessel used in AIS (Automatic Identification System) communications.

2. **BaseDateTime**: The timestamp indicating when the data was recorded.

3. **LAT**: The latitude coordinate of the vessel at the recorded time.

4. **LON**: The longitude coordinate of the vessel at the recorded time.

5. **SOG**: Speed Over Ground, indicating the vessel's speed relative to the ground, typically measured in knots.

6. **COG**: Course Over Ground, representing the vessel’s direction of travel relative to the earth’s surface, usually in degrees.

7. **Heading**: The direction in which the vessel's bow is pointing, typically in degrees. It may differ from COG if the vessel is drifting.

8. **VesselName**: The name of the vessel.

9. **IMO**: The International Maritime Organization number, a unique identifier for ships, assigned by the IMO.

10. **CallSign**: The vessel's radio call sign, used for communication.

11. **VesselType**: The type or category of the vessel (e.g., cargo ship, tanker, passenger ship).

12. **Status**: The current status of the vessel, such as whether it is anchored, underway, or moored.

13. **Length**: The length of the vessel, usually measured in meters.

14. **Width**: The width or beam of the vessel, also measured in meters.

15. **Draft**: The depth of water the vessel needs to float, indicating how much of the vessel is submerged.

16. **Cargo**: Information about the type of cargo the vessel is carrying, if applicable.

17. **TransceiverClass**: The class of the AIS transceiver installed on the vessel (e.g., Class A for larger vessels, Class B for smaller vessels), which can affect the range and frequency of AIS signals.