# stardraw-ledger

[하늘의 별 따기](https://game.byb.kr/stardraw)(Stardraw) 회차 장부의 앵커 기록입니다.

회차 서버가 회차마다 장부 끝 해시를 이 저장소에 커밋합니다. 누구나 이 기록과 공개 장부(`https://game.byb.kr/stardraw-api/ledger/`)를 비교해, 운영자가 지난 회차를 고치거나 사람마다 다른 장부를 보여 주지 않았는지 확인할 수 있습니다.

- 계산 규칙과 검사 방법: https://game.byb.kr/stardraw/verify
- 서버·검사기 소스: https://github.com/ybbarng/mighty (`apps/stardraw-server`, `packages/stardraw-core`)
- 시험 운영 기간의 기록은 `trial` 브랜치에 쌓이고, 정식 장부는 `main` 브랜치에 쌓입니다.
