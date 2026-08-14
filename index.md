---
layout: default
title: RobustiPy
description: Open-source Python software for multiverse analysis and model uncertainty assessment, published in Patterns.
image: /assets/robustipy_logo_large.png
home: true
---

<section class="hero-wrap" aria-labelledby="hero-title">
  <div class="shell hero">
    <div class="hero-copy">
      <a class="publication-pill" href="https://www.cell.com/patterns/fulltext/S2666-3899(26)00118-2">Published in <em>Patterns</em> · 14 August 2026</a>
      <h1 id="hero-title">See how conclusions change across the analytical multiverse.</h1>
      <p class="hero-lead">RobustiPy is an open-source Python library for multiverse analysis and model uncertainty assessment. It brings specification search, resampling, model comparison, validation, and interpretation into one reproducible workflow.</p>
      <div class="hero-actions">
        <a class="button button-primary" href="https://www.cell.com/patterns/fulltext/S2666-3899(26)00118-2">
          Read the paper
          <svg aria-hidden="true" viewBox="0 0 20 20"><path d="M4 10h12M11 5l5 5-5 5"/></svg>
        </a>
        <a class="button button-ghost" href="https://robustipy.readthedocs.io/en/latest/">Read the documentation</a>
      </div>
      <ul class="hero-meta" aria-label="Project details">
        <li>Python package</li>
        <li>Available on PyPI</li>
        <li>GNU GPL v3.0</li>
      </ul>
    </div>

    <aside class="terminal-card" aria-label="Installation command">
      <div class="terminal-bar">
        <div class="terminal-dots" aria-hidden="true"><span></span><span></span><span></span></div>
        <span>terminal</span>
      </div>
      <pre><code><span class="prompt">$</span> pip install robustipy</code></pre>
      <div class="terminal-note">
        <span>Install the stable release</span>
        <a href="https://pypi.org/project/robustipy/">View on PyPI &rarr;</a>
      </div>
    </aside>
  </div>
</section>

<section class="evidence-band" aria-label="Evaluation reported in the paper">
  <div class="shell evidence-strip">
    <div class="evidence-item">
      <strong class="evidence-value">5</strong>
      <div class="evidence-copy"><strong>Controlled simulations</strong><span>reported in the paper</span></div>
    </div>
    <div class="evidence-item">
      <strong class="evidence-value">10</strong>
      <div class="evidence-copy"><strong>Empirical replications</strong><span>across four research domains</span></div>
    </div>
    <div class="evidence-item">
      <strong class="evidence-value">≈672m</strong>
      <div class="evidence-copy"><strong>Regression-equivalent fits</strong><span>in the reported time-profiling benchmark</span></div>
    </div>
  </div>
</section>

<section class="home-section" aria-labelledby="capabilities-title">
  <div class="shell">
    <div class="section-heading section-heading--split">
      <div>
        <p class="eyebrow">One coherent toolkit</p>
        <h2 id="capabilities-title">Assess robustness from more than one angle.</h2>
      </div>
      <p>RobustiPy helps researchers make defensible modelling choices explicit, estimate their consequences, and inspect uncertainty across specifications.</p>
    </div>

    <div class="feature-grid">
      <article class="feature-card">
        <span class="feature-number">01</span>
        <h3>Specification search</h3>
        <p>Explore admissible outcome constructions and candidate-control combinations, with support for multiple focal estimands.</p>
      </article>
      <article class="feature-card">
        <span class="feature-number">02</span>
        <h3>Bootstrap inference</h3>
        <p>Quantify sampling uncertainty across specifications with reproducible bootstrap-based routines.</p>
      </article>
      <article class="feature-card">
        <span class="feature-number">03</span>
        <h3>Model selection and averaging</h3>
        <p>Compare specifications using fit criteria and summarise results with weighted or unweighted estimates.</p>
      </article>
      <article class="feature-card">
        <span class="feature-number">04</span>
        <h3>Out-of-sample validation</h3>
        <p>Use cross-validation to assess whether model performance holds beyond the estimation sample.</p>
      </article>
      <article class="feature-card">
        <span class="feature-number">05</span>
        <h3>Joint inference</h3>
        <p>Evaluate evidence across related estimates rather than relying on isolated significance tests.</p>
      </article>
      <article class="feature-card">
        <span class="feature-number">06</span>
        <h3>Feature-level explanations</h3>
        <p>Inspect variable influence in the full-specification predictive model with explainable-AI tools.</p>
      </article>
    </div>
  </div>
</section>

