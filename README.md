
# Kaspi Logo Detector App

Kaspi Logo Detector App created using Swift.

### Run

1. Clone the repository:
   ```sh
   git clone https://github.com/qonstant/KaspiLogoDetectorApp.git
2. Go to the ./Kaspi Logo Detector/Kaspi Logo Detector.xcodeproj and run the App

### Task
#### Application for determining the "Kaspi" icon using AI

### &#9745; First requirement:

- [x]  Integrate TensorFlow ML model to train a recognition model for the “Kaspi” icon.

\
I have trained CoreML model. Collected 63 images and labeled every single one of them.

<img width="1470" alt="ML Core object detection" src="https://github.com/qonstant/KaspiLogoDetectorApp/assets/98641240/bec01058-e4b5-4433-931c-1e55d32d8d9e">

<img width="1470" alt="Supervised Learning 1" src="https://github.com/qonstant/KaspiLogoDetectorApp/assets/98641240/ec91a3a3-c122-45fd-ad1b-5d080a2ae69a">

<img width="1470" alt="Supervised Learning 2" src="https://github.com/qonstant/KaspiLogoDetectorApp/assets/98641240/c52e5aeb-23af-461d-8d74-9630e0645c41">

<img width="1470" alt="Image Processing" src="https://github.com/qonstant/KaspiLogoDetectorApp/assets/98641240/86395693-b840-4437-8826-d28dbe27c337">

<img width="1470" alt="Training" src="https://github.com/qonstant/KaspiLogoDetectorApp/assets/98641240/d529ab46-ea3c-4397-a31f-3fa37abb960d">

### &#9745;Second requirement:

- [x] Develop an interface for loading images and receiving predictions from the model.

\
Users can upload their images for object detection. The app will predict and show its confidence level below.

\
<img src="https://github.com/qonstant/KaspiLogoDetectorApp/assets/98641240/7e68da5d-8126-4b96-8151-42f43fcb55ec" width="30%" height="30%">
<img src="https://github.com/qonstant/KaspiLogoDetectorApp/assets/98641240/1fa8ab6d-2b40-435a-925d-1b0ae2d828eb" width="30%" height="30%">
<img src="https://github.com/qonstant/KaspiLogoDetectorApp/assets/98641240/63b720e2-340e-4039-916c-a4802488a0f6" width="30%" height="30%">


### &#9745; Third requirement: 

- [x] Develop an interface for loading images and receiving predictions from the model.

\
I have created a button with a link to the email, thanks to which users can send new data for training the model. Since it's not possible to realize transfer learning in this case, we will have to train the model from the beginning, and it will take a couple of hours.

\
<img src="https://github.com/qonstant/KaspiLogoDetectorApp/assets/98641240/9a303299-5ec7-4522-8816-f8b8f39f9830" width="30%" height="30%">
<img src="https://github.com/qonstant/KaspiLogoDetectorApp/assets/98641240/01ed1513-fbf7-4051-8cb5-eaabee0c2bb9" width="30%" height="30%">

