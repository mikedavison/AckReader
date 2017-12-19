# AckReader
Biopac Acqknowledge ( .acq) File Reader
BIOPAC's AcqKnowledge™ software saves its files in a complex binary file format that follows some order of structure, however much of the details of structures are undocumented and mysterious. Older file versions up to 3.9.1 were partially documented in BIOPAC’s Application Note 156. As of writing this AcqKnowledge™ is now up to release version 5.0.1, so there is a huge gap in information for later versions. 
Whilst not all information is understood, there is sufficient information to successfuly read most of the file structures. The understanding ofthe structures so far have been tested on files from version 3.7 all up to 5.0.1. 
This is "work in progress" and I would greatly appreciate any contributions to the body of knowledge.
Soon to be posted:
- Compete description of the file structure
- Sample code (java)

Notes: A huge thanks to Nate Vack for his work on BIOREAD that provided the basis for working out what the file structure is.

BIOPAC and AcqKnowledge are trademarks of BIOPAC Systems, Inc. The authors of this software and information have no affiliation with BIOPAC Systems, Inc, and that company neither supports nor endorses this package. 
