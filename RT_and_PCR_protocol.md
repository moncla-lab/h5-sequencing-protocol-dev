# Reverse transcription and PCR


### Reverse transcription/cDNA synthesis
Reverse transcription is performed with the Protoscript II first strand synthesis kit (NEB, catalogue # E6560L) and uses the Uni12 primer (AGCRAAAGCAGG) instead of the included random primers. 

1. Combine 2 µl of Uni12 primer with 8 ul of vRNA in a PCR tube for each sample. Incubate at 65°C for 5 minutes. After incubation, briefly spin down and put on ice. 

2. To each reaction, add 10 ul of Protoscript II reaction mix (2x) and 2 µl of Protoscript II enzyme mix (10x). This can be made up as a mastermix and aliquoted into each PCR tube to save time. 

3. Incubate this 22 µl cDNA synthesis reaction at 42°C for 1 hour, and then a final inactivation step at 80°C for 5 minutes. The cDNA product should be stored at -20 C.

### PCR
Primers are adapted from H1N1 primers from (Braun et al 2023)(https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9939568/). These primers utilize the the Hoffman universal primer sequences with several bases added for specificity based on alignments of relevant H5N1 sequences to improve specificity.  
Additional internal primers have been added for genes that we have had trouble amplifying (PB1, PB2, PA, and HA).
Primer sequences and pooling scheme with annealing temperatures can be found in this repo in file 'H5Nx_seq_primers'. Primers are pooled at 10uM total concentration.
10 Pools:

1. PB1-1
2. PB1-2
3. PB2-1
4. PB2-2
5. PA-1
6. PA-2
7. HA-1
8. HA-2
9. NA
10. NS_NP_MP

We amplified cDNA using 10 primer pools for each sample: using 2ul of cDNA and 1.25ul of forward and reverse primers at 10uM.

PCR was performed with the Q5 Hotstart DNA polymerase (NEB, catalogue # M0493L), with the following reaction volumes: 

For reactions with primer pools 1-9:

**Reagent** | **1X volume**
--- | --- 
Nuclease-free water| 14.75 µl
Q5 Reaction buffer | 5 µl
10 mM dNTP| 0.5 µl
Q5 DNA Polymerase| 0.25 µl
Forward Primer| 1.25 µl
Reverse Primer| 1.25 µl
cDNA | 2 ul
**total reaction volume** | 25 µl

For reaction with primer pool 10 (NS_NP_MP):
**Reagent** | **1X volume**
--- | --- 
Nuclease-free water| 14.75 µl
Q5 Reaction buffer | 5 µl
10 mM dNTP| 0.5 µl
Q5 DNA Polymerase| 0.25 µl
primer pool| 2.5 µl
cDNA | 2 ul
**total reaction volume** | 25 µl

For reactions for HA and NA separate amplification:

**cycling conditons:**

98 °C 30 seconds

35 cycles:
* 98 °C 10 seconds
* 67 °C 30 seconds (or 62C as indicated by primer pool spreadsheet)
* 72 °C 2 minutes

72 °C 2 minutes

10 °C forever


### Amplicon cleanup with AMPure XP beads
Following PCR, amplicons were cleaned via a 1X bead cleanup using AMPure XP beads.

1. Add 25µl of Ampure beads to your 25µl PCR product and pipette up and down 10x.
2. Place the tubes on the magnet rack for 3-5 minutes.
3. Wash the beads with 100µl 80% EtOH, removing Et (freshly made, however much will fit in the tube and fully submerge the beads).
4. Remove and discard the EtOH and wash again.
5. Remove and discard teh EtOH and air dry the pellet at room temperature until the pellet is no longer shiny.
6. Remove the samples from teh magnet and resuspend the pellet in 10-15µl of molecular grade H2O.
7. Return the tubes to the magnet rack to pellet the beads.

Following bead cleanup, 1µl of each sample was used to quantify using Qubit 1X dsDNA HS Assay kit (Thermo Fisher, catalogue #Q33230). 
