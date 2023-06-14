# first_venus_white_beam_experiment
First experiment done at VENUS to test the apertures, the beam center, repeatability of some settings...etc.

List of tasks:

* Beam profile (along xy plan, across the images) versus apertures
* Position of the center of the beam versus aperture
* Repeatability of the center position after several openings and closings of the main shutter
* Resolution vs aperture

Feel free to edit the list of tasks. 

Workflows:

# Position of the beam center for various apertures

1. Select images (taken from the same folder)
2. calculate median of images (remove gammas)
3. retrieve various horizontal and vertical profiles using dedicated *profile* notebook from imaging suite
4. develop algorithm that determines the value of the center of the profile