# Published Paper Results

This file records the quantitative results reported in the published paper:

**Advanced CAPTCHA Verification System Using Deep Learning and Adversarial Distortion Techniques for Enhanced Cybersecurity**

DOI: https://doi.org/10.1109/IC2NC67409.2025.11376476

> The values below are reported by the published paper. They are not presented as independently reproduced results from the repository notebook.

## CNN Recognition

The paper reports a final CNN validation accuracy of **96.8%** after the reported training procedure.

## Security Effectiveness

| Attack Vector | Proposed System |
|---|---:|
| Traditional OCR | 98.7% |
| Deep Learning CNN | 96.2% |
| Adversarial ML | 97.8% |
| Reinforcement Learning | 95.4% |
| Ensemble Methods | 94.9% |

## Statistical Analysis Reported in the Paper

| Attack Vector | Resistance | 95% CI | p-value |
|---|---:|---|---:|
| Traditional OCR | 98.7% | [98.1, 99.3] | < 0.001 |
| Deep Learning CNN | 96.2% | [95.4, 97.0] | < 0.001 |
| Adversarial ML | 97.8% | [97.2, 98.4] | < 0.001 |
| Reinforcement Learning | 95.4% | [94.5, 96.3] | < 0.001 |
| Ensemble Methods | 94.9% | [93.8, 96.0] | < 0.001 |

## Comparative Metrics Reported in the Paper

| Metric | Proposed | reCAPTCHA v3 | hCaptcha |
|---|---:|---:|---:|
| Security | 0.95 | 0.73 | 0.68 |
| Usability | 0.92 | 0.81 | 0.84 |
| Accessibility | 0.87 | 0.76 | 0.82 |
| Performance | 0.89 | 0.78 | 0.75 |
| Scalability | 0.91 | 0.74 | 0.71 |
| Adaptability | 0.94 | 0.69 | 0.66 |
| Average | 0.91 | 0.75 | 0.74 |

## Other Reported Experimental Details

- Human completion rate: approximately **91% or higher**
- Reported latency: **below 85 ms**
- Synthetic CAPTCHA dataset: **10,000 images**
- Augmented dataset: **50,000 images**
- CNN parameter count: approximately **9.8 million**
- Reported deployment/evaluation period: **six months**

## Important Interpretation

These values belong to the **published research paper**. The repository notebook is the experimental implementation supplied for this project and should not be described as reproducing every paper result exactly.
