### 4주차 - 자동차와 협업

## 학습 내용

# 절대 경로와 상대경로
- 절대 경로 : 루트(/)부터 시작하는 경로
- 상대 경로 : 현재 위치를 기준으로 하는 경로
- . : 현재 디렉터리
- .. : 상위 디렉처리
- ~ : 사용자 홈 디렉터리

# 파일 검색
- grep : 파일에서 특정 문자열 검색
- find : 조건에 맞는 파일 검색
- head : 파일 앞부분 출력
- tail : 파일 뒷부분 출력
- wc -l : 줄 수 확인

# 셸 스크립트
반복 작업을 자동으로 처리하기 위해 사용

## 실습 명령어

# 셸 스크립트 검색
find . -type f -name "*.sh"

# ERROR 문자열 검색
grep "ERROR" server.log

# ERROR 개수 확인
grep -c "ERROR" server.log

# 파일 앞부분 출력
head -2 diary.txt

# 파일 뒷부분 출력
tail -1 diary.txt

# 줄 수 확인
wc -l diary.txt

# Git 상태 확인
git status
