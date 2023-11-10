# googlecampus2023
Google Campus 2023 talk resources.

Here you'll find all relevant recourses to be able to run the Jupyter notebook used as support material.

## Environment install

You will need `virtualenv` tool (if isolating the project). Python 3.11 is recommended.

```
$ virtualenv -p python311 venv
$ . venv/bin/activate

(venv) $ pip install jupyterlab
(venv) $ pip install RISE
(venv) $ ln -s venv/lib/python3.11/site-packages/jupyterlab_rise/static static
```

RISE plugin is what allows the notebook to play as a presentation, with slides and sections. It is really interesting to dedicate some time to read about it! 

https://rise.readthedocs.io/en/latest/

> IMPORTANT: the best strategy is to install RISE from within the Jupyter Lab Extension Manager.

## MUSE2 libraries

If you want to test MUSE2 EEG examples, you will need to install muselsl resources (not required for the notebook to work).


