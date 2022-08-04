Description
=============

#### - Face mask classification
  - Image classification of wearing face mask or not
  
<img src="https://user-images.githubusercontent.com/52263269/182492229-3d9e020b-d59b-4ea3-b1c7-3baa2ec5ebff.png" width="30%"></img>
<img src="https://user-images.githubusercontent.com/52263269/182492233-18e54940-40a3-4c3e-91d6-ad2358872ea8.png" width="30%"></img>
<img src="https://user-images.githubusercontent.com/52263269/182492235-4cbaa788-09a6-4981-92ee-17bc0074ec05.png" width="30%"></img>

Contents
=============

#### - [Face Mask Types Classification with RegNet backbone](https://github.com/qbxlvnf11/face-mask-classification/blob/main/Face%20Mask%20Type%20Classification.ipynb)
  - Docker env run command
```
docker run --gpus all -it --rm -p 9000:9000 -e GRANT_SUDO=yes --user root -v {source code path}:/workspace -w /workspace pytorch/pytorch bash -c "pip install jupyter && pip install pandas && pip install seaborn && pip install sklearn && apt-get update && apt-get install -y python3-opencv && apt-get install gcc && apt-get install git && pip install torchmetrics && pip install tensorflow && pip install opencv-python && pip install torch_snippets torch_summary && jupyter notebook --ip='0.0.0.0' --port=9000 --allow-root"
```

Dataset
=============

#### - Face Mask Types Dataset

https://www.kaggle.com/datasets/bahadoreizadkhah/face-mask-types-dataset

References
=============

#### - RegNet Paper
```
@article{RegNet,
  title={Designing Network Design Spaces},
  author={Mehdi Mirza, Simon Osindero},
  journal = {arXiv},
  year={2020}
}
```

Author
=============

#### - LinkedIn: https://www.linkedin.com/in/taeyong-kong-016bb2154

#### - Blog URL: https://blog.naver.com/qbxlvnf11

#### - Email: qbxlvnf11@google.com, qbxlvnf11@naver.com
