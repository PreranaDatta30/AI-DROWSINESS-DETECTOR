# AI-DROWSINESS-DETECTOR
An AI-based drowsiness detection system using Eye Aspect Ratio (EAR), Mouth Aspect Ratio (MAR), and Head Tilt Ratio to detect eye closure, yawning, and fatigue in real time. Designed for use across multiple fields including transportation safety, workplaces, healthcare, and education.
# What is drowsiness?
DROWSINESS refers to a state of feeling excessively sleepy or tired, particularly during the day. It can lead to falling asleep at inappropriate times and may be accompanied by symptoms such as forgetfulness, lethargy, and lack of mental agility. Drowsy driving is a major cause of road accidents. This project aims to prevent such incidents by developing a real-time system that detects a driver's state of alertness. Using computer vision and machine learning, the system monitors key facial features—eyes, mouth, and head position—to identify signs of drowsiness and alert the driver<img width="18825" height="140" alt="image" src="https://github.com/user-attachments/assets/7580bcd8-ce2f-478e-a2b2-396d2094e15e" />
# Existing work with limitations
Existing drowsiness detection systems often rely on a single metric, such as eye closure, which can lead to false alarms or missed detections. These systems may fail if a driver is drowsy but keeps their eyes partially open or if they are looking down at their phone. Additionally, some solutions require specialized, expensive hardware, limiting their accessibility. Our project addresses these limitations by incorporating multiple physiological indicators and running on standard camera equipment.
<img width="16029" height="140" alt="image" src="https://github.com/user-attachments/assets/59d972a2-7fee-4878-ac14-5749e8d8626b" />
# Proposed work and methodology
Our proposed system uses a multi-faceted approach to assess a driver’s state accurately. It will continuously monitor the following:
Eye Aspect Ratio (EAR): A metric to determine how open or closed the eyes are. A low EAR value indicates drowsiness.
Mouth Aspect Ratio (MAR): A metric to detect yawning, a key indicator of fatigue.
Head Pose Estimation: Tracking the driver's head movements, such as nodding or tilting, which are common signs of fatigue.
<img width="4105" height="441" alt="image" src="https://github.com/user-attachments/assets/bea9a875-a4ca-408f-b20e-39d32a5b29d5" />
The methodology involves:
Capturing a video feed from a camera.
Using Dlib's facial landmark detector to locate key facial features.
Calculating the EAR and MAR in real-time.
Estimating head pose using the 2D facial landmarks and 3D model points.
Applying a counter-based system to confirm prolonged drowsiness before triggering an alert.
The system will issue a visual and/or audio warning when drowsiness is detected.
<img width="2876" height="689" alt="image" src="https://github.com/user-attachments/assets/4ced9734-8fde-4a78-9241-145718d33645" />
