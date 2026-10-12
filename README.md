<a href="https://youssefsah05.vercel.app">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/hero-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="./assets/hero-light.svg">
    <img alt="Youssef Sahraoui — Applied mathematics, machine learning and software. Portfolio: youssefsah05.vercel.app" src="./assets/hero-light.svg" width="100%">
  </picture>
</a>

<p align="center">
  <a href="https://youssefsah05.vercel.app"><img src="./assets/buttons/portfolio.svg" alt="Portfolio" height="40"></a>
  <a href="https://youssefsah05.vercel.app/cv/youssef-sahraoui-cv.pdf"><img src="./assets/buttons/cv.svg" alt="CV (PDF)" height="40"></a>
  <a href="mailto:youssef.sahraoui@enpc.fr"><img src="./assets/buttons/email.svg" alt="Email" height="40"></a>
  <a href="https://linkedin.com/in/youssef-sahraoui"><img src="./assets/buttons/linkedin.svg" alt="LinkedIn" height="40"></a>
</p>

I study applied mathematics and machine learning, and build software to explore how models and systems behave. I'm an **MVA student at ENS Paris-Saclay** and an **engineering student at École des Ponts**, with a background in statistics, optimization and computer science. My open-source projects range from physics simulation to on-device speech search and demand forecasting.

<p>
  <img src="./assets/schools/ens-paris-saclay.png" alt="ENS Paris-Saclay" width="220">
  &nbsp;
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/schools/ecole-des-ponts-dark.png">
    <img src="./assets/schools/ecole-des-ponts.png" alt="École des Ponts" width="220">
  </picture>
</p>

> **Seeking a 4–6 month research internship in machine learning, deep learning or NLP, starting April 2027.**
> [Get in touch →](mailto:youssef.sahraoui@enpc.fr)

## Featured projects

### [Septhuit](https://github.com/YoussefSah05/septhuit) · 3D pool, exact physics, trained opponents

<a href="https://github.com/YoussefSah05/septhuit">
  <img src="./assets/projects/septhuit-menu.webp" alt="Septhuit main menu with the sept and huit wordmark over the tournament hall and pool table" width="100%">
</a>

A realism-first 3D pool game built from scratch in C++20 and OpenGL, without a game engine. Formerly *Billiards Saloon*.

- **Event-based physics:** sliding, rolling and spin are computed exactly between collisions, and regression-tested against pooltool golden shots.
- **Referee:** WPA rules for 8-, 9- and 10-ball, including breaks, fouls and full matches.
- **Opponents:** they search candidate shots with the same simulator. A 132,951-parameter relational Transformer value network, trained by league self-play, contributes to shot scoring. Its strength is comparable to classical search, not yet better.
- **CI:** builds and tests on macOS, Ubuntu and Windows.

<p>
<img src="./assets/technology/cplusplus20.png" alt="C++20" width="32" height="32">
<img src="./assets/technology/opengl.png" alt="OpenGL" width="32" height="32">
<img src="./assets/technology/python.png" alt="Python" width="32" height="32">
<img src="./assets/technology/pytorch.png" alt="PyTorch" width="32" height="32">
</p>

<a href="https://github.com/YoussefSah05/septhuit"><img src="./assets/buttons/repository.svg" alt="Septhuit repository" height="36"></a>
<a href="https://youssefsah05.vercel.app/projects/septhuit/"><img src="./assets/buttons/case-study.svg" alt="Septhuit case study" height="36"></a>

<table>
<tr>
<td width="50%" valign="top">

### [Nova](https://youssefsah05.vercel.app/projects/nova/)

**Turn spoken media into searchable moments.**

<a href="https://youssefsah05.vercel.app/projects/nova/#demo">
  <img src="./assets/projects/nova-search.webp" alt="Nova player with a searchable Whisper transcript beside the video" width="100%">
</a>

A native macOS media player with on-device Whisper captions. Its hybrid dialogue search combines E5 embeddings and SQLite FTS5 using reciprocal rank fusion. A Rust core keeps credentials out of the React webview.

