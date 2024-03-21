# Library preparation

Library preparation was performed with the Nextera XT DNA Library Prep kit (Illumina, catalogue # FC-131-1096), following the manufacturer's recommended protocol. For sequencing runs 1-3, we halved the reagent volumes for each step. For sequencing run 4, we had quite a few samples with high Ct values and a few samples that were old (from 2006), so we used full reaction volumes. The protocol below is for the half reaction volumes. To perform the full reaction (as specified in the Illumina recommended protocol), double the volumes and concentrations for each step. You can also follow this [protocol](https://support.illumina.com/content/dam/illumina-support/documents/documentation/chemistry_documentation/samplepreps_nextera/nextera-xt/nextera-xt-library-prep-reference-guide-15031942-02.pdf) from the prep kit manual.

### Pooling amplicons
For each sample, pool 1, pool 2, HA, and NA amplicons were combined in equimolar concentrations to a total of 1 ng in 4 µl in a PCR strip tube. This generally required diluting the cleaned PCR product, re-quantifying, and using the diluted product for pooling. All reactions were brought up to 5 µl with water. Amplicons that were below the limit of detection of the Qubit HS dsDNA Assay were tagmented and indexed separately to maximize recovery of these gene segments.

### Nextera XT DNA Library prep
1. Thaw ATM, TD, and input DNA on ice for 20 minutes. Thaw NT at room temp.

2. To each tube of pooled amplicons, add 10 µl of TD buffer. 

3. Add 5 μl of ATM to the wells containing input DNA and TD Buffer. Pipette up and down 5 times to mix (or vortex gently), then spin down. 

4. Immediately incubate reactions in a thermocycler for 5 minutes at 55°C, followed by a hold at 10°C. Make sure to use a heated lid. Once the samples reach 10°C, remove from the thermocycler, spin down, and proceed immediately to step 5. 
* when samples go into the thermocycler, take indices out to thaw at RT and NPM out to thaw on ice.

5. Add 5 µl of NT buffer to each tube, pipetting up and down 5 times (or vortex gently) to mix. Spin down and incubate at room temperature for 5 minutes. This step halts the tagmentation process. 

6. To each tube, add 15 µl of NPM (This should be thawed on ice for 20 minutes). 

7. Being careful not to touch the caps, add 5 µl of the i5 indices to each tube. Replace caps with new ones.

8. Add 5 µl of the i7 indices to each tube. Pipette up and down 5 times to mix. Replace caps with new ones.

9. Gently vortex and spin down.

10. Place tubes in a thermocycler and run the following limited-cycle PCR program. 

Ensure that the thermocycler lid is heated during the incubation. (total volume = 50 µl)

  1. 72°C for 3 minutes
  2. 95°C for 30 seconds
  3. 15 cycles of:
      1. 95°C for 10 seconds
      2. 55°C for 30 seconds
      3. 72°C for 30 seconds
  4. 72°C for 5 minutes
  5. Hold at 4°C

* After the PCR step is complete, reaction products can be stored at 4°C for up to 2 days. 

### Library cleanup with ampure beads
11. If desired, transfer your 50ul product to a new strip tube. (I like to use the capless ones for this step- labeled with library pool number on the side)

12. Add 30 µl of Ampure XP beads (0.6x) to your 50ul product and pipette up and down 10X.

13. Incubate at room temperature for 5 min. 

14. Place the tube on a magnetic particle concentrator (MPC) for 3-5 min. 

15. Wash the beads twice with 100ul of 80% EtOH. The volume of ethanol here is not critically important, as long as the entire bead pellet is submerged. 

16. Remove and discard EtOH and air dry the pellet at RT for 5-10 min, until the pellet is no longer shiny and there is no drops of EtOH remaining in the tube. 

17. Add 10-15 μl of Buffer RSB (Resuspension buffer) and pipette up & down 10x to resuspend the beads. Place the tube back on the MPC for 1 min to pellet the beads, and transfer the SN to clean PCR strip tubes (make sure no beads are transferred).

18. Go back to step 11 and repeat for a second AMPure XP clean-up (0.7X- steps below). 

19. Add 85-90µl of EB buffer (or H2O or RSB) to the 10-15 µl of eluted DNA. 

20. Add 70µl of Ampure XP beads (0.7x)

21. Incubate at room temperature for 5 min

22. Place the tube on a magnetic particle concentrator (MPC) for 3-5 min.

23. Wash the beads twice with 100µl of 80% EtOH.

24. Remove and discard EtOH and air dry the pellet at RT for 5-10 min

25. Add 12 μl of EB buffer and pipette up & down 10x to resuspend the beads. Place the tube back on the MPC for 1 min to pellet the beads, and transfer the supernatant to a clean microcentrifuge tube (make sure no beads are transferred).


### Quantification and QC with the Tapestation
Quantify tagmentation products with the Qubit 1X dsDNA HS Assay kit (Thermo Fisher, catalogue #Q33230). 

In order to determine the average fragment length, all samples should be run on the Tapestation using the D1000 or D5000 High Sensitivity Assay.

1. Allow reagents to come to room temperature for 30 minutes (ScreenTape, buffer, ladder). Label 
2. Vortex reagents and samples and spin down.
3. Combine 2μl of Sample Buffer and 2μl of Ladder in Agilent optical strip tubes.
4. Combine 2μl of Sample Buffer and 2μl of your library in Agilent optical strip tubes.
5. Apply caps, vortex, and spin down.
6. Load ScreenTape and samples into the TapeStation instrument, remove caps, assign sample labels, and press start. Refer to [user manual](https://www.agilent.com/cs/library/usermanuals/public/HS-D5000_QuickGuide.pdf) for more details on using TapeStation instrument and software.
