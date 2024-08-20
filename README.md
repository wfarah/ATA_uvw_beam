# ATA_uvw_beam
Code to compute UVWs and simulate synthesized beam patterns

Dependencies
------------
- numpy
- scipy
- pandas
- pytoml
- astropy

To modify, comment/uncomment antennas in the `telinfo_ata.toml` file. Coordinates of source, time and length of observation can be modified inside the script

Example plots:
--------------
The above script should generate the following plots; UV coverage and simulated beam pattern (amongst others) for a 6h track of the calibrator 3c286 at 3GHz:

<img width="1103" alt="Screenshot 2024-08-20 at 1 16 33 PM" src="https://github.com/user-attachments/assets/f6200872-931a-4710-b566-9e6d4d9f5f24">

</br>
</br>
</br>

<img width="1152" alt="Dirty beam w/ primary beam attenuation" src="https://github.com/user-attachments/assets/1654019e-0f8d-4e54-8708-8ae2e3d43607">
