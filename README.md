# Influx

This project is concerned with using timeseries data coming from a drilling rig EDR system.

This project is designed to ultimately enable the user to import the data from a CSV file and to keep track of the estimated volume of fluid influx (or losses) from the well.
Two classes are defined. The first one essentially configures the well design (parameters such as casing set point and ID and hole diameter etc.). An object of this class is passed onto a second class, along with dataframes contaning the EDR data. The second class contains methods to extract volume information needed to perform a simple mass balance and estimate a discrepancy registering it as an influx (or loss).
The project is currently under development and testing.
