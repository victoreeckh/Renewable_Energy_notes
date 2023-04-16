- ### Intro
	- #### Energy Storage
	  collapsed:: true
		- Increased importance
			- the growing share of renewable energy sources
				- Why renewables?
				  collapsed:: true
					- mismatch demand-supply in time and location
					- potential congestion of electricity grid
					- higher demand for flexibility, smart grid
					- the highly fluctuating electricity price (optimization towards minimal cost) and financial incentives
				- Role of storage in relation to renewables
				  collapsed:: true
					- Intermittent renewable energy sources (variable and difficult to
					  predict), e.g. solar thermal, PV, wind ...
					- Time shift towards consumption during off-peak periods and production during peak-periods, e.g. geothermal heat pump (consumption), biomass-fired-CHP (production) ...
					- Increasing performance (and thus reducing emissions) by less transient operation and less cycling, e.g. heat pumps, biomass boiler ...
					- Avoid problems of electricity grid infrastructure (voltage fluctuations), e.g. PV, heat pumps ...
			- more emphasis on energy conservation: residual heat recovery
		- Implies losses ($$\eta<1$$)
		- Types
			- TES
			- Electrical Energy Storage (EES)
			- Power-to-Heat, Power-to-Cold + TES
	- #### TES
		- *TES is a technology that stores thermal energy by heating or cooling a storage medium so that the stored energy can be used later for heating and cooling applications or power generation*
		- Offers flexiblity
		  collapsed:: true
			- Demand shifting
			- Variable supply integration
			- Sector integration
			- Network management
			- Seasonal storage
		- Sectors
		  collapsed:: true
			- Power
			- Buildings
			- District heating and cooling
			- Cold chain
			- Industry
		- Energy density
		  collapsed:: true
			- TCM (thermochemical materials)> PCM (phase changing materials)> water
		- TES selection
			- Parameters
			  collapsed:: true
				- Temperature range
				- Storage density (space limited?)
				- Long versus short term
				- Application scale: decentralized versus centralized
				- Cost
				- Applicability – market readiness
					- Sensible: fully developed
					- Latent: improvements in thermal conductivity still needed
					- Thermochemical:
						- sorption is applied
						- chemical reaction in demonstration phase
			- Selection
			  collapsed:: true
				- ![image.png](../assets/image_1681635599138_0.png)
					- Sensible:
						- Water
							- Highest Energy density/heat capacity
							- with $$T \in [0,100]^{\circ}C$$
					- PCM
					- TCM
- ### TES - Sensible Storage
	- General
		- Heat is stored as internal energy, in the temperature increase of a medium (usually liquid or solid): $$Q = m\int_{T_1}^{T_2}c_p(T)dT$$
		- Temperature difference ($$\Delta T$$) drives the heat transfer; $$\Delta T$$ decreases while charging/discharging
		- Low energy storage density (large physical footprint); volumetric thermal capacity ($$c_p\rho$$) is important if space limitations
		- Power density can be limited by low thermal conductivity (solid) or low convective heat transfer rates (liquid) of some storage materials
		- State-of-the-art: well demonstrated, clearly understood, reliable, widely used, cheap
		- Considerable self discharge (heat losses) à insulation needed if high T or long storage times
	- Materials
		- Low cost:
			- Water: best choice in T range 20-80°C
			- Solid state: soil, rocks
		- Higher cost:
			- Oil: for higher temperatures
			- Salt solutions (brines):when old salt mines (caverns) are used as storage tanks and flooded
			- Blocks or plates of different solid materials (graphite, concrete, iron, iron oxide ...)
			- Molten salts
	- Types
		- Water
			- Characteristics
			  collapsed:: true
				- the best choice in T range 20-80°C
				- High thermal capacity (4.2kJ/kgK)
				- (-) Low cost
				- (-) Limited temperature range, but appropriate for building applications and for connection with solar thermal
				- High convective heat transfer rate
					- High heat injection and extraction rates
					- Makes stratification more difficult (because of mixing)
			- Configurations
				- ==Water tanks== (TTES)
					- Immersed coil heat exchanger
					  collapsed:: true
						- Generally located at bottom of tank (profit from high $$\Delta T$$, HT easier when $$\Delta T$$ is higher)
						- Mixed tank (not stratified)
					- External (side-arm) heat exchanger
					  collapsed:: true
						- Natural convection HEx to eliminate a circulation pump
						- Potential for increasing thermal stratification in tank
					- Mantle heat exchanger
					  collapsed:: true
						- Double walled storage tank, heat transfer fluid circulated through the storage mantle
						- Large heat transfer surface area
						- More costly
				- ==Aquifer== (ATES)
					- Working
					  collapsed:: true
						- Wells are used to carry (ground) water to/from the aquifer, allowing transport of heat
						- Cold and warm wells (distance 50-250m)
					- Characteristics
					  collapsed:: true
						- Potential for economical large scale and long term (seasonal) storage
						- Amount of energy stored depends on allowable temperature change, thermal conductivity, natural ground water flow
				- ==Solar Ponds==
					- Surface water (ponds or lakes) used to collect and store solar heat, with very little losses
					- As a result of the fact that Solar ponds contain salt solutions
					  collapsed:: true
						- Salinity gradient results in higher salt concentrations (and thus
						  higher density) at the bottom
						- Heat absorbed at the bottom remains trapped there
						- Salinity gradient inhibits natural convection and the cooler water at the surface acts as an insulator
						- Economically attractive in regions with little snow fall and areas where land is readily available
						- Maintenance similar to that of a swimming pool, control of algae and bacteria growth
		- Solid State
			- Characteristics
			  collapsed:: true
				- Working
					- Heat transport fluid (water, air) circulated through a bed of solid material, discharging/charging heat
				- Considered for seasonal storage when geological conditions favour this type of system
				- Materials:
					- ceramic bricks, beds of rock or concrete, for higher T refractory bricks based on oxides, carbonates and their mixtures
				- Lower thermal capacity than water, but can easily operate at higher temperatures
				- (+)Simple, relatively cheap, scalable
				- Air based systems: low energy density (3 times more space needed compared to water but economically favourable for short-term storage)
			- Configurations
				- ==Ground== (soil or solid rock), closed system
					- Low-cost system since soil is free, however drilling is expensive (21-24% of total storage system cost)
					- Ground is drilled to insert tubes (vertical or horizontal), in which a heat transport fluid circulates, injecting/extracting heat in/from the ground
					- Energy piles can also be integrated in foundation
					- Thermal energy storage versus energy dissipation: depends on thermal conductivity and groundwater flow, storage efficiency is rather low
					- Usually connected with a heatpump (for heating) and heat exchanger (for direct cooling)
				- Concrete Core Activation (CCA)
					- ==Thermally Activated Building Systems== (TABS)
						- Concrete floors/ceilings of a building are activated by embedding water tubes in the concrete and forcing warm/cold water through the tubes
						  id:: 643bcabb-2ed8-4a14-9a5b-292ab4abac4e
						- High temperature cooling and low temperature heating -> High COPs
						- Thermal capacity of concrete presents storage capacity
						  (thermal inertia, large time constant)
						- Difficult to control since heat/cold transfer to building
						  rooms is governed by $$\Delta T$$
						- Self regulating effects
					- ==GEOTABS==
						- *sensible storage in ground and building mass*
						- Both cooling and heating load in buildings (e.g. offices) => beneficial to long term ground thermal balance
							- Heating: high source temperature (ground) and low emission temperature (TABS) => high HP performance
							- Cooling: cold directly available in ground and high emission temperature (TABS) => passive cooling
						- GEO-HP + TABS: energy saving potential of 20-70%