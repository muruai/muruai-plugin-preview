# 무루아이 프리뷰 플러그인

무루아이 프리뷰 환경(`qa-muru-57.muruai-fe.pages.dev`)에 연결해 새 기능을 미리 시험하는 플러그인입니다. 선생님용 플러그인은 [muruai/muruai-plugin](https://github.com/muruai/muruai-plugin)입니다.

## 설치

프리뷰 웹 **계정 설정 > AI 도구 연결**에서 설정 문장을 복사해 AI 도구에 붙여 넣으면 AI 도구가 설치합니다.

직접 설치할 때는 아래 명령을 차례로 실행합니다.

Claude Code

```
claude plugin marketplace add muruai/muruai-plugin-preview
claude plugin install muruai-preview@muruai-preview
```

Codex

```
codex plugin marketplace add muruai/muruai-plugin-preview
codex plugin add muruai-preview@muruai-preview
```

## 로그인

새 대화를 열고 `/mcp`에서 `muruai`를 골라 로그인합니다. 프리뷰 로그인 화면에서는 이메일로 로그인합니다.

## 연결 끊기

프리뷰 웹 **계정 설정 > AI 도구 연결**에서 끊을 수 있습니다.
