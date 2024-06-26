# make_pictogram_human-pose-estimation

googlenet, openpose 모델 활용 MATLAB 예제 코드에 추가적으로 영상처리 코드 개발

|  | 멀티미디어신호처리 기말 1인 프로젝트 | 
| --- | --- |
| 제목 |Matlab Deep Learning & Computer Vision ToolBox를 활용한 pictogram maker |
|학번/이름|C015143 / 이수빈 |
| ToolBox 사용 여부/ Add-on| Deep Learning, Computer Vision, Image processing Toolbox / Deep Learning Toolbox Converter for ONNX Model Format, Deep Learning Toolbox Model for GoogLeNet Network/ OpenPoseNet Network |
| 구현 예제 site 주소| https://kr.mathworks.com/help/vision/ug/estimate-body-pose-using-deep-learning.html#EstimateBodyPoseUsingDeepLearningExample-3 <br> https://kr.mathworks.com/help/deeplearning/ug/classify-image-using-googlenet.html|
| 문제 정의 |로봇 기술에 중요한 Mashine Vision <br> deep learning을 이용한 body pose 측정, Image processing and Computer Vision|
| 방법론 | 1. openposenet 신경망을 이용한 input의 body pose를 측정 <br> 2. body pose에 shape을 넣어 skeleton을 픽토그램화 <br> 3. 이진영상 필터링으로 픽토그램만 남기고 흰 배경 처리 <br> 4. googlenet 신경망을 통해 사진의 스포츠 종목을 판단, 픽토그램 공 위치 결정|


## 결과
  
* 축구 사진 결과
  
  <img src="https://github.com/subin111/human_pose_estimation/assets/143717650/947e5bcb-b66f-4009-b199-be7b1d713775" width="350" height="450" />
  <img src="https://github.com/subin111/human_pose_estimation/assets/143717650/0ece45f4-e127-4b44-9285-4799d4d1e232" width="350" height="450" />
  <img src="https://github.com/subin111/human_pose_estimation/assets/143717650/d3ffea21-402f-4028-b7c7-d8529be1f759" width="350" height="450" />
  <img src="https://github.com/subin111/human_pose_estimation/assets/143717650/4d76f1e7-e0dd-4e24-9f32-9571176928c8" width="350" height="450" />
  <img src="https://github.com/subin111/human_pose_estimation/assets/143717650/14f0f26e-4b49-4db6-83c4-c3cea297a365" width="350" height="450" />
  <img src="https://github.com/subin111/human_pose_estimation/assets/143717650/4f1d9e12-e98f-4d67-a9fe-392fd424e996" width="500" height="450" />
  <img src = "https://github.com/subin111/human_pose_estimation/assets/143717650/e3a3aca5-4518-438a-866c-198e96db35e4" width="350" height="450" />
  <img src="https://github.com/subin111/human_pose_estimation/assets/143717650/0e56a6ae-2592-4719-99df-baf70a5d73e8" width="350" height="450" />

  
  * 배구 사진 결과

    <img src="https://github.com/subin111/human_pose_estimation/assets/143717650/8d45f7e2-db4f-408a-b05e-5ac9f71b1e2c" width="350" height="450" />
    <img src="https://github.com/subin111/human_pose_estimation/assets/143717650/a797ef18-8ff2-4641-a8d0-6fd86853b143" width="350" height="450" />
    <img src="https://github.com/subin111/human_pose_estimation/assets/143717650/ded12583-2a09-4b50-9449-e5d1ab676d08" width="350" height="450" />
    <img src="https://github.com/subin111/human_pose_estimation/assets/143717650/a45ce7e0-54c6-47d3-b475-5c1ee1a7a8db" width="350" height="450" />
    <img src="https://github.com/subin111/human_pose_estimation/assets/143717650/0d5222cd-27f7-4caf-92c5-cb1c2a5e1109" width="350" height="450" />
    <img src="https://github.com/subin111/human_pose_estimation/assets/143717650/74c88d34-949c-4aed-9825-67171f4c7864" width="500" height="450" />
    <img src="https://github.com/subin111/human_pose_estimation/assets/143717650/46f85b24-74e1-4d05-af28-5222c65743a6" width="350" height="450" />
    <img src="https://github.com/subin111/human_pose_estimation/assets/143717650/c47cbd6c-732b-4b88-9857-5549588ec874" width="350" height="450" />









    

    
