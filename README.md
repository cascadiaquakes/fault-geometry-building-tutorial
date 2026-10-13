# Fault Geometry Building Tutorial

[![License: BSD-3-Clause](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg)](LICENSE)

A tutorial for building 3D fault geometries for the CRESCENT Community Fault Model with QGIS and the CRESCENT QGIS plugins.

**Read the tutorial:** https://cascadiaquakes.github.io/fault-geometry-building-tutorial/

---

## Contents

- **Introduction**: overview of the fault geometry workflow
- **QGIS Plugin**: installing and using the CRESCENT QGIS plugins (`QGIS_plugin.md`)

---

## Building Locally

The book is built with [Jupyter Book](https://jupyterbook.org). From the repository root:

```bash
pip install -r requirements.txt
jupyter-book build .
```

Then open `_build/html/index.html`.

---

## Deployment

GitHub Actions builds the book on every push to `main` and publishes it to GitHub Pages.

---

## License

This project is licensed under the BSD 3-Clause License. See [LICENSE](LICENSE).

---

## Contacts

- **CRESCENT CFM team**: [crescentcfm@cascadiaquakes.org](mailto:crescentcfm@cascadiaquakes.org)

For bugs or questions, please [open an issue](https://github.com/cascadiaquakes/fault-geometry-building-tutorial/issues).

---

## Acknowledgments

<table>
  <tr>
    <td align="center" valign="middle">
      <img src="https://raw.githubusercontent.com/cascadiaquakes/.github/main/assets/crescent-circle.png" alt="CRESCENT Logo" width="150" />
    </td>
    <td align="center" valign="middle">
      <img src="https://raw.githubusercontent.com/cascadiaquakes/.github/main/assets/nsf-logo.png" alt="NSF Logo" width="450" />
    </td>
  </tr>
</table>

This project is supported by the National Science Foundation through the Cascadia Region Earthquake Science Center (CRESCENT), Cooperative Agreement EAR-2225286.
