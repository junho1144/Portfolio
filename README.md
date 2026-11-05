# Portfolio

게임 개발에 관심 있는 JBNU 학생 junho의 개인 소개 사이트입니다.

- 사이트: https://junho1144.github.io/Portfolio/
- 저장소: https://github.com/junho1144/Portfolio

## 사용 도구와 버전

- Hugo extended 0.167.0
- Node.js / npm (빌드 시 CSS 처리용, 워크플로가 자동 설치)
- 테마: TailBliss (nusserstudios)

## 로컬에서 확인하기

1. Hugo extended를 설치합니다.
2. 저장소를 받고 `site` 폴더로 이동합니다.
3. 실행: `hugo server -s site`
4. 브라우저에서 http://localhost:1313/Portfolio/ 를 엽니다.

(빌드 명령이 다르면 `.github/workflows/hugo-pages.yml`의 명령을 그대로 적으세요.)

## 수정할 파일 위치

- 사이트 설정·메뉴·홈 문구: `site/hugo.yaml`
- About 페이지: `site/content/about.md`
- 대표 활동(Project): `site/content/prose.md`, `site/content/posts/my-project.md`
- Contact: `site/content/contact.md`

## 수정 후 배포 확인

1. 파일을 수정하고 `git add`, `git commit`, `git push`로 main에 올립니다.
2. GitHub 저장소의 Actions 탭에서 "Deploy Hugo to GitHub Pages"가 초록인지 확인합니다.
3. 시크릿 창에서 사이트를 열어 변경이 반영됐는지 확인합니다.

## 출처와 이용 조건

- 테마: [TailBliss](https://github.com/nusserstudios/tailbliss), 라이선스 (LICENSE 파일 확인 후 기재). 원본 LICENSE 파일을 저장소에 유지합니다.
- 이미지·문구: 직접 작성한 것과 테마 기본 이미지를 구분해 아래에 적습니다.
  - 직접 작성: About, Project, Contact 문구
  - 테마 제공: (사용 중인 테마 이미지 파일명)
  - AI 도움: 설정 오류 분석과 문구 구조 (Claude)