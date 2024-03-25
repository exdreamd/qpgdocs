# QuecPigeon Documentation

Personal notes for QuecPython, designed to make development more convenient and faster.

## Deployment

### Installation

```powershell
python -m pip config set global.index-url https://pypi.tuna.tsinghua.edu.cn/simple
python -m venv .venv
.venv/Scripts/Activate.ps1
python -m pip install --upgrade --requirement ./requirements.txt
```

### Clone

```powershell
git clone https://github.com/exdreamd/qpgdocs.git .
```

### Serve

```powershell
mkdocs --verbose --color serve --clean --strict --config-file ./config.yml --dev-addr localhost:8000
```

### Build

```powershell
mkdocs --verbose --color build --clean --strict --config-file ./config.yml
```
