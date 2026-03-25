# Econ

A code companion for an upcoming book on economics — providing reproducible data analysis, visualizations, and computational models that bring key economic concepts to life using real-world data.

---

## Table of Contents

- [Overview](#overview)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Topics Covered](#topics-covered)
- [Contributing](#contributing)
- [License](#license)

## Overview

**Econ** is a hands-on repository designed to accompany an upcoming book on economics. Each module pulls from publicly available economic data sources (e.g., FRED, BLS, World Bank) and walks through the analysis step by step — from data collection to visualization — so readers can reproduce every chart and table in the book.

Goals of this project:

- Deepen understanding of key economic concepts through code
- Provide clear, reproducible data pipelines and visualizations
- Make economics accessible to programmers and data enthusiasts
- Offer ready-to-run notebooks for interactive exploration

## Project Structure

```
Econ/
├── data/
│   ├── raw/                  # Original, unmodified datasets
│   └── processed/            # Cleaned and transformed data
├── notebooks/                # Jupyter notebooks for interactive exploration
├── src/
│   ├── data_collection/      # Scripts to fetch data from APIs and public sources
│   ├── analysis/             # Statistical models and economic computations
│   └── visualization/        # Chart and graph generation
├── tests/                    # Unit and integration tests
├── docs/                     # Additional documentation and references
├── requirements.txt          # Python dependencies
├── .gitignore                # Git ignore rules
└── README.md
```

## Getting Started

### Prerequisites

- Python 3.9+
- pip

### Installation

```bash
# Clone the repository
git clone https://github.com/espin086/Econ.git
cd Econ

# Create a virtual environment (recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

## Usage

**Notebooks** — Launch Jupyter and explore the interactive notebooks:

```bash
jupyter notebook notebooks/
```

**Scripts** — Run individual analysis modules directly:

```bash
python -m src.data_collection.<module_name>
python -m src.analysis.<module_name>
python -m src.visualization.<module_name>
```

**Tests** — Verify everything works:

```bash
pytest tests/
```

## Topics Covered

| Topic | Description |
|---|---|
| **GDP & Growth** | Measuring economic output and long-run growth trends |
| **Inflation & Prices** | CPI, PCE, and the dynamics of price levels |
| **Labor Markets** | Unemployment, labor force participation, and wage trends |
| **Monetary Policy** | Interest rates, the Federal Reserve, and money supply |
| **Fiscal Policy** | Government spending, taxation, and debt |
| **Trade & Globalization** | Balance of payments, tariffs, and exchange rates |
| **Inequality** | Income distribution, Gini coefficients, and wealth gaps |
| **Financial Markets** | Stock indices, bond yields, and market indicators |

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m "Add your feature"`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

Please ensure any new analysis includes tests and clear documentation.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---

**Author:** JJ Espinoza
