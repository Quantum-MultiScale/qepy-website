# QEpy website (Cursor build)

Static documentation site for [QEpy](https://github.com/Quantum-MultiScale/QEpy): Quantum ESPRESSO in Python.

Design follows the [Quantum Multiscale](https://github.com/Quantum-MultiScale/quantum-multiscale) site layout with a **Rutgers scarlet** color palette.

## Preview locally

```bash
cd docs
python3 -m http.server 8080
```

Open [http://localhost:8080](http://localhost:8080).

## Structure

| Page | Description |
|------|-------------|
| `index.html` | Home, architecture overview, contributors |
| `install.html` | Requirements, pip & source install |
| `tutorials.html` | CLI, Python/MPI examples, Jupyter notebook index, videos |
| `source.html` | Expanded “The code”: Driver API, Calculator, I/O, repo layout |
| `faq.html` | Troubleshooting |
| `contact.html` | Developers, GitHub, citations |

## Deploy

The site is published from the `docs/` folder on the `main` branch via [GitHub Pages](https://pages.github.com/) at [qepy.rutgers.edu](https://qepy.rutgers.edu/). No build step is required; `docs/.nojekyll` ensures static assets under `_static/` are served as-is.

## Assets

Logo and SCF animation copied from the legacy [qepy-website](https://github.com/Quantum-MultiScale/qepy-website) build output.
