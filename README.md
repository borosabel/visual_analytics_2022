# Visual Analytics Lab Project
Submission template for the Visual Analytics lab project at the Johannes Kepler University Linz.

**Explanation:**
This `README.md` needs to be updated and pushed to GitHub.
Change/extend the corresponding sections by replacing the [TODO] markers.

For a detailed project spezification look up the [Visual Analytics Moodel page](https://moodle.jku.at/jku/course/view.php?id=20471).

**Tip:** Make yourself familiar with [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

## General Information

### Group Members

| Student ID    | First Name  | Last Name      | E-Mail | Workload [%]  |
| --------------|-------------|----------------|--------|---------------|
| k11814156        | Felix      | Breiteneder         |felix.breiteneder@aon.at  |[25%]         |
| K12227403        | Angelika      | Vižintin         |angelika.vizintin@gmail.com  |[25%]         |
| K12107459        | Andeol        | Albitre          |albitrec@protonmail.com  |[25%]         |
| [k11944603]        | [Abel]      | [Boros]          |[boros.abel99@gmail.com]  |[25%]         |

### Dataset

* What is the dataset about?
* Where did you get this dataset from (i.e., source of the dataset)?
* How big is the dataset?

**Description:**
Our dataset includes numerous statistics about the Covid-19 pandemic in Austria since its beginning. Daily number of infections, hospitalization and deaths are available among different age groups. Moreover, all of the data is aggregatable by states and disctricts. Additionally, the dataset also includes vaccine, test and available hospital beds statistics.

The source for our dataset is: https://covid19-dashboard.ages.at/. It consists of seven individual datasets of which we are going to use five for this project. However, we did also include vaccine statistics from https://www.data.gv.at/katalog/dataset/85d040af-e09a-4401-8d67-8cee3e41fcaa because it was not available via the ages covid dashboard dataset. Finally we included, demographic statistics about Austria from https://www.statistik.at/statistiken/bevoelkerung-und-soziales/bevoelkerung/bevoelkerungsstand/bevoelkerung-zu-jahres-/-quartalsanfang.

The size of our dataset in its raw form consists of six individual datasets. Combined we do have 542,507 row entries. Moreover the total of entry summarizes to 4,380,134 entries.


## General Submission Information

* Make sure that you pushed your GitHub repository and not just committed it locally.
* Sending us an email with the code is not necessary.
* Please update the *environment.yml* file if you need additional libraries, otherwise the code is not executeable.
* Save your executed submission notebooks as HTML and add them to your repository.  
  * Select 'File' -> 'Save and Export Notebook As...' -> 'HTML'
* Upload the exported HTML file on Moodle, if it is required for the submission.

## Usage

### Locally
Checkout this repo and change into the folder:

```shell
git clone https://github.com/jku-icg-classroom/va-project-2022-<GROUP_NAME>.git
cd va-project-2022-<GROUP_NAME>
```

Load the conda environment from the `environment.yml` file, if you haven't already in previous assignments:

```sh
conda env create -f environment.yml
```

Activate the loaded conda environment:

```sh
conda activate python-tutorial
```

Install Jupyter Lab extension to use *ipywidgets* in JupyterLab:

```sh
jupyter labextension install @jupyter-widgets/jupyterlab-manager
```

Launch Jupyter :

```shell
jupyter lab
```

Jupyter should open a new tab with url http://localhost:8888/ and display the tutorial files.



