# Git Flow

```bash
git config --global user.name blueboy1593
# 이렇게 해주는건 알고 있지.
```

### 보통 나누는 브랜치

- Master
- Release
  - Bugfix를 주로 한다.
  - Develop에서 한 것의 디버깅을 하는 것인듯
- Develop
  - 실질적으로 작업하는 공간

브랜치를 많이 생성해보고 부딪혀보는게 좋음.

Branch

- 코드를 관리하기 위한 흐름(flow)
- 커밋을 가리키는 Pointer / Alias 와 같은 개념

코드 리뷰를 하는 이유 - 한명의 개발자가 책임을 독박 쓰지 않고 같이 하면 효율적인 결과물이 나올 수 있기 때문에.

Conflict를 줄이는 방법 - 코드의 모듈화를 확실하게 해서 서로 간섭하지 않게 한다.

Binary Low Data는 git 형상관리에 올라가지 않는 것이 좋다.