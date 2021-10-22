# Official Phase Entry code in MATLAB for the PhysioNet/CinC Challenge 2019

## Contents

This prediction code uses three scripts:

* `get_sepsis_score.m` makes predictions on clinical time-series data. 
* `load_sepsis_model.m` loads model weights, etc. for making predictions.  
* `driver.m` calls `load_sepsis_model` once and `get_sepsis_score` many times. 



## Running

You can run this prediction code by starting MATLAB and running

    driver(input_directory, output_directory)

where `input_directory` is a directory for input data files and `output_directory` is a directory for output prediction files.  The PhysioNet/CinC 2019 webpage provides a training database with data files and a description of the contents and structure of these files.

## Details

See the PhysioNet webpage for more details, including instructions for the other files in this repository.
