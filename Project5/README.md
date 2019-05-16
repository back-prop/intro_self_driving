## Project Overview

Reconstruct the trajectory of a vehicle from the raw data consisting of time, displacement, yaw_rate and acceleration

## Your Job
Your job is to complete the following functions, all of which take a processed data_list (with  𝑁  entries, each  Δ𝑡  apart) as input:

get_speeds - returns a length  𝑁  list where entry  𝑖  contains the speed ( 𝑚/𝑠 ) of the vehicle at  𝑡=𝑖×Δ𝑡

get_headings - returns a length  𝑁  list where entry  𝑖  contains the heading (radians,  0≤𝜃<2𝜋 ) of the vehicle at  𝑡=𝑖×Δ𝑡
get_x_y - returns a length  𝑁  list where entry  𝑖  contains an (x, y) tuple corresponding to the  𝑥  and  𝑦  coordinates (meters) of the vehicle at  𝑡=𝑖×Δ𝑡

show_x_y - generates an x vs. y scatter plot of vehicle positions.
