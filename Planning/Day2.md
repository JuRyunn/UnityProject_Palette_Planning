## 게임 최적화
- 이동, 공격, UI 등의 기능을 씬별로 넣어주는 것이 아니라 UI Canvas를 따로 만들어 넣어주는 방식 차용.
- 브다샤펄처럼 하나의 씬에 모든 맵을 넣어두고 필요에 따라 불러오는 형식. (ex: 2-1 씬을 불러올 경우 2-1만 on 나머지 씬은 off)
- [최적화_1](https://202psj.tistory.com/1263)


<br>

## 협업 방식
- Github로 관리.
- Commit이 꼬일 가능성을 고려해 branch를 n개 만들어 최종 단계에서 merge 하는 방식으로 진행.
- Jira, Google Work space, Notion, etc...

<br>

## 진행 방식
- 금주는 Discord로 소통하면서 각자 학습해보며 담당 기능을 구현해보는 방식으로 진행.
1. Joystick으로 캐릭터 자연스럽게 이동시키기.
2. 몬스터 인공지능 기능 추가 (맵에서 자연스럽게 돌아다니기, 일정 범위에 플레이어가 들어갔을 경우 플레이어를 따라가는 기능 등...)
3. 플레이어가 몬스터 Hit 시 상호작용 발생 (데미지 적용, 뒤로 밀리기 등...)
