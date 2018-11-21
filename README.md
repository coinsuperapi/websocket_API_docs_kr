# websocket API

소개

```
Websocket API는 거래센터가 외부 개발자를 상대하여 제공하는 개발 인터페이스이다.
```

------

업그레이드 기록

| 버전        | 시간       | 설명          | 작가     |
| --------- | -------- | ----------- | ------ |
| v1.0.0(β) | 20180726 | 새로 만든 파일    | liyong |
| v1.0.1(β) | 20180809 | 조정host、port | liyong |

------

## [1.전면 규칙](https://github.com/coinsuperapi/websocket_API_docs_kr/wiki#1%EC%A0%84%EB%A9%B4-%EA%B7%9C%EC%B9%99)

#### [인터페이스 규칙](https://github.com/coinsuperapi/websocket_API_docs_kr/wiki#%EC%9D%B8%ED%84%B0%ED%8E%98%EC%9D%B4%EC%8A%A4-%EA%B7%9C%EC%B9%99)

#### [구독 파라미터 약정](https://github.com/coinsuperapi/websocket_API_docs_kr/wiki#%EA%B5%AC%EB%8F%85-%ED%8C%8C%EB%9D%BC%EB%AF%B8%ED%84%B0-%EC%95%BD%EC%A0%95)

## [2.상세 인터페이스 정의](https://github.com/coinsuperapi/websocket_API_docs_kr/wiki#2%EC%83%81%EC%84%B8-%EC%9D%B8%ED%84%B0%ED%8E%98%EC%9D%B4%EC%8A%A4-%EC%A0%95%EC%9D%98)

### [인터페이스 목록](https://github.com/coinsuperapi/websocket_API_docs_kr/wiki#%EC%9D%B8%ED%84%B0%ED%8E%98%EC%9D%B4%EC%8A%A4-%EB%AA%A9%EB%A1%9D)

### [API 인터페이스 정의](https://github.com/coinsuperapi/websocket_API_docs_kr/wiki#api-%EC%9D%B8%ED%84%B0%ED%8E%98%EC%9D%B4%EC%8A%A4-%EC%A0%95%EC%9D%98)

#### [1.시세](https://github.com/coinsuperapi/websocket_API_docs_kr/wiki#1%EC%8B%9C%EC%84%B8)

##### [1.1 깊이 시세(최신 깊이도 데이터)](https://github.com/coinsuperapi/websocket_API_docs_kr/wiki#11-%EA%B9%8A%EC%9D%B4-%EC%8B%9C%EC%84%B8%EC%B5%9C%EC%8B%A0-%EA%B9%8A%EC%9D%B4%EB%8F%84-%EB%8D%B0%EC%9D%B4%ED%84%B0)

##### [1.2 가격시세(최신 주문서 데이터)](https://github.com/coinsuperapi/websocket_API_docs_kr/wiki#12-%EA%B0%80%EA%B2%A9%EC%8B%9C%EC%84%B8%EC%B5%9C%EC%8B%A0-%EC%A3%BC%EB%AC%B8%EC%84%9C-%EB%8D%B0%EC%9D%B4%ED%84%B0)

##### [1.3 시간대 시세(최신 k 라인 데이터)](https://github.com/coinsuperapi/websocket_API_docs_kr/wiki#13-%EC%8B%9C%EA%B0%84%EB%8C%80-%EC%8B%9C%EC%84%B8%EC%B5%9C%EC%8B%A0-k-%EB%9D%BC%EC%9D%B8-%EB%8D%B0%EC%9D%B4%ED%84%B0)

##### [1.4 실시간 거래성사 시세(최신 거래 성사 시세 데이터)](https://github.com/coinsuperapi/websocket_API_docs_kr/wiki#14-%EC%8B%A4%EC%8B%9C%EA%B0%84-%EA%B1%B0%EB%9E%98%EC%84%B1%EC%82%AC-%EC%8B%9C%EC%84%B8%EC%B5%9C%EC%8B%A0-%EA%B1%B0%EB%9E%98-%EC%84%B1%EC%82%A) 

#### [2.사용자 개인 데이터](https://github.com/coinsuperapi/websocket_API_docs_kr/wiki#2%EC%82%AC%EC%9A%A9%EC%9E%90-%EA%B0%9C%EC%9D%B8-%EB%8D%B0%EC%9D%B4%ED%84%B0)

##### [2.1 사용자 계정 자산 변경](https://github.com/coinsuperapi/websocket_API_docs_kr/wiki#21-%EC%82%AC%EC%9A%A9%EC%9E%90-%EA%B3%84%EC%A0%95-%EC%9E%90%EC%82%B0-%EB%B3%80%EA%B2%BD)

##### [2.2 주문 상태 변경](https://github.com/coinsuperapi/websocket_API_docs_kr/wiki#22-%EC%A3%BC%EB%AC%B8-%EC%83%81%ED%83%9C-%EB%B3%80%EA%B2%BD)

##### [2.3 성사된 거래 내역](https://github.com/coinsuperapi/websocket_API_docs_kr/wiki#23-%EC%84%B1%EC%82%AC%EB%90%9C-%EA%B1%B0%EB%9E%98-%EB%82%B4%EC%97%AD)

------

## 저희를 연락하십시오

```
도움이 필요하시면 아래의 api문제교류 동아리를 가입하세요(가입시 비고란에 api+coinsuper아이디를 입력하세요)：
1.QQ동아리：472488338 
2.Telegram 전문 동아리：https://t.me/joinchat/HEgiSxBKVx6nwQ33otJ3Zg
```

