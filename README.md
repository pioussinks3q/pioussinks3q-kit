# pioussinks3q-kit

Summarize numeric CSV columns (n / min / max / mean).

Small, dependency-free Python utility package generated for day-to-day file chores.
Standard library only — no third-party imports.

## Install

```bash
pip install -e .
```

## Usage

```bash
python -m pioussinks3q_kit.cli --help
```

```python
from pioussinks3q_kit.core import Pioussinks3qTool

tool = Pioussinks3qTool()
print(tool)
```

## Layout

```
pioussinks3q_kit/
  __init__.py
  core.py
  cli.py
tests/
  test_core.py
```

## License

MIT © 2026 pioussinks3q
