# Read
## 1단계 Gstreamer 버젼 및 다운로드 링크

1. 버젼 : gst-launch-1.0 version 1.26.4
           GStreamer 1.26.4

1. 다운로드 링크 : https://gstreamer.freedesktop.org/download/#windows

<img width="872" height="266" alt="image" src="https://github.com/user-attachments/assets/36bb892e-1717-4768-87f4-25ae06588cee" />


- MSVC 64bit (VS2019, Release CRT)
    
    **runtime installer / development installer 둘 다 다운로드**
    
1. 설치 진행 모두 **“Complete” 선택하고 설치**
2. 설치 경로 (로컬기준) C:\Program Files\gstreamer\1.0\msvc_x86_64

---

## 2단계 c_cpp_properties.json / task.json 설정

1. Github에 아래 두 파일이 확인 후 복사
- setting_task.json
- setting_c_cpp_properties.json
1. 실행환경 Vscode에 맞게 붙여넣기
- c_cpp_properties.json
- task.json

---

## 3단계 컴파일 설정

1. Vscode에서 Microsoft C/C++ 확장 파일 다운로드

<img width="891" height="266" alt="image" src="https://github.com/user-attachments/assets/2c5f2794-9074-4d1a-95af-7ec0fd3c1aea" />


1. 2단계에서 c_cpp_properties.json / task.json 확인 후 

1. **X64 Native Tools Command Prompt for Vs 터미널 실행(**주의점 : Cmd, Vscode에서 터미널이 아님)
    
    <img width="853" height="457" alt="image" src="https://github.com/user-attachments/assets/8cccac19-5c23-4d84-9092-5836e945fbea" />

    
    ### 4. 컴파일
    
    1. 현재 레포지토리에서 컴파일 진행 해야함
    ex : cd C:\Users\장성욱\Desktop\ws\summer2025-team1\Gstreamer
    2. Complie_method.txt 에서 컴파일 내용 복사 붙여넣기
    3. 파일실행
