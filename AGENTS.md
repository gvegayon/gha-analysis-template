## Overall context

- This is a repository where we include mostly R and Python code.
- The code is built for running epidemiological analyses.

## Coding information

### R

- For R, we like using fewer dependencies.
- For data wrangling, we like `{data.table}`.
- For data visualization, we use `{ggplot2}`.
- Functions should always be documented using `{roxygen2}` comment blocks.
- For testing, we like using `{tinytest}`. Major functions should always include a tinytest test under `tests/`.

### Python

- We use `uv` for managing packages.
- We write functions using type annotations.
