# Step Type Detection using Pedometer Data

## Overview
- Preprocessed and normalized data used in Step Type Detection using Pedometer Data
- Original data sourced and manually labeled by Ryan Mattfeld
- Data cleaned and augmented by Chadd Brenner

- R. Mattfeld, E. Jesch, and A. Hoover, “A new
dataset for evaluating pedometer performance,” in 2017
IEEE International Conference on Bioinformatics and
Biomedicine (BIBM), IEEE, 2017

## Details
- P001 - P030 refers to individual participants in the original study
- Regular, Irregular, and SemiRegular refers to the environment where that data was collected from. For more information, refer to the original paper sourced above
- Files contain data from the wrist, hip, and ankle (sensor01, sensor02, sensor03) and contain accelerometer and gyroscope data in the X, Y, and Z orientiations for each sensor. Each sensor entry also contains the timestamp.
- The sensor used was the Shimmer 3.
- The data has already been normalized, synced at the beginning and end of the files, and interpolated in situations where the sensor failed to record data on it's regular interval (15hz, 67ms)
