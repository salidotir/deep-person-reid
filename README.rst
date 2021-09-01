Torchreid
===========
Torchreid is a library for deep-learning person re-identification, written in `PyTorch <https://pytorch.org/>`_ and developed for our ICCV'19 project, `Omni-Scale Feature Learning for Person Re-Identification <https://arxiv.org/abs/1905.00953>`_.

|
|

- Complete implementation code and explanation can be found at   `deep-person-reid <https://github.com/KaiyangZhou/deep-person-reid>`_  .
- You can also find more about the code and how to use it on `this link <https://kaiyangzhou.github.io/deep-person-reid/user_guide.html>`_

|

My Work
===========
This project forked mentioned repository above **deep-person-reid, torchreid,** to use it as base reid-tool.

What I did
-----------
- [X] Modifying the project to get the indices and ranks of result of torchreid on 'Market-1501' dataset
- [X] extracting the feature-vector of images in the dataset


To be done
-----------
- [ ] Later, it will be used to re-rank the result of torchreid checking if we can get a higher mAP or not.


Outputs untill now
-----------
- result.csv        -> query-index, galley_index, is_valid_or_invalid

- queries feature vectors
    - qf.csv        -> query features
    - q_pids.csv    -> query pids
    - q_camids.csv  -> query camera ids

- galleries feature vectors
    - gf.csv        -> galley features
    - g_pids.csv    -> gallery pids
    - g_camids.csv  -> gallery camera ids
