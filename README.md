# SPM-350M

![Parameters](https://img.shields.io/badge/Parameters-348.7M-blue)
![Architecture](https://img.shields.io/badge/Architecture-Decoder--Only-green)
![License](https://img.shields.io/badge/License-Apache%202.0-orange)
![Status](https://img.shields.io/badge/Status-Research-red)

**SPM-350M** is a 350 million parameter decoder-only language model developed by **Syclient**.

The model is designed for research, education, conversational AI, and efficient language model development. SPM-350M serves as the foundation of the Strategic Pretrained Model (SPM) family and represents Syclient's first large-scale language model project.

---

## Overview

SPM-350M is part of the SPM (Strategic Pretrained Model) family, a research initiative focused on building efficient and scalable language models from the ground up.

The project explores language modeling, instruction following, conversational AI, tokenizer design, and future experimental architectures.

---

## Model Specifications

| Property                    | Value                    |
| --------------------------- | ------------------------ |
| Model Name                  | SPM-350M                 |
| Organization                | Syclient                 |
| Architecture                | Decoder-only Transformer |
| Parameters                  | 348.7M                   |
| Hidden Size                 | 1024                     |
| Layers                      | 24                       |
| Attention Heads             | 16                       |
| KV Heads                    | 8                        |
| Context Length              | 2048                     |
| Recommended Sequence Length | 1024                     |
| Vocabulary Size             | 32,000                   |
| Primary Language            | English                  |
| Secondary Language          | Turkish                  |

---

## Training Data

SPM-350M was trained using a mixture of publicly available datasets, including:

* FineWeb-Edu
* Wikipedia
* UltraChat
* OpenAssistant

The training corpus was curated for research, conversational modeling, and general language understanding tasks.

---

## Model Weights

The model weights are available on Hugging Face.

Coming Soon.

## Intended Use

SPM-350M is intended for:

* Research
* Education
* Conversational AI
* Text Generation
* Experimentation
* Language Model Development

---

## Limitations

SPM-350M is an experimental research model.

The model may:

* Generate incorrect information
* Produce biased outputs
* Make reasoning mistakes
* Hallucinate facts
* Fail on complex tasks

Users should independently verify important information.

---

## Roadmap

* [x] SPM-70M Vertigo
* [x] SPM-350M Foundation
* [x] SPM-350M Chat Edition
* [ ] SPM-350M Ultra Edition
* [ ] SPM-1.2B
* [ ] SPM Flux Architecture
* [ ] SPM-8B

---

## Vision

Our goal is to build efficient language models that are accessible, practical, and scalable.

Rather than focusing solely on model size, the SPM project explores how far efficiency, data quality, and architecture design can be pushed within limited computational resources.

---

## License

Apache License 2.0

---

## Citation

```bibtex
@misc{spm350m2026,
  title={SPM-350M},
  author={Syclient},
  year={2026},
  publisher={GitHub}
}
```

---

**Building efficient language models from the ground up.**
