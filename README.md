# 월간 데이콘 Computer Vision 이상치 탐지 알고리즘 경진대회

데이콘에서 주최한 Computer Vision 딥러닝 프로젝트 참여 코드입니다.

score : public score : 79.0 private score : 80.3 (상위 9%)

### Members

- 정영운
- 남민우
- 박성연

### problems

- image augmentation, tta 기법을 주로 썼습니다.
- 원래 label별 good과 bad를 100개씩 oversampling하여 efficientnet에 측정했으나 결과가 좋지 않았습니다.
- 기본 resnet50, CNN, tinyVGG 모델 또한 기본 efficient 모델보다 성능이 좋지 않았습니다.
- 최종적으로 argumentation을 code 안에 넣어줌으로서 해결했습니다.

### 아쉬운 점

- 시간이 없어서 ensemble, 5-folds 같은 기타 기법을 쓰지 못해 아쉬웠습니다.
- 첫 팀장이었던 만큼 모든 걸 다 도맡아 하려 했기에 팀원들에게 약간 소홀했던 점이 있었습니다.
