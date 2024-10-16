# AI Braille English-Korean Translator, E-yes

현재 적은 수의 교정자가 교정을 수작업으로 진행하기 때문에 시각장애인의 48%가 제작 소요 시간에 불만을 느낀다. 2021년 국립국어원의 점자 출판 실태조사에 따르면 점자 교과서·학습서 전체 48종에서 권당 약 15~20개 이내의 번역 오류가 있다. 이중으로 영어 점자와 한글 점자를 배워야 하는 어려움도 있어 시각장애인의 학습 권리가 침해되는 사례가 제기되고 있다. 

시각장애인들이 촉각을 사용하여 점자를 읽는 속도가 목독이나 청독보다 현저하게 느리다. 이에 따라, 문서 요약 서비스와 시각장애 학생들이 청독으로 학습하기 위한 음성 서비스가 필요하다.

본 프로젝트는 기존의 점자 교육 및 번역 서비스의 한계를 극복하기 위해 16가지의 다양한 번역 메커니즘과 문서 요약 기능을 제공하여 시각장애인의 학습자료의 접근성을 향상한다. 점역사의 번역작업을 자동화하여 정확하고 빠른 점역 및 교정을 지원한다. 음성파일을 제공하여 시각장애인의 학습 시간을 단축할 수 있다. E-yes는 시각장애인의 학습 효율을 높이고 학습자료 접근성 개선을 목적으로 한다.

## Details for UI/UX
시각장애인 대부분이 약시라는 사실에 기반하여 크고 명확한 UI, 반응형 디자인을 구현했다. 화면 페이지 수를 줄이고, 직관적인 기능, 명확한 작동방식을명시하는 것으로 사용자의 초기 앱 적응 비용을 최소화한다. 
시각장애인은 휴대폰 키보드의 STT 기능을 이용하거나 소장하고 있는 문서 파일을 첨부하여 텍스트를 입력할 수 있다.

<p align="center">
  <img src="https://github.com/user-attachments/assets/2687ff6e-fac8-4e62-a705-5fbe0b972aa6" width="450" />
  <img src="https://github.com/user-attachments/assets/0556451f-7212-4d3b-8e2f-abffebf4e7a5" width="450"/>
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/c48bdb1f-b4f7-4a6a-8865-7124393362bf" width="450"/>
  <img src="https://github.com/user-attachments/assets/bf1d475c-0e83-43cc-b805-e7b1bd8f9c79" width="450"/>
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/e3b147a5-0f57-4f13-9e4c-2eb3507df21c" width="450"/>
  <img src="https://github.com/user-attachments/assets/0df804f5-38bc-49b6-9dea-8bf845eab46a" width="450"/>
</p>


## Main Functions
- 점자 번역/역번역: 점자 텍스트를 묵자로 번역 및 묵자를 점자로 역번역
- 영어 ↔ 한글 번역: 영어 문장과 한글 문장간의 번역 변환
- 음성 파일 생성: 한글 및 영어로 된 문장을 음성 파일로 생성
- 교정문자 생성: 잘못 입력된 점자 및 문자를 인식하고 교정
- 문서 요약 : KoBART 모델을 활용한 문서 요약


## Paper
[ACK 2023, Development of a Braille Translation and Document Summarization System for the Visually Impaired Education](https://koreascience.kr/article/CFKO202333855044754.page)


## Website Video
[시연영상](https://www.youtube.com/watch?v=nr0ZrB_GpGo)


## Awards
🏆 2023 한이음 ICT멘토링 - 정보통신기획평가원장상(은상)

🏆 2023 ICT멘토링 한국정보처리학회 학술대회 (ACK 2023) - 최우수상
