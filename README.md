# Analysing grey seal movement tracks in the North Sea (2008)

This is a repo for using ```MovingPandas``` to analyse the movement of a seal and make a map for the #30DayMapChallenge "Movement" theme!

![seal gif](seal_a_better_place.gif)


## Libraries
```MovingPandas``` was the primary library used for data analysis alongside ```Imageio``` and ```OpenCV``` for gif/video creation. All libraries used are listed below:
- MovingPandas
- GeoPandas
- Pandas
- Datetime
- Holoviews
- Imageio
- OpenCV

## Notebooks
- The ```data_exploration.ipynb``` notebook is what I used to experiment with MovingPandas.
- The ```gif_ims.ipynb``` is for plotting and saving out imagery to make into gifs/videos (```if_gif_ims_interrupted.ipynb``` was a quick fix for if gif_ims stopped running unexpectedly).
- The ```animation_creator.ipynb``` notebook is to make gifs or videos from a folder of images (i.e. what was created with ```gif_ims.ipynb```)

## The data used here is from Movebank:

Data package citation:
McConnell BJ (2019) Data from: State-switching continuous-time correlated random walks. Movebank Data Repository. https://doi.org/10.5441/001/1.m7j2263r

These data are described in the following written publications:
Michelot T, Blackwell PG (2019) State-switching continuous-time correlated random walks. Methods in Ecology and Evolution. https://doi.org/10.1111/2041-210X.13154

Relevant data info from Michelot T, Blackwell PG (2019):

- "Trajectory of 2,535 observations, collected in the North Sea between April and December 2008".
- "The base sampling frequency was of one location every 30 min, but many fixes were missed, and the resulting time grid was highly irregular...".