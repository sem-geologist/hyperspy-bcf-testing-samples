This folder contains bcf hypermap samples collected on real SEM (Zeiss Sigma FE-SEM equiped with 2 Bruker SSD XFlash|10 eds detectors).

Data in this folder is made available under the Public Domain Dedication and License v1.0 whose full text can be found at: http://www.opendatacommons.org/licenses/pddl/1.0/

P50_situation.bcf is from sample P50 - thin section of Variscan granitoid (Polish Sudetes)
P45* are from sample P45 - the dacite from Polish Sudetes

|files           | describtion
|-----------------|-----------
|P50_situation.bcf| counting rates at levels where bruker instructively packed arrays kicks in. A perfect sample of 12bit and instructively packed pixel mix. The array should be 8bit.
|`   all P45*` | smallest possible size settable on Esprit(100x75), all aquisitions done on the same ROI
|P45_instructively_packed_8bit.bcf| sample with level of counts/pulses where instructive packing is used mostly.
|P45_instructively_packed_8bit_compressed.bcf| -//- compressed.
|P45_12bit_packed_8bit.bcf| sample with short counting time.
|P45_12bit_packed_8bit_compressed.bcf| -//- compressed.
|P45_16bit_compressed.bcf| sample where hypermap aquisition was terminated after any channel in any pixel exceeded 260. It can be used to test 16bit array (>255).
|P45_8bit_compressed_80keV_range.bcf| sample to test if bcf are able to save whole 4096 channel resolution (actual just to v1?)
|P45_job_hyperspy.bcf | mapping aquired using Esprit "jobs" function, which tends to leave out some metadata. In this case all by default empty info bars (Name, Comment...) were filled with some strings.
|P45_the_default_job.bcf| same as above without any additional info filling.
