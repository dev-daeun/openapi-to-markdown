# openapi-to-markdown

### Github Action workflow
1. master에 있는 `openapi()`와 current branch의 `openapi()`를 비교해서 diff가 있으면  markdown으로 변환
2. upload artifact
3. `dev-daeun.automate-doc.github.io` 리퍼지토리에 이벤트를 일으키도 `repository_dispatch` 록 webhook  날리기
