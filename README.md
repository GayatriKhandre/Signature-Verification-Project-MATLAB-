# Signature Verification Project (MATLAB)
This project verifies signatures by comparing features from two images using Harris corner detection and feature matching in MATLAB.

## Requirements
- MATLAB with Image Processing Toolbox.
- Input images: `sign1.jpg` and `sign2.jpg`.

## Steps to Run
1. Place `sign1.jpg` and `sign2.jpg` in the script directory.
2. Run the MATLAB script.

## Workflow
1. Convert images to grayscale.
2. Detect Harris features.
3. Extract and match features.
4. Display matched points.
5. Verify similarity based on feature metrics.

## Result
The script displays `Matched` if the signatures are similar; otherwise, `Not Matched`.

![image](https://github.com/user-attachments/assets/e71c6593-aca8-481a-8cb0-5830c74714d4)
![image](https://github.com/user-attachments/assets/50ecb987-84ba-4a49-b813-197e2e7fdc11)


## Notes
- Adjust the threshold (`0.04`) for better accuracy.
- Ensure input images have consistent quality.

Author: Gayatri Pradeep Khandre
