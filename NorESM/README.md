# NorESM AeroTools workshop

Here you can find the files associated with the NorESM AeroTools workshop, first held 22.03.2024. The lectures assume that you have access to Lustre/PPI

Each folder holds a separate lecture, in the form of a jupyter notebook. Most of the notebooks can be used to run the tutorial code directly, while some notebooks have command line code, which has to be run in the terminal. 

1. [What is AeroTools?](1/what_is_aerotools.ipynb)
2. [Converting NorESM data](2/converting_noresm.ipynb)
3. ~~Reading data~~
4. [Using PyAeroval](4/pyaeroval.ipynb)
5. [Uploading and viewing on Aeroval](5/Aeroval.ipynb)


## Running the notebooks from Lustre
We will be running all the code in this workshop on lustre. While it is possible to read the notebooks locally and copy the code to PPI, you can also host the notebooks on PPI

Log onto PPI, then activate AeroTools

```
module use /modules/MET/rhel8/user-modules/ 
module load fou-kl/aerotools/aerotools
```

Then run 
```
pya_jupyter notebook --no-browser --ip=$(hostname -f)
```

In the output, you should see two urls. Copy one of them into your browser. You should now see the notebooks in your browser.