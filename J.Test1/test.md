# 헤더
## 헤더2
### 헤더3
#### 헤더 4

# orderderd 리스트
1. 1번
2. 엔터 눌러보세요
   1. tab 누르면 2-1번
   2. 2-2번
3. 3번
4. 4번
5. 5번

# unorderd 리스트
+ -기호 또는 +기호 또는 * 기호
- 엔터
  - tab키 누르기
* undorderd 리스트

# 체크 리스트 만들기

- [x] 토스트
- [x] 당근
- [ ] 양파
- [ ] 라면

# 코드 블럭 백틱 3번
```python

print('hello world')

```

# 링크 url 걸기
[네이버](https://www.naver.com/)

# 이미지 걸기
![강아지](https://search.pstatic.net/common?type=f&size=518x522&quality=95&direct=true&src=http%3A%2F%2Fshop1.phinf.naver.net%2F20200822_58%2F1598068211616jwG0r_JPEG%2F34203820214884529_-1787092264.jpeg)

# 이미지 걸기2
![강아지](./dog.jpg)

# 굵게 표현하기
__굵은 글씨__
중간에 **굵은 글씨**를 넣기

# 기울기 표현하기
_기울기 글씨_
중간에 *기울기 글씨*를 넣기

# 굵게 및 기울임
___굵게 및 기울임___

중간에 ***굵게 및 기울임***을 넣기

# 취소선
~~취소선~~

# **수평선**
---
vs code에서 ctrl s 저장장
ctrl + b : 사이드바
ctrl + ` : 터미널 열기
ctrl + , : 설정 열기
ctrl + c : 취소소
# markdown 왜 배울까?
github에 프로젝트 올릴 때 **README.md** 파일에 활용

# I : interface -> 대상을 제어하는 수단
interface : 리모컨

GUI<-> TUI(Text User Interface)--- 잘 사용x
CLI = Command Line Interface

Window OS의 Interface
GUI = "Windows Shell"
CLI = "Power Shell", "명령프롬프트(cmd라고 불러요)"

Linux OS의 Interface
GUI : "GNOME"
CLI " "Bash"

Bash 왜 쓸까?
Bash가 가진 장점 : Bash가 편해서, Tab키 자동완성

Git 을 다룰 때 Interface
GUI : "Github Desktop", "소스트리"
CLI : git bash(엄청 많이 쓸 예정)

Git 쓸 때 GUI로 다뤄야 할까? CLI로 다뤄야 할까?
GUI 장점1 : 보기 편하다. 친숙하다.
GUI 장점2 : 복잡한 분석(Graph 같은 것을 훨씬 보기 좋다.)
CLI 장점1 : 빠르다(Commit 명령어 2~3초면 끝)
CLI 장점2 : 29년 전에 배웠으면, 현재도 쓰고 있고, 미래에도 쓸 예정

결론 : 둘다 써야하지만 대부분 CLI 쓸 예정
---
IDE? 
VScode : IDE?? No
텍스트 에디터 : 여기에 익스텐션을 추가해서 마치 IDE처럼 사용

IDE
Python : Pycharm, 쥬피터노트북
C# : Visual Studio
Java : IntelliJ
---
민지W : MINGW64
Minimal GNU for Windows
: 윈도우 환경에서 리눅스에 쓰이는 툴들을 쓸 수 있게 가볍게 만든 프로젝트
---
리눅스는 항상 HOME 디렉토리 : ~
cd ~ : 홈 디렉토리
cd - : 뒤로 가기
cd .. : 상위 디렉토리

touch : 파일 생성
mkdir : 폴더(디렉토리) 생성
start : 파일 열기
rm : 삭제
cp : 복사 (폴더 시 -r)

절대 경로 : ~/Desktop/practicce
상대 경로 : ./practice2
            ../practice/practice3
---
git : 분산 버전 관리 시스템

GIT : 로컬 저장소

Working Directory ->(git add) Staging Area(중간 준비 영역역)
->(git commit) Repository(영구 저장영역 모든 버전 이력과 변경기록 기록됨됨)

->(push) <-(pull)

GITHUB:원격 저장소
---
git init -> git 시작 master(brench명)가 뜨는지 확인
rm -rf .git : git 삭제(git 종료료)
git add . (전체 다 Staging area로 올리기)
git status:staging area 작업 파일 확인

git config --global user.name "이름"
git config --global user.email "이메일"
git config --global -l : 확인

git push 이후 자리 옮겼을 때 제어판의 windows 자격증명
-> 일반 자격 증명에서 github 삭제하기

git commit -m "메시지명" : repository에 올리기
get log : repository 작업 파일 확인(커밋 되어 있는지 확인)
---
