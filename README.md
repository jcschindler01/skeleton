# Skeleton

This package is a skeleton for Python packages allowing:
  - `pip` distribution and installation,
  - sphinx/readthedocs documentation.


[GitHub](https://github.com/jcschindler01/skeleton).
[Docs](https://skeleton-jcschindler01.readthedocs.io/).
[Test Distro](https://test.pypi.org/project/skeleton-JCSCHINDLER01/).


Dev Tips/Steps:
  - Clone from GitHub
  - Local install with `pip install -e .` 
  - To release: `git tag`, `python -m build`, [upload](https://packaging.python.org/en/latest/tutorials/packaging-projects/#uploading-the-distribution-archives)
  - To document: Set up readthedocs to auto update on push. Manually rerun apidoc-rebuild as needed.
  - To test: Download and test in a venv.
