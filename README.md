# UB Tagger CROI

Current repository structure makes little sense.  The tagger code currently lives in the larlitecv repository.

However, larlitecv is better thought of as a tool for reading larcv/larlite data together. The tagger code is a big application that uses the tool.

This repository is an attempt to make the structure more sane. The code in the tmw_muon_tagger branch is moved to this repo. larlitecv is treated like a dependency.