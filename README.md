# Face13 Segmentation
BIDS structure and script for segmentation of BIDS-Lossless-EEG derivative of Face13 dataset.

## How to Run: Face and house, both upright and inverted
1. Inside of a `BIDS-Lossless-EEG` folder, run `mkdir derivatives`
2. Enter new directory with `cd derivatives`. Your current path should look like the following: `Dataset/derivatives/BIDS-Lossless-EEG/derivatives`
3. Run the following inside of the terminal: `git clone https://github.com/BUCANL/BIDS-Seg-Face13-EEGLAB.git`
4. Launch matlab, and point it to the root dataset, e.g. `Face13`
5. Inside of the matlab command window, add install folder for Lossless to the path: `addpath derivatives/BIDS-Lossless-EEG/code/install`
6. Run paths initializer script: `lossless_path`
7. Start eeglab: `eeglab`
8. To run the segmentation use the batch_context EEGLAB extension to execute the "seg_face_house_up_inv.htb" script (located in 'derivatives/BIDS-Seg-Face13-EEGLAB/code/scripts') on the *.edf files in the BIDS-Lossless-EEG derivatives directory.
