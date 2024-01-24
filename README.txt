## Structure of Code 
- 'train.py': train
- ''render.py': rendre the image
- 'convert.py': convert your own dataset to the COLMAP dataset
- 'data/*': input data

##Running
python convert.py -s <path to origin data> [--resize]#If not resizing, --resize is not needed 
python train.py -s <path to COLMAP dataset> -m <path where the trained model should be stored>
python render.py -m <path to pre-trained model> -s <path to COLMAP dataset>
