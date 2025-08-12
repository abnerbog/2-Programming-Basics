# 2-Programming-Basics

You can view this chapter in a rstudio session in your browser by following this link: https://mybinder.org/v2/gh/VT-Hydroinformatics/2-Programming-Basics/master?urlpath=rstudio

## Setup for building site locally with mkdocs

### Installation using `conda`

If you do not already have a `conda`-based package and environment management system, we recommend downloading [Miniconda](https://www.anaconda.com/docs/getting-started/miniconda/main). To set-up the environment configured with the necessary libraries to build the website locally, use the provided `environment.yml` file and run this command in the root directory:

```
conda env create --file environment.yml
```

Note this may take a few minutes to execute. To activate the newly created environment, in the same directory run this command:
```
conda activate mkdocs-quarto-env
```

You have now configured the required packages and environment to build the website locally!


### Building the website using `mkdocs`

[MkDocs](https://www.mkdocs.org/) comes with a built-in dev-server that lets you preview your documentation as you work on it! In the root directory, you can start the server through this command:
```
mkdocs serve
```
You will see a local link to the server in the command line (e.g., `http://127.0.0.1:8000/`) that you can use to view the website. Note that you can keep the server open while making local edits to the documentation. Once you save your changes, your edits will be dynamically added to your local build of the website.
