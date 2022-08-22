# CoastCam-Rectification
Location for Python code used for rectifying coastal imagery. Contains building-block code for rectifying images as well as various wrappers.

In the main folder are the 3 Python scripts needed for performing image rectification:
1. calibration_crs.py - contains the CameraCalibration class
2. rectifier_crs.py - contains the TargetGrid and Rectifier
3. coastcam_funcs.py - contains various functions needed for rectification

There are also folders for performing rectification with different wrapper code:
/exif_rectify - rectify imagery using parameters stored in an image's EXIF metadata.
/yaml_rectify - rectify imagery using parameters stored in YAML files
/s3_rectify - rectify imagery from S3. YAML files will also be needed.
