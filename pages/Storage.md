- ### Overview and general characteristics
  collapsed:: true
	- Why needed?
		- Solve electrical imbalance in space and time
		- Flexibility needed to equate demand with supply
			- Flexible demand
				- Flatten demand curve
				- By increasing self consumption
					- Of PV
					- with tariffs (direct)
			- flexible supply
	- Categorize technologies regarding
		- conversion process
		- Energy vs Power
		- Application
			- ![image.png](../assets/image_1682194036223_0.png){:height 283, :width 485}
			- Very important picture!
		- Location
			- Central vs distributed?
			- ![image.png](../assets/image_1682194207475_0.png){:height 264, :width 491}
	-
		- Maturity
	- Efficiency
		- Every conversion in the system yields a kind of efficiency
- ### Mechanical storage
	- #### Pumped Hydro Storage (PHS)
		- General
		  collapsed:: true
			- Position of body of water in gravitational field
			- Pure and mixed
			- Power pumping ≠ turbine
			- Roundtrip efficiency 65-85%
			- Most often in HV grid
			- Asset of producers in liberalized market
			- Energy: $$\Delta E_{pot} = \rho\cdot g\cdot \Delta h\cdot V$$
				- Big heights $$\Delta h$$ (e.g. mountains)
				- Big lakes $$V$$
			- Power: $$P = \rho\cdot g\cdot \Delta h\cdot Q\cdot \eta$$
		- Roll out
		  collapsed:: true
			- together with Nuclear
				- complimentary flexibility
		- Potential
		  collapsed:: true
			- Sizable potential still
			- Geographically limited
			- Of limited use with congestion issues
			- Not really long-term (security of supply context)
			- Limited power control flexibility (pumping), specifically around 0 MW (dewatering)
		- Energy island
		  collapsed:: true
			- ((644434c5-a6be-4994-a54a-906bc62b063b))
			- Recently proposed project (JD: will never be built)
			- Proven (mature) technology in a new innovative context
			- Facilitating the integration of off shore wind power
			- Future off shore Supergrid building block
	- #### CAES
		- = Compressed Air Energy Storage
		- used for storing energy by compressing air into an underground reservoir or storage tank with use of a compressor, which can be released later to generate electricity using a turbine.
		- Often combined with Gas plant
		- CBA
		  collapsed:: true
			- (+) Low capital cost (integrated in CCGT plant)
			- (-) Need for natural cavity (typically salt cavern)
			- (-) Lower round trip efficiency
				- Energy lost to the boundaries of the cavern
			- (-) Depends on presence of gas turbines and natural gas pipeline
		- Adiabatic Compressed Air Storage
		  collapsed:: true
			- Same but in combination with heat storage to increase efficiency
			- the compressed air is heated before it is stored and cooled before it is expanded through a turbine to generate electricity
	- #### Flywheel
	  collapsed:: true
		- Storage of kinetic energy, by rotation of large inertia
		- High speeds
			- Special generators/motors needed
		- Vacuum
		- Heavy inertia
		- Magnetic bearings
		- (+)Fast charge/discharge
			- high Power/low Energy
		- Applications
			- Not in renewable energy
			- Maybe in exotic applications like CERN
			- Supercapacitors took over the market that flywheels were occupying 20years ago
