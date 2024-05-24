# Context of MPTEX 

MPTEX allows the user to calculate the prospective life cycle inventory of direct air capture (DAC) systems for a specific year, between 2020 and 2050.

This new package would support the user to understand the environmental impact of a prospective DAC system in a temporal and spatial condition. First, it calculates the amount of energy produce via PV panels in a certain location, according to the .... Then, this is adapted within the grid mix in the selected location in the speifcic year. Next, the user will get ...


**Direct Air Capture (DAC) system inventory**

DAC is a product system (or technology) that takes in atmospheric air as an input and produces CO{sub}`2` as an output. The system typically uses CO{sub}`2`-absorbing chemicals, energy (heat), and electricity to remove CO{sub}`2` from the atmosphere. 


**Generating future Life Cycle Inventory (LCI):**

The prospective system inventory of the DAC system was estimated in two steps:
1. Energy consumption projection: We projected the expected reduction in energy and electricity consumption in the DAC system using technology learning curves. The learning rates were obtained from the peer-reviewed literature, and in our case, we used a learning rate of 2.5%.

2. PV efficiency projection (spatial): The annual solar irradiation over global locations varies significantly, and this can affect the total energy (kWh) that can be produced from a single PV panel. Since the total lifetime energy production from PV panels influences the per kWh emissions, it is important to understand how the efficiencies can change with locations and how they can be incorporated into the future LCI. Therefore, in our model, we estimated the changes in the efficiency of PV based on the lifetime solar irradiation observed across spatial locations using EU JRC datasets from Photovoltaic Geographical Information System (PVGIS). 


![dac](img/pLCI_PV-DAC.png)
