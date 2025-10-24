# PyTorch DeepFloorplan

## The original project 
[Original project](https://github.com/zcemycl/PyTorch-DeepFloorplan.git) 

[I get dataset from here](https://github.com/zlzeng/DeepFloorplan.git)


## How to run?
1. Install packages. 
```
pip install -r requirements.txt
```
2. Download r3d dataset to `dataset/r3d.tfrecords` and convert it to csv file.
```
python readTFRecord.py
python img2csv.py
```
3. Train the network,
```
python main.py
```
4. Deploy the network, 
```
python deploy.py
```