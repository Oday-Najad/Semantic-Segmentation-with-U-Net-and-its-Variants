Semantic Segmentation Project: Binary vs. Multi-Class Analysis

Overview
This project explores semantic segmentation using deep Unet models, focusin on two distinct tasks:
1. Binary Semantic Segmentation
2. Multi-Class Semantic Segmentation**

We implemented and evaluated models for both tasks, analyzed their performance, and investigated the broader implications of choosing one approach over the other. The project includes:
- Two Jupyter Notebooks: 
  - `Binary_Segmentation.ipynb`: Implementation and evaluation for binary segmentation.
  - `Multiclass_Segmentation.ipynb`: Implementation and evaluation for multi-class segmentation.
- A detailed report in `Project_Report.pdf`.

Report was finished by using the results of multiclass segmentation task while binary segmentation was done as a testing approach.

Key Objectives

1. Performance Comparison : Evaluate how well models perform on binary vs. multi-class tasks using metrics like IoU (Intersection over Union) and Dice Coefficient.
2. Model Adaptability : Test whether architectures designed for binary segmentation can scale effectively to multi-class problems.
3. Complexity Analysis : Understand how increased task complexity (from binary to multi-class).
4. Error Analysis : Identify common failure modes in both tasks.
