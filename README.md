# sfs-board — SkillFarmSurvivor 협업 보드 (셸)

이 repo는 **화면(셸)만** 호스팅한다. **데이터는 들어있지 않다.**

- 라이브 보드: https://qtdqtd002-coder.github.io/sfs-board/
- `index.html` = private repo `luapapa0613/project_2` 의 `planning/board/board.html` 과 동일한 파일.
- 데이터(`board-data.js`)는 private repo `luapapa0613/project_2` 안에 있고, 보드가 GitHub API(개인 토큰)로 직접 읽고/쓴다. 이 공개 repo엔 데이터가 없으므로 URL만으론 보드 내용이 보이지 않는다.

## 쓰는 법
URL 접속 → **⚙ 라이브 연결** → GitHub classic 토큰(scope `repo`) 1회 등록. 토큰은 브라우저 localStorage에만 저장된다.

## 갱신
화면(UI)을 고치려면 project_2 의 `planning/board/board.html` 을 고친 뒤 이 repo의 `index.html` 로 복사해 push 한다. 데이터는 항상 project_2.
