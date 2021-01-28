# Posedetection_silverYoga
https://silversquat.netlify.app/

실버요가 앱에서 사용하는 동작인식 시스템이다.
실시간으로 동작을 인식해서 동작의 정확도를 알려준다.
신체에 있는 16개의 key값을 인식하여 정확도를 산출한다.


Google Creative team의 Teachable Machine을 이용해서 구현했다.

(https://teachablemachine.withgoogle.com/)


Teachable Machine의 포즈 인식 기능을 이용하여 스쿼트 자세의 정확도를 판별하도록 했다.

Silver Yoga에서 사용할 기능은 요가 동작의 정확도를 테스트하는 것이므로, 요가 동작을 학습시켜서 사용하면 된다.
학습방법은 Teachable Machine 웹사이트에 잘 설명 되어있다. Pose 부문을 활용하여, 웹캠 혹은 크롤링 이미지를 통해 학습시키게 된다.

해당 웹사이트는 Netlify를 이용하여 Deploy하였다.

