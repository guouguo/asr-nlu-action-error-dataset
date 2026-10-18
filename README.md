# ASR-NLU Action-Level Error Propagation: Evaluation Data

This repository contains evaluation datasets and saved model outputs supporting the manuscript **“Action-Level Error Propagation and Decision Redundancy in an On-Device ASR-NLU System for Sensor-Based In-Vehicle Voice Control.”**

## Contents

| File | Description |
| --- | --- |
| `data/splits/audio603.csv` | Index of 603 held-out speech samples, manually verified reference transcripts, speaker pseudonyms, and gold intent labels. |
| `data/labels/text1351.csv` | 1,351-item within-ontology text evaluation set. |
| `data/labels/stress500.csv` | Frozen, template-generated 500-item stress evaluation set (270 Stress-A and 230 Stress-S). |
| `evaluation/audio603_results.csv` | Frozen ASR transcripts, normalized text, Rule decisions, BERT predictions, and final decisions for Audio603. |
| `evaluation/stress500_results.csv` | Frozen stress-set normalized text, Rule and BERT predictions, agreement outputs, and error indicators. |
| `deployment/validation160_consistency_summary.json` | Cross-platform validation consistency summary for 160 utterances. |
| `deployment/formal603_replay_summary.json` | RK3588S full-chain replay consistency and runtime measurements for Audio603. |


