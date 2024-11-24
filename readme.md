![Cover (7)](https://github.com/user-attachments/assets/b811da05-4c31-4d79-9adb-5d13aa284a85)


### **1 스트림릿 소개**

- 스트림릿 홈페이지 : https://streamlit.io/
- 스트림릿 깃허브 페이지 : https://github.com/streamlit/streamlit

### **2 스트림릿 초기 셋팅**

- 파이썬 가상환경 설정  https://github.com/dabidstudio/dabidstudio_guides/blob/main/python-set-venv.md https://youtu.be/Osu2M7QmgCQ?feature=shared
- 스트림릿 패키지 설치
    
    ```python
    pip install streamlit
    ```
    
- streamlit 예제코드 (test.py)
    
    ```python
    import streamlit as st
    st.write("안녕하세요")
    ```
    
- streamlit 코드 실행하기
    
    ```bash
    streamlit run test.py
    ```
    

### **3 스트림릿 텍스트 출력**

- 마크다운 소개영상 : https://youtu.be/GARAX8VuNXE?feature=shared

### **4 스트림릿 레이아웃**


### **5 스트림릿 위젯**

- 스트림릿 위젯소개 페이지 : https://docs.streamlit.io/develop/api-reference/widgets
1. 버튼 위젯
2. 입력 위젯 
3. 선택형 위젯
4. 파일 위젯
    
    ```jsx
    import streamlit as st
    
    uploaded_file = st.file_uploader("파일을 업로드하세요")
    if uploaded_file:  # ①
        st.write(uploaded_file.name)  # ②
        file_content = uploaded_file.read().decode("utf-8")  # ③
        st.write(file_content)  # ④
    
    ```
    

### **6 세션 상태**
