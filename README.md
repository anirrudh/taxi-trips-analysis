# Chicago Taxi Trips Exploration with Dask and Numba
----------
### Abstract
This was originally written with the intent of being a talk about Dask and Numba for PyLadies Chicago, and eventually was split apart.
I hope to present this at many other venues! Here, you can find _all_ the code that has been presented. Due to the wealth of knowledge
associated with each library, I have split the talk into two parts: The first part relates to Dask and how to use it for data exploration,
and the second part will be using Numba with NumPy to build a predictive model and speed it up.

### Binder 
Trying out the notebook in the cloud is possible via binder (to look at the output results of the data). I made certain choices to exemplify
Dask usage. Moreover, the notebook is still in a very primitive state, and needs to be better organized (something I am working on)! In the
meantime, I am also finding a place to make the `.parq` version of the data publically available. Please checkout the binder if you would like to run
it in the browser, just be aware that the data will not load until this readme is updated.


[![Binder](http://mybinder.org/badge_logo.svg)](http://beta.mybinder.org/v2/gh/anirrudh/taxi-trips-analysis/master?filepath=dask_exploration.ipynb)

Press the binder badge above to launch jupyterlab in the browser.

### Local
Clone the Repository, then install all the packages from enviornment.yml with conda. Run jupyter-lab!

### Data
The original, `.csv` dataset can be found online [here](https://data.cityofchicago.org/api/views/wrvz-psew/backups/2019-06-07T21:55:48.207Z), thanks to the City of Chicago, but may not be available. I will
try and upload the dataset myself, but for the time being, this original file should work.

