# DynamicNumberComponent
> 숫자를 포맷팅해 애니메이션효과를 사용할 수 있는 컴포넌트입니다.

#### Properties
| Name       | Type    | Desc                                                |
| :--------- | :------ | :-------------------------------------------------- |
| format | String  | 숫자 포맷 정보                                               |
| value | String  | 숫자 정보                                               |

#### Methods

DynamicNumberComponent는 함수를 제공하지 않습니다.

#### Events
|이벤트명|이벤트 인자|설명|
|---|---|---|
|click||마우스 클릭시 발생|
|dblclick||마우스 더블 클릭시 발생|
|register||화면에 등록시 발생|
|completed||리소스 로드 완료시 발생|
|destroy||컴포넌트 삭제시 발생|
|change|value|값을 선택시 발생|

#### How to use
```js
// 해당 컴포넌트의 속성을 변경하는 방법 01.
this.value = "123456";
// 해당 컴포넌트의 속성을 변경하는 방법 02.
this.setGroupPropertyValue("setter","value", "123456")
this.setGroupPropertyValue("normal","format", "(,ddd)");
// 이벤트 인자 확인 방법
console.log(event.data.value);
```
**현재 스크립트에서 format을 바꾸더라도 화면 갱신이 이루어지지 않고 있습니다. 코드 수정이 필요합니다.**


---

![gras](./images/dynamic_number.png)
<p align="right" style="margin-top: -.85em;font-style: italic;">Dynamic Number 설정 화면</p>