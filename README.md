# Prototype 1
[![Metaball Visual So Far](https://img.youtube.com/vi/BM3qe0Q5glw/0.jpg)](https://www.youtube.com/watch?v=BM3qe0Q5glw)

* Mercury animation with metaballs to capture data movements from t-SNE

Built with:
* [Unreal Engine](https://www.unrealengine.com/en-US/what-is-unreal-engine-4)
* [Metaballs Plugin](https://github.com/andyrst/ue4_metaballs)

### Data Pipeline

<p float="center">
  <img src="https://github.com/backslashart/backslashart.github.io/blob/master/assets/images/initialview.png" width="150" />
  <img src="https://github.com/backslashart/backslashart.github.io/blob/master/assets/images/blurring.gif" width="150" /> 
  <img src="https://github.com/backslashart/backslashart.github.io/blob/master/assets/images/3dmap.png" width="150" />
  <img src="https://github.com/backslashart/backslashart.github.io/blob/master/assets/images/topview.png" width="150" />
  <img src="https://github.com/backslashart/backslashart.github.io/blob/master/assets/images/morphing.gif" width="150" />
</p>
I developed a pipeline that takes in images from GANs and outputs dynamic motions that mimic the behaviors of liquid. From left to right, the images show each step of the process. First, GANs produce a static image. A gaussian blur transforms the static image, creating a smooth image with more cohesion. The brightness in each pixel is used as a third axis value for the heightmap. Finally, the pipeline iterates over each contour plot. 

# Prototype 2
[![Navier Stokes Velocity](https://img.youtube.com/vi/4wI4yDbP9sk/0.jpg)](https://youtu.be/4wI4yDbP9sk)
[![Navier Stokes Density](https://img.youtube.com/vi/zw3U7I0rC7E/0.jpg)](https://youtu.be/zw3U7I0rC7E)

I developed an interactive prototypes that use the Navier Stokes equations simulate the motions of fluids in Processing. The first video demonstrates the velocity field that changes according to external forces. You can see how the velocity propagates and finds an equilibrium. The second video shows the density field on top of the velocity field. As the velocity changes, the density also changes in a way that is very similar to a liquid. The models were built in Python. 

Built with:
* [Python Mode for Processing](https://github.com/jdf/processing.py)

# Prototype 3

![Alt Text](https://github.com/hyunjacoblee/-art_prototype/blob/master/prototype.gif)

Based on the audio input, the center figure changes its shape. It also adapts to verbal commands: "bigger" and "smaller." The demo is available [here](https://bit.ly/prototype_jacob), preferably on Chrome. In order to view it, you can take the following steps: 

* Search “chrome://flags/“ in the address bar
* Search “Autoplay Policy”
* Set it to “No user gesture is required.”
* Search "Experimental Extension APIs"
* Set it to "Enabled"
* Relaunch Chrome
* After viewing it, set the settings back to their previous conditions.

MICROPHONE ACCESS IS REQUIRED. 

Built with:
* [Audio Radial Line](https://bl.ocks.org/alexmacy/a39e1e54f68c45b5e1bb5b27c78908db)
* [Web Speech API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API)

# \Art Fellowship Blog 
* [Link](https://backslashart.github.io/)
