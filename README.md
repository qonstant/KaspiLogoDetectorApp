
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

<img width="1466" alt="1" src="https://github.com/qonstant/tengri-news-clone/assets/98641240/24555f67-ee12-4155-9e97-fb72c8f7698f">

### &#9745;Second requirement:

- [x] Develop an interface for loading images and receiving predictions from the model.

\
Users can upload their images for object detection. The app will predict and show its confidence level below.

### &#9745; Third requirement: 

- [x] Develop an interface for loading images and receiving predictions from the model.

\
I have created a button with a link to the email, thanks to which users can send new data for training the model. Since it's not possible to realize transfer learning in this case, we will have to train the model from the beginning, and it will take a couple of hours.

\
<img width="1280" alt="2_1" src="https://github.com/qonstant/tengri-news-clone/assets/98641240/f11b6eb9-963c-4d1e-a443-bea41916099d">


