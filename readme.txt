1. 아나콘다 설치
2. adb 설치
https://developer.android.com/tools/releases/platform-tools?hl=ko
3. c 드라이브로 옮기고 환경변수 설정
(adb version)
4. vscode 설치
5. 아나콘다 프롬프트
 - conda create -n ~ python=3.10
 - conda activate ~
 - pip install opencv-python
 - pip install pytesseract
 - pip install tesseract
 - pip install jupyter
6. 블루스택에서 adb 켜기
(adb devices)
 - 연결 안되면 adb connect 127.0.0.1:5555
 - 에뮬레이터는 하나만 연결되어야 함
