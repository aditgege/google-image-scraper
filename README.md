# Google Image Scraper

I opensource one of the helper modules from my `Fruit Sorting Conveyor Project` with image recognition combined with the sensors and cameras. The platform that I used for developing the project is NVIDIA Jetson Xavier controls over collecting and analyzing data from the camera and sensors. TensorFlow for training countless fruit images and labeling those images was time-consuming. I developed a program to crawl images from Google Image for the ML. A black color rackmount chassis filled with all modules, including power supply, connectors for sensors, external PLCs (programmable logic controller), ethernets, and 10-inches touch-screen LCD with the cozy cool user interface.

### _install

```bash
$ git clone https://github.com/loouislow81/google-image-scraper.git
$ cd google-image-scraper
# set up new Python 3 virtual environment
$ virtualenv -p python3 venv
# mount venv directory
$ source venv/bin/activate
# install dependencies
$ (venv) pip install -r requirements.txt
```

### _usage

CLI Options,

```bash
usage: scrape_image.py [-h] [--skip] [--threads] [--full] 
                       [--no_gui] [--limit]

  -h, --help    Show this help message and exit
  --skip        Skips already downloaded (bool) (default: true)
  --threads     Maximum threads of download (num) (default: 4)
  --full        Download full resolution (bool) (default: false)
  --no_gui      Speed up full-res downloads (bool) (default: auto=false)
  --limit       Maximum download per thread (default: 0=inifinite)
```

---

> Those who are using the opensource tool that I created. Brings happiness, eliminate troubles, and plant the seeds of Buddha, after all, they are free from suffering. Namo Amitabha. 凡是用了我所创造的布施工具的众生，都得开开心心的，烦恼消灭，皆种成佛种子，毕竟离苦得乐。南无阿弥佗佛。

---

[MIT](https://github.com/loouislow81/google-image-scraper/blob/master/LICENSE)

