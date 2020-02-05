# BPM Calendar

This Jupyter Notebook serves the purpose of visualizing the working days and overall workload for resources of a log register.

The log is provided in the repo, but it can be obtained via [BIMP](http://bimp.cs.ut.ee/) when provided a .bpmn file (you can
create one in [Signavio](https://www.signavio.com/) if you are an academic). Just replace it in the file directory and you are
ready to use your own dataset.

In order to run the Notebook you only need an [Anaconda](https://www.anaconda.com/distribution/) installation and [Pip](https://pypi.org/project/pip/) for
package management (all libraries used in here are included in the Anaconda installation) only if needed.

Once the Conda promp is launched, navigate to the file directory where this repository is and run:
```bash
jupyter notebook CountDays.ipynb
```
and once the browser shows the notebook, on the Kernel tab, click it and excecute "Restart & Run All" and voilá,
the full notebook will be executed and the data will be displayed.

Soon will be integrated to [Simod](https://github.com/AndreRdz7/Simod) for research purposes.
