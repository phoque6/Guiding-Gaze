# Guiding-Gaze

## Concept
Aiming to empower visually impaired individuals, we propose a real-time navigation system for the visually impaired via a mobile application
and wireless communication between electronic components.

## Setup
- Install the [DroidCam App](https://play.google.com/store/apps/details?id=com.dev47apps.droidcam&pcampaignid=web_share) app on your android.
- Install the [PC version](https://www.dev47apps.com/droidcam/windows/) of the app on your laptop. Similar versions are available for MacOS and linux.
- Follow [this guide](https://www.dev47apps.com/droidcam/connect/) to get it running. Once working, you can use your phone as a webcam.
- There is an option for WiFi connection as well, but due to high computational requirements of the model, we have used a data cable to reduce lag.
- Install this repo on your PC using the following commands:

```
  git clone https://github.com/MananGaur19/Guiding-Gaze.git
```
- Go inside the repo and install the dependencies

```
pip install -r requirements.txt
```
  
![Architecture](https://github.com/MananGaur19/Guiding-Gaze/assets/56295289/0b1577e4-9132-46ad-acb2-4b1d376f26f7)

## Modules
### Object Detection

### Depth Estimation
- We use MiDAS to calculate object distance from the user.
- Run the `MIDAS/MIDAS.ipynb` file to run this on your machine.

### Scene Recognition
Run the `Scene Recognition/scene_recognition.ipynb` on your PC for scene recognition.

### 



