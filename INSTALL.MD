# Installation Guide

This project requires **SUMO** and a Python environment with the required dependencies.

---

## 1. Install SUMO

Download and install SUMO from:

https://www.eclipse.org/sumo/

After installation:

- Ensure `sumo` and `sumo-gui` are accessible from your terminal.
- Set the `SUMO_HOME` environment variable.

### macOS / Linux

```bash
export SUMO_HOME=/path/to/sumo
export PATH=$SUMO_HOME/bin:$PATH
```

### Windows

Add the SUMO bin directory to your system PATH.
You can verify installation with:

```bash
sumo --version
```
---

## 2. Python Version
This project requires **Python 3.9 or newer**.

Check your version with:
```bash
python --version
```
---

## 3. Install Python Dependencies
```bash
pip install -r requirements.txt
```
---
## 4. Run the Notebooks

After installation:

```bash
jupyter notebook
```

Open and run:

- `SimpleTraci_FQ.ipynb`
- `Traci_QD.ipynb`