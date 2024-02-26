# React Study

<img width="878" alt="image" src="https://github.com/m3k0813/ReactStudy/assets/41982054/7baf063e-3710-4da7-ad49-d984ecea5e9f">

[참고 레퍼런스](https://react.vlpt.us/)

---
## 공부 정리

### JSX(Javascript Syntax eXtension) - 자바 스크립트를 확장한 문법, 리액트에서 생김새를 정의할 때 사용

### props(프로퍼티) - 어떠한 값을 컴포넌트에게 전달해줘야할 때 사용
- 부모 컴포넌트가 하위 컴포넌트에게 값을 전달할 때 사용하는 속성(단반향 데이터 흐름) 
- 부모 컴포넌트는 수정이 가능하지만, 자식 컴포넌트는 읽기만 가능

### 조건부 렌더링 - 특정 조건에 따라 다른 결과물을 렌더링

### State - 이벤트에 따라 변경되는 동적인 값, useState Hook을 통해 state를 관리

### DOM(Document Object Model) - 웹 페이지를 이루는 태그들을 자바스크립트가 이용할 수 있게 브라우저 에서 트리 구조로 만든 객체 모델
- useRef - DOM요소에 접근하기 위해 사용되는 Hook, 직접 DOM을 선택하기 위해 사용

### Hook
- useEffect - 컴포넌트가 렌더링 될 때마다 특정 작업을 실행, 마운트/언마운트/업데이트 시 처리
- useMemo - 성능 최적화를 위한 사용, 특정 값을 반복적으로 호출해야할 때 메모리에 저장하여 필요할 때마다 꺼내서 재사용
- useCallback - useMemo와 비슷, 특정 함수를 새로 만들지 않고 재사용
- useReducer - 컴포넌트에서 상태(state)를 다룰 때 사용, useState와 비슷하게 상태를 변경하지만, 복잡한 로직을 다룰 수 있음
