# NextJS 기초

`npx create-next-app@latest`

→ 프로젝트 생성. ts를 사용할거면 뒤에 `—typescript` 추가

React.js는 우리가 원할 때 부르고 원할 때 사용하는 library이고, framework는 집 같은 것인데, 내가 코드를 적절한 곳에 넣어야 하는 것. 기본적으로 내가 그 집을 수정할 수는 없다.

hydration → react.js를 프론트엔드 안에서 실행하는 것

### Link

우리에게 NextJS 어플리케이션의 클라이언트 사이드 네비게이션을 제공해준다.

![Untitled](https://user-images.githubusercontent.com/87460620/156514139-c372af6d-8280-477c-9eb5-9003ea026712.png)

### CSS Module

![Untitled 1](https://user-images.githubusercontent.com/87460620/156514121-9ab6b5fb-acde-4b08-baac-375bc1003b16.png)

하나의 컴포넌트에 2개의 css를 적용하는 방법

![Untitled 2](https://user-images.githubusercontent.com/87460620/156514125-8b6550c5-99be-466f-9420-c42988ce6ba6.png)

1. ``을 사용하여 각각 ${}으로 묶기
2. 리스트를 만들어서 공백으로 join

### Styles JSX

![Untitled 3](https://user-images.githubusercontent.com/87460620/156514127-2e8b2d8b-224f-4e6e-b931-4d705a6c80af.png)

### Global Style / Custom App

NextJS는 \_app.js를 먼저 확인하고, 그 다음에 index.js의 내용물을 렌더링한다.

![Untitled 4](https://user-images.githubusercontent.com/87460620/156514129-6dd87f39-a701-4715-818f-0603d3ccb82a.png)

### Patterns

Header를 관리하기 위해 새로운 파일 생성 Seo.js

![Untitled 5](https://user-images.githubusercontent.com/87460620/156514130-8e7f4c47-acc5-4632-ae8a-8dd1f721ce6b.png)

![Untitled 6](https://user-images.githubusercontent.com/87460620/156514133-67422305-43cd-4986-97d5-a3d1f3bb2132.png)

다른 파일에서 import하여 간편하게 사용 가능

### API KEY를 공개하지 않는 방법

rewrites를 사용하여

![Untitled 7](https://user-images.githubusercontent.com/87460620/156514134-ba885b54-3942-45ab-ad2d-b8e778aa110d.png)

![Untitled 8](https://user-images.githubusercontent.com/87460620/156514136-f25aebd8-8092-46e3-9422-cb33b824adfb.png)

### Server Side Rendering

![Untitled 9](https://user-images.githubusercontent.com/87460620/156514138-2ccd594f-e23b-4741-b122-0c7c2857eb0d.png)
