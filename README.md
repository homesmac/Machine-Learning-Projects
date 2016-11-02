# Machine Learning
Included are projects from the Google Dev Machine Learning course. Anaconda was giving me grief so I followed these instructions for getting most of the packages up and running:

Note: sklearn requires scipy, scipy requires numpy and nose

1. download numpy+MKL
"http://www.lfd.uci.edu/~gohlke/pythonlibs/" 
For python 2.7 on windows, grab this one: numpy-1.11.2+mkl-cp27-cp27m-win32.whl (if you have python 3.5, download the one /w 35 in its name). Download this and put it in windows/python27/scripts

2. install numpy+MKL
pip install numpy-1.11.2+mkl-cp27-cp27m-win32.whl
(if you're on python 3.5, look for the '35' in the filename instead of the '27'

3. install nose
pip install nose

4. download scipy
"http://www.lfd.uci.edu/~gohlke/pythonlibs/" 
Download: scipy-0.18.1-cp27-cp27m-win32.whl
Put it in windows/python27/scripts

5. install scipy
pip install scipy-0.18.1-cp27-cp27m-win32.whl

6. install sklearn
pip install sklearn

This is the bulk of what's needed. Anything else which may be missing will be easily found from errors and can easily be installed using pip.
