# RatSeizure: A Benchmark and Saliency-Context Transformer for Rat Seizure Localization

This repository is the official implementation of our paper [RatSeizure: A Benchmark and Saliency-Context Transformer for Rat Seizure Localization]().

Official repository for RatSeizure, a benchmark dataset and baseline model for temporal seizure behavior localization in rats.

Video festures and annotations will be releasing soon.
_________________
## Content Warning

This repository contains data from rat seizure experiments, which some may find disturbing. Viewer discretion is advised.

All animal use complied with guidelines from the National Institutes of Health (NIH) and the Albany Medical College (AMC) Institutional Animal Care and Use Committee (IACUC).

________________
## Action Unit Labels
The RatSeizure dataset defines 14 seizure-related behavioral Action Units (AUs).

| AU                          | Description                                  |
| --------------------------- | -------------------------------------------- |
| Normal                      | No seizure observed                          |
| Staring                     | Behavioral arrest without movement           |
| Mouth Clonus                | Mouth and jaw twitching                      |
| Wet-Dog Shake               | Whole body shaking                           |
| Head Nodding                | Repeated up/down "yes" head motion           |
| Neck Jerk                   | Repeated, intense or rapid "yes" head motion |
| Unilateral Forelimb Clonus  | Repetitive forelimb movement on one side     |
| Bilateral Forelimb Clonus   | Repetitive movement of both forelimbs        |
| Alternating Forelimb Clonus | Alternating forelimb movements               |
| Rearing                     | Standing upright on hind limbs               |
| Falling                     | Loss of posture with uncontrolled fall       |
| Wild Running                | Rapid uncontrolled circular running          |
| Jumping                     | Sudden upward jump                           |
| Tonic Extension             | Limbs rigidly extended while lying           |

________________
## License and Data Use

The **RatSeizure Dataset** is released by the **UA-CVML Lab, University at Albany, SUNY** for **research and educational use only**. RatSeizure is presented as a publicly available rat seizure behavior benchmark for research use. :contentReference[oaicite:0]{index=0}

Please review the following repository documents before downloading, accessing, or using the dataset:

- **`LICENSE`**: RatSeizure dataset license terms
- **`Data Use Agreement.md`**: RatSeizure data use agreement and user obligations

By downloading, accessing, or using this dataset, you agree to the terms described in both **`LICENSE`** and **`Data Use Agreement.md`**.

### Summary of Use Conditions
- You may use the dataset only for lawful research, educational, and scholarly purposes.
- You may not use the dataset for any unlawful, harmful, deceptive, or misleading purpose.
- You may not redistribute, sublicense, resell, publish, or otherwise share the dataset, in whole or in part, without prior written permission from the dataset maintainers.
- You must exercise reasonable care to protect the physical and electronic security of the dataset and prevent unauthorized access or misuse.
- If you discover any content in the dataset, metadata, annotations, or related documentation that appears sensitive, confidential, or improperly included, you must promptly report it to **uacvmllab@gmail.com** and identify the relevant location of the issue.
- Any paper, thesis, report, preprint, presentation, benchmark submission, model release, or software release arising from use of the dataset must appropriately cite the RatSeizure dataset and associated publication(s).
- Users are strongly encouraged to release code, evaluation scripts, and related reproducibility materials associated with published results whenever permitted by institutional, legal, and collaborative constraints.
- The dataset is provided for research purposes only and is **not** intended for clinical diagnosis, treatment, medical decision-making, or veterinary decision-making.

### No Warranty
The RatSeizure Dataset is provided **“as is”**, without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, title, and noninfringement. In no event shall the authors, copyright holders, dataset maintainers, or the UA-CVML Lab, University at Albany, SUNY be liable for any claim, damages, or other liability arising from, out of, or in connection with the dataset or its use.

### Contact
**CVML Lab, University at Albany, SUNY**  
**Email:** uacvmllab@gmail.com
________________
## Citation
Please kindly consider citing our papers in your publications. 
```bash
@article{Tsai2026RatSeizure,
  title   = {{RatSeizure: A Benchmark and Saliency-Context Transformer for Rat Seizure Localization}}, 
  author  = {Ting Yu Tsai and An Yu and Lucy Lee and Felix X.-F. Ye and Damian S. Shin and Tzu-Jen Kao and Xin Li and Ming-Ching Chang},
  year    = {2026},
  journal = {arXiv preprint arXiv:2603.26780},
  url     = {https://arxiv.org/abs/2603.26780}
}
```
