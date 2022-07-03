# FinalYearProject: Cuffless estimation of blood pressure from PPG signals using Transformers, Arijit Bhattacharyya (CID: 01496199)

## Year 4 MEng Electrical Engineering Final Year Project (FYP) 2021-2022, Imperial College London

Welcome to my FYP repository! For my FYP, I have developed several neural network algorithms to perform the cuffless estimation of blood pressure signals from photoplethysmography (PPG) signals. The following links summarise the main work conducted for this FYP:

- [Interim Report](https://github.com/ab10918/FinalYearProject---BP-from-PPG/blob/main/Interim%20Report/main.pdf)
- [Final Report](https://github.com/ab10918/FinalYearProject---BP-from-PPG/blob/main/Final%20Report/main.pdf)
- [Literature Survey matrix](https://github.com/ab10918/FinalYearProject---BP-from-PPG/blob/main/Final%20Report/Literature%20Survey.xlsx)
- [Final Presentation Slides](https://github.com/ab10918/FinalYearProject---BP-from-PPG/blob/main/FYP%20Final%20Presentation.pptx)
- [Code](https://github.com/ab10918/FinalYearProject---BP-from-PPG/blob/main/fyp.ipynb)

## Requirements

MUST HAVE GOOGLE ACCOUNT! COLAB PRO+ recommend to run LSTM and Transformer Encoder for more complex architecture settings

Refer to the second code cell in the Final.ipynb Jupyter notebook for more information. The system requirements are also summarised below:

%pip install h5py==2.10.0
%pip install heartpy==1.2.7
%pip install wfdb==3.4.0
# !git clone https://github.com/MIT-LCP/wfdb-python
# %cd wfdb-python
%pip install kapre==0.3.5
%pip install tensorflow-gpu==2.4.1
%pip install natsort==7.1.1
%pip install pandas==1.3.1
%pip install matplotlib==3.1.3
%pip install scikit-learn==0.24.2
%pip install numpy==1.18.5


- [h5py==2.10.0](https://docs.h5py.org/en/stable/) (HDF5 for Python, library to help store large amounts of signal data at a time)
- [heartpy==1.2.7](https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/install.html)
