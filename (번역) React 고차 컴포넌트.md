# Higher-Order Components(고차 컴포넌트)

고차 컴포넌트는 컴포넌트 로직을 재사용하기 위한 React의 고급 기술입니다. 고차 컴포넌트들은 React API는 아니지만, React의 구성적 특징에서 나온 패턴입니다.

구체적으로 말하자면, **고차 컴포넌트는 컴포넌트를 가져오고, 새로운 컴포넌트를 반환하는 함수입니다.**

```javascript
const EnhancedComponent = higherOrderComponent(WrappedComponent);
```

컴포넌트는 props를 UI로 변화하는 반면, 고차 컴포넌트는 컴포넌트를 다른 컴포넌트로 변환합니다.

고차 컴포넌트는 Redux의 `connect`와 Relay의 `createFragmentContainer`에 비해  일반적입니다.

이 문서에서, 우리는 왜 고차 컴포넌트가 유용하며, 여러분 자신만의 고차 컴포넌트를 어떻게 만들 수 있는지 이야기해보려고 합니다.





