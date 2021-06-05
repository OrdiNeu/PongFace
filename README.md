# PongFace
Play pong with your face! Watch my two roommates play a few rounds below:

<img src="2020-04-29_PongWithFaces.gif" alt="demo" style="width: 640px;" />

**[Play here](https://ordineu.github.io/PongFace/index.html)**

## What is this?

This is based heavily off of [Paruby's Snake-Face](https://github.com/paruby/snake-face)

Like it, I use [MediaPipe Facemesh](https://github.com/tensorflow/tfjs-models/tree/master/facemesh) to estimate the positions of faces in real time. Unlike Snake-Face, I don't really care about the facing of each face (though maybe I could use it for some pseudo-3D-pong? Ideas for later!). Face-Mesh can be a little shaky at times (or I'm not using it right?) so try and have a very generic facial expression the entire time for best results. Motion blur might also interfere with FaceMesh. 

Also in the time since I wrote this, FaceMesh looks to be deprecated. Whoops!

