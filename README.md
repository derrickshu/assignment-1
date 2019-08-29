# Assignment #1

### Due Date: 5pm on 9/5

This week's assignment will be broken into two parts:

## Part 1: Installing Python locally

Follow the [instructions](https://github.com/MUSA-620-Fall-2019/course-materials/blob/master/anaconda-guide/installing-anaconda.md) in the course materials repository for downloading and installing Anaconda locally and creating a new Python environment.

The course materials also includes notes on [getting started with Anaconda](https://github.com/MUSA-620-Fall-2019/course-materials/blob/master/anaconda-guide/managing-packages.md). The [official Anaconda User Guide](https://docs.anaconda.com/anaconda/user-guide/) is recommended reading.

The course materials repository also includes notes on:

- [Managing packages and common `conda` commands](https://github.com/MUSA-620-Fall-2019/course-materials/blob/master/anaconda-guide/managing-packages.md)
- [Commonly encountered problems with Anaconda](https://github.com/MUSA-620-Fall-2019/course-materials/blob/master/anaconda-guide/common-issues.md)

## Part 2: Finding the Philadelphia ZIP Code with the maximum ZHVI over time

Assuming you've successfully installed Python locally, now you can launch a Jupyter notebook with the `musa-620` environment. Notes on this
process can be found [here](https://github.com/MUSA-620-Fall-2019/course-materials/blob/master/anaconda-guide/managing-packages.md#launching-a-jupyter-notebook). For additional help running the notebook, see the tutorial from the [Jupyter documentation](https://jupyter.readthedocs.io/en/latest/running.html#running).

This will create the local Jupyter server. If it does not open in a browser, copy the link that is output by the command into your favorite browser. Once the server is running, you can create a new notebook and get started!

The notebook will execute code from the current working directory (the directory that the notebook was launched from). If using relative file paths to load the data, the path should be relative to this working directory. From within the Jupyter notebook, you can find out the current working directory by running the following command in a cell:

```python
pwd
```

Use a Jupyter notebook to find the Philadelphia ZIP code with the largest average annual ZHVI value, for each year in the data set. The Zillow data is available for download in this repository: [data/Zip_Zhvi_AllHomes.csv](data/Zip_Zhvi_AllHomes.csv).

The Jupyter notebook should use _pandas_ to load the data and analyze it. The following steps should be followed:

1. Load the ZHVI data for each ZIP code, selecting only Philadelphia ZIP codes.
1. Calculate the annual average ZHVI for each ZIP code in Philadelphia and each year.
1. Identify the ZIP code with the maximum value for each year.

The final result should be the year and the ZIP code with the maximum value.

## Submission

### Setting up GitHub for assignment submission

You can submit your assignment through Github. For each assignment, I will provide a GitHub link
that can be used to create a new repostiory. Each student will have their own private repository on GitHub where the assignment can be
submitted. Only the student and instructors will have access to the private repository.

The invitation link for this week is:

https://classroom.github.com/a/DrfpaX86

If you do not have a GitHub account yet, you should be prompted to make an account. After clicking on this link, GitHub will create a new private repo with permissions such that only you and the instructors can view the commits.

The assignment should be added to this GitHub repository before the deadline. You can add files to the repository through the web (github.com) interface or using the command line locally on your machine.

Below are some references if you need help:

- [Setting up git](https://help.github.com/articles/set-up-git/)
- [Managing files on GitHub](https://help.github.com/articles/managing-files-on-github/)
- [Managing files via the command line](https://help.github.com/articles/managing-files-using-the-command-line/)

**Important**: files should be committed to the newly created private repository (after following the above link) and _not_ to your forked version of the [assignment-1](https://github.com/MUSA-620-Fall-2019/assignment-1) repository.

Your Jupyter notebook should be submitted to your private repository by the deadline, 5pm on 9/5.
