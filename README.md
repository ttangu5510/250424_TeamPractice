## 팀플 실습
- 5일동안 만들 게임의 주제를 정하고, 팀원들과 역할을 분담한다.
- 게임은 `배틀시티(1985)`의 유니티 구현으로 정했다
 <div class="video-container">
    <iframe width="640" height="360" src="https://www.youtube.com/embed/Xww2jXpQSwQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </div>

- 5일이라는 기간이 게임을 구현하기에는 짧은 만큼, 간단하고 이미 배웠던 내용들로 충분히 구현 가능해야 한다. 그래서 해당 게임으로 정했다

### branch(분기) 만들기
- 역할을 나눈 이후, 팀원들 각자 이름의 `branch`를 만든다. 그러고 나서 각자의 **이름과 역할**로 폴더를 만든다
    - 이진영_플레이어, 김민수_스코어 등
- 폴더 안에는 `README.md` 파일을 각자 만들어 역할의 구체적인 구현 목표를 설계하고 작성한다.
- 작성이 완료되면 `commit` 한다


### 역할 분담
- 이진영 - 플레이어
- 김민수 - UI
- 최재민 - 몬스터
- 박희건 - 씬, 테스트씬
- 이하나 - 환경 프리팹

### Pull Request
- `commit` 한 이후, `Push`까지 진행한 후(브랜치 업데이트) `Pull Request`를 작성해서 병합하고 `branch`는 삭제한다
- Pull Request된 내용들을 깃허브 홈페이지에서 확인하고 병합한다
### Conflict(충돌)
- 일부러 `Conflict`를 일으켜본다
- `branch`를 `ConflictTest`를 만들고, Fetch를 해서 구성원 3명 정도가 그 폴더 안에 `ReadMe.md` 파일을 만든다
- `ReadMe.md` 파일 안에서 동일한 부분을 수정해서 의도적으로 `Conflict`를 발생시킨다
### Merge(병합)
- 병합하려고 할 때 Conflict를 해결시키는 과정을 기록한다
- Conflict가 해결 되면 병합을 완료한다