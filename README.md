# hadoop-mapreduce-weather

This MapReduce algorithm analyses data gathered from weather stations (Source: ftp://ftp.ncdc.noaa.gov/pub/data/uscrn/products/).

headers.txt includes a description of the data structure.

The main goals of the algorithm are:
- Present the number of months in which the temperature was above 25 degrees C
- Present the number of months in which the temperature was below 25 degrees C
- Present the number of months in which the difference between maximum and minimum temperatures was above 15 degrees C
