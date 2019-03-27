# What is this?
This script returns the maximum average heart rate during a training session of a fixed length.

This is useful if training for a specific amount of time, like 45 minutes, but the polar training session is longer.

# How to run?
1. Download training session csv from https://flow.polar.com/

2. Run
`python hr.py -csv_dir=sessions/2019_03_26.csv -session_length=45`

`-csv_dir` is the locaiton of the training session csv 

`-session_length` is the length of the training session in minutes 

The output is `>>>max average hr is 157.07`
