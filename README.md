This project presents an automatic forest fire monitoring system that leverages UAV (Unmanned Aerial Vehicle) technology combined with video image analysis for efficient, real-time detection of forest fires. The system is designed to address limitations in traditional monitoring methods, such as low efficiency and poor real-time responsiveness.
Features:
  1.Real-time video analysis using UAV-captured footage.
  2.Motion region extraction using dense optical flow and background modeling.
  3.Wavelet energy and texture feature analysis for robust fire detection.
  4.Gray Level Co-occurrence Matrix (GLCM) based feature extraction. 
Methodology:
  1.Video Acquisition: Multi-rotor UAV captures real-time footage of forest areas.
  2.Motion Detection:
       a)Dense Optical Flow to detect movement.
       b)Background Modeling to isolate relevant motion from noise.
  3.Feature Extraction:
       a)Apply Wavelet Energy transformation.
       b)Use Texture Features via GLCM for fire signature identification.
  4.Classification & Detection:
       a)Mean and standard deviation values from extracted features used as the basis for distinguishing fire from non-fire areas.
Results:
  The proposed system demonstrates effective forest fire detection capabilities.

