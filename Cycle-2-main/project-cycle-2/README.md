# Project Cycle 2 - Statistical Investigation of Student Profiles

## Group Information
- **Group number:** 13
- **Member names:**
- - 112370206 黃立帆
  - 111370235 林家昕
  - 113370231 王薪葳

## Dataset
- **Dataset used:** `YRBS_2007.csv`

## Selected Variables
- **Proportion analysis:** `CurrentCigaretteUse` (Binary: 1 for Yes, 0 for No)
- **Mean analysis:** `HowTallAreYouWithoutShoesInMeters` (Continuous: Height in meters)

## Benchmark Values
- **For `CurrentCigaretteUse`:** $p_0 = 0.20$
- **For `HowTallAreYouWithoutShoesInMeters`:** $\mu_0 = 1.70$

## Research Questions
1. **Primary Inference:** Is the proportion of students who currently smoke significantly different from 0.20?
2. **Secondary Inference:** Is the mean height of students significantly different from 1.70 meters?
3. **Advanced Interaction:** How do gender and height jointly influence the proportion of students who smoke?

## Short Final Conclusion
Through our hypothesis testing ($\alpha = 0.05$), we confirmed the macroscopic trends of the student population regarding smoking rates and height. However, our advanced EDA revealed a more nuanced reality: while height does not affect smoking behavior in females, there is a distinct **"step-wise" positive correlation** among males—where taller male students exhibit a higher propensity to smoke. Furthermore, by utilizing bubble-size scaling, we successfully identified and filtered out statistical noise in extreme height ranges, ensuring our conclusions are based on reliable, high-density data.