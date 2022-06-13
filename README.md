# 코로나 챗봇

BERT를 사용한 코로나 질문 답변 AI 설계


1. 질문-답변 pair 수집 (WHO 및 한국질본 공식 질문-답변)  
2. 각 질문별 비슷한 문장 생성 (수작업)
3. KoBERT를 이용한 Classification Model Fine Tuning
4. Siamese LSTM Network를 이용한 Similarity based model 훈련 (질문 추가를 좀 더 쉽게)
