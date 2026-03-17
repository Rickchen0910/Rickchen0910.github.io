# Page Story: Binzhi Chen — Academic Personal Homepage

## Identity & Goal

**Who:** Dr. Binzhi Chen, econometrician and PhD graduate.
**Purpose:** Academic personal homepage showcasing research, working papers, and professional identity to other economists, potential employers, and collaborators.
**Tone:** Scholarly, clean, confident — not flashy. Should feel like a top-tier economics job-market site.
**Output:** A single `index.html` file (self-contained, no build step needed).

---

## Personal Info

- **Name:** Binzhi Chen
- **Title:** Senior Research Fellow, Institute for Social and Economic Research (ISER), University of Essex
- **Email:** Binzhi.Chen@essex.ac.uk
- **Phone:** +44 (0)7931 174273
- **GitHub:** https://github.com/Rickchen0910
- **Current site:** https://sites.google.com/view/binzhichen/home

---

## About / Bio

Binzhi Chen is an econometrician specialising in panel data methods, factor models, and machine learning for causal inference. His research develops estimators and software tools that uncover latent group structures and interactive fixed effects in large panel datasets, with applications to income inequality, environmental economics, and macroeconomic dynamics.

He completed his PhD in Economics at the University of Birmingham (Sep 2020 – Jan 2025), supervised by Marco Barassi and Yiannis Karavias. He is now a Senior Research Fellow at ISER, University of Essex, where his work spans Double Debiased Machine Learning, Econometric Theory, and Computational Social Science.

**Research interests:** Panel data models · Grouped fixed effects · Interactive fixed effects · Double machine learning · Factor models · Latent group structures · Computational econometrics

---

## Education

| Degree | Institution | Period |
|--------|-------------|--------|
| Ph.D. in Economics | University of Birmingham, Birmingham, UK | Sep 2020 – Jan 2025 |
| (Prior degrees not listed on site) | | |

**PhD supervisors:**
- Marco Barassi — Associate Professor in Econometrics, University of Birmingham
- Yiannis Karavias — Professor in Finance, Brunel University London

---

## Working Experience

| Role | Institution | Period |
|------|-------------|--------|
| Senior Research Fellow | Institute for Social and Economic Research (ISER), University of Essex, Colchester, UK | Sep 2025 – present |

---

## Research

### Job Market Paper

**Panel VAR Model With Latent Group Structures**

Univariate panel models with interactive fixed effects have been well discussed in previous studies. This paper studies the multivariate panel vector autoregression (PVAR) model with group-based factors. It is flexible: the number of groups, group membership in each group, and the number of group factors per equation are not pre-specified, and the model can be extended to group-specific heterogeneous coefficient Panel VAR. Furthermore, it is a parsimonious structural model that is easy to compute. The paper derives the asymptotic distribution and establishes consistency of the estimator for N and T tending to infinity.

---

### Working Papers

**Double Machine Learning for Static Panel Data Models with Interactive Fixed Effects**
(with A. Polselli and P. S. Clarke)

**xtife: Interactive Fixed Effects Estimator for Panel Data in R** (2026)
An R package implementing the interactive fixed effects estimator for panel data.

**pgfe: Grouped Fixed Effects in Panel Data Models in R** (2026)
An R package implementing the grouped fixed effects (GFE) estimator (Bonhomme & Manresa 2015) for panel data. Available on GitHub.

**Group Patterns in Income Inequality and Economic Growth**
The relationship between income inequality and economic growth has been debated for a long time. This article uses the grouped fixed effects estimator to examine the growth-inequality nexus across countries. Results indicate a non-linear relationship consistent with the Kuznets curve — inequality has a positive impact on growth at low levels but negative at high levels. The paper also reveals heterogeneity in the response of growth to inequality across groups. Results are robust to two different Gini indexes and different model specifications.

**Critical Review of Carbon-Emitting Energy as an EKC Regressor: New Evidence from US State-Level Data**
The introduction of total fossil fuel or energy consumption as a regressor variable has become increasingly common in research on the carbon Kuznets curve (EKC). Given the way CO₂ emissions are calculated, this strategy implies a clear endogeneity problem. The paper proposes an alternative model applied to US state-level panel data, with empirical results showing that bias on the parameters of interest may be important enough to warrant avoiding this common empirical strategy.

---

## References

**Marco Barassi**
Associate Professor in Econometrics
University of Birmingham

**Yiannis Karavias**
Professor in Finance
Brunel University London

---

## Site Structure & Sections

The homepage should have:
1. **Hero / header** — name, title, institution, photo placeholder (or elegant initials avatar), brief tagline
2. **About** — 2–3 sentence bio + research interests as tags/badges
3. **Research** — Job Market Paper (highlighted), then Working Papers as a clean list with short abstracts collapsible or inline
4. **CV** — link to downloadable PDF (placeholder anchor `#`) + inline timeline of education + experience
5. **Contact** — email, GitHub, optionally phone
6. **Footer** — minimal, with "Last updated: March 2026"

---

## Design Preferences

- **Style:** Minimal academic. Think Princeton/Columbia economics faculty pages — typography-forward, no flashy animations.
- **Palette:** Navy or dark slate primary, white background, subtle warm accent (e.g., amber or teal). Academic feel.
- **Typography:** Serif for headings (Georgia, Playfair Display, or similar), clean sans-serif for body.
- **Layout:** Single-page with smooth scroll navigation, or clear section hierarchy. Responsive.
- **No distracting graphics.** Subtle dividers and whitespace do the heavy lifting.
- **Highlight the Job Market Paper** — it should visually stand out from the other working papers.

---

## Key Differentiators vs. Current Site

The current Google Sites page is functional but generic. The new page should:
- Feel professionally designed and distinctly academic
- Give immediate visual priority to the job market paper
- Make contact info and research interests findable in seconds
- Be a single self-contained HTML file, easy to host anywhere (GitHub Pages, university server)