<img src="./assets/technology/rust.png" alt="Rust" width="28" height="28"> <img src="./assets/technology/tauri.png" alt="Tauri" width="28" height="28"> <img src="./assets/technology/react.png" alt="React" width="28" height="28"> <img src="./assets/technology/sqlite.png" alt="SQLite" width="28" height="28">

<a href="https://youssefsah05.vercel.app/projects/nova/"><img src="./assets/buttons/case-study.svg" alt="Nova case study" height="36"></a>

</td>
<td width="50%" valign="top">

### [Supply Chain Control Tower](https://github.com/YoussefSah05/supply-chain-project)

**From sales data to inventory decisions.**

<a href="https://youssefsah05.vercel.app/projects/supply-chain/#demo">
  <img src="./assets/projects/supply-chain-forecast.webp" alt="Forecast explorer with p10–p90 uncertainty bands on synthetic data" width="100%">
</a>

A team-built forecasting and inventory app that grew from a Streamlit prototype into FastAPI and React. Holt smoothing and Monte Carlo sampling produce p10–p90 demand bands, and the codebase has 40 tests.

<img src="./assets/technology/python.png" alt="Python" width="28" height="28"> <img src="./assets/technology/fastapi.png" alt="FastAPI" width="28" height="28"> <img src="./assets/technology/react.png" alt="React" width="28" height="28"> <img src="./assets/technology/sqlite.png" alt="SQLite" width="28" height="28">

<a href="https://github.com/YoussefSah05/supply-chain-project"><img src="./assets/buttons/repository.svg" alt="Supply Chain repository" height="36"></a>
<a href="https://youssefsah05.vercel.app/projects/supply-chain/"><img src="./assets/buttons/case-study.svg" alt="Supply Chain case study" height="36"></a>

</td>
</tr>
</table>

<sub>Nova's preview is a native capture with original sample media. The Supply Chain forecasts use synthetic data, and their figures are illustrative.</sub>

## Research & coursework

| Project | Focus |
|---|---|
| **Optimization in interacting epidemic models**<br><sub>Research intern · CERMICS, École des Ponts · Jun–Aug 2026</sub> | Vaccination allocations in a two-population SIS model, analysed through curvature and Pareto frontiers. |
| **[Performer attention for LLMs](https://github.com/YoussefSah05/Performer-attention-LLM)**<br><sub>M2 research project · with CERMICS and Advansight</sub> | A kernel approach to reduce the computational cost of attention layers in LLMs. |
| **[Quantum PDE simulation](https://github.com/YoussefSah05/quantum-pde-simulation)**<br><sub>Student project · Python</sub> | Simulating quantum PDEs with circuits and numerical methods, with a written report. |

## Toolbox

<p>
<img src="./assets/technology/python.png" alt="Python" width="36" height="36">
<img src="./assets/technology/cplusplus.png" alt="C++" width="36" height="36">
<img src="./assets/technology/rust.png" alt="Rust" width="36" height="36">
<img src="./assets/technology/pytorch.png" alt="PyTorch" width="36" height="36">
<img src="./assets/technology/numpy.png" alt="NumPy" width="36" height="36">
<img src="./assets/technology/pandas.png" alt="Pandas" width="36" height="36">
<img src="./assets/technology/scikitlearn.png" alt="scikit-learn" width="36" height="36">
<img src="./assets/technology/huggingface.png" alt="Hugging Face" width="36" height="36">
<img src="./assets/technology/linux.png" alt="Linux" width="36" height="36">
<img src="./assets/technology/git.png" alt="Git" width="36" height="36">
</p>

**Languages & tools:** Python · C++ · Rust · Linux · Git<br>
**ML & data:** PyTorch · NumPy · Pandas · scikit-learn · Hugging Face<br>
**Mathematics:** Statistics · Convex optimization · Stochastic processes · Machine learning

---

<p align="center">
  <a href="https://youssefsah05.vercel.app"><b>youssefsah05.vercel.app</b></a> ·
  <a href="mailto:youssef.sahraoui@enpc.fr">Email</a> ·
  <a href="https://linkedin.com/in/youssef-sahraoui">LinkedIn</a> ·
  <a href="https://github.com/YoussefSah05?tab=repositories">All repositories</a>
</p>
