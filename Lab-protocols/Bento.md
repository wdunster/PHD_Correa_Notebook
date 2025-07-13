# Bento Lab 

Use [Bento Lab](https://bento.bio) for easy field extraction, pCR, and Gel imaging 

This is a general protocol for operating the Bento Lab in the field. Feel free to look at the [manual](https://bento.bio/protocol/dna-barcoding/dna-barcoding-pcr-protocol/) or find the original protocols for [DNA extraction](https://bento.bio/protocol/dna-barcoding/dna-extraction-for-barcoding/) and [PCR](https://bento.bio/protocol/dna-barcoding/dna-barcoding-pcr-protocol/)

## Contents
- [**Preparing**](#prep)
- [**Protocol**](#protocol)

## <a name="prep"></a> **Preparing**

**Equipment List:**
- HotSHOT DNA Extraction Kit
- PCR tubes
- Microcentrifuge tubes 
- 2-200 uL pipette tips
- 20-200 uL pipette
- 2-20 uL pipette 
- Glass beaker
- Microwave
- Bento Lab

**REAGENTS:**
- HotSHOT DNA Extraction Kit
    - Alkaline Lysis Solution
    - Neutralising Buffer

## <a name="protocol"></a> **Protocol**
**DNA Extraction** ~ 20 mins
1. Pipette 75uL of Alkaline Lysis Solution (From the HotSHOT Extraction kit) into each PCR tube containing sample
2. Place sealed PCR tubes in thermocycler and use the heat block function to heat tubes at 95C for 20 mins
3. Let tubes cool
4. Pipette 75uL of HotSHOT Neutralising Buffer into each tube
5. Mix by inverting pcr tube several times
6. Because of PCR inhibitors in the DNA+neutralised buffer, prepare a 1 in 10 dilution of the DNA extraction in PCR grade water. Pipette 180 uL of PCR grade water into a new PCR tube. Label the tube '[sample name] 1/10.' Add 20uL of extracted DNA+buffer. Mix by inverting several times
7. Store at -20C if not using imediately for PCR 

**PCR** ~3 hrs

Master Mix Recipe
- 4x uL 5X FIREPol master mix
- 12 uL PCR grade water
- 2 uL primer mix
- 2 uL DNA template 

1. Calculate how much master mx to make using the equation:
$$
[NumExtractions] + [Negative Control] + 0.10
$$

    i.e. 9 DNA extractions + 1 negative control + 10% = 11 PCR repeats 

2.  Combine Firepol master mix, PCR grade water, and primer mix into a microcentrifuge tube labeled "Master Mix." Invert several times to mix 
3. Transfer 18uL of Master Mix to each of your labeled sample PCR tubes
4. Add 2 uL of DNA to each PCR tube. Close the lid and invert several times. 
5. Tap the PCR tube firmly on the benchtop to remove any bubbles and collect all liquid at the bottom of the tube. If necissary you can flick the tube to remove bubbles. 
6. Place the PCR tubes on the thermocycler block and set the the appropriate PCR program. 

**Thermocycler Settings** for SymVar ITS2 Primers

run 35 cycles before final extention
step | temp | time | 
-----|------|------|
Initial Denaturation | 98°C | 2 min
Denaturation | 98°C | 10 sec 
Annealing | 56°C | 30 sec 
Extension | 72°C | 30 sec
Final Extension | 72°C | 5 mins

**Bento Thermocycler Buttons**
![](https://github.com/wdunster/PHD_Correa_Notebook/_images/Bento-thermocycler.png)

**Gel Electrophoresis** 
1. Make a 1.5% gel (1 agarose tablet in 33mL of 0.5X TBE)
    - Add 1 agarose tablet to beaker
    - Fill the beaker with the agarose tab to the 50 mL mark with 0.5x TBE Buffer
    - Swirl until the tablet has dissolved. This may take a few minutes 
    - Heat the solution in a microwave at full power for short bursts removing the beaker with heat protectant gloves from the microwave and swirling every 20-30 sec
    - Stop heating when the solution starts to bubble or boil and all the agarose is visibly dissolved. 
    - Let the gel solution cool on the benchtop until the beaker is cool enough to touch
    - Add 3uL of DNA Safe Stain to the gel solution and swirl to mix 
2. Slide open the gel box. Ensure the black buffer damns are installed correctly and install 1 comb
3. Slowly pour the gel solution into the gel box until it reaches the 6-7mm mark
4. Allow the gel to solidify for 30 mins at room temperature 
5. Remove the comb and buffer damns 
6. Add 0.5x TBE buffer solution to the gel box until the gel is covered. The liquid shoudl reach 2-3mm above the gel 

5x FIREPol® Master Mix Ready To Load already contains loading dye, so PCR products can be directly loaded into the gel. If you are using 5x FIREPol® Master Mix Ready To Load procede to step 8. If using a different master mix procede to step 7. 

7. Pipette 5uL of loading dye into the PCR tube containing your sample and pipette mix 5 times. Repeat for all samples 
8. Pipette 5uL of 100bp Ladder into left most well. Be careful not to pucture the gel. Discard your pipette tip
9. Load 5uL of a sample into the second well from the left. Discard pipette tip and repeat for all samples, moving each time one well over to the right in the gel
10. Close the gel box lid and plug the gel box into the Bento Lab power supply. Make sure to match colors, with the red wire plugged into the red socket and black wire into the black socket
11. Run the gel for 40min at 50V
![](https://github.com/wdunster/PHD_Correa_Notebook/_images/Bento-gelbox.png)

**Visualize the Gel** 
1. Once the gel has finished running, disconnect the gel box from the Bento Lab
2. Open the orange lid of the gel box and wipe off any condensation
2. Pour out the buffer and dispose of down the drain
3. In a dark room, place the gel box into the Bento Lab transilluminator
4. Turn Bento Lab on, select Gel Electrophoresis module, and turn on the Transilluminator light
5. Hold the orange filter lid over the gel to visualize the DNA bands. Take a picture with your phone holding the orange lid directly over your camera lense instead of the gel
