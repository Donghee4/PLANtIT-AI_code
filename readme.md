## 파일 목록 ##
ResNet 작물 질병, ResNet 작물 심각성, ResNet 작물 질병, 커스텀모델-고추_테스트용

### 프로젝트에 사용한 모델 2가지 ###
**작물의 질병이름과 risk(진행정도)를 나타내기 위해 모델 2가지를 사용함**
1. ResNet 작물 질병 : 작물의 질병을 분류하기 위한 모델 [<u>핵심모델</u>]
2. ResNet 작물 심각성 : 작물의 심각성(risk)를 분류하기 위한 모델

### 사용되지 않은 모델 2가지 ###
<u>작물의 이름은 모델을 구축했으나 필요없어서 사용하지 않음</u>

1. 커스텀모델-고추_테스트용 : 시도했으나 낮은 정확성을 이유로 탈락시킨 모델
2. ResNet 작물 이름 : 작물의 종류를 분류함. 하지만 질병 분류 모델에서 이름을 알 수 있으므로 사용하지 않음