# OStermproject

## opencv module을 활용하여 특정 인물의 얼굴을 학습 시킨 후 학습 시킨 얼굴만 컴퓨터의 내장 카메라를 이용하여 실시간 모자이크 처리하는 프로그램
## 시연 영상
### 시연 영상은 본 repository에 시연영상.mkv로 업로드 되어있습니다.

## 실행 방법
### 1. test_src의 test_detect_face.py를 실행시키고 노트북 카메라에 얼굴이 잘 나오게 있으면 카메라가 학습 데이터로 쓰일 얼굴 사진 100장을 찍어서 test_db에 저장합니다.
### 2. test_src의 test_train_face,py를 실행시키면 recognizer 모델을 훈련 시키고 그 결과를 face-trainer.yml에 저장합니다.
### 3. test_src의 test_face_dec.py를 실행시키면 노트북의 내장 카메라가 실행되면서 학습 시킨 특정 얼굴만 네모를 띄우고 모자이크 처리를 합니다.

## 참고 자료
### 파이썬#90 - 파이썬 opencv 로 얼굴 인식, 얼굴 자동 모자이크, https://blog.naver.com/PostView.naver?blogId=nkj2001&logNo=222747037611
### LBF를 이용한 얼굴 인식, https://kau-deeperent.tistory.com/53
### [opencv]얼굴 인식 프로그램, https://velog.io/@ch9eri/openCV-%EC%96%BC%EA%B5%B4-%EC%9D%B8%EC%8B%9D-%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%A8
