# Project Overview: 
This master’s project examined and characterized temporal patterns in pile-driving activity and associated changes in sound exposure levels (SEL) at Vineyard Wind 1, the first commercial-scale offshore wind farm in the United States.

In collaboration with Project WOW, a transdisciplinary research initiative evaluating the potential effects of offshore wind energy development on marine wildlife, six Rockhopper passive acoustic recording units (Cornell University) were analyzed. These units were deployed within and surrounding the Vineyard Wind 1 Wind Energy Area (WEA) from August 15, 2023 to February 13, 2024.

# Data Collection: 
Acoustic data were collected using Rockhopper recording units deployed at varying distances from turbine installation sites. Five of the six units were located within or adjacent to the Vineyard Wind 1 WEA and were used to quantify pile-driving activity.

# Methods: 
Pile-driving strikes were identified and quantified using Raven Pro, an acoustic analysis software used to visualize, measure, and analyze underwater sound. An automated pile-driving strike detector was developed in Raven Pro for the Rockhopper units closest to turbine installation activity.

For each detected pile-driving strike, the following acoustic parameters were measured:
- Sound Exposure Level (SEL), defined as the squared instantaneous sound pressure integrated over the pulse duration (dB re 1 µPa²·s)
- 5% and 95% energy intervals of the pulse

Using R, the following metrics were calculated:
- Duration of piling events
- Average inter-pulse interval between strikes
- Average inter-pulse interval within continuous piling periods
- Strike rate
- Average pulse duration
- Duty cycle

Additionally, SELs recorded at the nearest and farthest Rockhopper units were compared to assess spatial variation in sound levels during pile-driving activities.

# Tools Used: 
- Raven Pro
- R
- Rockhopper Passive Acoustic Recorders
- Microsoft Excel

# Code and Data Availability: 
Due to data sensitivity and project restrictions, analytical code and raw acoustic data are not publicly available. This repository contains only approved final outputs and documentation.

# Academic Context:
This project was submitted in partial fulfillment of the requirements for the Master of Environmental Management degree at the Nicholas School of the Environment, Duke University.
