# Cuffless estimation of blood pressure from PPG signals using Transformers

## Year 4 MEng Electrical Engineering Final Year Project (FYP) 2021-2022, Imperial College London, Arijit Bhattacharyya (CID: 01496199)

Welcome to my FYP repository! For my FYP, I have developed several neural network algorithms to perform the cuffless estimation of blood pressure signals from photoplethysmography (PPG) signals. The following links summarise the main work conducted for this FYP:

- [Interim Report](https://github.com/ab10918/FinalYearProject---BP-from-PPG/blob/main/Interim%20Report/main.pdf)
- [Final Report](https://github.com/ab10918/FinalYearProject---BP-from-PPG/blob/main/Final%20Report/main.pdf)
- [Literature Survey matrix](https://github.com/ab10918/FinalYearProject---BP-from-PPG/blob/main/Final%20Report/Literature%20Survey.xlsx)
- [Final Presentation Slides](https://github.com/ab10918/FinalYearProject---BP-from-PPG/blob/main/FYP%20Final%20Presentation.pptx)
- [Code](https://colab.research.google.com/drive/1QfJtCEfesJb9H2lDTL6713bSB-2qGRPy?usp=sharing) (Google Colaboratory link)

## Requirements

This section provides a description of the requirements needed to run the code in the [FYP.ipynb](https://colab.research.google.com/drive/1QfJtCEfesJb9H2lDTL6713bSB-2qGRPy?usp=sharing) Jupyter notebook. Please refer to the Table of Contents tab in Google Colab to quickly navigatee through all the code.

In order to run the first cell, the user must have a Google account and be able to connect their Google Drive storage to the Jupyter notebook. It is also recommend for users to sign up for Google Colab Pro (see [Colab Membership](https://colab.research.google.com/signup)) in order to run the neural network models efficiently.

In order to run the second code cell, the system requirements (library versions) are summarised below:

- [h5py = 2.10.0](https://docs.h5py.org/en/stable/) (HDF5 for Python, library to help store large amounts of signal data at a time)
- [heartpy = 1.2.7](https://python-heart-rate-analysis-toolkit.readthedocs.io/en/latest/) (Heartpy, Python Heart Rate Analysis Toolkit, used in signal preprocessing)
- [wfdb = 3.4.0](https://wfdb.readthedocs.io/en/latest/index.html) (Python waveform-database (WFDB) package, used for raw signal acquisition and plotting)
- [kapre = 0.3.5](https://kapre.readthedocs.io/en/latest/) (Keras Audio Preprocessors library, used for signal preprocessing)
- [tensorflow-gpu = 2.4.1](https://pypi.org/project/tensorflow-gpu/) (Python's Tensorflow library, used for creating neural network models)
- [natsort = 7.1.1](https://pypi.org/project/natsort/) (Python's natural sorting library)
- [pandas = 1.3.1](https://pandas.pydata.org/docs/) (Python's Pandas library, used for data manipulation and numerical analysis)
- [matplotlib = 3.1.3](https://matplotlib.org/stable/index.html) (Python's Matplotlib library, used for data visualisation)
- [scikit-learn = 0.24.2](https://scikit-learn.org/stable/) (scikit-learn library, used for signal processing and machine learning purposes)
- [numpy = 1.18.5](https://numpy.org/doc/stable/index.html) (Python's Numpy library, used for working with arrays)

