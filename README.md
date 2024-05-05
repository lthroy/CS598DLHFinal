# Steps to Run the Code

### Before you start
#### Make sure you python3 version is 3.8.
In command line, run `python3 --version` and it should print out `Python 3.8.x`. If not, you could install `pyenv` via `homebrew` (mac) or `apt-get install` (linux) and then run `pyenv install <version>`.

1. Clone this repo. 
```
git clone https://github.com/lthroy/CS598DLHFinal.git
```

2. Download the [data](https://drive.google.com/file/d/18wvJGDnAlhSRov3Z2ShVwjPy-_EGN22Q/view?usp=drive_link)<br/>
Unzip the folder such that the folder "fritz17k" is under the folder `CS598DLHFinal`. See the folder structure below for more details.

3. Download the [training results](https://drive.google.com/drive/folders/1paF6XRpFotOmCrJ4izckNVXGl9q93bRI?usp=drive_link)<br/> If the size of the zip file is too large, you can only download the `test_dfs.pickle` and `valid_dfs.pickle` file. Again, unzip such that the folder "run_result" is under the folder `CS598DLHFinal`. See the folder structure below for more details.

4. Run the following command to install the dependencies.
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

6. Launch jupyter notebook and run fitz.ipynb
