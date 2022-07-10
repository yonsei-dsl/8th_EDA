# Reference  

link: [Google play store dataset](https://www.kaggle.com/datasets/lava18/google-play-store-apps?select=googleplaystore.csv)

# 데이터 설명  
Google play store에 존재하는 앱들의 여러 정보를 포함하고 있는 데이터셋   

(ex. 앱 이름, 평점, 리뷰, 가격 등)  

# 데이터 변수
## googleplaystore.csv

- App : 앱 이름  
- Category : 앱의 카테고리 
- Rating : 평점  
- Reviews : 리뷰 수
- Size : 크기
- Installs : 설치 수
- Type : 유료/무료 여부
- Price : 가격 (무료인 경우 0)
- Content Rating: 이용 나이 
- Genres : 앱의 장르 (카테고리와 거의 동일)
- Last Updated : 최근 업데이트 일 (19년도 기준)
- Current Ver : 현재 버전
- Android Ver : 안드로이드 버전  

## googleplaystore_user_reviews.csv  
- App : 앱 이름
- Translated_Review : 리뷰(eng)
- Sentiment : 감정 (Positive/Negative/Neutral(Preprocessed))
- Sentiment_Polarity : Sentimant polarity score
- Sentiment_Subjectivity : Sentiment subjectivity score
   - Polarity : (p-n)/(p+n)
   - Subjectivity : (p+n)/N
      * p : 긍정 단어의 수
      * n : 부정 단어의 수
      * N : 단어의 수