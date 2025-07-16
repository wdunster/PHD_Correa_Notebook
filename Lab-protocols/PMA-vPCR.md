
# PMA Preservation for vPCR
For viability PCR (vPCR), divide 1 sample into 2 halves. Preserve 1 half in DNA/RNA shield in a bead tube. Follow the below protocol with the other sample halve. PMA is a high-affinity photoreactive DNA binding dye that allows us to differentiate live and dead cells using qPCR. PMA covalently bonds to dsDNA (double stranded) during photolysis leading to permanent DNA modification. PMA is also membrane impermeant, meaning it will only modify DNA of dead cells. PMA inhibits PCR amplification of the modified DNA allowing for comparison of a PMA-treated and PMA-untreated sample halves to determine the number of live and dead cells. qPCR measures the cycle threshold (Ct) or cycle at which DNA amplicons are first detected. Because PCR is exponential, lower Cts correspond with **more** target DNA being initially present in a sample. The relative proportion of viable target cells in a sample can be calculated by subtracting the Ct of the untreated sample halve from the PMA-treated sample halve. To compare across samples, a larger $\Delta$ Ct will correspond to a greater proportion of target cells being non-viable. 

*Protocol and infor adapted from [biotium](https://biotium.com/wp-content/uploads/2020/06/PI-40013-40019.pdf)*
### Considerations When Working With PMA:

**PMA is photoreactive...**
- Dim the lights in lab
- Cover working tubes with foil
- Store PMA in its opaque resealable bag at -20C

### Preparing: 
- If working with lyophilized PMA
    - Dim lab lights 
    - Obtain PMA from -20C
    - Pipette 98uL of sterile dH2O (distilled) into the 1mg vial of PMA
    - Pipette mix until dissolved 
    - Relabel vial "20mM stock solution PMA"

**Equipment List:**
- Aluminium foil 
- 2x 1.5mL microcentrifuge tubes 
- 2x bead tubes
- Microcentrifuge 

**Reagents:**
- 20 mM stock solution PMA
- DNA/RNA shield
- 2 microbial sample halves (i.e. 1 sample split into 2 fractions)

**Chemical Hazards**
- Non hazordous 
- "Do not dispose product directly into sewage. Consult local state or national regulation for proper disposal"
- PPE
    - Gloves

### Protocol: 
1. Dim lab lights 
2. Label 1x microcentrifuge tubes with sample label and "PMA"
3. Cover microcentrifuge tubes in alumium foil 
4. Determine amount of PMA to add to create a 50uM final concentration using 20mM (20,000uM) PMA stock solution. For this protocol we will use 1uL of PMA in 400uL of sample

$$
C_1V_1 = C_2V_2
$$

$$
V_1 = \frac{50\ \mu\text{M} \cdot SampleVol}{20{,}000\ \mu\text{M}}
$$

5. Pipette 400uL of sample into each microcentrifuge tube
6. Pipette 1uL of PMA into each microcentrifuge tube and pipette mix 3 times
7. Cover tubes, place tubes on tube rocker to mix, and incubate in the dark for 10 min 
8. Move tubes to PMA-Lite and incubate in blue light (465-475 nm wavelength) for 15 mins 
9. Remove tubes from the PMA-Lite 
10. Centrifuge tubes at 5,000g for 10min to pellet target cells
11. Pipette out and discard sample supernatant into hazardous waste container
12. Reconstitute pellet in 1mL of DNA/RNA shield. Pipette mix to breakup pellet and ensure it is fully disolved in DNA/RNA shield
13. Store tubes in 4C fridge
