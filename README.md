# virtual_enviroment
## Python 가상환경 설정
- python -m venv [가상환경이름] : 해당이름으로 가상환경설정
- [가상환경이름]/Scripts/activate : 가상환경 실행
- pip list : 가상환경 설치된 라이브러리 확인
- [가상환경폴더]/Lib : 설치된 라이브러리 확인가능
## ![image](https://user-images.githubusercontent.com/54635552/178024605-524ad623-2069-48fc-a615-92fa247d88f6.png)
- pip install [패키지이름] : 패키지 설치
- pip freeze > requirements.txt : 내가 설치한 패키지를 다른사람이 설치하기 편하도록 설치한 패키지목록 requirements.txt로 생성
## ![image](https://user-images.githubusercontent.com/54635552/178024998-be4f5379-c85a-4f43-b825-e98ebb791ca9.png)
- Scripts/deactivate : 가상환경 종료
- pip install -r requirements.txt : 해당 목록에 있는 라이브러리 설치하기
