# Cryostat Thermal Simulations

The cryostat simulation involves the new design featuring HDPE and will determine if this design is viable when considering the heat loads that may occur. There are two main heat loads that occur in the cryostat which come from the vacuum jacket in the dewar walls and from the stainless steel top flange. The top flange goes from stainless steel to HDPE, to gaseous argon and then ends at the gaseous/liquid argon interface layer. In this simulation, thermal conduction is the dominant method of heat transfer through each medium. 

The second simulation concerns the heat load from the vacuum jacket. Heat must travel through the outer dewar wall into the vacuum jacket region then into the inner 
dewar wall which then interfaces the liquid argon layer. Thermal radiation is dominant in the vacuum jacket region while conduction is dominant everywhere else. The liquid argon layer is held at 87K and the outside wall temperature is at 293K. For a worst case scenario 100% thermal conduction is assumed and the inside of the outer dewar wall is held at 293K and the outside of the inner dewar wall is held at 90K. The following diagram outlines the configuration:

(Air) 293K | | 293K (Vacuum jacket region) 90K | | 87K (LAr)

The following assumptions were used:
- The temperature at the GAr/LAr layer is 87K.
- The temperature of the outside wall of the dewar and stainless steel top flange is 293K.
- The dewar walls are 0.024" thick and made of stainless steel.
- Thermal radiation is dominant in the vacuum jacket, conduction dominates everywhere else.
- Under worst case scenario the temperature between the vacuum jacket walls is 293-90K.
