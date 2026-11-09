# Shake Table MiniSEED Processing

Codespaces-ready Python environment for processing and analyzing seismic MiniSEED data.

## Start in GitHub Codespaces

In the repository, select **Code → Codespaces → Create codespace on main**. The first container setup installs the packages listed in `requirements.txt`.

## Local setup

```bash
python -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
```

On Windows PowerShell, activate with `.venv\Scripts\Activate.ps1` instead.

## Included packages

ObsPy, NumPy, Matplotlib, SciPy, pandas, and pyserial.

> Codespaces cannot directly access USB/COM serial devices attached to your local computer. Use a serial-over-network bridge or run the project locally when direct hardware access is required.
