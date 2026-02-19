# Ryan Mulligan

**Staff AI Systems Architect** · Interpretability & Cognitive Architecture Research

---

Building **Lilly**, a self-steering cognitive AI running on Qwen3-8B with explicit internal state machinery:

- **8D Plutchik emotional field** (joy, trust, fear, surprise, sadness, disgust, anger, anticipation) with wave-packet interference for secondary emotion emergence
- **Evalatis**: evolutionary activation steering where vectors crystallize from activations, spawn children via crossover, and compete based on affinity x staleness vs. surprise EMA
- **AffectiveResonator**: queries episodic memory for similar past situations, computes weighted valence, injects a blended steering vector at layers 14-18 during inference
- **163k-feature SAE transcoders** trained on Qwen3-8B MLP layers via TransformerLens
- **6-phase cognitive cycle** (Generate, Curate, Simulate, Integrate, Reflect, Continue) with Active Inference / Free Energy Principle tracking prediction error across phases

The research question: can a model's behavior be continuously shaped by its own past emotional responses to similar situations? And if so, does it *know* this is happening?

This sits in direct conversation with mechanistic interpretability work on emergent introspection, building from the inside what that work probes from the outside.

---

**Stack:** Python · PyTorch · TransformerLens · SAELens · Letta · FalkorDB · Active Inference

**Open to roles in:** AI interpretability research · cognitive architectures · AI safety

---

🌐 [rmulligan.github.io](https://rmulligan.github.io) — Research portfolio
📦 [`lilly-steering`](https://github.com/rmulligan/lilly-steering): Core affect steering and evolutionary activation architecture
📧 ryan@mulligan.dev
