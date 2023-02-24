# Faking Sensor Noise Information

This is a continuation of my master's thesis that was conducted by myself at SJSU under the guidance of Chris Pollett. For more information about the work that I conducted previously, visit this URL for more info: http://www.cs.sjsu.edu/faculty/pollett/masters/Semesters/Fall21/justin/index.php?Bio.php#top

-----

This project will attempt to improve on the following:
* Clean up the data processing pipeline
* Improve model design to use more Keras functions
* Improve PRNU extraction method (will need to read more research papers)
* Determine whether to use cropping windows since whole PRNU image dimensions have to be spoofed. If the window or image is scaled down, then the PRNU fingerprint will have to be upscaled and still be able to fool the discriminator.
* Use CUDA-NN to speed up model run time
* Attempt to use Auxiliary Classifier Generative Networks (AC-GAN)
