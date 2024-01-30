1.4 Library vs Framework

# 라이브러리는 코드 내에서 불러와 내가 직접적으로 사용하는 코드

# 프레임워크는 내가 실제로 수정하며 사용하는 코드가 아닌, 프레임워크의 규칙에 맞게 사용하고 프레임워크가 자동적으로 실행하는 것

2.3 SSR vs CSR

# 리액트는 Client Side Rendering 사용

## CSR은 클라이언트에서 렌더링을 담당하기 때문에 소스코드에서 HTML의 내용을 확인할 수 없고 자바스크립트가 실행되어 구현된 컴포넌트를 렌더링함

## 따라서 자바스크립트가 비활성화된 웹 브라우저는 리액트 컴포넌트들이 렌더링되지 않으며, 인터넷 속도가 느리다면 자바스크립트가 전체 컴포넌트를 가져오는 데 오랜 시간이 걸릴 수 있음

# 넥스트는 Server Side Rendering 사용

## SSR은 서버에서 컴포넌트를 렌더링한 뒤 화면에 출력하기 때문에 소스코드에서 작성된 내용을 확인할 수 있다.

## 자바스크립트의 영향을 받지 않는다(단순 HTML을 화면에 출력하는 것이기 때문).
