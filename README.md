How to run code on Raspberry Pi
    1. Set up RPi .
    2. Boot into its OS.
    3. Open CLI
    4. Update the system using : (1)   sudo apt-get update  (2)  sudo apt-get dist-upgrade 
    5. Run these lines too
 sudo apt-get install libatlas-base-dev
sudo apt-get install libjpeg-dev libtiff5-dev libjasper-dev libpng12-dev
sudo apt-get install libavcodec-dev libavformat-dev libswscale-dev libv4l-dev
sudo apt-get install libxvidcore-dev libx264-dev
sudo apt-get install qt4-dev-tools libatlas-base-dev

    6. Then cd into the project Folder using :  cd [project folder path here] 
    7. Install the requirements using : pip3 install -r requirements.txt
    8. Restart the system.
Steps 1-8 are only needed for the first time on a new flashed OS 
    9. Cd into project folder.
    10.  Run: python3 main.py
    11. And then use this IP in browser to access the app.
