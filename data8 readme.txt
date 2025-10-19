CO2 Concentration Data

Target Variable:
- co2: Measured concentration of CO₂ (in parts per million, ppm) at time t.

Observed Regressors:
- people_t: The number of people present in the room at time t.
- door_t: Binary variable indicating the status of the door at time t.
  - 1 = door is open
  - 0 = door is closed
- window_t: Binary variable indicating the status of the window at time t.
  - 1 = window is open
  - 0 = window is closed

Description:
This dataset contains information on CO₂ concentration levels (ppm) within a room,
based on the number of people present and the status of the door and window at each recorded time t.