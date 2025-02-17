# Voice Pathology Detection Using Deep Learning

This master thesis is both supervived by the Centre for Digital Health Interventions, ETH Zurich and the Chair of Medical Engineering, Faculty of Mechanical Engineering, Helmholtz Institute for Biomedical Engineering, RWTH Aachen University.

With advancements in human-centered medical technology, the demand for non-invasive and remote diagnostic methods is steadily increasing. This thesis explores deep learning-based
approaches for voice pathology classification using the Vowel Voice Pathological Dataset (VVPD), which integrates data from Coswara (COVID-19), ALS dataset (Amyotrophic Lateral
Sclerosis), PC-GITA (Parkinson’s disease), and the Saarbrücken Voice Database (SVD). A novel two-stage classification architecture is proposed, incorporating gender-specific pathological
modeling to address potential voice feature differences between male and female patients. Additionally, this study examines the impact of data balancing techniques, comparing common
resampling methods with a newly introduced timewarp strategy. Experiments are conducted by using ResNet-50 based transfer learning models and evaluating the performance of one-stage
and two-stage architectures under different balancing techniques. Results indicate that the two-stage architecture with timewarp-based balancing achieves the highest Matthews Correlation
Coefficient (MCC) of 0.9525, outperforming the baseline around 5%. These findings highlight the importance of gender related modeling in voice pathology classification and demonstrate
the potential of deep learning for non-invasive disease detection.
