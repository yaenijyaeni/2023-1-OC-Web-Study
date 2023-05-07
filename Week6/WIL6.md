# 2023-1-OC-Web-Study
2023년 1학기에 진행된 OC 기초 웹 스터디 커리큘럼 과제 제출입니다.

## 🌞 오늘은 뭘 배웠을까? 🌞

***

#### 🫧 블록 레벨 요소
- 태그로 요소를 삽입할 때, 하나의 요소가 한 줄을 차지하는 것 즉, 해당 요소의 너비는 100%
- vs 인라인 레벨 요소: 줄을 차지하지 않는 요소
***

#### 💗 박스 모델 요소
- 구성: border, content, padding(content와 border 사이의 간격), margin(요소와 다른 요소 사이의 여백)


***

#### 🫧 그 외 우리가 눈 여겨 볼 아이들
- div flex-box: 🐸개구리🐸를 🍀연잎🍀 위로 옮기면서 알아보기 전에, 문법 몇 가지만 알고 가자 ‼️


***

#### 🐸: 우리를 어떻게 해당 연잎 위로 옮기는지 궁금해 !
- justify-content
🤍flex-start: 컨테이너 왼쪽으로 정렬

🤍flex-end: 컨테이너 오른쪽으로 정렬

🤍center: 컨테이너 가운데로 정렬

🤍space-between: 요소들 간의 동일한 간격 두기

🤍space-around: 요소들 주위에 동일한 간격 두기


- align-items
💚flex-start: 컨테이너 꼭대기로 정렬

💚flex-end: 컨테이너 바닥으로 정렬

💚center: 컨테이너의 세로선의 가운데로 정렬

💚baseline: 컨테이너 시작 위치에 정렬

💚stretch: 컨테이너에 맞도록 늘리기


- flex-direction
🤍row: 텍스트의 방향과 동일하게 정렬

🤍row-reverse: 텍스트의 반대로 정렬

🤍column: 위 -> 아래 정렬

🤍column-reverse: 아래 -> 위 정렬


- flex-wrap
💚nowrap: 모든 요소 한 줄에 정렬

💚wrap: 여러 줄로 정렬

💚wrap-reverse: 여러 줄에 걸쳐 반대로 정렬


***

#### 🐾FLEXBOX FROGGY 답

- 1. justify-content: flex-end;
- 2. justify-content: center;
- 3. justify-content: space-around;
- 4. justify-content: space-between;
- 5. align-items: flex-end;
- 6. align-items: center; justify-content: center;
- 7. justify-content: space-around; align-items: flex-end;
- 8. flex-direction: row-reverse;
- 9. flex-direction: column;
- 10. flex-direction:  row-reverse; justify-content:  flex-end;
- 11. flex-direction: column; justify-content: flex-end;
- 12. flex-direction: column-reverse; justify-content: space-between;
- 13. flex-direction: row-reverse; justify-content: center; align-items:flex-end;
- 18. flex-wrap: wrap;
- 19. flex-direction: column; flex-wrap: wrap;
- 20. flex-flow: column wrap;