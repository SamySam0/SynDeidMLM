## SynDeidMLM: Generating Synthetic Free-text Medical Records with Low Re-identification Risk using Masked Language Modeling

In this work, we introduce a system to generate synthetic free-text medical records, such as discharge summaries, admission notes and doctor correspondences, using Masked Language Modeling (MLM). Our system is designed to preserve the critical information of the records while introducing significant diversity and minimizing re-identification risk. The system incorporates a de-identification component that uses Philter to mask Protected Health Information (PHI), followed by a Medical Entity Recognition (NER) model to retain key medical information. We explore various masking ratios and mask-filling techniques to balance the trade-off between diversity and fidelity in the synthetic outputs without affecting overall readability. Our results demonstrate that the system can produce high-quality synthetic data with significant diversity while achieving a high HIPAA-compliant PHI recall rate.

Pre-print paper: https://arxiv.org/abs/2409.09831

### If you use this repository, please cite:
```
@article{belkadi2024generating,
  title={Generating Synthetic Free-text Medical Records with Low Re-identification Risk using Masked Language Modeling},
  author={Belkadi, Samuel and Ren, Libo and Micheletti, Nicolo and Han, Lifeng and Nenadic, Goran},
  journal={arXiv preprint arXiv:2409.09831},
  year={2024}
}
```
