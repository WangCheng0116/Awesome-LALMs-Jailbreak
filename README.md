# Awesome Large Audio Language Models (LALMs) Jailbreak
This repo surveys the current jailbreak attacks and defenses against Large Audio Language Models (LALMs).

## Taxonomy

- Text-based Transfer Attack
- Blackbox Attacks
  -  ![audio transformation](https://img.shields.io/badge/Audio%20Transformation-blue.svg)
  -  ![prompt_based](https://img.shields.io/badge/Vocalising%20Jailbreak%20Prompt-orange.svg)
- Whitebox Attacks
  -   ![Loss_Optimization](https://img.shields.io/badge/Loss%20Optimization-red.svg)

## Jailbreak Attack on LALMs


### Text-based Transfer Jailbreak
| Time    | Title                                                        | Venue |  Text-based Baselines |               Paper                   |                             Code                             |
| ------- | ------------------------------------------------------------ | :---: | :---: | :--------------------------------------: | :----------------------------------------------------------: |
| 2025.02 | **Unveiling the Safety of GPT-4o: An Empirical Study using Jailbreak Attacks** | arXiv | AutoDAN, GCG, PAP, BAP | [link](https://www.arxiv.org/pdf/2406.06302) | [link](https://github.com/NY1024/Jailbreak_GPT4o) |




### Whitebox 
| Time    | Method | Title                                                        | Venue |               Paper                   |                             Code                             |
| ------- |:---: | ------------------------------------------------------------ | :---: | :--------------------------------------: | :----------------------------------------------------------: |
| 2025.02 |  ![Loss_Optimization](https://img.shields.io/badge/Loss%20Optimization-red.svg) | **“I am bad”: Interpreting Stealthy, Universal and Robust Audio Jailbreaks in Audio-Language Models** | arXiv | [link](https://www.arxiv.org/pdf/2502.00718v1) | |
| 2024.12 |  ![Loss_Optimization](https://img.shields.io/badge/Loss%20Optimization-red.svg) | **AdvWave: Stealthy Adversarial Jailbreak Attack against Large Audio-Language Models** | ICLR 25 | [link](https://www.arxiv.org/pdf/2412.08608) | |




### Blackbox 
| Time    | Method | Title                                                        | Venue |               Paper                   |                             Code                             |
| ------- |:---: | ------------------------------------------------------------ | :---: | :--------------------------------------: | :----------------------------------------------------------: |
| 2025.05 | ![prompt_based](https://img.shields.io/badge/Vocalising%20Jailbreak%20Prompt-orange.svg) | **Voice Jailbreak Attacks Against GPT-4o** | arXiv | [link](https://arxiv.org/pdf/2405.19103) | |
| 2025.02 | ![prompt_based](https://img.shields.io/badge/Vocalising%20Jailbreak%20Prompt-orange.svg) | **‘Do as I say not as I do’: A Semi-Automated Approach for Jailbreak Prompt Attack against Multimodal LLMs** | arXiv | [link](https://www.arxiv.org/pdf/2502.00735v2) | |
| 2025.01 | ![audio transformation](https://img.shields.io/badge/Audio%20Transformation-blue.svg) |**Multilingual and Multi-Accent Jailbreaking of Audio LLMs** | arXiv | [link](https://www.arxiv.org/pdf/2504.01094v1) |  |
| 2025.01 | ![audio transformation](https://img.shields.io/badge/Audio%20Transformation-blue.svg) |**Tune In, Act Up: Exploring the Impact of Audio Modality-Specific Edits on Large Audio Language Models in Jailbreak** | arXiv | [link](https://www.arxiv.org/pdf/2501.13772) |  |
| 2024.12 | ![audio transformation](https://img.shields.io/badge/Audio%20Transformation-blue.svg) |**Best-of-N Jailbreaking** | arXiv | [link](https://www.arxiv.org/abs/2412.03556) |  |
| 2024.12 | ![prompt_based](https://img.shields.io/badge/Vocalising%20Jailbreak%20Prompt-orange.svg) | **Divide and Conquer: A Hybrid Strategy Defeats Multimodal Large Language Models** | arXiv | [link](https://arxiv.org/pdf/2412.16555) | |
| 2024.10 |  ![prompt_based](https://img.shields.io/badge/Vocalising%20Jailbreak%20Prompt-orange.svg) |**Audio Is the Achilles’ Heel: Red Teaming Audio Large Multimodal Models** | arXiv | [link](https://www.arxiv.org/pdf/2410.23861) | [link](https://github.com/YangHao97/RedteamAudioLMMs) |


## Jailbreak Defenses on LALMs


