- ### PV cell technology
	- #### Shockley-Queisser model: limiting efficiencies a.f.o. bandgap
	  collapsed:: true
		- Intro
			- ==Radiative recombination==
				- the energy of the recombining electron-hole pair is emitted as a photon
			- ==Auger Recombination==
				- the energy of the recombining electron-hole pair is transferred to another carrier
		- **Model**
			- Assumptions
				- Cell is black-body in thermal equilibrium with a thermal bath at temperature T
				- Isotropic irradiation
				- Unit absorbance for photons > Eg
				- Zero absorbance for photons < Eg
				- Only source of recombination is radiative (no Auger recombination)
				- Cell behaves like an ideal diode (ideality factor $$n=1$$): 
				  $$J(V)=J_0(exp(\frac{qV}{kT})-1)$$
				- Sun assumed to be black body radiator
			- Results
				- ![image.png](../assets/image_1681195487167_0.png)
					- Efficiency: $$\eta(V_g=bandgap)$$
					- Maximum ($$\pm 30\%$$)<- Trade off:
						- Lower bandgap
							- Higher absorbance (more photons with lower energy)
							- But extraction of electron-hole pairs happens at lower voltage
						- Higher bandgap
							- Mutatis mutandis
				- ![image.png](../assets/image_1681195853749_0.png)
					- Iterated experiment with AM1.5 solar spectrum (instead of black body radiator)
					- Si well positioned relative to maximum (but model as such not applicable because indirect bandgap material)
	- Overview of PV-technologies
		- ![image.png](../assets/image_1681196383643_0.png){:height 275, :width 542}
	- #### Crystalline Si solar cells
		- Sand to cell
			- Sand -> reduction -> metallurgical grade Si -> purification -> break and melt again -> wafers -> cells -> modules
		- Metallurgical grade silicon is obtained by a carbothermic reduction of silica in an arc furnace
		- MG-Si is reacted with HCl to form trichlorosilane in a fluidized bed rector by heating powdered MG-Si
		- Wacker process for poly-silicon production
		- PV crystalline silicon wafers are monocrystalline Si grown via Czochralski process or multicrystalline fabricated via a casting process
		- feedstock to Wafer with multiwire sawing
		- Screen printed cell
			- Texturing: make wafer even rougher
			  collapsed:: true
				- Chemical solution to remove mechanical damage but increase unevenness
				- Why? -> reduces reflection
			- Create pn junction
				- diffusion of fosphorus -> n side
					- Through POCl3 vapor diffusion
					- Gettering:
					  collapsed:: true
						- Intrinsic effect of P emitter formation
						- Diffusion of impurities to P rich layers
				- remove phosphorus-silicate glass (PSG) chemically
			- Put on Anti-Reflective Coating (ARC)
				- to reduce reflection even more
				- Si-N coating
					- Antireflection coating
					  collapsed:: true
						- Optimal refractive index: $$n_{ARC}=\sqrt{n_0 n_{Si}}=2$$
						- Optimal thickness: $$=\frac{\lambda_{highest\; flux}}{4n}$$
					- Bulk passivation
					  collapsed:: true
						- reduces recombination
					- Surface passivation
					  collapsed:: true
						- reduces recombination
						- Achieved because of Hydrogen
							- Positive fixed charge repels electrons from the surface and reduces the surface recombination velocity
			- Contacting: screen printing
				- Rear -> Al
				- Front -> Ag
				- Working
					- Screen with openings
					- Put paste (ink) on it
					- Squeegee pushes the paste through the openings, from the screen onto the wafer
				- CBA
					- Pro
						- Robustness
						- Flexibility
						- Environmentally benign
					- Contra
						- Smallest line width limited to 80 microns
						- Cost of Ag
		- Problems:
			- cost of Ag and wafer breakage
			- bowing for wafer thickness < 200 micron
	- ### Thin-film PV Technologies
		- Why look for Si alternative?
			- Much less material needed for same absorption fraction
			- However those materials not always readily available
		- ==Amorphous Si==
			- hydrogen needed to passivate dangling bonds (Covalent binding)
				- Improve electronic qualities
					- increased bandgap
					- Improves minority carrier lifetime $$\tau$$
			- But used for pin-junction
				- Carrier generation by $$L_{drift}$$ instead of $$L_p$$
			- CBA
				- Pro
					- High absorption coefficient
					- Thinner layers
					- Production at lower temperature (RF-PECVD, High-frequency PECVD, ETP, HW-CVD)
					- Compatible with cheaper substrates
						- Flexible solar cells
							- Glass
							- Steel foils
							- Polymers
					- Monolithic module production = production of cell & module at the same moment
				- Contra
					- Low $$\eta \;(\pm6\%)$$
						- Can be slightly increased by using multijunction (multi layers increase absorption)
		- ==CdTe==
			- Main properties
				- Basic properties:
					- Bandgap = 1.5 eV
					- Direct bandgap → high absorption coefficient
					- CdTe has a strong tendency to grow stoichiometric and behaves a p-type semiconductor (doping not really controllable)
					- CdTe solar cells based on a heterojunction with n-type CdS
				- Simple deposition techniques
					- Sublimation/condensation (heat sources to 600oC, deposition on glass substrates in the range 400-500oC)
					- High deposition rate in the order of 10 mm/min
					- Also spraying, electrodeposition and screenprinting can be used
					- Substrate: soda-lime glass
		- ==I-III-VI compounds==
			- Cover broad bandgap range
			- See CIGS
	- ### Multijunction cells
		- Stack cells with different bandgaps on top of each other
			- Still broad spectral absorption
			- reduce thermalisation losses (excess energy losses)
			- -> go above Schockley-Queisser limit
		- Latices should match (same lattice constant) to avoid defects
		- Requires tunnel junction with nanofeature to guarantee series connections of the cells
		- High concentration solar cells
			- Idea:
				- Replace solar cell by cheaper passive optical system like a lens or a mirror
					- optimise cell area
				- Concentration increases efficiency ($$V_{OC} \sim ln(I_{sc})$$)
				- Thus:
				  $$
				  \begin{equation*}
				  \begin{aligned}
				  J_{sc}&\rightarrow n\cdot J_{sc}\\
				  P_{in}&\rightarrow n\cdot P_{in}\\
				  V_{OC} &\sim ln(n)\Rightarrow FF \nearrow
				  \end{aligned}
				  \end{equation*}
				  $$
				- And:
				  $$
				  \begin{equation*}
				  \left.
				  \begin{aligned}
				  V_{OC}&\nearrow\\
				  FF&\nearrow
				  \end{aligned}
				  \right\}
				  
				  \end{equation*}
				  $$
- ### PV module technology
  collapsed:: true
	- Si-PV modules
	- Thin-film PV-modules
	  P V-systems
	- Different PV-systems
	- Maximum Power Point Tracking (MPPT)