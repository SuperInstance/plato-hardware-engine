# plato-hardware-engine

ParallelPlato + SequentialPlato + PlatoTimeSync + SnappingLogic — hardware ops, time sync, model snapping

## Dependencies

none (standalone)

## Usage

```python
from core.plato_hardware_engine import ...
```

## Shell Loading

This tool can be loaded into any PLATO shell environment:

```python
# Neo loads this tool from the weapon rack
from plato_shell_bridge import PlatoShell
shell = PlatoShell("agent-shell")
shell.load_tool("plato-hardware-engine")
```

## Tests

```bash
python3 -m pytest tests/test_plato_hardware_engine.py -v
```

## License

MIT — Part of the Cocapn Fleet Intelligence System
