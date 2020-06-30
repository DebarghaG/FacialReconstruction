# 3D Printing Facial Sculptures

Created: Jun 30, 2020 2:06 PM
Created By: Debargha Ganguly
Last Edited Time: Jun 30, 2020 2:56 PM
Status: Done
Type: Documentation

# Reconstructing my late Grandpa

### What if you could touch and feel their face, with haptic feedback.

While not just being stuck with a photo.

Reference Research Paper : Large Pose 3D Face Reconstruction from a Single Image via Direct Volumetric CNN Regression

**Photogrammetry** is the science of making measurements from photographs. The input to photogrammetry algorithms are usually photographs, and the output is typically a map, a drawing, a measurement, or a 3D model of some real-world object or scene.

In context, most of the maps you see today are created using a similar process, and aerial images.

**Facial 3D reconstruction** is a fundamental problem in Computer Vision, and is really quite difficult, mostly because : 

- Current CV methods, usually use multiple images. For people who have passed away, having pictures from different angles with the same lighting is a luxury.
- There's a number of intense challenges, such as estimating the facial pose, approximating the expression, and the non-uniform illuminations that can result from diffused light.

![3D%20Printing%20Facial%20Sculptures%2010093f6f552d43338eac8ece57e65826/screenshot.png](3D%20Printing%20Facial%20Sculptures%2010093f6f552d43338eac8ece57e65826/screenshot.png)

The researchers have put left a Convolutional Neural Network to do the feature engineering, from the 2D representation to its 3Dimensional one. I won't dive too deep into how this is done, check out the paper if you're interested. 

---

# How you can replicate this

Read the documentation, of how to run this codebase in the *originalreadme.md* file. 

Generate your own CAD model of the face, slice it up and 3D print it.

Keep a few things in mind : 

1. This is a print that takes time. Took my Ender 3 about 26 hours. You might want to consider what happens if your power fails and your printer doesn't have a resume function.
2. Before printing, try a number of different pictures and their resultant which may or may not be optimal. 
3. Print with support (configure it as such when 3D printing), and the orientation you think is the best. 

# Results

![3D%20Printing%20Facial%20Sculptures%2010093f6f552d43338eac8ece57e65826/mimma-dadababa.jpeg](3D%20Printing%20Facial%20Sculptures%2010093f6f552d43338eac8ece57e65826/mimma-dadababa.jpeg)