

# EESOB Electronics and Embedded System for Object Detection  Dataset

## Overview

The EESOB dataset is designed for object detection in electronic and embedded systems. It includes a diverse collection of images annotated with various electronic components and embedded systems. This dataset is tailored for training and evaluating object detection models, to accurately identify and classify these components.

## Dataset Details

- **Total Classes**: 48
- **Total Images**: 3,834 images without data augmentation, 9,382 images with data augmentation
- **Dataset Split**:
  - **Training**: 80%
  - **Validation**: 10%
  - **Testing**: 10%

### Classes

The dataset includes the following classes:

- `7-segment`
- `Arduino Mega`
- `Arduino Mini`
- `Arduino Nano`
- `Arduino Uno`
- `Battery 9V`
- `Bluetooth`
- `Breadboard`
- `Button`
- `Buzzer`
- `Capacitor`
- `DC Motor`
- `DHT`
- `Display`
- `ESP32`
- `ESP WiFi`
- `Fan`
- `Flame Sensor`
- `Gas Sensor`
- `H-Bridge`
- `IR Receiver`
- `IR Sensor`
- `Joystick`
- `Keypad`
- `LCD`
- `LCD OLED`
- `LDR`
- `LED Matrix`
- `Lilypad`
- `LiPo Battery`
- `Pile`
- `PIR Sensor`
- `Potentiometer`
- `Power Module`
- `Prototype PCB`
- `Relay`
- `RFID`
- `RTC`
- `Servo`
- `Soil Moisture Sensor`
- `Solar Panel`
- `Sound Sensor`
- `Speaker`
- `Stepper Driver`
- `Stepper Motor`
- `Support Pile`
- `Switch`
- `Ultrasonic Sensor`

## Access the Dataset

You can explore and download the dataset from the following link:

[**EESOB Dataset**](https://universe.roboflow.com/android-yolo/eesob)

## Requirements


This repository requires the following libraries:

- `ultralytics`
- `roboflow`
- `beautifulsoup4`
- `requests`
- `tqdm`

You can install these libraries using:

```bash
pip install -r requirements.txt
```


## Notebooks

This repository contains two notebooks:
1. **[Scraping Images](https://github.com/yacin-hamdi/EESOB/blob/main/web_scraper.ipynb)**: A notebook detailing the process of scraping images to build the dataset.
2. **[Training the Model](https://github.com/yacin-hamdi/EESOB/blob/main/training.ipynb)**: A notebook showing how to use the dataset to train a model.


## License

This dataset is licensed under the This dataset is licensed under the [MIT License](LICENSE).

## Acknowledgments

- **Roboflow** for the dataset management tools
- **Ultralytics** for training the model

## Contact

For any questions or suggestions, please reach out to me at [yacin.ha9@gmail.com].







