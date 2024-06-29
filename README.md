# Fishing_News_Detection

Abstract—대형 언어 모델이 대중적으로 사용됨에 따라 언론사는 낚시성 기사를 양산하고 있다. 게다가 낚시성 뉴스는 제목을 통한 클릭 유도와 본문에서 구매 유도를 하는 등 다양한 형태로 존재한다. 하지만 낚시성 기사 탐지는 주로 제목과 본문 간의 불일치를 탐지하는 방향으로 연구되어 왔다. 따라서 본 프로젝트는 본문 내 불일치도 함께 탐지할 수 있도록 새로운 모델링을 제안한다. 이는 특화된 데이터셋으로 학습한 모델들을 앙상블하는 기법이다. 이는 낚시성 기사 중 많은 수를 탐지하는 재현율(recall)에서 높은 성능을 보여주었다. 하지만 형태소 분석기와 모델 선정에 추가적인 연구가 이뤄진다면 성능을 향상시킬 수 있는 여지가 있다.

Keywords—낚시성 기사, 제목 낚시, 본문 낚시, 앙상블 기법, LightGBM

## 데이터셋: AI_Hub의 "낚시성 기사 탐지 데이터"
https://aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&dataSetSn=71338

본 데이터셋 중 EC(경제), PO(정치) 분야의 기사를 추출해서 프로젝트를 진행했습니다.
데이터셋에 대한 이해를 위해 '데이터구축 활용 가이드라인'을 참고하는 것을 추천합니다.

**데이터셋이 대용량이므로 직접 다운로드 받는 것을 추천합니다.**

---
### * 상세한 프로젝트 내용은 보고서를 확인해주세요.
### * 전반적인 프로젝트 결과 내용을 파악하고 싶다면 발표자료를 확인해주세요.
