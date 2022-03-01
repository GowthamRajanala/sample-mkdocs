# Documents Website

PLEASE DONT EDIT THE PAGES FROM WITHIN GITHUB.

We are using github pages to render the website. Any modification done directly can make the site behave irrationallly.
Please read the documentation properly before starting

    Note :
    Please always do `git pull` before working on your code and before committing any changes.


## How to start

### Prerequisite :

In order to manually install MkDocs you'll need Python installed on your system, as well as the Python package manager, pip. You can check if you have these already installed from the command line:


```

$ python --version
Python 2.7.16
$ pip3 --version
pip 19.0.3 from /Library/Developer/CommandLineTools/Library/Frameworks/Python3.framework/Versions/3.7/lib/python3.7/site-packages/pip (python 3.7)

```

### Install mkdocs

Install the mkdocs package using pip:
```
pip3 install mkdocs
```

Once Done  Run `mkdocs --version` to check that everything worked okay.
```
$ mkdocs --version
mkdocs, version 1.1 from /Library/Python/3.7/site-packages/mkdocs (Python 3.7)

```
### Install Material for mkdocs
```
pip3 install mkdocs-material

```

### Getting Started

Clone the git repo

```
git clone <---->
```


### Testing the site locally

MkDocs comes with a server . In order to run the site locally  use
```
mkdocs serve

```

Once done Open up http://127.0.0.1:8000/ in your browser, and you'll see the default home page.

### Building the site

Before building the site use

`echo "site/" >> .gitignore` to add the build files to gitignore

Build the site
```
mkdocs build
```

### Commit The Changes
```
git commit -m "test commit"

```

### Push Changes to Master Branch

```
git push origin master
```

### Deploy the changes to Github Pages
```
mkdocs gh-deploy

```

 More details about can be found here [MkDocs](https://www.mkdocs.org/) 