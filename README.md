# hERG Channel Inhibition and Drug Discovery

## Overview

The hERG channel is a voltage-gated potassium channel crucial for heart electrical activity. Inhibition of this channel poses a high cardiotoxic risk, making it a significant focus in the pharmaceutical industry. This project explores the binding modes of hERG blockers to enhance drug discovery processes.

## Objectives

- **Understand and Predict Interference**: Analyze how small molecules interact with the hERG channel and examine its binding promiscuity with various drugs.
- **Develop QSAR Models**: Utilize Decision Tree, Random Forest, and Light-GBM algorithms to predict potential drug candidates that do not inhibit the hERG channel.

## Methodology

1. **QSAR Model Development**:
   - Models were built using Decision Tree, Random Forest, and Light-GBM.
   - "One-Cluster-Out Cross Validation" was employed to validate models in a real-world scenario.

2. **Docking Studies**:
   - Conducted to unveil the binding modes of hERG inhibitors.
   - Focused on four binding modes, highlighting key interactions.

## Results

- **QSAR Models**:
  - Achieved good prediction accuracy (balanced accuracy > 70%) for Random Forest and Light-GBM.
  - Light-GBM maintained a low error rate (< 10%) during external validation.

- **Binding Modes**:
  - Discovery of four binding modes with tyrosines (Y652) playing a crucial role in stabilization.
  - Identified key residues such as alanines (A653), serines (S660 and S624), and glycines (G657) in interaction dynamics.

## Conclusion

The study provides insights into the binding mechanisms of hERG inhibitors and offers predictive models to aid in safer drug design. The findings emphasize the importance of specific amino acids in drug stabilization and binding within the hERG channel.
