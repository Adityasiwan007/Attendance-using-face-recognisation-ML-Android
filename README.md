# Face Recognition With Android & OpenCV
This is an open source android application that does face recognition using OpenCV. Originally made for attendence marking in college, 


### Screenshots
<img src="https://raw.githubusercontent.com/abhn/marvel/master/docs/static/collage.jpg" width="75%"/>

1. **Home page** - For switching between training and testing
2. **Home > Training (enter ID)** - Enter ID for the train images
3. **Home > Training (enter ID) > Capture** -  Capture train image for the ID
4. **Home > Recognition** - Recognize faces
5. **Home > Recognition > Review** - Review capture results (Optionally push to database)


- Clone this repository
- Open project in android studio
- Optional: Configure firebase if required. Check out comments in ReviewResults activity
- Compile, install the Apk
- Go to training, set an ID and capture a face to train. Repeat this a couple of times with different people and IDs
- Go to recognition, click scan and try to capture everyone in the video stream. The detected faces will be recognized and shown.
- Once done, stop scanning and click submit to review capture results. Implement the "Mark Attendence" button if required.

### Known Issues & TODO
- Face recognition is not accurate. Far from it
- Recognition model gets created each time "Recognize" tab is clicked. Slows down as number of training images increase

### Directories
- **/sdcard/facerecogOCV** - Training images

