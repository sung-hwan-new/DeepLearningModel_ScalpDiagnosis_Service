# 딥러닝을 통한 두피 진단과 두피케어 제품 추천 서비스 개발

![image](https://github.com/user-attachments/assets/cc8ff21d-bbc8-4392-8ac6-1b7986b70c03)

### 목적
최근 모 업체의 조사에 따르면 우리나라 20~50대 성인의 약 60%는 두피 문제를 고민하고 있습니다. 하지만 약 1/4은 정보 부족 때문에 관리의 어려움을 호소합니다. 하지만 전문 시설을 통한 두피 진단은 번거로울 뿐 아니라 많은 비용이 발생합니다. 간편한 증상 진단과 제품 추천을 통해 두피 관리에 대한 진입장벽을 낮추고자 서비스를 개발했습니다.

### 데이터
- 두피 증상별, 중증도별 이미지(Train 168,430건 / Validation 48,116건)(AI Hub)
- 올리브영 헤어 카테고리 제품 정보 크롤링(1,261건)(올리브영)
- 제품 페이지, 제품 링크, 이미지 주소, 브랜드 이름, 제품 이름, 별점, 리뷰 개수, 성분

### 서비스 개요
1. PC/Mobile에서 사용자의 두피 사진 업로드
2. 설문조사 진행(두피 타입 선택, 두피 고민/질환 선택, 추천 제품 선택)
3. 사용자 사진을 통한 두피 진단(6가지 증상, 3단계 중증도를 확률로 출력)
4. OpenAI를 통한 ChatGPT로 원인, 특징, 관리 방법 안내
5. 진단 결과 및 설문에 따른 제품 추천 및 증상에 유효한 성분 안내

### 결과(Model Accuracy)
- 모낭 사이 홍반(93.2%), 모낭 홍반 농포(89.5%), 미세 각질(84%), 비듬(92.7%), 탈모(93.5%), 피지 과다 (92.6%)

### 세부 내용
[<img src="https://img.shields.io/badge/Velog-1EBC8F?style=for-the-badge&logo=velog&logoColor=white" />](https://velog.io/@sung_hwan_new/CnnDeepLearningScalpDiagnosis)
[<img src="https://img.shields.io/badge/Adobe%20PDF-FF0000?style=for-the-badge&logo=adobe&logoColor=white" />](https://github.com/sung-hwan-new/DeepLearningModel_ScalpDiagnosis_Service/blob/main/Presentation.pdf)
[<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" />](https://9tcrmtebpkzuvxi8c6srx5.streamlit.app/)




