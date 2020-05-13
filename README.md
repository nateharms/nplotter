# `nplotter`: a Jupyter Notebook that creates fun plots of Spotify listening data!

A while back I requested my listening data from Spotify (an online streaming service). Once I got my data, I decided that I wanted to figure out some personal trends that I had and was thinking of a few fun plots to make along the way. These plots are as follows:

- Top 100 Artists
- Monthly listening
- Peak listening for top artists
- Typical weekly listening habits

Below is my code to make this all work, but before you run this you will need the following packages installed:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn` 

You can either install these into your own enviornment or create an `nplt_env` conda environment by running `conda env create -f enviornment.yml`.

To recreate this with your own listening data, simply request your listening data from Spotify ([a tutorial is on this website](https://www.makeuseof.com/tag/download-privacy-data-spotify/)) and move your `StreamingHistoryX.json` files into this directory. And if you have any suggestions of more fun plots, feel free to open issues!
