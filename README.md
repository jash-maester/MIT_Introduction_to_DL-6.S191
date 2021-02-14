# MIT_Introduction_to_DL-6.S191

### ***Not completed yet by me***

# For doing the Assignments Here Are the instructions provided my the instructors on their github repo 
[https://github.com/aamini/introtodeeplearning/](https://github.com/aamini/introtodeeplearning/)

# Opening the labs in Google Colaboratory:

The 2021 6.S191 labs will be run in Google's Colaboratory, a Jupyter notebook environment that runs entirely in the cloud, you don't need to download anything. To run these labs, you must have a Google account.

On this Github repo, navigate to the lab folder you want to run (lab1, lab2, lab3) and open the appropriate python notebook (*.ipynb). Click the "Run in Colab" link on the top of the lab. That's it!

# Running the labs

Now, to run the labs, open the Jupyter notebook on Colab. Navigate to the "Runtime" tab --> "Change runtime type". In the pop-up window, under "Runtime type" select "Python 3", and under "Hardware accelerator" select "GPU". Go through the notebooks and fill in the #TODO cells to get the code to compile for yourself!

# MIT Deep Learning package

You might notice that inside the labs we install the mitdeeplearning python package from the Python Package repository:

```
pip install mitdeeplearning
```

This package contains convienence functions that we use throughout the course and can be imported like any other Python package.

```
>>> import mitdeeplearning as mdl
```

We do this for you in each of the labs, but the package is also open source under the same license so you can also use it outside the class.
