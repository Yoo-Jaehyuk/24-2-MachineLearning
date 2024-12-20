# 24-2-MachineLearning

![스크린샷 2024-12-20 221417](https://github.com/user-attachments/assets/bb97c644-516e-42da-9a4d-b6a35051192b)

![스크린샷 2024-12-20 221537](https://github.com/user-attachments/assets/060c7a8e-fb10-4abf-b891-93f875350132)
(교수님께 보낸 이메일 주소와 동일한 이메일 주소를 Leetcode 이메일주소로 저장해놨습니다.)

음악의 장르 간의 경계는 점차 허물어지고 있습니다.
제 경우에는 힙합 음악을 듣는 것을 가장 좋아하는데 R&B와의 구분이 모호해진지는 거의 10년이 다 돼가고 락, 팝, 컨트리뿐만 아니라 클래식 음악과도 섞이고 있습니다.
저는 이런 음악의 변화에 있어서 머신러닝을 통해 음악의 장르를 찾아주는 것은 어떨까 하고 만들게 되었습니다.
앞으로 보여드릴 코드는 다양한 음악 오디오 데이터를 스펙토그램으로 바꾸고 이를 이미지트레이닝하여 음악의 장르를 분석해주는 코드입니다.

기본적으로 학습을 위한 데이터는
https://www.kaggle.com/code/andradaolteanu/work-w-audio-data-visualise-classify-recommend/notebook
여기서 가져왔습니다.

![image](https://github.com/user-attachments/assets/95b6a5e9-53d8-4859-9829-0b091f537037)
![image](https://github.com/user-attachments/assets/80507a49-001a-4133-967a-2e5e23057683)
![image](https://github.com/user-attachments/assets/8f654754-a7eb-4ef2-b978-daa701bc5da6)
![image](https://github.com/user-attachments/assets/e9a4ade5-3564-48e1-bcd2-836dfd5c1678)
(딥러닝 코드입니다.)

![image](https://github.com/user-attachments/assets/61f0b688-fab9-492d-b4d4-af8ac9f86541)
![image](https://github.com/user-attachments/assets/87cd09a0-f388-4187-9357-1a841698828b)
![image](https://github.com/user-attachments/assets/9782678f-99c1-4462-8020-99b795209c5e)
(스펙토그램 이미지를 받아서 예측하는 함수 하나와
마찬가지로 이미지를 받고 예측한 다음에 사용자에게 답안을 확인받고 이를 데이터셋에 추가하는 함수입니다.)

![image](https://github.com/user-attachments/assets/50d90043-b282-44d4-b603-5e44095b0888)
![image](https://github.com/user-attachments/assets/1cd1428c-fff3-4184-9b1f-c2d0f442783b)
(결국 오디오를 이미지로 변환하는 과정이 필요한데 오디오를 이미지로 변환하는 방법은 데이터셋 출처에 올라와있는 코드를 참고하여 작성하였습니다.
실제로 작동해봤을 때 rock을 disco로 잘못 해석하긴 했지만 작동 자체에는 문제가 없는 것으로 보입니다.)


