# 노트북 실행 순서

팀이 정리한 실행 순서를 그대로 옮겼습니다. 코랩과 주피터를 함께 사용했기 때문에, 파일을 불러올 때 경로를 환경에 맞게 바꿔야 할 수 있습니다.

## 피처 생성

1. `notebook/2nd feature/2.2nd_feature.ipynb`
2. `notebook/2nd feature/3.3rd_feature.ipynb`
3. `notebook/2nd feature/4.min_1st_feature.ipynb`
4. `notebook/2nd feature/5.min_2nd_feature.ipynb`
5. `notebook/2nd feature/feature_merge.ipynb`
6. `notebook/2nd feature/피쳐셀렉션 (1).ipynb`
7. `notebook/2nd feature + vector/피처+w2v.ipynb`
8. `notebook/2nd feature + vector/Catboost용 피처.ipynb`

## 모델링

9. `notebook/2nd feature + vector/CatBoost_version3 (1).ipynb`
10. `notebook/2nd feature + vector/Cat_범주형추가모델.ipynb`
11. `notebook/2nd feature/DNN.ipynb`
12. `notebook/2nd feature + vector/DNN_vector.ipynb`
13. `notebook/2nd feature/LGBM.ipynb`
14. `notebook/2nd feature/CatBoost_version3_0612scale후.ipynb`
15. `notebook/2nd feature/ktrain_mlp_ensemble.ipynb`
16. `notebook/2nd feature + vector/민수_mlp_ktrain_mlp_ensemble.ipynb` (여기서 나온 제출 파일을 다음 앙상블 단계에서 사용합니다.)

## 앙상블

17. `notebook/2nd feature + vector/mlp_23개피처_앙상블코드.ipynb`
18. `submission/ensemble/comp_mean_ensemble.ipynb`

`notebook/2nd feature/comp_mean_ensemble_mlp.ipynb`는 위 순서에는 없지만, 앙상블을 실험하며 함께 만든 노트북이라 같이 남겼습니다.

`src/`의 word2vec 스크립트는 7번 단계에서 브랜드·코너·파트·상품·고객정보 수준별 임베딩 피처를 만들 때 사용한 코드입니다.
