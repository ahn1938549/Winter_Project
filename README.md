# Winter_Project

도서관 분류 작업을 위한 알고리즘이 필요하다고 생각하여 기획하였음
현재 캡스톤으로 도서관 라벨 관리 기기를 만들 예정
![디자인2](https://user-images.githubusercontent.com/69898343/153860306-59075914-2293-4d05-b2f9-520574a2344c.png)
![qweww](https://user-images.githubusercontent.com/69898343/155981143-40c8e59a-dde9-4a52-b427-761e4f899b0e.png)


## DataSet

1048576개의 데이터셋
10개의 라벨

국립도서관 Open Dataset
[https://www.culture.go.kr/bigdata/user/data_market/detail.do?id=63513d7b-9b87-4ec1-a398-0a18ecc45411]

## Model

LSTM, Dense



## 최종목표

책 제목에 따라 자연과학, 인문 등의 분류를 나누어 라벨링에 활용하도록 할 예정
![123](https://user-images.githubusercontent.com/69898343/155983931-bfdc28cd-a2db-45a3-a6fc-ce11a6ef74b9.png)

![qwqwe](https://user-images.githubusercontent.com/69898343/155984477-fc0c761b-b4b9-4bba-8c98-9188ef05b7b7.png)


## 고찰

데이터셋을 직접 만드는 과정에서 많은 더미 데이터와 분류가 정확하게 되어있지 않은 라벨 작업중인 데이터들을 직접 값을 입력해야 해주는 시간이 많이 걸렸으며
제공하는 한국어 모델들을 적용하여 사용하여 보았으면 조금 더 좋은 결과가 나오지 않았을까 생각합니다.
또한, 생각보다 단어중 한번만 나오고 마는 단어들이 많아 학습하기에 좋은 효과를 얻기 어려웠습니다.

