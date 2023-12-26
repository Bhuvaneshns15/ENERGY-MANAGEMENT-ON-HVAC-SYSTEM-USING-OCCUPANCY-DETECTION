# ENERGY-MANAGEMENT-ON-HVAC-SYSTEM-USING-OCCUPANCY-DETECTION

This project proposes an energy management strategy for heating, ventilation, and air conditioning (HVAC) systems using occupancy detection to optimize energy usage in buildings. Occupancy sensors are employed to detect human presence in various zones, enabling dynamic adjustments in HVAC operation based on real-time occupancy data. By integrating occupancy information into the HVAC control system, parameters such as temperature set points, ventilation rates, and airflow distribution can be optimized. The approach aims to achieve energy savings during unoccupied periods while ensuring occupant comfort during occupied periods. Experimental results demonstrate the effectiveness of the proposed strategy inreducing energy consumption and improving HVAC system performance. The proposed method contributes to sustainable building practices by enabling energy-efficient HVAC operation based on occupancy detection.

PROCEDURE :
Give the connections as per IR receiver circuit diagram with nodemcu
Upload the IR Reciever.ino code which is present in code section to the nodemcu.
After uploading, Get the IR raw data codes by pressing temperature up and down buttons for desired temperature setpoint from the remote to the IR reciever
Save the reciever IR raw data codes for using it while transmission
Open the IR transmitter.ino code in Arduino IDLE
Replace the existing raw data IR code with your respective remotes IR codes
Give the connections as per IR transmitter circuit diagram
Upload the IR transmitter.ino to the nodemcu
After uploading, Run the control.py program
Thus temperature setpoint will be controlled by the occupancy received from system
