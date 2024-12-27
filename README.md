Inputs: 
- chan_204_20200209T034646_vis_real.fits
- chan_204_20200209T034646_vis_imag.fits
- antenna_locations.txt

PartA_imager_20200209_latest.ipynb: 
- Code for calculation of u, v and w coordinates for all the baselines.
- Assignment of the visibilities for the relevant antenna pairs. 

PartB_gridding_20200209_latest.ipynb:
- Grid the visibilities on a regaularly spaced grid.
- Perform a fourier transform on the visibilities to get an image of size: 180 pixels X 180 pixels. 

Input details:
- Telescope: Engineering Development Array 2 (EDA2), 256 antennas (65280 antenna pairs i.e. baselines)
- Visibilities corresponding to a single time and frequency channel.
- Frequency = 159.375 MHz
 
