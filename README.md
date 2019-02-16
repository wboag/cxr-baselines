# cxr-baselines
Baselines for generating radiology reports on the MIMIC-CXR chest x-ray dataset.

Use

    $ ssh -L 8095:localhost:8095 night    # for various values of 8095 

    $ cd /scratch/cxr-baselines/cxr-baselines

    $ . venv/bin/activate

    $ ipython notebook --no-browser --port=8095
  
Goals
    
    Targeting AMIA submission deadline (March 6). This is feasible, but will require a lot of quick progress.
    
    We need to start writing the paper ASAP. Into, previous work, etc.
    
    https://www.overleaf.com/project/5c6787b4a38eb8400bb4bdc6
    
    As soon as we get results, we can add those as well.


TODO: Writeup

    [] Write intro

    [] Write related work

    [] Write methods section

    [] Write results

    [] Write discussion
    
    [] Write conclusion



TODO: Experiments

    [x] visualize image/caption pairs

    [] KNN (n=1) baseline

    [] standard ngram language model

    [] non-parametric conditional ngram language model

    [] unconditional feedforward predict-based language model

    [] conditional feedforward predict-based language model

    [] evaluation metric: CIDEr, BELU, ROUGE
