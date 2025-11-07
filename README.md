# TAO-R³ • Temporal–Agentic–Ontological Relativity in 3D

**TAO-R³** is an interactive web application for exploring how worldviews, philosophies, and spiritual traditions occupy a shared 3-dimensional conceptual space.

Each axis represents one fundamental dimension of thought:

| Axis | Meaning | Range |
|------|----------|-------|
| **T (Temporal Orientation)** | Linear / Teleological ↔ Cyclical / Rhythmic | −1 → +1 |
| **A (Agency Orientation)** | Deterministic / Constrained ↔ Volitional / Participatory | −1 → +1 |
| **O (Ontological Continuity)** | Transcendent / Dualistic ↔ Immanent / Relational | −1 → +1 |

The project provides:
- a self-assessment questionnaire that locates a participant’s position in TAO-space,
- 3D reference plots of historical **religions, philosophies, and mystic traditions**,  
- a complementary dataset of **thinkers, scientists, and political figures**,  
- interactive toggles for color modes, time evolution, trend ribbons, and more.

---

## 🚀 Features

- **3D scatterplot** powered by [Three.js](https://threejs.org/)
- **Orbit controls** for rotation, zoom, and panning
- **Dynamic color modes**  
  - Category (religion / philosophy / mysticism / modern / politics / science)  
  - Time (historical gradient)  
  - Axis (T / A / O value ramp)
- **Time slider** — scrub through history and watch thought evolve
- **Trend ribbons** — smooth Catmull–Rom splines showing conceptual attractor paths
- **Dataset toggles** — enable/disable Traditions vs Figures layers
- **Theme toggle** (light/dark)
- **Exportable scores** (CSV, JSON)

---

## 📊 Conceptual background

TAO-R³ models how systems of belief and understanding organize around stable attractors in human thought.  
In the current dataset, two primary “arches” emerge:

- **Linear–Transcendent attractor** — Abrahamic and modern progress traditions  
- **Cyclical–Immanent attractor** — Asian, animist, and ecological systems

Philosophers, scientists, and leaders align along the same curvature, suggesting a shared cognitive manifold linking spirituality, philosophy, and modernity.

---

## 🧪 Future directions

- **Longitudinal trajectories** — track individuals’ TAO positions across life stages or interventions  
- **Substance / therapy studies** — test how psychedelics, meditation, or trauma alter TAO coordinates  
- **Population density mapping** — compare cohorts or cultures  
- **Integration API** — store responses, compute deltas, render personal vectors

---

## 🛠️ Tech stack (WIP)

### For POC

| Component | Purpose |
|------------|----------|
| **HTML / CSS / Vanilla JS (ES modules)** | Front-end and questionnaire logic |
| **Three.js** | 3D rendering and camera controls |
| **Catmull–Rom Spline (TubeGeometry)** | Trend ribbon visualization |
| **CSV inline data** | Reference datasets (no CORS issues) |

### Upcoming

This will be converted to a Ruby on Rails backend with PostgreSQL. The front end will be cleaned up and refactored into React/Typescript.

---

## 📂 Project structure

