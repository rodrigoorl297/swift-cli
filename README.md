# Swift CLI

CLI local para SHA-256 e resumo de JSON. Sem rede, sem credenciais.

```bash
python -m venv .venv
.venv/Scripts/activate
pip install -e ".[dev]"
swift-cli hash examples/sample.json
swift-cli json examples/sample.json
pytest -q
```
