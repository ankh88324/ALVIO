# ALVIO
Adaptive Line and Point Feature-based Visual Inertial Odometry for Robust Localization in Indoor Environments

RA-L & ICRA2020 ALVIO official page


1. Overall block diagram of ALVIO. ALVIO is an extension algorithm that considers the line feature in VIO to perform robust localization in indoor environment. The novelties of ALVIO include optical flow-based line tracker and the sensitivity-analysis-based adaptive feature selection algorithm.
![overall_3](https://user-images.githubusercontent.com/19143504/65028817-a3907600-d977-11e9-9123-e4d4b718b33f.png)

2. Block diagram illustrating the full pipeline of the proposed optical flow-based line tracker with an example image for each step.
![line_extraction_algo_final](https://user-images.githubusercontent.com/19143504/65028856-b440ec00-d977-11e9-8271-28abcae9d7d0.png width="100" height="100")

![FINAL_(3)](https://user-images.githubusercontent.com/19143504/65230306-9787ee00-db08-11e9-8c7d-5f043a0df806.gif)

3. Optical flow-based line feature tracking result.
![FINAL_(3)_result](https://user-images.githubusercontent.com/19143504/65230872-9e633080-db09-11e9-999e-5eb2bcc267b1.gif)

4. Sensitivity analysis diagram. 
The analysis was performed on two main categories: 
(1) The factor affecting the importance of individual features (feature-based factor). The factor considered for this is **the location in the 2D image plane**. 
(2) The factors affecting the relative importance between point and line features (sliding-window-based factors). **Average illumination** and **motion of sliding window** at time _t_ were used as input factors. 
![flow chart](https://user-images.githubusercontent.com/19143504/65228501-90131580-db05-11e9-9729-353deff82429.png)

5. Sensitivity analysis w.r.t the location in the 2D image plane.
![f_9](https://user-images.githubusercontent.com/19143504/65228517-9608f680-db05-11e9-9bd8-656212792acc.png)

6. Sensitivity analysis w.r.t the illumination.
![I_3](https://user-images.githubusercontent.com/19143504/65228566-aa4cf380-db05-11e9-97d8-c32c6ce0b248.png)

7. Sensitivity analysis w.r.t the motion.
![m_3](https://user-images.githubusercontent.com/19143504/65228591-b5a01f00-db05-11e9-98d4-faddd0c75319.png)

8. EXPERIMENTAL RESULTS

![FINAL_(4)(5)(6)(7)](https://user-images.githubusercontent.com/19143504/65231204-2ba68500-db0a-11e9-9aa0-e6e8f6c4b449.gif)
