---
permalink: /
title:
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<div class="homepage-shell">
  <section class="hero-panel">
    <p class="hero-kicker">Ph.D. Student in Computer Science</p>
    <h1>Xiaolong Han</h1>
    <p class="hero-lead">
      I am a Ph.D. student at the <a href="https://www.surrey.ac.uk/">University of Surrey</a>, advised by
      <a href="https://www.surrey.ac.uk/people/ferrante-neri">Prof. Ferrante Neri</a> and
      <a href="https://luuyin.com/">Assistant Prof. Lu Yin</a>.
    </p>
    <p class="hero-summary">
      My work focuses on parameter-centric machine learning: how model weights can be searched, analyzed, represented, and generated.
      I am currently most interested in weight space learning, neural architecture search, and functional representations for scientific data,
      and I actively collaborate with <a href="https://zehong-wang.github.io/">Zehong Wang</a> on related problems.
    </p>
    <div class="interest-tags">
      <span class="interest-tag">Deep Learning</span>
      <span class="interest-tag">Weight Space Learning</span>
      <span class="interest-tag">Neural Architecture Search</span>
      <span class="interest-tag">Evolutionary Computation</span>
    </div>
    <div class="hero-actions">
      <a href="{{ site.author.googlescholar }}">Google Scholar</a>
      <a href="https://github.com/{{ site.author.github }}">GitHub</a>
    </div>
  </section>

  <section class="home-section">
    <div class="section-header">
      <div>
        <p class="section-kicker">Research Direction</p>
        <h2>Focus</h2>
      </div>
      <p class="section-blurb">
        I study learning systems from the parameter level, with recent projects spanning model search, weight-space modeling,
        and function-space generation for scientific applications.
      </p>
    </div>
    <div class="info-card">
      <p>
        My recent work asks three connected questions: how to search neural architectures more reliably, how to organize model weights into
        useful representations, and how to generate neural functions directly for structured domains such as molecules. I am particularly
        interested in methods that are efficient enough to reuse pretrained models rather than retraining from scratch.
      </p>
    </div>
  </section>

  <section class="home-section">
    <div class="section-header">
      <div>
        <p class="section-kicker">Selected Research</p>
        <h2>Featured Projects</h2>
      </div>
      <p class="section-blurb">
        A curated snapshot of the public projects in my local research workspace, each paired with one representative figure from the paper.
      </p>
    </div>

    <div class="project-grid">
      <article class="project-card">
        <a class="project-visual" href="https://arxiv.org/abs/2603.10090">
          <img src="{{ '/images/projects/wsl-survey.png' | relative_url }}" alt="Overview figure for the Weight Space Learning survey">
        </a>
        <div class="project-body">
          <div class="project-meta">
            <span>2026</span>
            <span>Survey</span>
            <span>Weight Space Learning</span>
          </div>
          <h3>A Survey of Weight Space Learning: Understanding, Representation, and Generation</h3>
          <p class="project-authors"><strong>Xiaolong Han</strong>, Zehong Wang, Bo Zhao, Binchi Zhang, Jundong Li, et al.</p>
          <p class="project-summary">
            This survey organizes weight space learning into three axes: understanding, representation, and generation. It provides a unified map of
            how pretrained weights can be analyzed as structured objects and reused across retrieval, editing, federated learning, neural architecture
            search, and neural function generation.
          </p>
          <div class="project-tags">
            <span class="project-tag">Taxonomy</span>
            <span class="project-tag">Model Representations</span>
            <span class="project-tag">Generative Weights</span>
          </div>
          <p class="project-links">
            <a href="https://arxiv.org/abs/2603.10090">Paper</a>
            <a href="https://github.com/Zehong-Wang/Awesome-Weight-Space-Learning">Resources</a>
          </p>
        </div>
      </article>

      <article class="project-card">
        <a class="project-visual" href="https://arxiv.org/abs/2601.22327">
          <img src="{{ '/images/projects/molfield.png' | relative_url }}" alt="Framework figure for MolField">
        </a>
        <div class="project-body">
          <div class="project-meta">
            <span>2026</span>
            <span>Preprint</span>
            <span>Molecular Learning</span>
          </div>
          <h3>Molecular Representations in Implicit Functional Space via Hyper-Networks</h3>
          <p class="project-authors">Zehong Wang, <strong>Xiaolong Han</strong>, Qi Yang, Xiangru Tang, Fang Wu, et al.</p>
          <p class="project-summary">
            MolField models molecules in implicit functional space rather than fixed graph embeddings. The framework combines SE(3)-aware
            canonicalization, structured weight tokenization, and a transformer hyper-network to generate task-conditioned neural fields for
            molecular dynamics, property prediction, and related downstream tasks.
          </p>
          <div class="project-tags">
            <span class="project-tag">Hyper-Networks</span>
            <span class="project-tag">Implicit Neural Fields</span>
            <span class="project-tag">Molecular AI</span>
          </div>
          <p class="project-links">
            <a href="https://arxiv.org/abs/2601.22327">Paper</a>
          </p>
        </div>
      </article>

      <article class="project-card">
        <a class="project-visual" href="https://doi.org/10.1016/j.swevo.2024.101736">
          <img src="{{ '/images/projects/sadenas.png' | relative_url }}" alt="Framework figure for SaDENAS">
        </a>
        <div class="project-body">
          <div class="project-meta">
            <span>2024</span>
            <span>Swarm and Evolutionary Computation</span>
            <span>NAS</span>
          </div>
          <h3>SaDENAS: A Self-adaptive Differential Evolution Algorithm for Neural Architecture Search</h3>
          <p class="project-authors"><strong>Xiaolong Han</strong>, Yu Xue, Zehong Wang, Yong Zhang, Anton Muravev, Moncef Gabbouj</p>
          <p class="project-summary">
            SaDENAS revisits continuous evolutionary NAS through self-adaptive differential evolution. It balances local exploitation and global
            exploration in architecture-encoding space to reduce premature convergence and the small-model trap that can dominate supernet-based search.
          </p>
          <div class="project-tags">
            <span class="project-tag">Differential Evolution</span>
            <span class="project-tag">Continuous ENAS</span>
            <span class="project-tag">Search Stability</span>
          </div>
          <p class="project-links">
            <a href="https://doi.org/10.1016/j.swevo.2024.101736">Paper</a>
          </p>
        </div>
      </article>

      <article class="project-card">
        <a class="project-visual" href="https://doi.org/10.1109/TNNLS.2024.3371432">
          <img src="{{ '/images/projects/genas.png' | relative_url }}" alt="Representative framework figure for GENAS">
        </a>
        <div class="project-body">
          <div class="project-meta">
            <span>2024</span>
            <span>IEEE TNNLS</span>
            <span>NAS</span>
          </div>
          <h3>A Gradient-guided Evolutionary Neural Architecture Search</h3>
          <p class="project-authors">Yu Xue, <strong>Xiaolong Han</strong>, Ferrante Neri, Jiafeng Qin, Danilo Pelusi</p>
          <p class="project-summary">
            GENAS combines evolutionary search with gradient-guided local refinement in a weight-sharing supernet. The method keeps the exploration
            strength of evolutionary NAS while using efficient local updates to improve candidate architectures without retraining every subnet from scratch.
          </p>
          <div class="project-tags">
            <span class="project-tag">Weight Sharing</span>
            <span class="project-tag">Evolutionary NAS</span>
            <span class="project-tag">Local Search</span>
          </div>
          <p class="project-links">
            <a href="https://doi.org/10.1109/TNNLS.2024.3371432">Paper</a>
          </p>
        </div>
      </article>

      <article class="project-card">
        <a class="project-visual" href="https://doi.org/10.1109/TII.2023.3348843">
          <img src="{{ '/images/projects/swd-nas.png' | relative_url }}" alt="Framework figure for SWD-NAS">
        </a>
        <div class="project-body">
          <div class="project-meta">
            <span>2024</span>
            <span>IEEE TII</span>
            <span>Differentiable NAS</span>
          </div>
          <h3>Self-adaptive Weight Based on Dual-attention for Differentiable Neural Architecture Search</h3>
          <p class="project-authors">Yu Xue, <strong>Xiaolong Han</strong>, Zehong Wang</p>
          <p class="project-summary">
            SWD-NAS stabilizes differentiable neural architecture search with a dual-attention mechanism that reweights candidate operations more
            reliably than vanilla architecture parameters, reducing the bias and collapse behaviors often observed in DARTS-style search.
          </p>
          <div class="project-tags">
            <span class="project-tag">DARTS</span>
            <span class="project-tag">Dual Attention</span>
            <span class="project-tag">Architecture Weights</span>
          </div>
          <p class="project-links">
            <a href="https://doi.org/10.1109/TII.2023.3348843">Paper</a>
          </p>
        </div>
      </article>
    </div>
  </section>

  <section class="home-section split-grid">
    <div class="info-card">
      <h2>Earlier Publications</h2>
      <ul class="compact-publication-list">
        <li>
          <span class="compact-publication-year">2023</span>
          <div>
            <strong>Heterogeneous Graph Contrastive Multi-view Learning.</strong> SDM 2023.
            <a href="https://epubs.siam.org/doi/abs/10.1137/1.9781611977653.ch16">Paper</a>
          </div>
        </li>
        <li>
          <span class="compact-publication-year">2022</span>
          <div>
            <strong>Temporal Graph Transformer for Dynamic Network.</strong> ICANN 2022.
            <a href="https://doi.org/10.1007/978-3-031-15931-2_57">Paper</a>
          </div>
        </li>
        <li>
          <span class="compact-publication-year">2022</span>
          <div>
            <strong>Prediction of Willingness to Pay for Airline Seat Selection Based on Improved Ensemble Learning.</strong> Aerospace.
            <a href="https://doi.org/10.3390/aerospace9020047">Paper</a>
          </div>
        </li>
      </ul>
    </div>

    <div class="info-card">
      <h2>Service and Recognition</h2>
      <p>
        I serve as a reviewer for IEEE Transactions on Neural Networks and Learning Systems,
        IEEE Transactions on Circuits and Systems for Video Technology, Swarm and Evolutionary Computation,
        Scientific Reports, and Knowledge Engineering Review.
      </p>
      <p>
        Recent awards include the National Scholarship, the NUIST Graduate "Puxin" Elite Scholarship,
        the Principal Scholarship, and the First Prize Scholarship in 2024.
      </p>
    </div>
  </section>
</div>
