# Image-based anomaly detection for unmanned surface vehicle collision avoidance

In order to use an unmanned vehicle you must be certain that the collision avoidance system can handle all possible situations. In order to take the first steps towards such a system I was tasked by SAAB Kockums and AXIS Communications to create a machine learning algorithm that could find objects in image data which could become an obstacle for an unmanned surface vehicle.

The algorithm that I created for this purpose consists of a few major components namely, a variational autoencoder, superpixel segmentation and stereovision. In its final form the algorithm is able to detect anomalies in image data and subsequently calculate the distance to the object.

A video that was created during early development can be found in this repository.
