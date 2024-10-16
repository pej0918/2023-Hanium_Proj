## AI Braille English-Korean Translator, E-yes

### Project Introduction
본 프로젝트는 기존의 점자 교육 및 번역 서비스의 한계를 극복하기 위해 16가지의 다양한 번역 메커니즘과 문서 요약 기능을 제공하여 시각장애인의 학습자료의 접근성을 향상한다. 점역사의 번역작업을 자동화하여 정확하고 빠른 점역 및 교정을 지원한다. 음성파일을 제공하여 시각장애인의 학습 시간을 단축할 수 있다. E-yes는 시각장애인의 학습 효율을 높이고 학습자료 접근성 개선을 목적으로 한다.

### Service Scenario
E-yes 는 사용자가 입력한 텍스트를 바탕으로 번역 및 문서 요약 결과를 생성한 후, 그 결과를 웹 화면에 나타낸다. <br>
사용자는 한글, 영어, 한글 점자, 영어 점자 중 원하는 입출력 언어를 선택할 수 있으며 E-yes 는 16 가지의 번역 메커니즘을 제공한다. <br>
또한, 추가로 맞춤법 검사를 진행할 수 있다. 이러한 기능은 전문 점역‧교정사의 작업을 자동화하여 정확하고 빠른 점자 번역과 교정을 돕는다. <br>
문서 요약의 경우, KoBART 모델을 통하여 문서를 요약한다. 서비스 결과는 PDF 파일 혹은 결과를 텍스트 및 음성으로 제공하며, 사용자는 docx 파일 및 MP3 파일로 다운로드 받을 수 있다. <br>
시각장애인은 E-yes 에서 제공하는 문서 요약 기능과 음성 파일을 사용하여 학습 자료 습득 속도를 높일 수 있다.

### Details for UI/UX
시각장애인 대부분이 약시라는 사실에 기반하여 크고 명확한 UI, 반응형 디자인을 구현했다. 화면 페이지 수를 줄이고, 직관적인 기능, 명확한 작동방식을명시하는 것으로 사용자의 초기 앱 적응 비용을 최소화한다. 
시각장애인은 휴대폰 키보드의 STT 기능을 이용하거나 소장하고 있는 문서 파일을 첨부하여 텍스트를 입력할 수 있다.

### Main Functions
- 점자 번역/역번역: 점자 텍스트를 묵자로 번역 및 묵자를 점자로 역번역
- 영어 ↔ 한글 번역: 영어 문장과 한글 문장간의 번역 변환
- 음성 파일 생성: 한글 및 영어로 된 문장을 음성 파일로 생성
- 교정문자 생성: 잘못 입력된 점자 및 문자를 인식하고 교정
- 문서 요약 : KoBART 모델을 활용한 문서 요약

<img src="https://github.com/user-attachments/assets/b82fc716-bece-4ab2-be97-f295df9dde91" width="600" height="500"/>


### Paper
[ACK 2023, Development of a Braille Translation and Document Summarization System for the Visually Impaired Education](https://koreascience.kr/article/CFKO202333855044754.page)


### Website Video
[시연영상](https://www.youtube.com/watch?v=nr0ZrB_GpGo)


### Awards
🏆 2023 한이음 ICT멘토링 - 정보통신기획평가원장상(은상)

🏆 2023 ICT멘토링 한국정보처리학회 학술대회 (ACK 2023) - 최우수상
