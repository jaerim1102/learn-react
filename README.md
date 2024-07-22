# 리액트 과제 저장소

## homework01

중앙정렬을 하고 싶어서 ul에

```
   justify-content: center;
   align-items: center;
```

을 넣었지만 li가 뭉개지고 못생겨지는 문제가 생겼다...

그래서 ul을 감싸는 section을 만들어 코드를 넣었는데, 수직 중앙 정렬은 됐지만 수평 중앙 정렬이 되지 않았다.

height값이 없어서 정렬이 되지 않는 것을 문제라는 것을 알게 되어 section에 `height: 100vh`을 주었더니 정상적으로 작동했다.
