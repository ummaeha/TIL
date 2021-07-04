# 📝TIL(Today I Learned) 
사실은

Today [X]

This week [O]



**2021 1학기 캡스톤 프로젝트를 위한 공부내용 정리**

목표: 일주일에 2챕터 공부하기

분야: natural language processing



출처: https://wikidocs.net/21690



챕터

1. ~~자연어 처리(natural language processing)란?~~
2. ~~텍스트 전처리(Text preprocessing)~~
3. ~~언어 모델(Language Model)~~
4. 카운트 기반의 단어 표현(Count based word Representation)
5. 문서 유사도(Document Similarity)
6. 토픽 모델링(Topic Modeling)
7. 머신 러닝(Machine Learning) 개요
8. 딥 러닝(Deep Learning) 개요
9. 순환 신경망(Recurrent Neural Network)
10. 워드 임베딩(Word Embedding)



#1주차: 1강 ~ 2.5강 (01/04/2021 - 01/10/2021)

내용 정리: https://www.notion.so/2-Text-preprocessing-8335d1f99b8f47d3b2d40d586dafeb8e

한 줄 소감: 쥬피터 노트북에서 shift + enter 누르면 코드 실행되는거 넘 어색하다.

예제 코드 실행시, Resource punkt not found 오류나서, ipython 콘솔에서 import nltk; nltk.download('punkt'); 설치해서 해결!


#2주차 2.5강~3강 (01/11/2021 - 01/17/2021)

내용 정리: https://www.notion.so/3-Language-Model-a8df7f2db81a4522b440c354dc39ba2d

한 줄 소감: 확률이고, 제곱근이고 다 잊어버린 내 머리 덕분에 수학공부해따...  PPL 값이 작을 수록 정확도가 높다는 것이 인상깊었따.(마치 엔트로피같은 ..! ) 아 그리고, PPL로 테스트 데이터로 인한 정확도를 측정할수는 있지만, 그 것이 반드시 사람이 느끼기에 좋은 언어모델이라는 것을 의미하지 않는다니.. 지금 이순간에도 사람이 느끼기에 좋은 언어모델이 될 수 있도록 측정할 수 있는 모델에 대해 고민하고 있는 사람이 있겠구나 싶었다. 

궁금증: PPL에 n-gram을 적용했을때의 식에대해 궁금한 점이 생겼다., 글 설명에서는 PPL의 테스트 데이터에 대한 확률 부분을 n-gram식으로 대체해놓고 bigram의 예제라고 말해놓았는데, 나는 그 식이 모든 n-gram에 적용되는 식이라고 생각했다. 서영이한테 물어봐야징..

![Screen Shot 2021-01-24 at 6.35.46 PM](/Users/yangha/Library/Application Support/typora-user-images/Screen Shot 2021-01-24 at 6.35.46 PM.png)

=> N자리에 2가 들어가야할 것 같다는 것이 결론

#3주차 4강~5강 (01/18/2021 - 01/24/2021)


<h3>=> colab & notion으로 이동 ~ 🏃‍♀️</h3>
**google colab:** https://drive.google.com/drive/u/2/folders/1Pko07cHuUaxEYtC4zMAIwStwIBtpHGOV <br/>
**Notion:** https://www.notion.so/ca974669acde44ca94ca01a913e4cc0d <br/>