<section class="home-section home-section--compact section-soft section-border" aria-labelledby="workflow-title">
  <div class="shell">
    <div class="section-heading">
      <p class="eyebrow">A transparent workflow</p>
      <h2 id="workflow-title">From modelling choices to interpretable evidence.</h2>
    </div>
    <div class="workflow">
      <article class="workflow-step">
        <h3>Frame the choice space</h3>
        <p>Define the outcomes, predictors, controls, estimators, and resampling strategy that are defensible for the question.</p>
      </article>
      <article class="workflow-step">
        <h3>Estimate the multiverse</h3>
        <p>Run combinations systematically, with sampling and parallelisation options when the specification space is large.</p>
      </article>
      <article class="workflow-step">
        <h3>Interpret results together</h3>
        <p>Compare estimates, uncertainty, fit, predictive performance, and feature influence across a shared set of outputs.</p>
      </article>
    </div>
  </div>
</section>

<section class="home-section section-blue section-border" aria-labelledby="paper-title">
  <div class="shell paper-panel">
    <div class="paper-copy">
      <p class="journal-mark">Patterns · Open access</p>
      <h2 id="paper-title">RobustiPy: An efficient next-generation multiversal library with model selection, averaging, resampling, and explainable AI</h2>
      <p>The paper introduces the library and demonstrates its use across simulations and empirical replications in economics, sociology, psychology, and medicine.</p>
      <div class="paper-actions">
        <a class="button button-dark" href="https://www.cell.com/patterns/fulltext/S2666-3899(26)00118-2">Read the full text</a>
        <a class="button button-outline" href="https://doi.org/10.1016/j.patter.2026.101609">Open the DOI</a>
        <a class="button button-outline" href="#how-to-cite">How to cite</a>
      </div>
    </div>

    <aside class="citation-card" aria-labelledby="how-to-cite">
      <h3 class="citation-label" id="how-to-cite">How to cite</h3>
      <p class="citation-text"><strong>Valdenegro, D., Yan, J., Dai, D., &amp; Rahal, C.</strong> (2026). RobustiPy: An efficient next-generation multiversal library with model selection, averaging, resampling, and explainable AI. <em>Patterns, 7</em>, 101609. <a href="https://doi.org/10.1016/j.patter.2026.101609">https://doi.org/10.1016/j.patter.2026.101609</a></p>
      <p class="paper-evidence">The paper reports five simulations, ten empirical replications, and a time-profiling benchmark spanning approximately 672 million regression-equivalent fits.</p>
      <details class="citation-details">
        <summary>BibTeX</summary>
        <pre><code>@article{valdenegro2026robustipy,
  title   = {RobustiPy: An efficient next-generation
             multiversal library with model selection,
             averaging, resampling, and explainable AI},
  author  = {Valdenegro, Daniel and Yan, Jiani and
             Dai, Duiyi and Rahal, Charles},
  journal = {Patterns},
  volume  = {7},
  pages   = {101609},
  year    = {2026},
  doi     = {10.1016/j.patter.2026.101609}
}</code></pre>
      </details>
    </aside>
  </div>
</section>

<section class="home-section" aria-labelledby="resources-title">
  <div class="shell">
    <div class="section-heading section-heading--split">
      <div>
        <p class="eyebrow">Learn and apply</p>
        <h2 id="resources-title">Everything needed to get started.</h2>
      </div>
      <p>Begin with a practical walkthrough, consult the API documentation, or work through complete examples in the source repository.</p>
    </div>

    <div class="resource-grid">
      <a class="resource-card" href="https://robustipy.readthedocs.io/en/latest/">
        <span class="resource-meta">Reference <span class="resource-arrow" aria-hidden="true">&nearr;</span></span>
        <h3>Documentation</h3>
        <p>API reference and package documentation on Read the Docs.</p>
      </a>
      <a class="resource-card" href="{{ '/getting-started.html' | relative_url }}">
        <span class="resource-meta">Guide <span class="resource-arrow" aria-hidden="true">&rarr;</span></span>
        <h3>Getting started</h3>
        <p>A concise path from installation to fitting and plotting results.</p>
      </a>
      <a class="resource-card" href="{{ '/interpretation-guide.html' | relative_url }}">
        <span class="resource-meta">Guide <span class="resource-arrow" aria-hidden="true">&rarr;</span></span>
        <h3>Interpret the figures</h3>
        <p>Read each panel in the standard RobustiPy results output.</p>
      </a>
      <a class="resource-card" href="https://github.com/RobustiPy/robustipy/tree/main/empirical_examples">
        <span class="resource-meta">Notebooks <span class="resource-arrow" aria-hidden="true">&nearr;</span></span>
        <h3>Empirical examples</h3>
        <p>Reproducible applications across several substantive domains.</p>
      </a>
      <a class="resource-card" href="https://www.youtube.com/@RobustiPy">
        <span class="resource-meta">Video <span class="resource-arrow" aria-hidden="true">&nearr;</span></span>
        <h3>Tutorials and talks</h3>
        <p>Introductions, demonstrations, and recorded project material.</p>
      </a>
      <a class="resource-card" href="https://doi.org/10.5281/zenodo.15700697">
        <span class="resource-meta">Archive <span class="resource-arrow" aria-hidden="true">&nearr;</span></span>
        <h3>Software archive</h3>
        <p>Versioned RobustiPy releases preserved on Zenodo.</p>
      </a>
    </div>

    <aside class="hackathon-note" aria-labelledby="hackathon-title">
      <p class="hackathon-date">Oxford · June 2024</p>
      <div>
        <h3 id="hackathon-title">RobustiPy Hackathon</h3>
        <p>The team hosted a hands-on hackathon at the University of Oxford, bringing researchers together to explore the library and work through multiverse analyses. We thank everyone who participated and contributed their time, questions, and feedback.</p>
      </div>
    </aside>

  </div>
