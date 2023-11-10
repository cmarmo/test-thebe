---
jupytext:
  text_representation:
    extension: .md
    format_name: myst
kernelspec:
    display_name: Python 3
    language: python
    name: python3
---

### This is a test

```{code-cell} python
import numpy as np
np.__version__
```

+++

```{code-cell} python
a = np.arange(4).reshape((2,2))
np.min(a, axis=0)
```
