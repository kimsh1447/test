# Bar Progress Component
> 막대 형태의 진척도를 나타내는 컴포넌트

#### Properties
| Name       | Type    | Desc                                                |
| :--------- | :------ | :-------------------------------------------------- |
| value   | Number | 0-100까지의 숫자                                 |

#### Methods
BarProgressComponent는 함수를 제공하지 않습니다.

#### Events
|이벤트명|이벤트 인자|설명|
|---|---|---|
|click||마우스 클릭시 발생|
|dblclick||마우스 더블 클릭시 발생|
|register||화면에 등록시 발생|
|completed||리소스 로드 완료시 발생|
|destroy||화면에 해제시 발생|
|change|value|값을 선택시 발생|

#### How to use
<!-- js-console -->
```js
// BarProgressComponent의 그래프를 10%로 바꾸는 예제
this.value = 10;
```