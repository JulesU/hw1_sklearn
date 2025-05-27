# hw1_sklearn

Information on using my homework

Development workflows
=======================

Create new project
----------------------

Ran:

```bash
cookiecutter
 gh:JulesU/hw1_sklearn
```

Put project under version control
---------------------------------

Added files to my git foler

```bash
git init
git add *.ipynb
git add *.md
git add output/*.html
git commit -m "Initial commit"
```

For the remote repository, make a github repository named hw1_sklearn, then do;

```bash
git remote add origin git@github.com:JulesU/hw1_sklearn.git
git branch -M main
git push -u origin main
```

Version control is good.

Once done with notebook, notes, and readme file changes, ran again from command line::

git push -u origin main

Folder structure
-----------------

Here's the folder structure that gets created by `cookiecutter-datascience-simple`:

	├── hw1_sklearn	<- Your notebooks and scripts will live in the main project folder
		│   .gitignore					<- Common file types for git to ignore
		│   README.md					<- The top-level README for developers (you) using this project
		│   template-nb.ipynb			<- A Jupyter notebook template
        |   hw1_sklearn_jurbano.ipynb   <- Jupyter notebook of my finished hw
		│
		├───data						<- Final and intermediate data
		│   └───raw						<- The original, immutable data dump
		│
		├───docs
		│       notes.md				<- Simple markdown template for project notes
		│
		└───output
				readme.md				<- Guidance for using this folder


Documentation
--------------

In this very simple project structure template, I included a markdown file (notes.md) with some section headings to use for project notes.


