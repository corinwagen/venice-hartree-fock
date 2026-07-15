# Venice Hartree–Fock

What if tourists in Venice behaved like electrons around nuclei? This project
turns that analogy into a small, numerical restricted Hartree–Fock calculation:
landmarks attract, tourists repel, and walking contributes kinetic energy.

The guided, executable lesson is in
[`venice_hartree_fock.ipynb`](venice_hartree_fock.ipynb). It includes the model,
the equations, convergence checks, map overlays, and suggested experiments.

## Run it

With [uv](https://docs.astral.sh/uv/) installed:

```bash
uv sync
uv run jupyter lab venice_hartree_fock.ipynb
```

Then use **Run → Run All Cells**. The checked-in notebook also contains outputs
from a reference run.

## Map attribution

`assets/venice_map.png` is *Venezia-map 1-1220x900.png* by Wikimedia Commons
user Luestling, licensed under
[CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/). The original
and full attribution are available on the
[Wikimedia Commons description page](https://commons.wikimedia.org/wiki/File:Venezia-map_1-1220x900.png).
The image is included unmodified.

The numerical model, annotations, and code are educational abstractions and
must not be used for navigation or crowd management.
