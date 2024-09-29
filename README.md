git clone https://github.com/yourusername/wafer-defect-detection.git
pip install -r requirements.txt
/data
  /train
    - wafer1.png
    - wafer2.png
  /test
    - wafer3.png
    - wafer4.png
python preprocess.py
python train.py
python test.py