- ### Electromagnetic Storage
	- #### Supercapacitors
		- *A supercapacitor or an ultracapacitor is an electrochemical capacitor that has an unusually large amount of energy storage capability relative to its size when compared to common capacitors.*
		- Concept
		  collapsed:: true
			- electrochemical energy storage device that stores electrical energy in an electric field between two electrodes separated by an electrolyte
			- Supercapacitors can store much more energy than traditional capacitors due to their larger surface area and thinner dielectric layers, allowing them to store more charge
				- Electrostatic: low capacitance, no electrolyte, insulating material in between electrodes: mica, teflon, ceramic, ...
				- Electrolytic: “Elco”, DC-link energy storage, high single cell voltage compared to EDLC, high capacitance compared to electrostatic caps, inherently polar
		- CBA
		  collapsed:: true
			- (+)
				- (+) Very high rates of charge and discharge.
				- (+) Little degradation over hundreds of thousands of cycles.
				- (+) High cycle efficiency (95% or more) due to its low equivalent
				  series resistance (ESR)
			- (-)
				- (-) The amount of energy stored per unit weight is considerably lower than that of an electrochemical battery (3-5 Wh/kg for an Ultra Capacitor compared to 30-190 Wh/kg for a battery).
				- (-) The voltage varies strongly with the energy stored. To effectively store and recover energy requires sophisticated electronic control and switching equipment.
				- (-) Exhibits the highest dielectric absorption (inability, when being charged for a long time, to completely discharge) of all types of capacitors: 15-25 % Vnom
				- (-) Low cell voltage (2,5-2,7 V): series coupling of several tens of cells to obtain a useful voltage
		- Applications
		  collapsed:: true
			- Leuven buses
				- Store braking energy
				- But hybrid buses are being pushed out the market
	- #### Superconducting Magnet Energy Storage (SMES)
		- Concept
		  collapsed:: true
			- Formula: $$E = \frac{1}{2}L I^2$$
				- High inductance
				- High current needed
					- Low resistance needed-> superconductor
			- type of energy storage system that uses a superconducting coil to store electrical energy in a magnetic field
			- The superconducting coil is made of a material that exhibits zero electrical resistance when it is cooled to a very low temperature, typically near absolute zero (-273.15°C or -459.67°F). This allows a large amount of electrical current to flow through the coil without any energy loss due to resistance.
				- e.g. Liquid nitrogen
			- When energy is stored in the SMES system, a large current is passed through the superconducting coil, creating a strong magnetic field. When energy is required, the magnetic field is used to generate an electrical current that can be used to power devices or systems.
		- CBA
		  collapsed:: true
			- (+) High $$P$$
			- (-) Low $$E$$
			- (-) Losses related to the high cooling efforts
		- Applications
		  collapsed:: true
			- only CERN
			- Out of picture for renewable energy storage
- ### Chemical Storage
	- #### Electricity to gas (P2X)
	  collapsed:: true
		- ![image.png](../assets/image_1682669389567_0.png)
		- More for direct use than for storage
		- Fuel cells needed to do the oxidation (conrtolled)
			- By definition, the process of any fuel cell could be reversed.
			- However, a given device is usually maximized for operating in one modus and may not be built in such a way that it can be operated backwards.
			- Fuel cells operated backwards generally do not make very efficient systems.
		- (-) Low efficiency
	- #### Batteries
		- Concept
		  collapsed:: true
			- Negative electrode: good electron donor
			- Positive electrode: electron acceptor (lithium cobalt oxide,
			  lead oxide)
			- Electrolyte: pure ionic conductor, usually liquid solvent- based, only stable in certain voltage ranges otherwise decomposition
		- At low discharge depth: flat voltage characteristic (not linear as with capacitors)
		  collapsed:: true
			- battery management system added (keeps track of how much energy is charged/discharged by integrating the currents)
			- Avoid the voltage collapse
		- Losses
		  collapsed:: true
			- Electrical (Joule losses because of internal resistence)
			- Chemical losses
		- Equivalent circuit
		  collapsed:: true
			- ![image.png](../assets/image_1682671139364_0.png)
			- With capacitors $$C_{trans}$$, $$C_{ss}$$ High
			- With capacitors $$C_{trans}$$, $$C_{ss}$$ small, otherwise $$\tau = RC$$ is big and discharge is slow
			- -> possible to design towards requirements
		- See safety slide
		- ![image.png](../assets/image_1682670364570_0.png){:height 314, :width 394}
			-
		- ![image.png](../assets/image_1682670398058_0.png){:height 315, :width 417}
	- **Lead Acid**
		- Lead-acid baderies are the oldest type of galvanic cells and are the most commonly used rechargeable baderies today
		- They have the second lowest energy density (next to the obsolete NiFe badery)
		- Effective lead pollution control system is a necessity for sustainable environment
		- Problems
			- Gel instead of liquid to avoid dry out
			- Salt crystal growth on diodes, reduces conduction
		- Technologies
			- Absorbed Glass Mat (AGM) VRLA: low resistance
			  microporous glass fiber immobilizes the electrolyte and acts as separator, newer and more abuse tolerant than Gel VRLA
			- Gel VRLA: mixing electrolyte with micron diameter silicon dioxide, very small rate of charge (C/20) to prevent excess gas from damaging the cell
			- Open / Flooded Cells: during overcharging gasses escape àreplenishing with water
-