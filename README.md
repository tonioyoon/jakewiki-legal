# jakewiki-legal

[JakeWiki](https://github.com/tonioyoon) Android 앱의 법적 고지 페이지.
GitHub Pages로 호스팅되며 앱 설정 화면에서 링크로 연결된다.

## 페이지

| 문서 | 경로 |
| --- | --- |
| 랜딩 | [`index.html`](https://tonioyoon.github.io/jakewiki-legal/) |
| 개인정보처리방침 | [`privacy.html`](https://tonioyoon.github.io/jakewiki-legal/privacy.html) |
| 이용약관 | [`terms.html`](https://tonioyoon.github.io/jakewiki-legal/terms.html) |
| 오픈소스 라이선스 | [`licenses.html`](https://tonioyoon.github.io/jakewiki-legal/licenses.html) |

## 갱신

- 의존성을 추가/변경하면 `licenses.html`을 갱신하고, 앱 내 `SettingsScreen.kt`의
  `OSS_LICENSES` 목록과 일치시킨다.
- 데이터 처리 방식이 바뀌면 `privacy.html`의 시행일과 본문을 갱신한다.

순수 정적 HTML/CSS이므로 빌드 단계가 없다. `main` 브랜치에 push하면 Pages가 자동 배포한다.
