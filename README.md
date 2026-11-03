# worklearn-hrd/.github

organization 공용 이슈·PR 템플릿의 **원본**. 레포 루트의 `ISSUE_TEMPLATE/`와 `PULL_REQUEST_TEMPLATE.md`가 자기 템플릿이 없는 레포(`worklearn-api`, `worklearn-batch`, `worklearn-web`, `worklearn-infra`)에 기본 적용된다.

`worklearn-docs`는 에픽 템플릿이 필요해서 자기 `.github/`를 가진다. 규칙은 `worklearn-docs/conventions/git-conventions.md`.

```
.
├── PULL_REQUEST_TEMPLATE.md
└── ISSUE_TEMPLATE/
    ├── config.yml
    ├── bug_report.yml
    └── task.yml
```

라벨(`type:task`, `type:bug`)과 마일스톤은 레포마다 미리 있어야 자동 부착된다. `worklearn-docs/conventions/github-bootstrap.sh`로 만든다.
