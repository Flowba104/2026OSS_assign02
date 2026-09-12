# Assignment 02 - HTML & CSS Practice

## 학번 / 이름
학번: 22500076
이름: 김두훈

## Assignment 02 수행 내용
동일한 HTML 문서에 서로 다른 CSS를 적용하여 페이지 레이아웃이 어떻게 달라지는지 비교하는 과제를 진행했습니다. nostyle.html을 기준 문서로 작성한 뒤 이를 복사하여 두 가지 스타일(style1.html, style2.html)을 적용했고, index.html을 만들어 세 페이지를 하나의 사이트로 연결했습니다.

## 각 페이지 설명 및 URL
index.html은 새 페이지로 이동할 수 있는 홈페이지입니다.
https://2026-oss-assign02-weld.vercel.app/index.html

nostyle.html은 모든 style의 뼈대가 되는 html입니다.
https://2026-oss-assign02-weld.vercel.app/nostyle.html

style1.html은 style1을 구현한 버전입니다.
https://2026-oss-assign02-weld.vercel.app/style1.html

style2.html은 style3을 구현한 버전입니다.
https://2026-oss-assign02-weld.vercel.app/style2.html

모든 페이지 상단에는 index.html로 돌아갈 수 있는 Home 링크가 있습니다.

## Vercel Deploy URL
https://2026-oss-assign02-weld.vercel.app

## Weekly Review - Week 2

### Key Learning
이번 주에는 header, nav 같은 시맨틱 태그로 페이지 구조를 잡는 법을 배웠습니다. 또한 원하는 UI를 어떻게 잡아나가는지, 실제로 Dev Tools를 켜서 색상이나 스타일 값을 확인하고 조정하는 법도 익혔습니다. 그 과정에서 코드를 좀 더 깔끔하게 정리하는 법도 함께 배웠습니다.

### HTML vs CSS
HTML은 페이지에 어떤 내용이 들어가고 어떤 구조로 배치되는지를 담당하고, CSS는 그 구조에 색상, 여백, 배치 같은 스타일을 입히는 역할을 합니다. 같은 HTML이라도 CSS를 어떻게 적용하느냐에 따라 완전히 다른 화면이 나올 수 있다는 걸 이번 실습으로 확인했습니다.

### Problem & Solution
style1.html을 만들 때 nav, 본문, 사이드바를 flex로 배치했더니 세 영역의 높이가 전부 본문 높이만큼 늘어나는 문제가 있었습니다. flex의 기본 정렬(stretch) 때문이라는 걸 확인하고, grid로 바꿔서 각 영역이 자기 콘텐츠 높이만큼만 차지하도록 해결했습니다.

### AI Usage
HTML 문서의 구조를 파악하거나 CSS 문법을 공부하는 데 AI를 활용했습니다. AI가 제안해준 코드는 그대로 쓰지 않고 직접 브라우저에서 실행해 결과를 확인한 뒤, 필요한 부분은 스스로 수정했습니다.

### Reflection
같은 HTML에 CSS만 바꿔도 완전히 다른 페이지처럼 보일 수 있다는 점이 새롭게 느껴졌습니다. 앞으로 flex와 grid를 좀 더 다양한 레이아웃에 활용해보고 싶습니다.