# DigitalClockComponent
> 서버 시간 기준으로 시간을 설정하는 컴포넌트입니다.

#### Properties
| Name       | Type    | Desc                                                |
| :--------- | :------ | :-------------------------------------------------- |
| dateFormat | String  | 시간 포맷 정보                                  |

#### Methods

DigitalClockComponent does not provide any methods.

#### Events
|이벤트명|설명|
|---|---|
|click|마우스 클릭시 발생|
|dblclick|마우스 더블 클릭시 발생|
|register|화면에 등록시 발생|
|completed|컴포넌트 로딩 완료시 발생|
|destroy|컴포넌트 삭제시 발생|

#### WScript Example
```js
// DigitalClockComponent 시간 포맷을 바꾸는 예제
this.dateFormat = "yyyy-MM-dd HH:mm:ss";
```

---