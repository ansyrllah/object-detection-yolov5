# Capstone Project: OPTISENSE

## People involved:
  1. Abdullah Amali (1217050001)
  2. Alya Kusuma W (1217050008)
  3. Ansyarullah (1217050019)
  4. Desi Ainul Amelia (1217050034)

## About Optisense
The Optisense Object Detector project aims to develop a cutting-edge system that leverages advanced machine learning algorithms to detect and identify objects in various environments. By harnessing the power of computer vision and deep learning techniques, this project endeavors to provide accurate, efficient, and real-time object detection capabilities.

### Proposal Capstone Project

For further information about this project, please see the [Proposal Capstone Project](https://my.visme.co/view/w46z1j7o-opti-sense).

 [official website here.](https://docs.anaconda.com/miniconda/#latest-miniconda-installer-links).

## How to use this program

### Preparation
Install Miniconda from [official website here.](https://docs.anaconda.com/miniconda/#latest-miniconda-installer-links).

Or with command-line. 
    
```bash
# for windows
curl https://repo.anaconda.com/miniconda/Miniconda3-latest-Windows-x86_64.exe -o miniconda.exe

start /wait "" miniconda.exe /S

del miniconda.exe
```


### Running program
1. Open Anaconda Promt (miniconda3) in your windows.
2. Clone [Optisense Repository](https://github.com/ansyrllah/object-detection-yolov5)
    ```bash
      git clone https://github.com/ansyrllah/object-detection-yolov5.git # clone
    ```
3. Open the repository
    ```bash
      cd object-detection
    ```
3. Install all requirements
    ```bash
      pip install -r requirements.txt  # install
    ```
3. Create conda environtment
    ```bash
      conda create --name yolov5 python=3.8
    ```
2. Activate environtment
    ```bash
      conda activate yolov5
    ```
2. Run program
    ```bash
      python detect.py --source 0 --view-img
    ```
2. CLose program
    ```bash
      Ctrl + C  #on miniconda terminal
    ```

### Program Demo
 <div align="center">
  <img width="100%" src="optisense-demo.gif">
  <h3>Thank You</h3>
</div>