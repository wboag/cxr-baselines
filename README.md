# cxr-baselines
Baselines for generating radiology reports on the MIMIC-CXR chest x-ray dataset.

Use

    $ ssh -L 8095:localhost:8095 night    # for various values of 8095 

    $ cd /scratch/wboag/2019/cxr/cxr-baselines

    $ . venv/bin/activate

    $ ipython notebook --no-browser --port=8095
    
    
    Overview
    
        build_similarities_matrix.ipynb 
            - load the image embeddings, and create img_id -> [img_id] top-100 nearest neighbors
            - /crimea/wboag/2019/cxr/camera_ready_top100.pkl
            
            
            
            
