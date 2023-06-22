# first_venus_white_beam_experiment
First experiment done at VENUS to test the apertures, the beam center, repeatability of some settings...etc.

List of tasks:

* Beam profile (along xy plan, across the images) versus apertures
* Position of the center of the beam versus aperture
* Repeatability of the center position after several openings and closings of the main shutter
* Resolution vs aperture

Feel free to edit the list of tasks. 

# Analysis done

1. For runs with more than 1 image, images were combined using median to improve statistics and remove gammas. 
The neutron imaging notebook called 'combine_all_images_selected' was used to combine the images. (check the notebook **step1_combine_images**)
2. The optimum profile width to use was estimated using notebook **calculate_center_of_beam_vertical_using_different_profile_width**
3. Calculation of beam center for each aperture. Check notebook **calculate_horizontal_and_vertical_center_of_beam_for_all_apertures**
3. Study of beam center stability after several shutter closing/opening. Check notebook **calculate_beam_center_for_300deg_vs_shutter_cycles**
4. Calculate real space beam center (in mm) and the pixel size (using 300deg data sets) Check notebook **calculate_horizontal_and_vertical_center_of_beam_300deg**
