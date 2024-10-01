# SenseCrypt-Walkthrough

This walkthrough gives you hand on expierence on using SenseCrypt eID and SenseCrypt FacePKI.
For more in depth information about SenseCrypt, you checkout our [Website](https://seventhsense.ai) or the [SenseCrypt Documentation](https://docs.sensecrypt.com/sensecrypt-v3.1.1).


### Quick Start

The notebooks can all be hosted on Google Colab. If you want to run the notebooks in the local environment, you can set up the environment as shown below in the command line:

To set up a virtual environment (Recommended, below shows an example to set up virtual environment using [virtualenvwrapper](https://virtualenvwrapper.readthedocs.io/en/latest/)):

```
pip install virtualenvwrapper
mkvirtualenv sensecrypt-walkthrough # Create a new virtual environment called sensecrypt-walkthrough 
workon sensecrypt-walkthrough # Activate the created virtual environment
```

To install the dependencies:

```
pip install -r requirements.txt
```

To deactivate the virtual environment:
```
deactivate 
```

To remove the virtual environment (If you no longer need it):
``` 
rmvirtualenv sensecrypt-walkthrough
```

### 1.1 Overview

This walkthrough is split up in 6 chapters. The chapters build upon each other,  you need to go through them in order.

1. [Chapter 1_ Charlie gets an ID (eID)](https://colab.research.google.com/github/Seventh-Sense-Artificial-Intelligence/SenseCrypt-Walkthrough/blob/main/Chapter%201_%20Charlie%20gets%20an%20ID%20(eID).ipynb)
1. [Chapter 2_ Charlie wants a loan (eID)](https://colab.research.google.com/github/Seventh-Sense-Artificial-Intelligence/SenseCrypt-Walkthrough/blob/main/Chapter%202_%20Charlie%20wants%20a%20loan%20(eID).ipynb)
1. [Chapter 3_ Charlie signs up for Petflix (FacePKI)](https://colab.research.google.com/github/Seventh-Sense-Artificial-Intelligence/SenseCrypt-Walkthrough/blob/main/Chapter%203_%20Charlie%20signs%20up%20for%20Petflix%20(FacePKI).ipynb)
1. [Chapter 4_Charlie_signs into Petflix (FacePKI)](https://colab.research.google.com/github/Seventh-Sense-Artificial-Intelligence/SenseCrypt-Walkthrough/blob/main/Chapter%204_Charlie_signs%20into%20Petflix%20(FacePKI).ipynb)
1. [Chapter 5_Petflix sends Charlie a catbond meme (FacePKI)](https://colab.research.google.com/github/Seventh-Sense-Artificial-Intelligence/SenseCrypt-Walkthrough/blob/main/Chapter%205_Petflix%20sends%20Charlie%20a%20catbond%20meme%20(FacePKI).ipynb)
1. [Chapter 6_Charlie decrypts catbond meme (FacePKI)](https://colab.research.google.com/github/Seventh-Sense-Artificial-Intelligence/SenseCrypt-Walkthrough/blob/main/Chapter%206_Charlie%20decrypts%20catbond%20meme%20(FacePKI).ipynb)
