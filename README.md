# reports-bgc-val
Repository that contains HTML reports and plots from BGCVal 2.0

BGCVal 2.0beta00
================

- [Source - temporary fork](https://github.com/valeriupredoi/bgc-val)
- Python 3.9
- modern conda/mamba [environment](https://github.com/valeriupredoi/bgc-val/blob/main/environment.yml)
- full integration with Python 3.9-upgraded auxiliary packages (eg netcdf manipulator by Lee)

How to view `index.html` pages
==============================

Github renders html straight into the browser, with source being any given `index.html`.
For that, one needs to prepend the `https://htmlpreview.github.io/?` before the http address of the `index.html`.

For each of the repos here, open:

### Initial Run (see issue [comment](https://github.com/valeriupredoi/bgc-val/issues/4#issuecomment-1108353175))

https://htmlpreview.github.io/?https://github.com/valeriupredoi/reports-bgc-val/blob/main/bgc-val-initial-report/u-bc179/index.html

### `level2` run for u-bc179

- cwd: `/home/users/valeriu/bgc-val`
- command run analysis: `./analysis_timeseries.py u-bc179 level2`
- command run page generation: `python makeReport.py u-bc179 2010`

https://htmlpreview.github.io/?https://github.com/valeriupredoi/reports-bgc-val/blob/main/bgc-val-level2-report/u-bc179/index.html
