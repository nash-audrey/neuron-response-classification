# neuron-response-classification
Implementations for classifiying neural responses in the gustatory cortex of mice according to different intraoral stimuli.

This repository contains the implementations and figures in the paper _Cortical Coding of Gustatory and Thermal Signals in Active Licking Mice_ by Audrey N. Nash, Morgan Shakeshaft, Cecilia G. Bouaichi, Katherine E. Odegaard, Tom Needham, Martin Bauer, Richard Bertram, and Roberto Vincis. This paper is available on BioArxiv at https://www.biorxiv.org/content/10.1101/2024.04.27.591293v2.

This material is based upon work supported in part by the NSF under grant DMS2324962, grant number R01 DC-019326 from the National Institute on Deafness and Other Communication Disorders and grant number T32 DC000044.



### Notes:
Keep in mind that as you change the stimuli, all that is necessary is to change the original dataframes neuronDF and LickDF that you import into the first notebook (01- Bayesian Coding Neuron Classification), which should originate from the 'Neuron and Lick data.zip'. Instructions for modifying the code in order to classify different numbers of stimuli are provided.

Files in 'GC taste.zip', 'GC temp.zip' and Somatosensory cortex.zip' are files containing saved data for the analysis/figure creation notebooks. There are many places in the figure creation/ data analysis notebooks where you will need to fill in the path leading to the files in these .zip folders once unzipped, and I find it easiest to keep these seperate instead of merging into a single folder.
