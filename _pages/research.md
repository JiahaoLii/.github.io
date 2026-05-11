---
title: "Research"
permalink: /research/
author_profile: false
---

<style>
.research-card {
  display: flex;
  align-items: flex-start;
  gap: 2rem;
  margin: 2.2rem 0;
  padding-bottom: 1.8rem;
  border-bottom: 1px solid #e5e5e5;
}

.research-image {
  flex: 0 0 32%;
  max-width: 320px;
}

.research-image img {
  width: 100%;
  height: 200px;
  display: block;
  object-fit: cover;
  border-radius: 6px;
}

.research-text {
  flex: 1;
  min-width: 0;
}

.research-text h2 {
  margin-top: 0;
  margin-bottom: 0.8rem;
}

.research-text p {
  margin-bottom: 0;
  line-height: 1.75;
}

@media (max-width: 768px) {
  .research-card {
    flex-direction: column;
    gap: 1rem;
  }

  .research-image {
    max-width: 100%;
    flex: 0 0 auto;
  }
}
</style>

# Research

My research lies at the intersection of photonics and artificial intelligence.

<div class="research-card">
  <div class="research-image">
    <img src="/images/research-program.jpg" alt="Programmable photonic devices">
  </div>
  <div class="research-text">
    <h2>Programmable Photonic Devices</h2>
    <p>
      I work on MEMS-tunable metadevice platforms for programmable spectral responses and opto-logic operation. By independently controlling electrostatically actuated elements, these devices can produce tunable resonances and EIT-like spectral features, enabling reconfigurable terahertz functionality within a compact platform.
    </p>
  </div>
</div>

<div class="research-card">
  <div class="research-image">
    <img src="/images/research-inverse.jpg" alt="Inverse design for metasurfaces">
  </div>
  <div class="research-text">
    <h2>Inverse Design for Metasurfaces</h2>
    <p>
      I am interested in inverse design methods for metasurfaces and photonic devices. Instead of relying only on forward parameter sweeping, inverse design starts from a target optical or electromagnetic response and searches for suitable physical structures, device states, or operating conditions.
    </p>
  </div>
</div>

<div class="research-card">
  <div class="research-image">
    <img src="/images/research-AI.jpg" alt="AI-assisted electromagnetic field modeling">
  </div>
  <div class="research-text">
    <h2>AI-Assisted Electromagnetic Field Modeling</h2>
    <p>
      My machine-learning work focuses on electromagnetic field prediction and reconstruction. I aim to incorporate physics-inspired knowledge into neural networks to improve generalization, reduce the dependence on purely data-driven modeling, and make electromagnetic prediction more efficient and robust.
    </p>
  </div>
</div>

## Future Interests

I am interested in extending these methods toward silicon photonics, optical neural networks, and AI-assisted inverse design for integrated photonic devices.
