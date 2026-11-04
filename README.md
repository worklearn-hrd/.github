# worklearn-hrd/.github

organization 공용 이슈·PR 템플릿의 **원본**. `.github/ISSUE_TEMPLATE/`와 루트의 `PULL_REQUEST_TEMPLATE.md`가 자기 템플릿이 없는 레포(`worklearn-api`, `worklearn-batch`, `worklearn-web`, `worklearn-infra`)에 기본 적용된다.

GitHub 규칙: 이 레포에서 이슈 템플릿과 `config.yml`은 반드시 `.github/ISSUE_TEMPLATE/` 아래에 있어야 한다. 루트의 `ISSUE_TEMPLATE/`는 무시된다. 어떤 레포가 자기 `.github/ISSUE_TEMPLATE/`를 하나라도 가지면 그 레포에는 이 기본 템플릿이 보이지 않는다.

`worklearn-docs`는 에픽 템플릿이 필요해서 자기 `.github/`를 가진다. 규칙은 `worklearn-docs/conventions/git-conventions.md`.

```
.
├── PULL_REQUEST_TEMPLATE.md
└── .github/
    └── ISSUE_TEMPLATE/
        ├── config.yml
        ├── bug_report.yml
        └── task.yml
```

라벨(`type:task`, `type:bug`)과 마일스톤은 레포마다 미리 있어야 자동 부착된다. `worklearn-docs/conventions/github-bootstrap.sh`로 만든다.
