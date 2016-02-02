# unity-parallax-2d
Simple script for creating 2d parallax layer in Unity. This is modified from the script in [this article](http://www.gamasutra.com/blogs/DavidDionPaquet/20140601/218766/Creating_a_parallax_system_in_Unity3D_is_harder_than_it_seems.php)

## Usage
Just attach the `ParallaxLayer` script to the specific layer that you want to move relatively to the main camera. Then you can set speed in X and Y direction from 0 to 1. The farther the layer is, the higher the speed. So a layer at infinity will have speed of 1, while the closest layer will have speed of 0.

There's a `TestScene` for an example of how this work.

