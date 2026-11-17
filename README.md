# Statistical Process Control Analysis of Semiconductor Manufacturing Data

Applying statistical process control (SPC) techniques in Python to real production data from a semiconductor manufacturing line, to identify process variables linked to product failures.

## Data
SECOM dataset (1,567 production runs, 590 sensor measurements, pass/fail labels), available from the UCI Machine Learning Repository: https://archive.ics.uci.edu/dataset/179/secom

Download and unzip it into a `data/` folder before running the notebooks.

McCann, M. & Johnston, A. (2008). SECOM [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C54305

## Progress
- [x] Data loading, exploration and cleaning
- [ ] Identifying sensors associated with failures
- [ ] Control charts and out-of-control detection
- [ ] Process capability analysis and DMAIC write-up