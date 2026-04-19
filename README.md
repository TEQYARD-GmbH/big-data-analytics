# Big Data Analytics

This repository contains code and resources for the Big Data Analytics course. It includes assignments, projects, and lecture materials related to big data processing, analysis, and visualization.

## Getting Started

### Prerequisites

- [Python 3.13+](https://www.python.org/downloads/)
- [Jupyter](https://jupyter.org/install) (or VS Code with the Jupyter extension)

### Setup

1. **Clone the repository**

   ```bash
   git clone <repository-url>
   cd big-data-analytics
   ```

2. **Create and activate a virtual environment**

   ```bash
   python -m venv .venv
   # macOS / Linux
   source .venv/bin/activate
   # Windows
   .venv\Scripts\activate
   ```

3. **Install dependencies**

   ```bash
   pip install -e .
   ```

4. **Launch Jupyter**

   ```bash
   jupyter notebook
   ```

   Then open the relevant notebook (e.g. `Session_01_Practical.ipynb`) in your browser.

> The first cell in each notebook also runs `pip install` for its required packages, so you can alternatively skip step 3 and let the notebook handle it.