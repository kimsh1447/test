# TickerComponent
> 설정된 시간에 텍스트를 애니메이션 하여 사용 할 수 있는 컴포넌트입니다.

#### Properties
| Name       | Type    | Desc                                                |
| :--------- | :------ | :-------------------------------------------------- |
| text | String  | 화면에 나타낼 text                              |
| direction | String  | text가 애니메이션되는 방향                          |
| delay | Number  | text가 애니메이션 되는 시간                          |

#### Methods

TickerComponent는 함수를 제공하지 않습니다.

#### Events
|이벤트명|이벤트 인자|설명|
|---|---|---|
|click||마우스 클릭시 발생|
|dblclick||마우스 더블 클릭시 발생|
|register||화면에 등록시 발생|
|completed||리소스 로드 완료시 발생|
|destroy||컴포넌트 삭제시 발생|
|change|value|데이터값이 변경될시 발생|

#### How to use
```js
// TickerComponent 시간 포맷을 바꾸는 예제
this.text =  "Hello World!";

```