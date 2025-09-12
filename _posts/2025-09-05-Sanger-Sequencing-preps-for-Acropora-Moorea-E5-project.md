---
layout: post
title: 2025-09-05 Sanger Sequencing Preps for Moorea E5 Project Acropora sp.
date:  2025-09-05
categories: E5 Acropora Sanger sequencing
tags: [E5, Acropora, Sanger Sequencing, PCR]
---

The samples processed today are of *Acropora* species. Total of 50 colonies of *Acropora* were collected as a part of E5 Moorea Project. Here, I am processing the gDNA samples extracted from these 50 colonies for Sanger sequencing to identify species within these genera. 

This post is also adapted based on the procedure from Arianna Huffmyer [Notebook Post](https://github.com/AHuffmyer/ASH_Putnam_Lab_Notebook/blob/master/_posts/2024-11-20-Sanger-sequencing-preps-at-URI.md?plain=1). 

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

## Primer selection 

Hollie and Arianna have previously talked about the primers to use for *Acropora* species identification. Hollie previously tested some of the primers from the literature. 
Arianna have used both the PaxC (PaxC_intron_FP1 forward and PaxC_intron_RP1 reverse) and CRf/CO3r (CRF forward and CO3r reverse) which were avaliable in the lab previously while prepping *Acropora* samples in 2024. 

This time, Hollie recommended to use the [CRf/CO3r](https://github.com/AHuffmyer/moorea_symbiotic_exchange_2023/blob/main/data/dna/pcr/acr-primers/primer1-1.jpeg) (CRf forward and CO3r reverse) primer. 
|

### Crf/CO3r sequencing 

#### 2025-09-05

- Mitochondrial putative control (933+ bp) + 83 bp of cytochrome oxidase III as in [Vollmer et al. 2002](https://www.science.org/doi/full/10.1126/science.1069524)


The primers were hydrated but were present in their original concentration which was 100μM each. Hence, I diluted the primers as required for the Master mix to 10μM in two tubes.


|Component|  Volume of Primer (μL) | Volume of Nuclease Free Water (μL) | Final Concentration of the product (μM)|
|----------|------------|-------------|-----------|
| CRf Primer 100μM |10μL|90μL|10μM|
|CO3r Primer 100μM| 10μL|90μL|10μM|

The diluted primers are stored in the tubes in the same "Putnam Lab Stick Primer Transparent Box on Shelf 1 -20 C Freezer F" along with the concentrated primers.

I prepared the master mix using One*Taq* Quick-Load 2X Master Mix from New England Biolabs. I made the master mix for 60 rxns as I was doing PCR for the first time. 

|Component|1 rxns|60 rxns|
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
- 95°C for 3 min [1 cycle]
- 94°C for 30 sec, 53°C for 30 sec, 72°C for 1 min [35 cycles] 
*Note: Melting temperature chosen based on lowest primer melting temperature* 
- 72°C for 5 min 
- Hold at 4°C 


After PCR, samples were stored in the 4 C fridge. 

I than ran two gels i.e. One Small and One Medium for the CRf/CO3r primer set using 2% gel at 80V for 90 min. I used only one DNA ladder of 1 KB for the same. 

  *For 2% Gel*

| Gel Format| 1X TAE BUffer (mL) | Agarose (in g)|
|---------|------------|------------|
| Small Box| 75 mL | 1.5 g|
|Medium Box| 100 mL| 2.0 g|
|Large Box| 150 mL|3.0 g|


Sample loaded in each gel is 4μL. 

Only one DNA ladder 1KB was used for these gels as previously 100 bp ladder was also used by Arianna. The 100 bp ladder was not avaliable and as the targeted band size expected was closer to a 1000 bp, I went forward to just use the 1KB DNA Ladder.


![ACR CRf/CO3r Gel 1](https://github.com/ppednekar25/Pednekar_Putnam_Lab_Notebook/blob/094911b938e4a365df157e68618b0a94866c48cf/images/E5_gDNA_Acropora_POST_PCR_gel_1_09_05_2025.jpg?raw=TRUE)
![ACR CRf/CO3r Gel 2](https://github.com/ppednekar25/Pednekar_Putnam_Lab_Notebook/blob/094911b938e4a365df157e68618b0a94866c48cf/images/E5_gDNA_Acropora_POST_PCR_gel_2_09_05_2025.jpg?raw=TRUE)

#### Results from the Gel

   1. Out of the 50 Colonies for *Acropora*, two colonies which are **ACR-140** and 
   **ACR-180** did not show any bands signifying that the PCR amplification did not work for those two.
   2. The gel products look nice however have a weird shape for all the bands. After consulting with Hollie, I realized that there could be too much product hence later for the next PCRs I loaded on 3μL of sample for running the gel on her recommendation.
   3. There were **no** bands in the negative controls and band in the positive control for *A. pulchra*. All other samples look good.
   4. As the two samples from the colonies failed I would be redoing the PCR again with dilutions as well as the original concentration using the same tube numbers from timepoint 1.


#### 2025-09-10

For today, I redid PCR for two colonies that did not show any band for the gel ran on 2025-09-05. The two colony_ids with no band were ACR-140 and ACR-180.

I also made a new master mix today. 

|Component|1 rxns|16 rxns|
|---------|---------|----------|
|One*Taq* Quick-Load 2X master mix | 12.5 μL | 200 μL | 
|10 μM CRf Primer| 0.5 μL|8.0 μL|
|10 μM CO3r Primer| 0.5 μL|8.0 μL|
|Nuclease Free Water|10.5 μL|168 μL|
|DNA Template| 1μL | |
|| 25 μL rxns |24 μL rxns|

I am re-running the PCR using an 8-strip tube. For each colony, I’ve prepared three reactions corresponding to:

1. The original sample (same concentration as before)
2. A 1:10 dilution
      |Sample ID| Volume of Sample| Volume of Water|
      |----------|------------|-----------|
      | T-207 ACR-140| 10 μL | 90 μL|
      | T-197 ACR-180| 10 μL| 90 μL|
3. A 1:100 dilution
      |Sample ID| Volume of Sample| Volume of Water|
      |----------|------------|-----------|
      | T-207 ACR-140| 1.0 μL | 99.0 μL|
      | T-197 ACR-180| 1.0 μL| 99.0 μL|

In total, I’m including three samples per colony. I used a Danielle Becker Heatwave *Acropora pulchra* as a postive control (no. 24 gDNA from 10/29/23). Water was used as a negative control in the plate.

The PCR Map for this day is below

![PCR MAP](https://github.com/ppednekar25/Pednekar_Putnam_Lab_Notebook/blob/49135e754116f2b4b12257e3f1017c786244d877/images/PCR_Map_Day_2.png?raw=TRUE).

Samples were stored in the fridge for the next steps.

The same setting was run for the PCR again and I ran only one 2% gel at 80 V for 90 min for 8 samples. 

This time I only loaded 3μL of sample and used the same DNA ladder 1KB.

![ACR CRf/CO3r Gel 1 09-10-2025](https://github.com/ppednekar25/Pednekar_Putnam_Lab_Notebook/blob/49135e754116f2b4b12257e3f1017c786244d877/images/E5_gDNA_Acropora_POST_PCR_failed_gel_1_09_10_2025.JPG?raw=TRUE)


#### Results from the Gel

   1. Out of the two colonies for *Acropora*, **ACR-140** did not show any bands even with dilutions.
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
|Component|1 rxns|8 rxns|
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

![ACR CRf/CO3r Gel 1 09-11-2025](https://github.com/ppednekar25/Pednekar_Putnam_Lab_Notebook/blob/49135e754116f2b4b12257e3f1017c786244d877/images/E5_gDNA_Acropora_POST_PCR_failed_gel_1_09_11_2025.JPG?raw=TRUE)

#### Results from the Gel

   1. The gel products look nice for colony_id ACR-140 and the bands looks more linear now.  
   2. There were **no** bands in the negative controls and band in the positive control for *A. pulchra*. 

**As by the end of DAY 3, the PCR worked for all the 50 colonies of *Acropora* we are going to progress for cleaning and sample prepping to send off to sequencing.**
  












   

















