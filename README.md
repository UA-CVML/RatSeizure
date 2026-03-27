# RatSeizure: A Benchmark and Saliency-Context Transformer for Rat Seizure Localization

This repository is the official implementation of our paper [RatSeizure: A Benchmark and Saliency-Context Transformer for Rat Seizure Localization]().

Official repository for RatSeizure, a benchmark dataset and baseline model for temporal seizure behavior localization in rats.

Video festures and annotations will be releasing soon.
_________________
## Content Warning

This repository contains data from rat seizure experiments, which some may find disturbing. Viewer discretion is advised.

All animal use complied with guidelines from the National Institutes of Health (NIH) and the Albany Medical College (AMC) Institutional Animal Care and Use Committee (IACUC).
_________________
## Sample Dataset Visualization

Below is an example visualization of seizure behaviors across different Action Units.  
The video shows 14 seizure-related action units arranged in a 3×5 grid, with one blank cell.

<!-- ![RatSeizure Demo](ratseizure_demo.gif) -->
<img src="sample/ratseizure_demo.gif" width="900"/>

________________
## Action Unit Labels
The RatSeizure dataset defines 14 seizure-related behavioral Action Units (AUs).

| AU                          | Description                                  |
| --------------------------- | -------------------------------------------- |
| Normal                      | No seizure observed                          |
| Head Nodding                | Repeated up/down "yes" head motion           |
| Staring                     | Behavioral arrest without movement           |
| Neck Jerk                   | Repeated, intense or rapid "yes" head motion |
| Mouth Clonus                | Mouth and jaw twitching                      |
| Unilateral Forelimb Clonus  | Repetitive forelimb movement on one side     |
| Wet-Dog Shake               | Whole body shaking                           |
| Bilateral Forelimb Clonus   | Repetitive movement of both forelimbs        |
| Rearing                     | Standing upright on hind limbs               |
| Alternating Forelimb Clonus | Alternating forelimb movements               |
| Jumping                     | Sudden upward jump                           |
| Falling                     | Loss of posture with uncontrolled fall       |
| Tonic Extension             | Limbs rigidly extended while lying           |
| Wild Running                | Rapid uncontrolled circular running          |


________________
<!-- ## Citation
Please kindly consider citing our papers in your publications. 
```bash
@article{Tsai2026ratseizure,
  title={{RatSeizure: A Benchmark and Saliency-Context Transformer for Rat Seizure Localization}},
  author={Tsai, Ting Yu and Yu, An and Lee, Lucy and Ye, Felix and Shin, Damian and Kao, Tzu-Jen and Li, Xin and Chang, Ming-Ching},
  year={2026}
}
``` -->
