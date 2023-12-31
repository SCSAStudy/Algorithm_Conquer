## 🤓 Algorithm_Conquer 알고리즘 정복하기 스터디 !

<br> 

### 📝 스터디 운영
1. 1일 1개 기출 문제 풀이 : 개인 Branch 활용 (일요일 휴식)
2. 주 1회 온라인 미팅 진행 : 문제풀이 질의 및 Merge 단계

<br> 

### 💻 학습 진행

1. 취침 전 익일 문제를 당번이 Issue에 업데이트.
   - 당번 순서 : 서요셉 > 윤다영 > 손록형 > 손동우 > 김민성
   - 출제 범위 : <[프로그래머스](https://programmers.co.kr/)> LV1 ~ LV3 | <[코드트리](https://www.codetree.ai/training-field/frequent-problems)> 삼성기출문제 위주 | <[백준](https://www.acmicpc.net/workbook/view/1152)> 특정 알고리즘이나 구현력에 도움되는 문제 위주. | <[SWEA](https://swexpertacademy.com/main/main.do)> D3 이상
2. 이후 개인 브랜치에서 문제 풀이 진행.
3. 제출된 문제 사이트 폴더 내의 `문제 이름 폴더` 생성.
4. 해결한 문제는 `문제명_본인이름`으로 본인 브랜치에 업데이트.
   - 예시 : 아기상어_서요셉.java
5. 커밋메시지 컨벤션은 다음과 같이 진행.
   - 해결한 경우 : `#문제이슈번호 add: solved 문제명`
   - 해결하지 못한 경우 : `#문제이슈번호 add: unsolved 문제명`
6. 문제 파일은 파일간 충돌을 최소화하기 위해 다른 폴더에서 클래스 파일 작성 후 해당 레포지토리에 복사,붙여넣기로 진행.
7. 주 1회 리뷰 후 Pull Request - Merge.

<br> 

### 📂 폴더 구조
```
Study Git
│
├─ Baekjoon
│ └─ <문제별>
│
├─ 프로그래머스
│ └─ <문제별>
│
├─ CodeTree
│ └─ <문제별>
│
└─ SWEA
  └─ <문제별>
```
- 양식 : `/사이트명/문제이름/`
  - 특수기호, 문제번호, 공백 없이 문제의 원본 이름 그대로 작성.
- 예시
  - 백준 : /Baekjoon/아기상어
  - 코드트리 : /CodeTree/돌아가는팔각의자
  - SWEA : /SWEA/문자열세개

<br>

### ➡️ 브랜치 방식
```
main
└─ <스터디원 이름>_<주차>
```
- 주차 : 1week, 2week, ... Nweek
- ex) YOSEPH_1week, YOSEPH_2week ... 

<br> 

### ✏️ 커밋 메시지
- 양식 : `#<문제이슈번호> add: <풀이여부> 문제명`
  - 풀이여부 : (PASS 시) solved, (FAIL ) unsolved
- 예시 : #1 add: solved 아기상어

<br> 

### 📃 코드리뷰
- 매주 수요일 11:00 PM에 1회 진행하며, 한 주 내 진행한 문제 리뷰.
- 해결하지 못한 문제 혹은 풀이 방법을 공유.
- 리뷰가 종료되면, Pull Request로 Merge합니다.
- 양식 : `[N주차] 문제풀이`
