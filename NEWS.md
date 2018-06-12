Known issues: https://github.com/PredictiveEcology/fpCompare/issues

version 0.2.2
=============
* update maintainer's email address

version 0.2.1
=============
* update maintainer's email address
* use HTTPS for CRAN urls
* improved vignette formatting (use `rmarkdown::render`)

version 0.2.0
=============
* add `%<<%` and `%>>%` operators ('less than'; 'greater than')
* move `cph` to end of the author field so `aut` displays as first name on CRAN
* fix bug report url in documentation
* improved documentation and formatting:

    - use short urls to avoid links spilling into margins

version 0.1.0
=============
* initial version
* adds new numeric relational operators that do comparisons using a tolerance value:

    - `%>=%`, `%<=%`, `%==%`, `%!=%`

* use `options(fpCompare.tolerance = value)` to set tolerance