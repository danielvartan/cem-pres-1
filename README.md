# cem-pres-1

<!-- badges: start -->
[![Project Status: Inactive – The project has reached a stable, usable state but is no longer being actively developed; support/maintenance will be provided as time allows.](https://www.repostatus.org/badges/latest/inactive.svg)](https://www.repostatus.org/#inactive)
[![License: GPLv3](https://img.shields.io/badge/license-GPLv3-bd0000.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/license-CC_BY--NC--SA_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
<!-- badges: end -->

## Overview

This repository contains the slides from the presentation _AcessoSAN Data Plan_, delivered on October 16, 2025, at the [Center for Metropolitan Studies](https://centrodametropole.fflch.usp.br/).

The slides are available [here](https://danielvartan.github.io/cem-pres-1/).

## How to Use

This presentation was created using the [Quarto](https://quarto.org/) publishing system and the [R](https://www.r-project.org/) programming language. To build the slides locally, you will need to have these tools installed on your computer.

The [`renv`](https://rstudio.github.io/renv/) R package is used to manage the R package dependencies. To install the required packages, run the following commands in your R console before rendering the slides:

```r
# install.packages("renv")
renv::restore()
```

After installing the dependencies, you can render the slides by executing the following command at the project root directory in your terminal:

```bash
quarto render
```

This will generate the slides in the `docs` directory.

## How to Cite

To cite this work, please use the following format:

Vartanian, D. (2025). *AcessoSAN Data Plan* \[Presentation\].
<https://danielvartan.github.io/cem-pres-1>

A BibTeX entry for LaTeX users is:

``` latex
@Misc{vartanian2025,
  title = {AcessoSAN Data Plan},
  author = {{Daniel Vartanian}},
  year = {2025},
  url = {https://danielvartan.github.io/cem-pres-1},
  langid = {en},
  note = {Presentation}
}
```

## License

[![License: GPLv3](https://img.shields.io/badge/license-GPLv3-bd0000.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/license-CC_BY--NC--SA_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

The code in this repository is licensed under the [GNU General Public License Version 3](https://www.gnu.org/licenses/gpl-3.0), while the report is available under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-nc-sa/4.0/).

``` text
Copyright (C) 2025 Daniel Vartanian

The code in this report is free software: you can redistribute it and/or
modify it under the terms of the GNU General Public License as published by the
Free Software Foundation, either version 3 of the License, or (at your option)
any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A
PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with
this program. If not, see <https://www.gnu.org/licenses/>.
```
