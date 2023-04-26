# preprocess-birdbrains
Library for preprocessing jointly recorded neural and behavioral data, putting it in standard NWB format

-------
Functionality needed:

- Specify filenames 
- functionality for converting between hdf5, nwb?

Filestructure:
BirdID
--day1
|    |-----session 1
|    |        |-.wav
              |-.mat (calcium)
              |-metadata
                |-recording time
                |-date
                |-age of bird
                |-nFrames?
     |
     |------session 2
      ...
|    
|
--day 2
|    
.....
