# .github

somehowsiblings 조직의 기본 커뮤니티 파일과 재사용 워크플로를 둡니다. 자체 템플릿이 없는 조직 내 모든 저장소에 자동 적용됩니다.

- `.github/ISSUE_TEMPLATE/`: 이슈 템플릿 일곱 종. 규칙은 [development-guidelines/git/issue-convention.md](https://github.com/somehowsiblings/development-guidelines/blob/main/git/issue-convention.md)
- `.github/PULL_REQUEST_TEMPLATE.md`: PR 본문 템플릿. 규칙은 [development-guidelines/git/pull-request-rule.md](https://github.com/somehowsiblings/development-guidelines/blob/main/git/pull-request-rule.md)
- `.github/workflows/gradle-ci.yml`: JDK + Gradle 빌드 재사용 워크플로

규칙 원본은 [development-guidelines](https://github.com/somehowsiblings/development-guidelines)에 있습니다. 여기서는 형식만 다룹니다.

## 공개 저장소 주의

이 저장소는 GitHub 제약(조직 기본 커뮤니티 파일은 public 저장소에서만 읽음) 때문에 **공개**입니다. 여기에는 형식만 둡니다.

- 넣지 않는 것: 서비스·제품 이름, 화면 코드, 스펙 내용, 내부 문서 링크의 요약, 인프라·계정·도메인 정보, 비밀값
- 넣는 것: 이슈·PR 템플릿의 절 이름과 안내 문구, 재사용 워크플로의 일반적인 빌드 단계
- 프로젝트에 묶인 예시가 필요하면 비공개 저장소인 development-guidelines에 적고 링크만 둡니다.
- 이 저장소에 PR을 올릴 때는 위 기준으로 한 번 더 확인합니다.
