# Sign-Language-Detection 🌞
## Introduction to Sign Language Detection Program 

Sign Language Detection is a program designed to analyze and subsequently translate sign language, enabling users to communicate easily with others through expressive gestures and communication. This program brings numerous values and significances in developing practical products for the deaf and hard of hearing. Here are several key points:

1. **Effective Communication:** Sign Language Detection helps users of sign language interact more effectively, reducing communication barriers between them and those unfamiliar with the language.

2. **Development of Useful Products:** This program can be integrated into various applications and devices to create practical products, such as mobile apps, wearable devices, or other assistive tools.

3. **Creating Real-Time Communication Opportunities:** Sign Language Detection can provide real-time communication abilities, allowing the deaf and hard of hearing to confidently participate in conversations and interactions.

4. **Education and Learning:** The program can serve as an educational tool to help learners of sign language understand and practice gestures.

5. **Feedback and Flexibility:** Sign Language Detection can provide real-time feedback on the accuracy of gestures, assisting users in improving their skills and enhancing flexibility in interactions.

6. **Emergency Situation Support:** In emergency situations, individuals with hearing impairments can use Sign Language Detection to convey messages quickly and effectively.

7. **Enhancing Diversity and Acceptance:** By supporting communication within the deaf community, this program contributes to enhancing diversity and fostering acceptance in society.

In summary, Sign Language Detection is not just a communication support tool; it is a vital tool for creating practical solutions, contributing to improving the quality of life for the deaf and hard of hearing.

<hr>

## THE DESIRED OUTCOME:
<hr>

![IMG](https://github.com/yunee19/Sign-Language-Detection/assets/133479803/35a9190b-883c-4252-881c-dca161a0be4d)


<hr>

## TO DO LIST:
- Cloning Baseline Code 
- Collecting Images using OpenCV
- Labelling Images for Object Detection
- Training the Model
- Making Real Time Detections

## THE ACTUAL WORK:


### Step 1: Create Necessary Files and Folders

Before running the program, you need to establish the required folder structure. This structure consists of a root folder (e.g., "data") with subfolders for each label.

### Step 2: Image Collection

![quantrong1](https://github.com/yunee19/Sign-Language-Detection/assets/133479803/13d2762d-6175-4602-b4ec-8eace0edd9b3)

The provided code executes the following actions:

1. **Create Folders for Each Label:**
   - For each label in the list of labels, the program creates a subfolder in the root folder (`IMAGES_PATH`).
   - The `os.makedirs` function is used to ensure the folder exists or create it if it doesn't already.

2. **Image Collection:**
   - Open the camera using OpenCV (`cv2.VideoCapture(0)`) to capture images.
   - For each label, the program displays the image from the camera and saves the image to the corresponding folder.
   - Each image is saved with a name consisting of the label and a portion of the UUID to ensure uniqueness.

3. **Waiting Time and Exit:**
   - The program waits for 5 seconds (for preparation) before starting the image collection.
   - For each image, the program waits for 2 seconds (adjustable) before capturing the next one.
   - Pressing the 'q' key exits the program.

### Notes:

- **UUID:** The UUID portion in the image file name is used to ensure each image has a unique name.

- **Waiting Time:** You can adjust the waiting time before capturing each image by modifying the value of `time.sleep(2)`.

### Step 3: Labelling Images for Object Detection
Run labelImg.py then assign the name using the box label

## Progress Completion: 60%
☑️ Cloning Baseline Code : Done

☑️ Collecting Images using OpenCV: Done
![pyproanh1](https://github.com/yunee19/Sign-Language-Detection/assets/133479803/285d3188-c7e3-4fb9-ae97-cc86ab4b0609)
☑️ Labelling Images for Object Detection: Done
![pypoanh2](https://github.com/yunee19/Sign-Language-Detection/assets/133479803/9487b359-d143-4aad-abf7-33a379a5e0bc)
❌ Training the Model

❌ Making Real Time Detections

## References
AUTHOR: Nicholas Renotte 

The video :[Sign Language Detection ](https://www.youtube.com/live/V0Pk_dPU2lY?si=AS2qrB97H2yDQN-v)

Original works : 
[Real Time Object Detection Code](https://github.com/nicknochnack/RealTimeObjectDetection),
[Image Collection Code](https://github.com/nicknochnack/RealTimeSignLanguageDetectionwithTFJS/blob/main/Image%20Collection.ipynb) ,[LabelImg](https://github.com/HumanSignal/labelImg)
