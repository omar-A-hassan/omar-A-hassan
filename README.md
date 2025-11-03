# Omar Hassan (@omar-a-hassan)

Projects where ( Biology ) ∩ ( AI & ML ), a dash of NLP & LLMs

## Selected Projects

1. **Arabic NLP Benchmarks & Evaluation**

[Benchmark-Whisper](https://github.com/omar-A-hassan/Benchmark-Whisper)

> Expanded upon Pico-voice ASR benchmark to support benchmarking of OpenAI's Whisper in transcription of Egyptian ARZ speech into ARZ and english text.

[Benchmark-Nllb200](https://github.com/omar-A-hassan/lm-evaluation-harness)

> Expanded lm-evaluation-harness to support machine translation of ARZ to english and vice versa with a new ARZ corpus dataset from hugging face and Meta's Nllb200.

2. **LLM Hallucination Detection & Mitigation**

  [ACE-Hallucinations](https://github.com/omar-A-hassan/ACE-Hallucinations)

  > Competition solution for Russian hallucination detection (codeforces) using Agentic Context Engine
  (ACE)—trained Gemma-3-270M (Generator) with Gemini Flash 2.5 (Reflector/Curator) to learn 83
  anti-hallucination strategies from 380 SberQuAD-derived examples that were transformed using Gemini Flash 2.5, achieving 0% hallucination
  rate with conservative refusal behavior deployed via llama.cpp + GGUF for GPU inference for the competition.

3. **Geospaital AI Esri North Africa**

[Presto-GeoAI](https://github.com/omar-A-hassan/Presto-for-Crop-classification)

> As part of my GIS intership at Esri, A fine tuned Presto (GeoAI foundational model) on the task of classifying 3 crop types across Africa and also as part of a GeoAI competition on Zindi where it achieved leaderboard position 37, The model's outputs integrate seamlessly into ArcGIs and can be viewed as a feature layer.

4. **Explainable AI and Adversarial Attacks**

[XAI, Adversarial attacks and model hardening on CNNs tutorial](https://github.com/omar-A-hassan/Adversarial-attacks-and-XAI-on-CNNS)

> A 4 step workflow outlining how to fine-tune ResNet-34/MobileNetV2 on Caltech-101, generate FGSM adversaries using torchattacks, interpret with Grad-CAM & saliency, and evaluate defenses (adversarial training, input transforms).


4. **Robotics & Voice Control**

[SHATO — Voice-Controlled Robotic Assistant](https://github.com/omar-A-hassan/Project-Shato?tab=readme-ov-file#shato---voice-controlled-robotic-assistant)

> A production-grade microservices system that turns speech into schema-validated robot commands—Whisper STT → Fine tuned Gemma3-270M intent extraction → Pydantic validation (self-correction) → Parler TTS—built with FastAPI and Docker, with zero malformed commands reaching hardware.

You're probably wondering where's the Bio AI projects, here's one ;)

5. **Parkinson's Disease Voice Detection**

[Parkinsons](https://github.com/omar-A-hassan/Parkinsons)

> Production-grade ML pipeline for detecting Parkinson's Disease from voice recordings using Wav2Vec2
  foundation model features—implements dual approach: fine-tuned neural classifier (Wav2Vec2-base-960h → pooling
  → classification head with dropout) vs Random Forest on frozen embeddings, trained on 81-sample balanced
  dataset (HC/PD) with stratified split, comprehensive test suite, CI/CD (GitHub Actions), and Makefile
  workflow—engineered for small medical datasets with configurable YAML-driven training, W&B logging, and
  device-agnostic execution (MPS/CUDA/CPU).
