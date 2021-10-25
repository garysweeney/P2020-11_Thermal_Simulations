# Gas Handling System Thermal Simulation

The purpose of this simulation is to obtain an acceptable length of piping that will allow argon gas to cool back to room temperature from 50-100C, this ensures no external cooling mechanisms will be used which saves our power consumption in the lab. This will be important when considering the temperature profiles between the gas purifier and radon trap. It is critical to understand the temperature profiles between these two components in order to ensure the purification and radiopurification of argon gas before entering the cryostat. The physics behind the components will be discussed below.

The gas purifier involves argon gas flowing through a hot, porous metal plate which breaks the van der Waal bonds between atmospheric impurities (oxygen, nitrogen, etc.) and the argon atoms. The atmospheric impurities bond to the metal plate and allowing the pure argon gas to flow through. The temperature of the argon gas will increase over long operational times due to longer exposure to the hot plate and may result in high temperatures from 50-100C. Down the line, still in thermal connection with the gas purifier, is the radon trap which removes radioactive contaminants in the gas. The radon trap works by flowing the argon gas through activated charcoal at low temperatures to bond the radon isotopes to the charcoal, thus, removing them from the gas. For higher efficiency in removing radioimpurities, the radon trap must be kept at cold temperatures on the order of -40C to -196C. 

The goal of this simulation is to get the gas back down to room temperature from extending the pipe length, this helps to increase the thermal cooling efficiency on the radon trap and avoid the need for external cooling mechanisms. 

The following assumptions were used in simulation:
- Straight stainless steel pipe allowing for laminar flow in the gas.
- Gas flows in at 3slpm.
- Gas temperatures at the gas purifier range from 50-100C
- The surface of the pipes are held at 293K (room temperature).
