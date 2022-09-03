## Instructions

- Get dependencies:

      conda env create -f imail.yml
      conda activate imail
    
- Download the [DAVIS 2017 dataset](https://davischallenge.org/davis2017/code.html) and extract it into "images". Make sure to select the 2017 TrainVal - Images and Annotations (480p). The training images will be used as distracting backgrounds.

- Expert demonstratons are available in "expert_datadir". To train agents for each environmnet run:

      python3 imail.py


- The training will generate tensorabord plots in the log folder:

      tensorboard --logdir ./logdir

