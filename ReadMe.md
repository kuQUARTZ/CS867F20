# CS867: Computer Vision

This repository contains the released assignments for the Fall 2020 offering of CS 867 Computer Vision Elective Course. 

The assignments cover a wide range of topics in computer vision and should expose students to a broad range of concepts and applications. Thaere is rich set of image processing and machine learning libraries available in Python. During this and following cources the students will be trainined to use them with the help of assignments. 

A comprehensive list of Python libraries and packages used for computer vision can be seen [here](https://opensource.com/article/19/3/python-image-manipulation-tools). 

Saveral electronic books are provided in a google drive, the link is shared on LMS. These books can be an excellent resource for the beginers as well as for the experts. 

**Assignment 1** starts off with an introduction on how to use images in python and numpy. It focuses on understanding and implemting the basic concepts such as image manipulation operation using matrices, convolutions, different kernels and how to design them and edge detection e.t.c. A couple of extra credit questions are also there.

## How do you download the assignments?

All the assignments will be released via github. You can download the files directly from the website. The link will be shared on LMS also. 

## Assignment Submission Instructions

After you have completed each assignment, you need to submit the following deliverables:

1: Assignment_*.pdf - Export the Assignment*.ipynb ipython notebook as a PDF and submit it to LMS. In order to export notebook as a PDF, you will need to install [additional libraries](https://nbconvert.readthedocs.io/en/latest/install.html#installing-nbconvert).

2: Assignment_*.ipynb 

3: *.py - All the python files we ask you to code up must be submitted to LMS

Place all files in a folder. Rename the folder as *Your FirstName_Your LastName*, zip it and submit on LMS. 

**Please make sure that the code must run without errors, because it will be marked by automated scripts. NO credit will be given if code fails to run properly.**

## How to start working on an assignment?
Before working on each homework, you need to setup a few things:

1: **Installing Python 3.6+:** To use python3, make sure to install version 3.6 or 3.7 on your local machine. If you are on Mac OS X, you can do this using Homebrew with [brew install](https://raw.githubusercontent.com/Homebrew/homebrew-core/f2a764ef944b1080be64bd88dca9a1d80130c558/Formula/python.rb). You can find instructions for Ubuntu [here](https://www.digitalocean.com/community/tutorials/how-to-install-python-3-and-set-up-a-local-programming-environment-on-ubuntu-16-04).

2: **Setting up a virtual environment:** we strongly recommend working using a [virtual environment](http://docs.python-guide.org/en/latest/dev/virtualenvs/) for each Assignment. This will allow you to have a working environment with all the package dependencies within the repository of your homework, without messing up your work environment in other repositories.

To set up a virtual environment with name `.env`, run the following inside your Assignments Home directory (ex: inside cs867/Assign1):

```python
  sudo pip install virtualenv        # You will need to do this only once
  virtualenv -p python3 .env         # Creates a virtual environment with python3
  source .env/bin/activate           # Activate the virtual environment
  pip install -r requirements.txt    # Install all the dependencies
  # Work on the assignement for a while...
  deactivate                         # Exit the virtual environment when you're done
```

Note that every time you want to work on the assignment, you should run source .env/bin/activate (from within your assignment folder) to re-activate the virtual environment, and deactivate again whenever you are done.

The above mentioned instructions for virtual environment setup are for UBUNTU. It is a little bit different for Windows.

3 :**Working with Jupyter notebooks:** In your assignment repository, start the *notebook* with the *jupyter notebook* command. You might have issues if you are in a virtual environment, as the notebook might not recognize your virtual environment and might not find the kernel located in .env to execute code. In this case, refer to this page and do the following within your virtual environment:

```python
python -m ipykernel install --user --name=my-virtualenv-name
```
If you are unfamiliar with Jupyter notebooks, you can also refer this [IPython tutorial](http://cs231n.github.io/ipython-tutorial).

When working with a Jupyter notebook, you can edit the ***.py** files either in the Jupyter interface (in your browser) or with your favorite editor (vim, Atom...). Whenever you save a ***.py** file, the notebook will reload their content directly.

## Collaboration Policy
- Study groups are allowed but we expect students to understand and complete their own assignments and to hand in one assignment per student.
- If you worked in a group, please put the names of your study group on your assignment on top.
- Finally, we expect students to not look at implementations online. We take the student Honor Code seriously.
