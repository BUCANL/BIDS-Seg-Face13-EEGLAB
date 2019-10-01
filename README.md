# Face13 segmentation to face and house both upright and inverted

Script for segmentation of BIDS-Lossless-EEG derivative of Face13 dataset.

Copy this 'BIDS_Seg-Face13-EEGLAB' folder to the 'face13/diruvatives/BIDS-Lossless-EEGLAB/derivatives' folder. 

Use EEGLAB with Matlab working directory set to:

face13/derivatives/BIDS-Lossless-EEG

Add to the Matlab path:

addpath('code/dependencies/eeglab_lossless/');

Then start EEGLAB:

eeglab

To run the segmentation use the batch_context EEGLAB extension to execute the "seg_face_house_up_inv.htb" script (located in 'derivatives/BIDS-Sef-Face13_EEGLAB/code/scripts') on the *.edf files in the BIDS-Lossless-EEG derivatives directory.
