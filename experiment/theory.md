Introduction
A slot line structure is a planar structure. It consists of a dielectric substrate, in which a slot is etched on the metallization of the substrate. The other surface is without any metallization. The series and parallel elements can be connected without much difficulty in this type of substrate. The structure is thus complementary to that of the microstrip. The slot-line configuration (shown in Fig. 1) is useful in circuits requiring high-impedance lines, series stubs, and short circuit and in hybrid combinations with microstrip circuit in MICs.
Approximate electric and magnetic field distribution in the structure are shown in fig. 2. It can be seen that the magnetic field has a component in the direction of propagation as well. Thus the mode of propagation is TE mode and not the TEM mode. The main features of slot line are as follows.
1.      The slot transmission line has a simple geometry that is compatible with microwave integrated circuits.
2.      In a slot line, both the conductors are in one plane, and therefore shunt mounting of the component (active or passive) across the line is very convenient.
3.     In the cross section of the line, at some region the magnetic field is circularly polarized. This feature can be used in the design of several ferrite components such as resonance isolators.
4.     Slot line configuration is useful in circuits requiring high impedance line, series stub, and short circuit and in hybrid combination with microwave circuits in MICs.
A slotline on a dielectric surface and electric and magnetic field distribution in the slot line are shown in following figure…..
 
 
Figure 1: (a) Slot line on a dielectric substrate (b) Slot line configuration
 
                                        
 
Figure.2  (a) E-field distribution in cross section. (b) H field in longitudinal section
 
Slot Wavelength:  The slot line field component is not confined to the substrate only but extended into the air region above the slot and also below the substrate. Thus the energy is distributed between the substrate and the air region. Therefore, the effective dielectric constant for the slot line is less than the substrate permittivity for an infinitely large thick substrate the average dielectric constant of the two media is:
  
          
 
 
 
 
 
where   is the cutoff value for the TE10 surface-wave mode on the slot line and is given by
 
 
 
1.     For  0.02  ≤ W/h ≤ 0.2
  
 
  
 
  
 
2.     For 0.2  ≤  W/h  ≤  1.0
 
  
 
  
 
 
 
Given Parameters:
Frequency f = 2.670 GHz
Substrate Thickness h = 3.4798 mm
Substrate Permittivity εr = 20
width of the device W = .635 mm
Calculate:
Guided Wavelength (length of microstrip line) λg = ?
Why the H-field makes slotline special
In a slotline the magnetic field forms ellipses in the plane of propagation — it has a longitudinal component, unlike TEM lines. This elliptically polarised H-field is exactly what non-reciprocal ferrite devices (isolators, circulators) need, which is one reason slotline was developed.
The high characteristic impedance range (60–200 Ω) also fills a gap: microstrip struggles to reach high Z₀ because the strip becomes impractically narrow, while a slot just gets wider.
Where slotlines are used
•	Microstrip-slotline transitions — the two lines on opposite faces of one substrate cross at right angles, coupling through the magnetic field. This gives compact baluns, mixers and phase inverters.
•	Tapered slot (Vivaldi) antennas — flare the slot exponentially and it radiates a wideband end-fire beam.
•	High-impedance circuit sections — filters and matching networks needing Z₀ above what microstrip can reach.
•	Ferrite devices — the elliptical H polarisation enables resonance isolators.
•	Hybrid microstrip-slot circuits — using both faces of the board doubles routing freedom; series stubs come free in slotline where microstrip only gives shunt stubs.
Procedure for Calculating Length of Slotline
To design the slotline, we have to calculate the guided wavelength which is equal to length of the slotline.
Procedure is given as following:
To calculate the the guided wavelength of the slotline (equal to length of slotline) first of all we have to calculate the value of wavelength   corresponding to given frequency at which we want to design slotline.
 
Where   = wavelength in free space
c = velocity of light in free space
Conditions are given as following
 
 
 
where    is the cutoff value for the TE10 surface-wave mode on the slotline and is given by
 
Calculate the ratio     for given case
Case 1:  For  0.02  ≤ W/h ≤ 0.2
 
Case 2: .     For 0.2  ≤  W/h  ≤  1.0
 
 
Example: Calculate the wavelength (length) of slotline at 2.67 GHz .
 
Given Parameters:
Frequency f = 2.67 GHz
Substrate Thickness h = 3.4798 mm
Width of slotline W = 0.635 mm
Substrate Permittivity εr = 20
Characteristic Impedance z0 = 50 Ω
Speed of light c =  
 Calculate the wavelength  
 
 
 
Now calculate the value of
 
 
 
Now width  W and substrate thickness h are already given so check the case 1
Case 1: For  0.02  ≤ W/h ≤ 0.2
W/h = 0.1824
It is clear from the above value that case 1 exist for the calculation of  
 
 
 
 
 
But we consider case 1 hence guided wavelength of slotline  is 33.72 mm. that means the length of slotline is 33.72 mm.
 
