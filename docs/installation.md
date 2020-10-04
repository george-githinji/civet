
<section id="banner">
    <div class="content">
      <header>
        <h2>Installation</h2>
        <p>Instructions for installing civet locally</p>
      </header>
    </div>
    <span class="image object">
        <img src="./figures/civet_logo.png" alt="" style="max-width:150px"/>
        </span>
</section>

### Requirements

civet runs on MacOS and Linux. The conda environment recipe may not build on Windows and is not supported but can be run using the Windows subsystem for Linux.

1. Some version of conda, we use Miniconda3. Can be downloaded from [here](https://docs.conda.io/en/latest/miniconda.html)
2. Access to CLIMB or to a local data directory

### Install civet

1. Clone this repository and ``cd civet``
2. ``conda env create -f environment.yml``
3. ``conda activate civet``
4. ``python setup.py install``

> Note: we recommend using civet in the conda environment specified in the ``environment.yml`` file as per the instructions above. If you can't use conda for some reason, dependency details can be found in the ``environment.yml`` file. 


### Check the install worked

Type (in the civet environment):

```
civet
```
and you should see the help menu of civet printed



### Updating civet

> Note: Even if you have previously installed ``civet``, as it is being worked on intensively, we recommend you check for updates before running.

To update:

1. ``conda activate civet``
2. ``git pull`` \
pulls the latest changes from github
3. ``python setup.py install`` \
re-installs civet
If you have previously installed civet using ``pip``, you will need to update civet in the same way (``pip install .``).  
4. ``conda env update -f environment.yml`` \
updates the conda environment 
