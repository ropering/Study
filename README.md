
## Front-end
- [React](https://efficacious-dart-9b5.notion.site/React-21ee92da381f4251a63601efc431adfd)

### firestore
- Query
    - .orderBy(), where()… 을 통해 Query를 만들고 .get()을 통해 서버통신으로 데이터를 가져온다. (바로 .get()을 쓰면 모두 가져오라는 Query이다)
- .add ↔ .update 차이
    - .add : 다 지우고 대체
        - doc() 이름 명시하지 않아도 됨
    - .update : 기존 값 유지하며 특정 필드만 대체
        - doc() 명시 해야함