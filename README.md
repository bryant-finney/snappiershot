# SnappierShot


## Configuration
Snappier shot is following the [trend of packages](https://github.com/carlosperate/awesome-pyproject/)
in performing project-wide configuration through the pyproject.toml file established by
[PEP 518](https://www.python.org/dev/peps/pep-0518/).

Within the pyproject.toml file, all snappiershot configuration can be found under the
`[tool.snappiershot]` heading.

### Example (with default values):
```toml
[tool.snappiershot]
file_format = "json"
significant_figures = 6
float_absolute_tolerance = 1e-6
float_relative_tolerance = 0.001
```
