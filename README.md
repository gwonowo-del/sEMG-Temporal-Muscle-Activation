# sEMG-Temporal-Muscle-Activation

## sEMG-based Temporal Muscle Activation Pattern Analysis During Badminton Upper-limb Movements

**Young-Jae Gwon¹, Jieun Park², Sang-Il Choi³*, Jung-Hun Kim⁴***

¹ School of Computer Software, Daegu Catholic University, Gyeongsan-si, Republic of Korea  
² Kyungpook National University Hospital, Daegu, Republic of Korea  
³ School of Computer Software, Daegu Catholic University, Gyeongsan-si, Republic of Korea  
⁴ School of Computer Software, Daegu Catholic University, Gyeongsan-si, Republic of Korea

*Corresponding authors: sangilchoi@cu.ac.kr, fainal2@cu.ac.kr

---

## Overview

This repository provides the experimental surface electromyography (sEMG) datasets used in the study:

**"sEMG-based Temporal Muscle Activation Pattern Analysis During Badminton Upper-limb Movements."**

Unlike previous studies that primarily focused on movement classification using conventional features, this study investigates the temporal organization and consistency of muscle activation patterns during badminton upper-limb movements.

To achieve this, we propose a temporal analysis framework that combines temporal window analysis, representative muscle channel selection, time-resolved separation analysis, and a novel **Pattern Stability Index (SSI)** for quantifying movement consistency across repeated trials.

The repository contains the experimental CSV datasets used throughout the study and is intended to support research reproducibility and future investigations on temporal muscle activation analysis.

---

## Key Contributions

- Public experimental sEMG dataset collected during badminton upper-limb movements.
- Eight-channel muscle activation recordings from upper-limb muscles.
- Temporal muscle activation pattern analysis beyond conventional movement classification.
- Introduction of the **Pattern Stability Index (SSI)** for evaluating movement consistency.
- Benchmark dataset for temporal sEMG analysis in sports biomechanics and biosignal research.

---

## Dataset Description

Surface electromyography (sEMG) signals were recorded from eight upper-limb muscles using an eight-channel biopotential recording system.

| Channel | Muscle |
|:-------:|--------------------------------|
| CH1 | Flexor Digitorum Superficialis |
| CH2 | Extensor Carpi Radialis Brevis |
| CH3 | Brachioradialis |
| CH4 | Biceps Brachii |
| CH5 | Triceps Brachii |
| CH6 | Posterior Deltoid |
| CH7 | Middle Deltoid |
| CH8 | Anterior Deltoid |

### Recording Information

- Sampling frequency: **1000 Hz**
- Number of channels: **8**
- Participants: **6 healthy male subjects**
- Recording period: **7 days**
- Repetitions: **15 trials per movement per day**
- Total trials per participant: **525**
- Total recorded trials: **3150**

### Recorded Movements

| Label | Movement |
|:-----:|------------------|
| BH | Backhand |
| BHV | Backhand Volley |
| FH | Forehand |
| FHV | Forehand Volley |
| SV | Serve |

---

## Repository Structure

```
sEMG-Temporal-Muscle-Activation/
│
├── data/
│   ├── *.csv
│
├── LICENSE
└── README.md
```

---

## File Naming Rule

Each CSV file corresponds to one experimental recording.

The filenames encode the experimental information, including:

- Movement type
- Trial number
- Participant identifier

Please refer to the dataset for the detailed file naming convention.

---

## Data Processing

The datasets were processed using the following analysis pipeline.

1. Trial segmentation
2. Hit-time alignment
3. RMS envelope computation
4. Temporal normalization
5. Temporal window analysis
6. Representative channel selection
7. Temporal separation analysis
8. Pattern Stability Index (SSI) computation
9. Feature-based movement classification

---

## Data Usage

This dataset can be used for research on:

- Surface electromyography (sEMG)
- Sports biomechanics
- Badminton motion analysis
- Temporal muscle activation analysis
- Human movement analysis
- Motor control
- Muscle coordination
- Pattern stability analysis
- Machine learning for biosignal analysis
- Biomedical signal processing

---

## Data Availability

This repository contains the experimental CSV datasets used in the associated study.

The datasets are publicly available to support research reproducibility and future comparative studies on temporal muscle activation analysis.

---

## Ethics Statement

This study was approved by the Institutional Review Board (IRB) of **Kyungpook National University Hospital**.

**IRB Approval No.: KNUH 2025-08-024-003**

All participants provided written informed consent prior to participation.

---

## Citation

If you use this dataset in your research, please cite the following paper.

> Young-Jae Gwon, Jieun Park, Sang-Il Choi, Jung-Hun Kim.  
> **sEMG-based Temporal Muscle Activation Pattern Analysis During Badminton Upper-limb Movements.**  
> *(Publication information will be updated after publication.)*

---

## License

This dataset is distributed under the **Apache-2.0 License**.

See the LICENSE file for additional information.

---

## Contact

For questions regarding this repository, please contact:

**Young-Jae Gwon**

or the corresponding authors.

- sangilchoi@cu.ac.kr
- fainal2@cu.ac.kr
