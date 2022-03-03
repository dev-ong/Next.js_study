# NextJS 기초

`npx create-next-app@latest`

→ 프로젝트 생성. ts를 사용할거면 뒤에 `—typescript` 추가

React.js는 우리가 원할 때 부르고 원할 때 사용하는 library이고, framework는 집 같은 것인데, 내가 코드를 적절한 곳에 넣어야 하는 것. 기본적으로 내가 그 집을 수정할 수는 없다.

hydration → react.js를 프론트엔드 안에서 실행하는 것

### Link

우리에게 NextJS 어플리케이션의 클라이언트 사이드 네비게이션을 제공해준다.

![Untitled](%E1%84%82%E1%85%A9%E1%84%86%E1%85%A1%E1%84%83%E1%85%B3%20%E1%84%8F%E1%85%A9%E1%84%83%2083236/Untitled.png)

### CSS Module

![Untitled](%E1%84%82%E1%85%A9%E1%84%86%E1%85%A1%E1%84%83%E1%85%B3%20%E1%84%8F%E1%85%A9%E1%84%83%2083236/Untitled%201.png)

하나의 컴포넌트에 2개의 css를 적용하는 방법

![Untitled](%E1%84%82%E1%85%A9%E1%84%86%E1%85%A1%E1%84%83%E1%85%B3%20%E1%84%8F%E1%85%A9%E1%84%83%2083236/Untitled%202.png)

1. ``을 사용하여 각각 ${}으로 묶기
2. 리스트를 만들어서 공백으로 join

### Styles JSX

![Untitled](%E1%84%82%E1%85%A9%E1%84%86%E1%85%A1%E1%84%83%E1%85%B3%20%E1%84%8F%E1%85%A9%E1%84%83%2083236/Untitled%203.png)

### Global Style / Custom App

NextJS는 \_app.js를 먼저 확인하고, 그 다음에 index.js의 내용물을 렌더링한다.

![Untitled](%E1%84%82%E1%85%A9%E1%84%86%E1%85%A1%E1%84%83%E1%85%B3%20%E1%84%8F%E1%85%A9%E1%84%83%2083236/Untitled%204.png)

### Patterns

Header를 관리하기 위해 새로운 파일 생성 Seo.js

![Untitled](%E1%84%82%E1%85%A9%E1%84%86%E1%85%A1%E1%84%83%E1%85%B3%20%E1%84%8F%E1%85%A9%E1%84%83%2083236/Untitled%205.png)

![Untitled](%E1%84%82%E1%85%A9%E1%84%86%E1%85%A1%E1%84%83%E1%85%B3%20%E1%84%8F%E1%85%A9%E1%84%83%2083236/Untitled%206.png)

다른 파일에서 import하여 간편하게 사용 가능

### API KEY를 공개하지 않는 방법

rewrites를 사용하여

![Untitled](%E1%84%82%E1%85%A9%E1%84%86%E1%85%A1%E1%84%83%E1%85%B3%20%E1%84%8F%E1%85%A9%E1%84%83%2083236/Untitled%207.png)

![Untitled](%E1%84%82%E1%85%A9%E1%84%86%E1%85%A1%E1%84%83%E1%85%B3%20%E1%84%8F%E1%85%A9%E1%84%83%2083236/Untitled%208.png)

### Server Side Rendering

![Untitled](%E1%84%82%E1%85%A9%E1%84%86%E1%85%A1%E1%84%83%E1%85%B3%20%E1%84%8F%E1%85%A9%E1%84%83%2083236/Untitled%209.png)
