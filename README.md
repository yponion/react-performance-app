# React Developer Tools

## Components

Highlight updates when components render.

## React Profiler

# React.memo

Memoizing (shallow)

props가 다른 경우가 대부분인 컴포넌트는 불필요한 비교를 하게 되므로 react memo를 지양해야 한다.

react.memo()는 리 렌더링을 막기 위한 도구보다 성능 개선의 도구(버그 유발 가능성)
항상 좋은 것이 아니기에 profiler를 이용해서 성능상 이점이 있는지 확인 후 사용하면 좋다.

# useCallback

불필요한 렌더링 방지

# useMemo

Memoization

비용이 많이 드는 함수 호출의 결과를 저장하고 동일한 입력이 다시 발생할 때 캐시된 결과를 반환하여 컴퓨터 프로그램의 속도를 높이는 데 주로 사용되는 최적화 기술.

---

[`Free Fake REST API`](https://jsonplaceholder.typicode.com/)
