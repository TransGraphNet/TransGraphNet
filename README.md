Datasets and code for `TransGraphNet: Robust detection of malicious encrypted network traffic via transformer and graph neural models`.

## Datasets

We provide the raw dataset and the processed dataset, which are stored in two folders respectively. The raw dataset can be obtained from the following link.

1、The MTA dataset (malware-traffic-analysis) can be obtained at [malware-traffic-analysis.net](https://www.malware-traffic-analysis.net/index.html).

2、The Stratosphere dataset can be obtained at [Malware Capture Facility Project]( https://www.stratosphereips.org/datasets-malware).

3、The CIC-IOT-2023 dataset can be obtained at [Canadian Institute for Cybersecurity]( https://www.unb.ca/cic/datasets/iotdataset-2023.html).

## Directory Structure
1、**raw_dataset**  We provide the raw MTA and CIC-IoT-2023 datasets used in this study.

1、**processed_dataset:**  We provide the processed MTA and CIC-IoT-2023 datasets. Both datasets have been preprocessed using the improved Power Law Division (PLD) algorithm and modeled using the Adaptive Flow-level Burst Graph (AFG) structure. The datasets are available in both `.bin` and `.pkl` formats.

2、code：We have integrated the data reading and classification modules into a single Python file.

## How to clone
`git clone https://github.com/PeerJ-RDNet/RDNet.git`

`git lfs pull`


## Environment
python 3.9

requirement：`requirement.txt`

## How to run
`cd code`

`python RDNet.py`