</section>

<section class="home-section home-section--compact section-soft section-border" aria-labelledby="team-title">
  <div class="shell">
    <div class="section-heading">
      <p class="eyebrow">Creators</p>
      <h2 id="team-title">Built by an interdisciplinary team.</h2>
      <p>RobustiPy was developed at the University of Oxford by researchers working across computational social science, demography, and data science.</p>
    </div>
    <div class="team-grid">
      <article class="person-card">
        <span class="person-initials" aria-hidden="true">DV</span>
        <h3>Daniel Valdenegro</h3>
        <p>Co-author · Software development</p>
        <a href="https://github.com/dhvalden">GitHub profile &nearr;</a>
      </article>
      <article class="person-card">
        <span class="person-initials" aria-hidden="true">JY</span>
        <h3>Jiani Yan</h3>
        <p>Co-author · Software development</p>
        <a href="https://jianiyan.com/">Personal website &nearr;</a>
      </article>
      <article class="person-card">
        <span class="person-initials" aria-hidden="true">DD</span>
        <h3>Duiyi Dai</h3>
        <p>Co-author · Code review</p>
        <a href="https://duiyidai.github.io/">Personal website &nearr;</a>
      </article>
      <article class="person-card">
        <span class="person-initials" aria-hidden="true">CR</span>
        <h3>Charles Rahal</h3>
        <p>Software initiator · Lead contact</p>
        <a href="https://crahal.com/">Personal website &nearr;</a>
      </article>
    </div>
  </div>
</section>

<section class="home-section section-border" aria-labelledby="open-title">
  <div class="shell open-grid">
    <div class="open-copy">
      <p class="eyebrow">Open by design</p>
      <h2 id="open-title">Research software that can be inspected and improved.</h2>
      <p>RobustiPy is released under the GNU General Public License v3.0. Contributions, bug reports, feature requests, and reproducible examples are welcome through GitHub.</p>
      <div class="open-links">
        <a class="button button-dark" href="https://github.com/RobustiPy/robustipy">View the source</a>
        <a class="button button-outline" href="https://github.com/RobustiPy/robustipy/issues">Open an issue</a>
        <a class="button button-outline" href="https://github.com/RobustiPy/robustipy/blob/main/CODE-OF-CONDUCT.md">Code of conduct</a>
      </div>
    </div>
    <aside class="license-card" aria-label="Software license">
      <p class="license-mark">Open-source software · Copyleft</p>
      <strong>GNU General Public License v3.0</strong>
      <p>The journal article is separately published open access under the Creative Commons Attribution 4.0 license.</p>
    </aside>
  </div>
</section>

<section class="home-section home-section--compact section-blue section-border" aria-labelledby="acknowledgements-title">
  <div class="shell acknowledgements">
    <p class="eyebrow">Acknowledgements</p>
    <h2 id="acknowledgements-title">Research support</h2>
    <p>The authors are grateful for funding from the ESRC (grant ES/W002302/1), the Leverhulme Trust (grant RC-2018-003) for the Leverhulme Centre for Demographic Science and Nuffield College, and a Grand Union DTP ESRC studentship.</p>
    <div class="partner-logos" aria-label="Research-support organisations">
      <a href="https://centreforcare.ac.uk/">
        <img src="{{ '/assets/cfc_logo.png' | relative_url }}" alt="ESRC Centre for Care" width="1868" height="710" loading="lazy">
      </a>
      <a href="https://www.demography.ox.ac.uk/">
        <img src="{{ '/assets/lcds_logo.png' | relative_url }}" alt="Leverhulme Centre for Demographic Science" width="1594" height="417" loading="lazy">
      </a>
      <a href="https://www.nuffield.ox.ac.uk/">
        <img class="partner-logo--nuffield" src="{{ '/assets/nuffield_college_logo.png' | relative_url }}" alt="Nuffield College, University of Oxford" width="600" height="277" loading="lazy">
      </a>
    </div>
  </div>
</section>
