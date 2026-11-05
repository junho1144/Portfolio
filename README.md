# Portfolio

게임 개발에 관심 있는 JBNU 학생 junho의 개인 소개 사이트입니다.

- 사이트: https://junho1144.github.io/Portfolio/
- 저장소: https://github.com/junho1144/Portfolio

## 사용 도구

- Hugo extended 0.167.0 (워크플로에서 버전 지정)
- Node.js / npm (CSS 처리용, GitHub Actions가 자동 설치)
- 테마: TailBliss

## 로컬에서 확인하기

1. Hugo extended와 Node.js를 설치합니다.
2. 저장소를 받고 루트 폴더에서 실행합니다.

    hugo server -s site

3. 브라우저에서 http://localhost:1313/Portfolio/ 를 엽니다.

빌드만 할 때: `hugo -s site`

위 명령이 환경에 따라 동작하지 않으면 `.github/workflows/hugo-pages.yml`의 빌드 명령을 따릅니다.

## 수정할 파일

- 사이트 설정, 메뉴, 홈 문구: `site/hugo.yaml`
- About 페이지: `site/content/about.md`
- 대표 활동(Project): `site/content/prose.md`
- Contact 페이지: `site/content/contact.md`

## 수정 후 배포

1. 파일을 수정합니다.
2. `git add`, `git commit`, `git push`로 `main` 브랜치에 올립니다.
3. 저장소의 **Actions** 탭에서 "Deploy Hugo to GitHub Pages"가 초록색(성공)인지 확인합니다.
4. 시크릿 창에서 사이트를 열어 변경이 반영됐는지 확인합니다.

## 출처와 이용 조건

- 테마: [TailBliss](https://github.com/nusserstudios/tailbliss) (nusserstudios). 원본 `LICENSE` 파일을 저장소에 그대로 유지합니다.
- 직접 작성: About, Project, Contact, 홈 소개 문구
- 테마 제공: 기본 이미지와 레이아웃
- AI 도움: 설정 오류 분석과 문구 구조 정리에 Claude(Anthropic)를 사용했습니다.