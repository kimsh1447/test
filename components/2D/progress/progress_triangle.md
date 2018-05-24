# Triangle Progress Component
> Progress Pack

#### Properties
| Name       | Type    | Desc                                                |
| :--------- | :------ | :-------------------------------------------------- |
| value   | Number | 0-100까지의 숫자                                 |


#### Methods
TriangleProgressComponent does not provide any methods.


#### Events
|이벤트명|설명|
|---|---|
|click|마우스 클릭시 발생|
|dblclick|마우스 더블 클릭시 발생|
|register|화면에 등록시 발생|
|completed|리소스 로드 완료시 발생|
|destroy|화면에 해제시 발생|
|change|값을 선택시 발생|

#### WScript Example
<!-- js-console -->
```js
// TriangleProgressComponent의 그래프를 10%로 바꾸는 예제
this.value = 90;
```