# glider-panel-demo
Demo of how to use holoviz to visualize gliderdata

test on pangeo binder:

[![Binder](https://mybinder.org/badge_logo.svg)](https://aws-uswest2-binder.pangeo.io/v2/gh/scottyhq/glider-panel-demo/main?urlpath=%2Fpanel%2Fapp)

Run locally (note, can take a few minutes for code app to appear due to data loading)
```
git clone https://github.com/dhruvbalwada/glider-panel-demo.git
cd glider-panel-demo 
conda env create -f binder/environment.yml
conda activate gliderviz 
panel serve app.ipynb
# or launch jupyter lab to edit the app with `jupyter lab`
```
