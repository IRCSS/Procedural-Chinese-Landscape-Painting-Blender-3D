Procedural Chinese Landscape Mountain Generator With Geometry Node in Blender 3D
=================

![screenshot](documentation/16By9AsGif.gif)
![screenshot](documentation/ChineseLandscapePainting.gif)

This repo contanis the nodes generating the images you see above. It was made and tested on **Blender version 3.5**. 

If you want a top level explaination of how the stuff are made, you can read my blog post here: https://medium.com/@shahriyarshahrabi/procedural-chinese-landscape-painting-in-geometry-nodes-blender-3d-6417403430e6

## How to use the Repo
=================
Everything is in one scene and in one geometry node. Just select the Plane (bad naming I know), which is at entire object. On it there is a geometry mode modifier, you can simply change the seed to see the effect shown in the video. Also in edit mode you can change the base shape of the plane, to get different aspect ratios in the landscape. 
I havent exposed much of the paramters inside the geometry nodes. You can do that yourself, the nodes are well tidied up, each section has a name so you know how things connect with eachother. Just go to the segment you are interested in, start playing with the paramters there and you can exposed the paramters that are important to you. 

The material is also fully procedural. On the same object, in the material section you can see various materials coloring the various different objects. Just click on them to see the nodes. 

## known issues
=================
A known issue is that the bridges might spawn too close to each other or even worse cross. I havent gotten around solving this, maybe one day when looping is added  to geometry nodes. 
