# BPM Calendar

This Jupyter Notebook serves the purpose of extracting the working days and overall workload for resources of a log register.

Demo logs are provided, 'default.csv' is the standard 5-9 M-F schedule, while 'custom.csv' reduces work hours and days of work.

Both logs are made with [Scylla](https://github.com/bptlab/scylla) and converted to csv with parsers (MXML to XES then to CSV).
Scylla comes with .bpmn files, however, if needed, you can create one in [Signavio](https://www.signavio.com/) if you are an academic.

In order to run the Notebook you only need an [Anaconda](https://www.anaconda.com/distribution/) installation and [Pip](https://pypi.org/project/pip/) for
package management (all libraries used in here are included in the Anaconda installation) only if needed.

Once the Conda promp is launched, navigate to the file directory where this repository is and run:
```bash
jupyter notebook CountDays.ipynb
```
and once the browser shows the notebook, on the Kernel tab, click it and excecute "Restart & Run All" and voilá,
the full notebook will be executed and the data will be displayed.

Soon will be integrated to [Simod](https://github.com/AndreRdz7/Simod) for research purposes.
