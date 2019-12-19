# text-classification
text classification using NLP, ML, DL

# NLP, ML, DL을 활용한 문장 분류.

구현상의 특징:
1. 모델에 들어가는 target data의 형식이 N-hot encoding이므로, output layer의 활성화함수로 softmax가 아닌 sigmoid를 사용했습니다.
2. 모델의 성능향상을 위해서 word2vec로 단어임베딩을 하였습니다.
3. 성능 검증이 부족하며, 다양한 테스트 케이스가 필요합니다.

사용시 고려사항:
1. 모델 훈련시 수렴하기 위해서 hypterparameter의 조정 또는 모델의 layer 수정이 필요할 수 있습니다.
2. 데이터셋의 라벨의 빈도수가 불균형할 때 focal loss를 사용하면 수렴성이 향상될 수 있습니다.
