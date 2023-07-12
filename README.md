The goal of human activity recognition is to examine activities from video sequences or still images. Motivated by this fact, human activity recognition systems aim to correctly classify input data into its underlying activity category. Depending on their complexity, human activities are categorized into: (i) gestures; (ii) atomic actions; (iii) human-to-object or human-to-human interactions; (iv) group actions; (v) behaviors; and (vi) events. 
Gestures are considered as primitive movements of the body parts of a person that may correspond to a particular action of the person. Herein this model, we will consider gestures as our basis. We will collect a series of data and record what kind of movement and what amount of movement is happening. Based on the data collected the measurement of the movement is captured. 
Human activity recognition (HAR) aims to classify a person's actions from a series of measurements captured by sensors. Nowadays, collecting this type of data is not an arduous task. With the growth of the Internet of Things, almost everyone has some gadget that monitors their movements. It can be a smartwatch, a pulsometer, or even a smartphone. Usually, this is performed by following a fixed-length sliding window approach for the feature extraction. Here two parameters need to be fixed: the size of the window and the shift. These are some of the data you could use:
Body acceleration.
Body angular speed.
Body angular acceleration.
Etc.

The machine learning model used for activity recognition relies on top of the devices' available sensors. However, analyzing this data can be a big challenge due to the complexity of human activities and the existing differences between two individuals.
