*Saudi Face ID* is a facial recognition system built using traditional computer vision techniques (no deep learning), designed to identify well-known Saudi public figures based on facial features.

The project was built using the *face_recognition* library (based on dlib) and *OpenCV, with data collected and labeled manually. Despite using a lightweight approach, the system achieved over **90% accuracy* on real, unseen faces.

---

## Overview

- *Technology Stack*: face_recognition (dlib), OpenCV, Python
- *Approach*: Feature-based face encoding + vector distance matching
- *Data*: Manually collected images of Saudi public figures
- *Accuracy*: >90% on test cases

---

## Key Features

- *No deep learning* – built entirely on facial embeddings and distance thresholds
- *Manually labeled, Saudi-specific dataset*
- Detects and recognizes public figures using fast and interpretable logic
- Real-world evaluation with challenging test images (angles, lighting, expressions)

---

## My Role

- Collected face images manually from public sources
- Cleaned and organized training/test datasets
- Implemented face detection, encoding, and comparison logic
- Tuned thresholds for optimal accuracy
- Validated performance and handled false positives/negatives

---

## Example Output (not shared for privacy)

> تم التعرف بنجاح على شخصية سعودية باستخدام صورة من مصدر إعلامي.  
> نتيجة النموذج: "تم التعرف على الوجه: [اسم الشخصية]"  
> (الصورة غير مرفقة احترامًا للخصوصية)

---

## Tools Used

- face_recognition  
- OpenCV  
- NumPy, Matplotlib  
- Python 3.9+

---

## Ethical Notice

This project is for academic and technical demonstration purposes.  
No code, dataset, or identifiable images of individuals are publicly shared. All data was sourced from open sources and used for educational exploration only.

---

## Future Plans

- Upgrade model to use deep learning for more complex generalization  
- Add support for real-time webcam detection  
- Explore UI integration (streamlit or web-based dashboard)

---

## Contact

*[Khulod Almarwani]*  
[https://www.linkedin.com/in/khulod-aljuhani?] | [Khulodalmarwani@gmail.com]
