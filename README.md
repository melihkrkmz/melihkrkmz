# Melih Rıdvan Korkmaz

Software Development student at Cappadocia University. I build computer vision systems that have to work in real time: detecting something on a live camera feed, tracking it, and acting on it. Lately I'm also making games, first with Flutter and now with Unity.

[LinkedIn](https://www.linkedin.com/in/melihkrkmz)

<!-- Optional: add an email link here, e.g. · [Email](mailto:you@example.com) -->

## Focus

**Computer vision.** Training and tuning object detectors, mostly YOLO. A lot of my time goes into the data side: growing a dataset from a small set of labeled images, choosing augmentations that reflect real conditions, and checking how the model holds up on live video instead of a clean test split.

**Tracking and control.** Getting from "the model found something" to "the system follows it": Kalman filters for state estimation, PID loops for motion, and the code that connects the camera to the hardware.

**Apps and games.** Cross-platform mobile development with Flutter, and game development in Unity, where I'm learning how to structure gameplay systems so they stay manageable as a project grows.

## Projects

### Autonomous Air Defense System · Teknofest

A system that detects aerial targets on a live camera feed, follows them from frame to frame and aims at them without human input. Built as a Teknofest competition project.

- **Detection:** YOLOv8 trained on a custom dataset. The original set had around 900 labeled images; augmentation expanded it to roughly 10,000, giving the model far more variation than could have been collected and labeled by hand.
- **Tracking:** A Kalman filter smooths noisy detections and predicts where the target will be next, so tracking survives missed frames and brief occlusions.
- **Control:** A PID controller turns the tracking error into aiming commands, keeping the target centered as it moves.
- **Runtime:** The full loop (capture, detection, tracking, control) runs in real time with OpenCV.

`Python` `YOLOv8` `OpenCV` `Kalman Filter` `PID`

<!-- Worth adding: repo link, a short demo GIF, your role on the team, and concrete results (mAP, FPS, how far you got in the competition). -->

### Type to Defend · Mobile game

A defense game you play by typing. Threats keep coming, and the only way to stop them is to type fast and accurately under pressure. Built with Flutter, so the same codebase runs on Android and iOS.

`Flutter` `Dart`

<!-- Add a store or repo link, plus one or two screenshots or a short GIF. -->

## Tools

- **Languages:** Python, C, Dart, JavaScript
- **ML & vision:** YOLOv8, OpenCV
- **Backend:** Flask, PostgreSQL, Docker
- **Frontend & mobile:** Flutter, React
- **Other:** Git, Linux (Ubuntu), Unity

## Currently

- Improving YOLO training: augmentation strategies, dataset balance and inference speed
- Learning Unity through small, finished prototypes
- Designing backends that are modular from the start, so features can be added without rewrites

## Working toward

- Shipping a mobile game to the app stores
- Building an AI-powered SaaS product around a real problem, not a demo
- A deeper grasp of machine learning fundamentals, beyond applied detection work
- Products that people outside my own circle actually use

## Contact

Open to internships, collaborations and competition teams. The quickest way to reach me is [LinkedIn](https://www.linkedin.com/in/melihkrkmz).
