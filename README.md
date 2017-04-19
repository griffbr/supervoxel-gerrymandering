# supervoxel-gerrymandering
SVXGRM: Video Object Segmentation using Supervoxel-Based Gerrymandering
Authors: Brent Griffin and Jason Corso
Contact: griffb@umich.edu
Date: 2017-03-27
Version: 1.0

This is the source code implementation for the following paper (cite this paper):
Griffin, B. and Corso, J. "Video Object Segmentation using Supervoxel-Based Gerrymandering"
http://arxiv.org/abs/1704.05165

-------------------------------------------------------------------------------------------

Files:

demo.m - Demonstration of Supervoxel-Based Gerrymandering given images in the exampleTrial directory.
SVXGRM.m - Performs video object segmentation given directory information and configuration settings.

Notes: 

Supervoxel images are included with the examples but must be generated for new videos (see LIBSVX below).
MVSO algorithm can be run using video images alone.
Output annotations exhibit slight variations each time optical flow data is re-processed due to stochastic processes.

Have fun!

-------------------------------------------------------------------------------------------

Included External Files:

C. Liu. Beyond Pixels: Exploring New Representations and Applications for Motion Analysis. Doctoral Thesis. Massachusetts Institute of Technology. May 2009.
	Optical Flow
	https://people.csail.mit.edu/celiu/OpticalFlow/
	
R. Margolin, L. Zelnik-Manor and A. Tal. "What Makes a Patch Distinct" in CVPR 2013
	Visual Saliency
	http://cgm.technion.ac.il/Computer-Graphics-Multimedia/Software/DstnctSal/


Recommended External Files:

LIBSVX: A Supervoxel Library and Benchmark for Early Video Processing
	Necessary for generating supervoxels for new videos.
	http://web.eecs.umich.edu/~jjcorso/r/supervoxels/

DAVIS: A Benchmark Dataset and Evaluation Methodology for Video Object Segmentation
	Includes 50 diverse videos with ground truth annotations and evaluation code.
	http://davischallenge.org/code.html
