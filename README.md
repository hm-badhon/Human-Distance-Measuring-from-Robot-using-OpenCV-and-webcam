# Human-Distance-Measuring-from-Robot-using-OpenCV-and-webcam
# Face Distance Measurement Project

This project uses OpenCV to measure the distance to a face in real-time video based on a known reference distance and width. The code captures video from a webcam, detects faces, and calculates the distance to the face using the focal length.
## Demo video

https://github.com/hm-badhon/Human-Distance-Measuring-from-Robot-using-OpenCV-and-webcam/assets/85755347/8dd213f0-0862-4b41-8de0-674ff7e8ac84


## Prerequisites

- Python 3.x
- OpenCV library
- haarcascade_frontalface_default.xml file (Haar cascade classifier)

## Installation

1. Clone the repository:

    ```bash
    git clone [https://github.com/your-username/face-distance-measurement.git](https://github.com/hm-badhon/Human-Distance-Measuring-from-Robot-using-OpenCV-and-webcam)
    cd face-distance-measurement
    ```

2. Install dependencies:

    ```bash
    pip install opencv-python
    ```

3. Download the `haarcascade_frontalface_default.xml` file and place it in the project directory. You can find this file in the OpenCV GitHub repository or other sources.

4. Run the script:

    ```bash
    python face_distance_measurement.py
    ```

## Configuration

- Adjust the `known_distance` and `known_width` variables in the script based on your real-world setup.

## Usage

1. Run the script as described in the installation section.

2. The script will open a window showing the webcam feed with the calculated distance to the detected face displayed on the frame.

3. Press 'q' to exit the application.

## Troubleshooting

- If you encounter issues with the script, make sure the webcam is working, and the reference image is loaded correctly.

- Ensure that the `haarcascade_frontalface_default.xml` file is available in the project directory.

## Author

- **H.M. Mehedi Hasan (Badhon)**

![85755347](https://github.com/hm-badhon/Natural_Language_Processing_NLP_with_hmb/assets/85755347/1c4c9b08-71fe-463d-8117-cc2b23acb3d9)

  - [GitHub Profile](https://github.com/hm-badhon)
  - [LinkedIn Profile](https://bd.linkedin.com/in/h-m-mehedi-hasan-575563159)
  - [Email](mailto:h.m.badhoneee@gmail.com)
  - Associate Robotics Engineer, NSL
    

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
