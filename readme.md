![Cover (7)](https://github.com/user-attachments/assets/b811da05-4c31-4d79-9adb-5d13aa284a85)



### **1 스트림릿 소개**

### **2 스트림릿 초기 셋팅**

- 파이썬 가상환경 설정  https://github.com/dabidstudio/dabidstudio_guides/blob/main/python-set-venv.md
- 스트림릿 패키지 설치

### **3 스트림릿 텍스트 출력**

### **4 스트림릿 레이아웃**

### **5 스트림릿 위젯**

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
    

https://docs.streamlit.io/develop/api-reference/widgets

### **6 세션 상태**
