# Steps

0. Make sure you python3 version is 3.8

1. Clone this repo. 
```
git clone https://github.com/lthroy/CS598DLHFinal.git
```

2. Download the data
https://drive.google.com/file/d/18wvJGDnAlhSRov3Z2ShVwjPy-_EGN22Q/view?usp=drive_link

Download and unzip such that the folder "fritz17k" is under the folder "CS598DLHFinal"

3. Download the training results

https://drive.google.com/drive/folders/1paF6XRpFotOmCrJ4izckNVXGl9q93bRI?usp=drive_link

If too large, you can just download test_dfs.pickle and valid_dfs.pickle

Again, unzip such that the folder "run_result" is under the folder "CS598DLHFinal"

4. Run
```
pip install -r requirements.txt
```
If any of the installations failed, try running the pip install command with the requirements_lock.txt `pip install -r requirements_lock.txt`.

5. Your folder structure should look like


```
CS598DLHFinal/
│
├── README.md
│
├── src/
│ 
│
├── fritz17k/
│   
│
├── run_result/
|   |── valid_dfs.pickle
|   └── test_dfs.pickle
|   |--- ...
|
|
|
├── requirements.txt
│
├── skin_info2.csv
│
└── fitz.ipynb
```

6. Run ./fitz.ipynb


