[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/chekos/censusgeocode-example/HEAD?labpath=geocode_latlong.ipynb)

# censusgeocode-example

A simple example of how to use `censusgeocode` to enrich address/location data.

## Set up

To run this on your browswer just click here [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/chekos/censusgeocode-example/HEAD?labpath=geocode_latlong.ipynb)

**To run this locally**

Clone this repo locally running
```shell
git clone https://github.com/chekos/censusgeocode-example
```

From within the `censusgeocode-example/` folder create a new virtual environment and install the required packages.
```shell
# go to directory
cd censusgeocode-example

# new environment using venv (included with python)
python -m venv .venv

# activate
source venv/bin/activate

# install required packages
python -m pip install -r requirements.txt
```

If you are using VS Code as an editor you can open this directory on VS Code from the terminal by running
```shell
code .
```
from within the directory

## References
- censusgeocode repo (and documentation): https://github.com/fitnr/censusgeocode 
- Pandas documentation on `.iterrows()`: https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.iterrows.html
- Mockaroo for creating fake data: https://mockaroo.com

