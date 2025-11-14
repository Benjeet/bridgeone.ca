---
layout: splash
title: "Bridge One Technologies"
excerpt: "Sovereign data fusion for agencies, operators, and investors."
classes: wide
header:
  overlay_color: "#0b0e14"
  overlay_filter: "0.75"
  overlay_image: /assets/img/network-bg.jpg # optional background image
  actions:
    - label: "Schedule a Briefing"
      url: "mailto:info@bridgeone.ca?subject=Bridge%20One%20Briefing"
      btn_class: "btn--primary"
feature_row:
  - title: "For Government Programs"
    excerpt: "Auditable, Canadian-controlled software ready for IRAP, IDEaS, and rapid procurement pilots."
    icon: "fas fa-flag"
  - title: "For Operational Teams"
    excerpt: "Ingest → fusion → CoT gateway already integrated with TAK. Demo scripts prove the workflow in minutes."
    icon: "fas fa-satellite-dish"
  - title: "For Investors & Partners"
    excerpt: "A de-risked MVP, tight roadmap, and measurable adoption metrics—designed to scale responsibly."
    icon: "fas fa-chart-line"
---

## Canada’s sovereign data fusion & decision platform

**Bridge One Technologies** connects sensors, networks, and mission systems so decision-makers can trust what they see.  
We serve Canadian and allied agencies that need secure situational awareness, commercial operators who require reliable tooling, and investors who back strategic infrastructure.

### Why agencies partner with us
- **Sovereign control:** Built and operated in Canada with clear supply-chain provenance.  
- **Production discipline:** Each capability lands with tests, health checks, and Prometheus metrics.  
- **Rapid demos:** `make e2e` shows ingest → fusion → Cursor-on-Target output in under five minutes—ideal for funding reviews and stakeholder briefings.

### Field-ready for end users
- Secure HTTP ingest, PostGIS persistence, and `/v1/tracks` APIs for dashboards or partner tooling.  
- Deterministic CoT mapper + TLS-ready gateway streaming directly into TAK.  
- Replay scripts, TAK sink emulators, and dashboards so operators can practice without bespoke setup.

### A credible path for investors
- Clear MVP checklist with Steps 1–9 delivered (telemetry, DB, fusion, API, CoT, e2e).  
- Referenceable innovation support (NRC IRAP, IDEaS).  
- Roadmap for scaling to richer analytics, auth, and mission packaging.

{% assign highlights = site.data.proof_points.highlights %}
<div class="proof-points" role="list">
{% for item in highlights %}
  <article class="proof-points__card" role="listitem">
    <p class="proof-points__label">{{ item.label }}</p>
    <p class="proof-points__value">{{ item.value }}</p>
    <p class="proof-points__detail">{{ item.detail }}</p>
  </article>
{% endfor %}
</div>

{% assign programs = site.data.proof_points.programs %}
### Innovation partners
<div class="program-grid" role="list">
{% for program in programs %}
  <article class="program-card" role="listitem">
    <h4>{{ program.name }}</h4>
    <p>{{ program.blurb }}</p>
  </article>
{% endfor %}
</div>

{% assign testimonials = site.data.proof_points.testimonials %}
### What reviewers are saying
<div class="testimonial-grid">
{% for quote in testimonials %}
  <blockquote class="testimonial-card">
    <p>{{ quote.quote }}</p>
    <cite>— {{ quote.author }}</cite>
  </blockquote>
{% endfor %}
</div>

📂 **Open implementation:** [github.com/bridgeone/bridgeone](https://github.com/bridgeone/bridgeone) — includes README demos, ROADMAP, and MVP checklist for due diligence.

<div class="notice--success" style="margin-top:2rem; text-align:center;">
  <h3>Ready for your review board</h3>
  <p>We’ll bring the ingest → fusion → TAK replay, telemetry dashboards, and security artefacts. You bring the decision makers.</p>
  <p>
    <a class="btn btn--primary" href="mailto:info@bridgeone.ca?subject=Bridge%20One%20Agency%20Briefing">Book an agency briefing</a>
    <a class="btn" href="mailto:benjeet@bridgeone.ca?subject=Bridge%20One%20Investor%20Call">Investor intro</a>
  </p>
</div>

{% include feature_row %}
---

<div style="text-align:center; margin-top:2rem; font-size:0.9rem; color:#9ca3af;">
© 2025 Bridge One Technologies Inc. | Canadian Controlled | 
<a href="mailto:info@bridgeonetechnologies.ca">info@bridgeonetechnologies.ca</a>
</div>
