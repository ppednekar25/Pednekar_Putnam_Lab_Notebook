---
layout: post
title: 2025-09-05 Sanger Sequencing Preps for Moorea E5 Project Acropora sp.
date:  2025-09-05
categories: E5 Acropora Sanger sequencing
tags: [E5, Acropora, Sanger Sequencing, PCR]
---

The samples processed today are of *Acropora* species. Total of 50 colonies of *Acropora* were collected as a part of E5 Moorea Project. Here, I am processing the gDNA samples extracted from these 50 colonies for Sanger sequencing to identify species within these genera. 

This post is also adapted based on the procedure from Arianna Huffmyer [Notebook Post](https://github.com/AHuffmyer/ASH_Putnam_Lab_Notebook/blob/master/_posts/2024-11-20-Sanger-sequencing-preps-at-URI.md?plain=). 

# Overview

gDNA extractions for 44 of the colonies were completed by Kristina Terpis in 2021 and 2022. Some of the gDNA extractions from six colonies were sent off to Azenta for sequencing. Hence, Hollie Putnam extracted gDNA for those colonies on 08/29/2025. 

My samples were included in different boxes which were extracted by Kristina. The gDNA samples I used for the colonies are below. The Master Molecular Sample List is [here](https://docs.google.com/spreadsheets/d/1A764av1a3VORX6m9aDUEcoY9Bx9l0fvGtV5ycm2J9Wo/edit?gid=0#gid=0) while the *Acropora* colony IDs for the master timeseries data is [here](https://github.com/urol-e5/timeseries/blob/master/time_series_analysis/Output/master_timeseries.csv).



# Protocols Used

- [Sanger Sequencing Preps](https://github.com/AHuffmyer/ASH_Putnam_Lab_Notebook/blob/master/_posts/2024-11-20-Sanger-sequencing-preps-at-URI.md)
- [Analysis of DNA Sequenced](https://ahuffmyer.github.io/ASH_Putnam_Lab_Notebook/Analysis-of-DNA-sequences-for-species-identification-in-the-Moorea-2023-project/)
- [Gel electrophoresis](https://emmastrand.github.io/EmmaStrand_Notebook/Gel-Electrophoresis-Protocol/) 
- [PCR product cleaning](https://github.com/AHuffmyer/moorea_symbiotic_exchange_2023/blob/main/data/dna/pcr/protocol_zr-96_dna_clean-up_kit.pdf) 
- [Sanger sequencing at URI](https://web.uri.edu/riinbre/mic/)
- [Pocillopora spp gDNA Extraction Protocol](https://github.com/PierrickHarnay/PierrickHarnay_Notebook/blob/master/_posts/2024-09-26-PocID-Relative-abundance-gDNA-extraction.md)
- [Pocillopora mtORF-PocHistone after PCR before cleaning](https://github.com/PierrickHarnay/PierrickHarnay_Notebook/blob/master/_posts/2024-10-09-PocID-Relative-abundance-gel-after-PCR-before-cleaning.md)


# Acropora 

## Sample Information

Add sheet of all the samples you selected and their timepoints. 

## Primer selection 

Hollie and Arianna have previously talked about the primers to use for *Acropora* species identification. Hollie previously tested some of the primers from the literature. 
Arianna have used both the PaxC (PaxC_intron_FP1 forward and PaxC_intron_RP1 reverse) and CRf/CO3r (CRF forward and CO3r reverse) which were avaliable in the lab previously while prepping *Acropora* samples in 2024. 

This time, Hollie recommended to use the [CRf/CO3r](https://github.com/AHuffmyer/moorea_symbiotic_exchange_2023/blob/main/data/dna/pcr/acr-primers/primer1-.jpeg) (CRf forward and CO3r reverse) primer. 
|

### Crf/CO3r sequencing 

#### 2025-09-05

- Mitochondrial putative control (933+ bp) + 83 bp of cytochrome oxidase III as in [Vollmer et al. 2002](https://www.science.org/doi/full/10.1126/science.1069524)


The primers were hydrated but were present in their original concentration which was 100μM each. Hence, I diluted the primers as required for the Master mix to 10μM in two tubes.


|Component|  Volume of Primer (μL) | Volume of Nuclease Free Water (μL) | Final Concentration of the product (μM)|
|----------|------------|-------------|-----------|
| CRf Primer 100μM |10μL|90μL|10μM|
|CO3r Primer 100μM| 10μL|90μL|10μM|

The diluted primers are stored in the tubes in the same "Putnam Lab Stick Primer Transparent Box on Shelf  -20 C Freezer F" along with the concentrated primers.

I prepared the master mix using One*Taq* Quick-Load 2X Master Mix from New England Biolabs. I made the master mix for 60 rxns as I was doing PCR for the first time. 

|Component| rxns|60 rxns|
|---------|---------|----------|
|One*Taq* Quick-Load 2X master mix | 12.5 μL | 750 μL | 
|10 μM CRf Primer| 0.5 μL|30 μL|
|10 μM CO3r Primer| 0.5 μL|30 μL|
|Nuclease Free Water|10.5 μL|630 μL|
|DNA Template| 1μL | |
|| 25 μL rxns |24 μL rxns|

I prepared one single PCR plate containing 52 samples; 50 of which were gDNA extracted from 50 *Acropora* colonies by Kristina in 2021-2022 and Hollie in 2025. 

I used a Danielle Becker Heatwave *Acropora pulchra* as a postive control (no. 24 gDNA from 10/29/23). Water was used as a negative control in the plate.

The PCR plate maps for this PCR shows the tube number followed by colony ID of the sample collected. 

The PCR Map for this day is below

![PCR MAP](https://github.com/ppednekar25/Pednekar_Putnam_Lab_Notebook/blob/master/images/PCR_Map.png?raw=TRUE).

As the gDNA samples were present in the tubes and not plated on gDNA plates like before, I directly plated the samples onto the 96 well plates for PCR. 

The PCR protocol ("Acro" on Putnam Account) was used similar to previous *Acropora* PCRs by Arianna. 

The settings for the thermocycler is follows:
- 95°C for 3 min [ cycle]
- 94°C for 30 sec, 53°C for 30 sec, 72°C for  min [35 cycles] 
*Note: Melting temperature chosen based on lowest primer melting temperature* 
- 72°C for 5 min 
- Hold at 4°C 


After PCR, samples were stored in the 4 C fridge. 

I than ran two gels i.e. One Small and One Medium for the CRf/CO3r primer set using 2% gel at 80V for 90 min. I used only one DNA ladder of  KB for the same. 

  *For 2% Gel*

| Gel Format| 1X TAE BUffer (mL) | Agarose (in g)|
|---------|------------|------------|
| Small Box| 75 mL | .5 g|
|Medium Box| 100 mL| 2.0 g|
|Large Box| 150 mL|3.0 g|


Sample loaded in each gel is 4μL. 

Only one DNA ladder 1KB was used for these gels as previously 100 bp ladder was also used by Arianna. The 100 bp ladder was not avaliable and as the targeted band size expected was closer to a 1000 bp, I went forward to just use the 1KB DNA Ladder.


![ACR CRf/CO3r Gel ](https://github.com/ppednekar25/Pednekar_Putnam_Lab_Notebook/blob/094911b938e4a365df157e68618b0a94866c48cf/images/E5_gDNA_Acropora_POST_PCR_gel_1_09_05_2025.jpg?raw=TRUE)
![ACR CRf/CO3r Gel 2](https://github.com/ppednekar25/Pednekar_Putnam_Lab_Notebook/blob/094911b938e4a365df157e68618b0a94866c48cf/images/E5_gDNA_Acropora_POST_PCR_gel_2_09_05_2025.jpg?raw=TRUE)

#### Results from the Gel

   . Out of the 50 Colonies for *Acropora*, two colonies which are **ACR-140** and 
   **ACR-180** did not show any bands signifying that the PCR amplification did not work for those two.
   2. The gel products look nice however have a weird shape for all the bands. After consulting with Hollie, I realized that there could be too much product hence later for the next PCRs I loaded on 3μL of sample for running the gel on her recommendation.
   3. There were **no** bands in the negative controls and band in the positive control for *A. pulchra*. All other samples look good.
   4. As the two samples from the colonies failed I would be redoing the PCR again with dilutions as well as the original concentration using the same tube numbers from timepoint .


#### 2025-09-10

For today, I redid PCR for two colonies that did not show any band for the gel ran on 2025-09-05. The two colony_ids with no band were ACR-140 and ACR-180.

I also made a new master mix today. 

|Component| rxns|16 rxns|
|---------|---------|----------|
|One*Taq* Quick-Load 2X master mix | 12.5 μL | 200 μL | 
|10 μM CRf Primer| 0.5 μL|8.0 μL|
|10 μM CO3r Primer| 0.5 μL|8.0 μL|
|Nuclease Free Water|10.5 μL|168 μL|
|DNA Template| 1μL | |
|| 25 μL rxns |24 μL rxns|

I am re-running the PCR using an 8-strip tube. For each colony, I’ve prepared three reactions corresponding to:

. The original sample (same concentration as before)
2. A :10 dilution
|Sample ID| Volume of Sample| Volume of Water|
|----------|------------|-----------|
| T-207 ACR-140| 10 μL | 90 μL|
| T-197 ACR-180| 10 μL| 90 μL|
3. A :100 dilution
|Sample ID| Volume of Sample| Volume of Water|
|----------|------------|-----------|
| T-207 ACR-140| .0 μL | 99.0 μL|
| T-197 ACR-180| .0 μL| 99.0 μL|

In total, I’m including three samples per colony. I used a Danielle Becker Heatwave *Acropora pulchra* as a postive control (no. 24 gDNA from 10/29/23). Water was used as a negative control in the plate.

The PCR Map for this day is below

![PCR MAP](https://github.com/ppednekar25/Pednekar_Putnam_Lab_Notebook/blob/49135e754116f2b4b12257e3f1017c786244d877/images/PCR_Map_Day_2.png?raw=TRUE).

Samples were stored in the fridge for the next steps.

The same setting was run for the PCR again and I ran only one 2% gel at 80 V for 90 min for 8 samples. 

This time I only loaded 3μL of sample and used the same DNA ladder 1KB.

![ACR CRf/CO3r Gel  09-10-2025](https://github.com/ppednekar25/Pednekar_Putnam_Lab_Notebook/blob/49135e754116f2b4b12257e3f1017c786244d877/images/E5_gDNA_Acropora_POST_PCR_failed_gel_1_09_10_2025.JPG?raw=TRUE)


#### Results from the Gel

   . Out of the two colonies for *Acropora*, **ACR-140** did not show any bands even with dilutions.
   2. The gel products look nice for colony_id ACR-180 and the bands looks more linear now. 
   3. There were **no** bands in the negative controls and band in the positive control for *A. pulchra*. 
   4. **As the one samples from the ACR-140 colony failed I would be redoing the PCR again with other samples from different timepoints.**



#### 2025-09-11

Today's goal was to redo the ACR-140 colony_id's remaining timepoints to check if the DNA is amplified for further process. There were total three more timepoints (TP2, TP3 and TP4) however I could only find tubes for TP2 and TP3 hence moved forward with only processing those two. 

   **Sample Information**

   | Tube Number | Colony_ID | Timepoint |
   |-------------|----------|----------|
   | 467 | ACR-140 |TP2|
   |675| ACR-140|TP3|


The Master mix for today goes as follows:
|Component| rxns|8 rxns|
|---------|---------|----------|
|One*Taq* Quick-Load 2X master mix | 12.5 μL | 100 μL | 
|10 μM CRf Primer| 0.5 μL|4.0 μL|
|10 μM CO3r Primer| 0.5 μL|4.0 μL|
|Nuclease Free Water|10.5 μL|84 μL|
|DNA Template| 1μL | |
|| 25 μL rxns |24 μL rxns|


In total, I’m including two samples for each timepoint ACR-140 colony. I used a Danielle Becker Heatwave *Acropora pulchra* as a postive control (no. 24 gDNA from 10/29/23). Water was used as a negative control in the plate.

The PCR Map for this day is below

![PCR MAP](https://github.com/ppednekar25/Pednekar_Putnam_Lab_Notebook/blob/49135e754116f2b4b12257e3f1017c786244d877/images/PCR_Map_Day_3.png?raw=TRUE).

The same setting was run for the PCR again and I ran only one 2% gel at 80 V for 90 min for 4 samples. 

This time sample loaded was 3.0 μL and used the same DNA ladder 1KB.

Samples were stored in the fridge for the next steps after loading.

![ACR CRf/CO3r Gel  09-11-2025](https://github.com/ppednekar25/Pednekar_Putnam_Lab_Notebook/blob/49135e754116f2b4b12257e3f1017c786244d877/images/E5_gDNA_Acropora_POST_PCR_failed_gel_1_09_11_2025.JPG?raw=TRUE)

#### Results from the Gel

   . The gel products look nice for colony_id ACR-140 and the bands looks more linear now.  
   2. There were **no** bands in the negative controls and band in the positive control for *A. pulchra*. 

**As by the end of DAY 3, the PCR worked for all the 50 colonies of *Acropora*.**
  
For all the 50 colonies from a single timepoint of the *Acropora sp* worked, we can now proceed with cleaning and preparation for sequencing for all the single timepoint for all the 50 *Acropora* colonies. 

I then perfomed a clean up using the [Zymo DNA Clean & Concentrator-5 50 Preps Kit](https://github.com/ppednekar25/Pednekar_Putnam_Lab_Notebook/blob/0242329d8049ee7ea11709ccadd92719ac509b9a/images/Zymo_DNA_Concentrator_e5_acropora.jpg?raw=TRUE) in single tube format. 

**NOTE: During this cleaning process, I removed the failed samples from the first round of PCR and replaced with the successful PCR product for those samples. For ACR-140, I used the Tube# 467 from Timepoint 2 and that for ACR-180, I chose Tube # 197 with successful PCR product.**

As the kit was not opened previously, I added 24 mL 100% Ethanol to the 6mL DNA Wash Buffer concentrate. I also diluted the forward and reverse primer to 3.2µM. 

 For 50 colonies, I made enough diluted primer that I can use it for the sequencing plate.
 Final Volume= 200 μL

|Component|Volume of Water μL | Volume of Primer μL  | Final Concentration μM|
|---------|---------|----------|--------|
|100 μM CRf Primer| 193.6 μL|6.4 μL|3.2 μM|
|100 μM CO3r Primer| 193.6 μL|6.4 μL|3.2 μM|

### The steps for the cleanup goes as follows: 

 . Spin the PCR Product plate in the centrifuge or the rotator.
 2. Take .5 mL of microcentrifuge tubes and add DNA Binding Buffer in 5: ratio to the PCR product.
 
     *Note: As some of my samples were not exactly 20 μL in volume I had to do adjustments. I added the DNA buffer in 5: ratio as per below calculations.*

    |Volume of DNA Binding Buffer in μL |PCR Product Volume in μL|
    |----------|-----|
    |35 uL | 7 μL|
    |75 μL | 15 μL|
    |85 μL| 17 μL|
    |100 μL|20 μL|
 3. Vortex the mixture or mix it with the pipette so that it is completely mixed.
 4. Transfer the mixture to a provided Zymo-Spin COlumn in a collection tube.
 5. Centrifuge for  min at 13,000 rcf. Discard the flow-through in a beaker for now.
 6. Add 200 μL of DNA Wash Buffer to the column. Centrifuge for  min at 13,000 rcf. **REPEAT THIS STEP AGAIN** 

    *All of the discarded flow through is collected in a ZR-96 DNA Cleaning waste bottle placed in the waste area next to the molecular hood. Even though the waste collection bottle was made for ZR-96 kit, the buffers that are used in the kit I am using also contains the same buffers and chemicals, hence I emptied the flow-through in the same ZR-96 cleanup waste bottle.*

7. Carefully transfer the spin-column to the final microcentrifuge tubes that can hold your Ultra-pure DNA after the elution step.
8. Lastly, add 40 μL of Elution Buffer directly to the column matrix and incubate at room temperature. Centrifuge for  minute at 13,000 rcf and elute the DNA.
The Ultra-pure DNA is now ready to use. 

I then plated the Ultra-pure DNA in a 96-well plate with the below Plate map.


### Quantification of DNA through Qubit

To make sure that the eluted DNA is of desired concentration, we randomly selected 10 colonies to test their concentration.

Stock solution:

dsDNA Broad Range = 13 X 199 μL= 2587 μL

dsDNA BR reagent= 13 x  μL= 13 μL

DNA Standards: 

S1= 170.76 μg/mL          
S2= 20572.80 μg/mL

|Qubit Tube|Colony|Well|Reading |Reading 2|
|---|---------|-----|-------|---------|
||A5|ACR-190|2.96|2.92|
|2|A12|ACR-180|10.3|10.3|
|3|B2|ACR-145|5.62|5.66|
|4|B7|ACR-390|6.54|6.54|
|5|C4|ACR-360|5.18|5.16|
|6|C10|ACR-244|7.07|7.00|
|7|D3|ACR-374|7.39|7.42|
|8|D8|ACR-231|7.06|7.02|
|9|E1|ACR-389|8.26|8.24|
|10|A8|ACR-368|3.76|3.64|


### Sequencing plate post cleanup

We then sequenced both the forward and reverse for the CRf/CO3r primer set.

Sample information is as follows:

 #### CRf forward

Plate 1/2

|Sample ID| Sample Name|Plate Well| Template Type| PCR Template Volume (µl)| H2O Volume (µl)|Primer Volume (µl)|Primer Name|
 |----|-------------|----|---|-----|-----|-----|-----|
 |PP0001|ACR-165|A1|PCR|2|8|2|CRf|
 |PP0002|ACR-193|B1|PCR|2|8|2|CRf|
 |PP0003|ACR-265|C1|PCR|2|8|2|CRf|
 |PP0004|ACR-364|D1|PCR|2|8|2|CRf|
 |PP0005|ACR-389|E1|PCR|2|8|2|CRf|
 |NA|Empty|F1|empty|empty|empty|empty|CRf|
 |NA|Empty|G1|empty|empty|empty|empty|CRf|
 |NA|Empty|H1|empty|empty|empty|empty|CRf|
 |PP0006|ACR-175|A2|PCR|2|8|2|CRf|
 |PP0007|ACR-145|B2|PCR|2|8|2|CRf|
 |PP0008|ACR-256|C2|PCR|2|8|2|CRf|
 |PP0009|ACR-241|D2|PCR|2|8|2|CRf|
 |PP0010|ACR-139|E2|PCR|2|8|2|CRf|
 |NA|Empty|F2|empty|empty|empty|empty|CRf|
 |NA|Empty|G2|empty|empty|empty|empty|CRf|
 |NA|Empty|H2|empty|empty|empty|empty|CRf|
 |PP0011|ACR-186|A3|PCR|2|8|2|CRf|
 |PP0012|ACR-218|B3|PCR|2|8|2|CRf|
 |PP0013|ACR-258|C3|PCR|2|8|2|CRf|
 |PP0014|ACR-374|D3|PCR|2|8|2|CRf|
 |NA|Empty|E3|empty|empty|empty|empty|CRf|
 |NA|Empty|F3|empty|empty|empty|empty|CRf|
 |NA|Empty|G3|empty|empty|empty|empty|CRf|
 |NA|Empty|H3|empty|empty|empty|empty|CRf|
 |PP0015|ACR-187|A4|PCR|2|8|2|CRf|
 |PP0016|ACR-345|B4|PCR|2|8|2|CRf|
 |PP0017|ACR-360|C4|PCR|2|8|2|CRf|
 |PP0018|ACR-393|D4|PCR|2|8|2|CRf|
 |NA|Empty|E4|empty|empty|empty|empty|CRf|
 |NA|Empty|F4|empty|empty|empty|empty|CRf|
 |NA|Empty|G4|empty|empty|empty|empty|CRf|
 |NA|Empty|H4|empty|empty|empty|empty|CRf|
 |PP0019|ACR-190|A5|PCR|2|8|2|CRf|
 |PP0020|ACR-350|B5|PCR|2|8|2|CRf|
 |PP0021|ACR-363|C5|PCR|2|8|2|CRf|
 |PP0022|ACR-237|D5|PCR|2|8|2|CRf|
 |NA|Empty|E5|empty|empty|empty|empty|CRf|
 |NA|Empty|F5|empty|empty|empty|empty|CRf|
 |NA|Empty|G5|empty|empty|empty|empty|CRf|
 |NA|Empty|H5|empty|empty|empty|empty|CRf|
 |PP0023|ACR-351|A6|PCR|2|8|2|CRf|
 |PP0024|ACR-379|B6|PCR|2|8|2|CRf|
 |PP0025|ACR-246|C6|PCR|2|8|2|CRf|
 |PP0026|ACR-176|D6|PCR|2|8|2|CRf|
 |NA|Empty|E6|empty|empty|empty|empty|CRf|
 |NA|Empty|F6|empty|empty|empty|empty|CRf|
 |NA|Empty|G6|empty|empty|empty|empty|CRf|
 |NA|Empty|H6|empty|empty|empty|empty|CRf|
 |PP0027|ACR-347|A7|PCR|2|8|2|CRf|
 |PP0028|ACR-390|B7|PCR|2|8|2|CRf|
 |PP0029|ACR-228|C7|PCR|2|8|2|CRf|
 |PP0030|ACR-225|D7|PCR|2|8|2|CRf|
 |NA|Empty|E7|empty|empty|empty|empty|CRf|
 |NA|Empty|F7|empty|empty|empty|empty|CRf|
 |NA|Empty|G7|empty|empty|empty|empty|CRf|
 |NA|Empty|H7|empty|empty|empty|empty|CRf|
 |PP0031|ACR-368|A8|PCR|2|8|2|CRf|
 |PP0032|ACR-396|B8|PCR|2|8|2|CRf|
 |PP0033|ACR-243|C8|PCR|2|8|2|CRf|
 |PP0034|ACR-231|D8|PCR|2|8|2|CRf|
 |NA|Empty|E8|empty|empty|empty|empty|CRf|
 |NA|Empty|F8|empty|empty|empty|empty|CRf|
 |NA|Empty|G8|empty|empty|empty|empty|CRf|
 |NA|Empty|H8|empty|empty|empty|empty|CRf|
 |PP0035|ACR-140|A9|PCR|2|8|2|CRf|
 |PP0036|ACR-178|B9|PCR|2|8|2|CRf|
 |PP0037|ACR-343|C9|PCR|2|8|2|CRf|
 |PP0038|ACR-229|D9|PCR|2|8|2|CRf|
 |NA|Empty|E9|empty|empty|empty|empty|CRf|
 |NA|Empty|F9|empty|empty|empty|empty|CRf|
 |NA|Empty|G9|empty|empty|empty|empty|CRf|
 |NA|Empty|H9|empty|empty|empty|empty|CRf|
 |PP0039|ACR-150|A10|PCR|2|8|2|CRf|
 |PP0040|ACR-185|B10|PCR|2|8|2|CRf|
 |PP0041|ACR-244|C10|PCR|2|8|2|CRf|
 |PP0042|ACR-220|D10|PCR|2|8|2|CRf|
 |NA|Empty|E10|empty|empty|empty|empty|CRf|
 |NA|Empty|F10|empty|empty|empty|empty|CRf|
 |NA|Empty|G10|empty|empty|empty|empty|CRf|
 |NA|Epty|H10|empty|empty|empty|empty|CRf|
 |PP0043|ACR-173|A11|PCR|2|8|2|CRf|
 |PP0044|ACR-210|B11|PCR|2|8|2|CRf|
 |PP0045|ACR-213|C11|PCR|2|8|2|CRf|
 |PP0046|ACR-231|D11|PCR|2|8|2|CRf|
 |NA|Empty|E11|empty|empty|empty|empty|CRf|
 |NA|Empty|F11|empty|empty|empty|empty|CRf|
 |NA|Empty|G11|empty|empty|empty|empty|CRf|
 |NA|Empty|H11|empty|empty|empty|empty|CRf|
 |PP0047|ACR-180|A12|PCR|2|8|2|CRf|
 |PP0048|ACR-51|B12|PCR|2|8|2|CRf|
 |PP0049|ACR-234|C12|PCR|2|8|2|CRf|
 |PP0050|ACR-267|D12|PCR|2|8|2|CRf|
 |NA|Empty|E12|empty|empty|empty|empty|CRf|
 |NA|Empty|F12|empty|empty|empty|empty|CRf|
 |NA|Empty|G12|empty|empty|empty|empty|CRf|
 |NA|Empty|H12|empty|empty|empty|empty|CRf|

 #### CO3r reverse

Plate 2/2 

 |Sample ID| Sample Name|Plate Well| Template Type| PCR Template Volume (µl)| H2O Volume (µl)|Primer Volume (µl)|Primer Name|
 |----|-------------|----|---|-----|-----|-----|-----|
 |PP0051|ACR-165|A1|PCR|2|8|2|C03r|
 |PP0052|ACR-193|B1|PCR|2|8|2|C03r|
 |PP0053|ACR-265|C1|PCR|2|8|2|C03r|
 |PP0054|ACR-364|D1|PCR|2|8|2|C03r|
 |PP0055|ACR-389|E1|PCR|2|8|2|C03r|
 |NA|Empty|F1|empty|empty|empty|empty|C03r|
 |NA|Empty|G1|empty|empty|empty|empty|C03r|
 |NA|Empty|H1|empty|empty|empty|empty|C03r|
 |PP0056|ACR-175|A2|PCR|2|8|2|C03r|
 |PP0057|ACR-145|B2|PCR|2|8|2|C03r|
 |PP0058|ACR-256|C2|PCR|2|8|2|C03r|
 |PP0059|ACR-241|D2|PCR|2|8|2|C03r|
 |PP0060|ACR-139|E2|PCR|2|8|2|C03r|
 |NA|Empty|F2|empty|empty|empty|empty|C03r|
 |NA|Empty|G2|empty|empty|empty|empty|C03r|
 |NA|Empty|H2|empty|empty|empty|empty|C03r|
 |PP0061|ACR-186|A3|PCR|2|8|2|C03r|
 |PP0062|ACR-218|B3|PCR|2|8|2|C03r|
 |PP0063|ACR-258|C3|PCR|2|8|2|C03r|
 |PP0064|ACR-374|D3|PCR|2|8|2|C03r|
 |NA|Empty|E3|empty|empty|empty|empty|C03r|
 |NA|Empty|F3|empty|empty|empty|empty|C03r|
 |NA|Empty|G3|empty|empty|empty|empty|C03r|
 |NA|Empty|H3|empty|empty|empty|empty|C03r|
 |PP0065|ACR-187|A4|PCR|2|8|2|C03r|
 |PP0066|ACR-345|B4|PCR|2|8|2|C03r|
 |PP0067|ACR-360|C4|PCR|2|8|2|C03r|
 |PP0068|ACR-393|D4|PCR|2|8|2|C03r|
 |NA|Empty|E4|empty|empty|empty|empty|C03r|
 |NA|Empty|F4|empty|empty|empty|empty|C03r|
 |NA|Empty|G4|empty|empty|empty|empty|C03r|
 |NA|Empty|H4|empty|empty|empty|empty|C03r|
 |PP0069|ACR-190|A5|PCR|2|8|2|C03r|
 |PP0070|ACR-350|B5|PCR|2|8|2|C03r|
 |PP0071|ACR-363|C5|PCR|2|8|2|C03r|
 |PP0072|ACR-237|D5|PCR|2|8|2|C03r|
 |NA|Empty|E5|empty|empty|empty|empty|C03r|
 |NA|Empty|F5|empty|empty|empty|empty|C03r|
 |NA|Empty|G5|empty|empty|empty|empty|C03r|
 |NA|Empty|H5|empty|empty|empty|empty|C03r|
 |PP0073|ACR-351|A6|PCR|2|8|2|C03r|
 |PP0074|ACR-379|B6|PCR|2|8|2|C03r|
 |PP0075|ACR-246|C6|PCR|2|8|2|C03r|
 |PP0076|ACR-176|D6|PCR|2|8|2|C03r|
 |NA|Empty|E6|empty|empty|empty|empty|C03r|
 |NA|Empty|F6|empty|empty|empty|empty|C03r|
 |NA|Empty|G6|empty|empty|empty|empty|C03r|
 |NA|Empty|H6|empty|empty|empty|empty|C03r|
 |PP0077|ACR-347|A7|PCR|2|8|2|C03r|
 |PP0078|ACR-390|B7|PCR|2|8|2|C03r|
 |PP0079|ACR-228|C7|PCR|2|8|2|C03r|
 |PP0080|ACR-225|D7|PCR|2|8|2|C03r|
 |NA|Empty|E7|empty|empty|empty|empty|C03r|
 |NA|Empty|F7|empty|empty|empty|empty|C03r|
 |NA|Empty|G7|empty|empty|empty|empty|C03r|
 |NA|Empty|H7|empty|empty|empty|empty|C03r|
 |PP0081|ACR-368|A8|PCR|2|8|2|C03r|
 |PP0082|ACR-396|B8|PCR|2|8|2|C03r|
 |PP0083|ACR-243|C8|PCR|2|8|2|C03r|
 |PP0084|ACR-231|D8|PCR|2|8|2|C03r|
 |NA|Empty|E8|empty|empty|empty|empty|C03r|
 |NA|Empty|F8|empty|empty|empty|empty|C03r|
 |NA|Empty|G8|empty|empty|empty|empty|C03r|
 |NA|Empty|H8|empty|empty|empty|empty|C03r|
 |PP0085|ACR-140|A9|PCR|2|8|2|C03r|
 |PP0086|ACR-178|B9|PCR|2|8|2|C03r|
 |PP0087|ACR-343|C9|PCR|2|8|2|C03r|
 |PP0088|ACR-229|D9|PCR|2|8|2|C03r|
 |NA|Empty|E9|empty|empty|empty|empty|C03r|
 |NA|Empty|F9|empty|empty|empty|empty|C03r|
 |NA|Empty|G9|empty|empty|empty|empty|C03r|
 |NA|Empty|H9|empty|empty|empty|empty|C03r|
 |PP0089|ACR-150|A10|PCR|2|8|2|C03r|
 |PP0090|ACR-185|B10|PCR|2|8|2|C03r|
 |PP0091|ACR-244|C10|PCR|2|8|2|C03r|
 |PP0092|ACR-220|D10|PCR|2|8|2|C03r|
 |NA|Empty|E10|empty|empty|empty|empty|C03r|
 |NA|Empty|F10|empty|empty|empty|empty|C03r|
 |NA|Empty|G10|empty|empty|empty|empty|C03r|
 |NA|Empty|H10|empty|empty|empty|empty|C03r|
 |PP0093|ACR-173|A11|PCR|2|8|2|C03r|
 |PP0094|ACR-210|B11|PCR|2|8|2|C03r|
 |PP0095|ACR-213|C11|PCR|2|8|2|C03r|
 |PP0096|ACR-231|D11|PCR|2|8|2|C03r|
 |NA|Empty|E11|empty|empty|empty|empty|C03r|
 |NA|Empty|F11|empty|empty|empty|empty|C03r|
 |NA|Empty|G11|empty|empty|empty|empty|C03r|
 |NA|Empty|H11|empty|empty|empty|empty|C03r|
 |PP0097|ACR-180|A12|PCR|2|8|2|C03r|
 |PP0098|ACR-51|B12|PCR|2|8|2|C03r|
 |PP0099|ACR-234|C12|PCR|2|8|2|C03r|
 |PP00100|ACR-267|D12|PCR|2|8|2|C03r|
 |NA|Empty|E12|empty|empty|empty|empty|C03r|
 |NA|Empty|F12|empty|empty|empty|empty|C03r|
 |NA|Empty|G12|empty|empty|empty|empty|C03r|
 |NA|Empty|H12|empty|empty|empty|empty|C03r|
 
 
#### 20250915
The sequencing plates were sent off for sequencing to Janet Atoyan at the RI Genomics & Sequencing Center in the loading dock freezer of the pharmacy building. 


### Next Steps

We will analyze sequences to determine species ID and then decide how to proceed further. 












   

















